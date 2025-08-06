# Project Memory

## Document Overview

### Core Documents
- **`project-idea.md`**: Comprehensive project specification document containing summary, requirements, architecture options, technical specifications, and implementation roadmap for the agentic multi-agent baseline solution
- **`basic-requirements-and-goals.txt`**: Original project requirements and goals document outlining the three architecture options and core functionalities
- **`research.md`**: Future research items and advanced features to be considered in later versions, including monitoring, security, resilience patterns, and advanced architecture considerations

### Configuration Files
- **`.github/instructions/csharp.instructions.md`**: C# coding standards and documentation requirements for the project
- **`.github/copilot-instructions.md`**: GitHub Copilot configuration with rules for memory management, Context7 integration, and commit procedures
- **`.github/prompts/new.idea.prompt.md`**: Template prompt for project idea creation and refinement

## Project Status
- **Current Phase**: Initial project definition and documentation
- **Next Phase**: Technology stack validation and architecture proof of concept
- **Version**: 1.0 (Initial Draft)

## Key Technical Decisions
- **Primary Language**: C# with .NET 8+ for main components
- **Secondary Language**: Python for potential third agent implementation
- **AI Framework**: Semantic Kernel for agent capabilities
- **Communication Protocol**: MCP (Model Context Protocol) with stdio for local, REST API for distributed
- **Deployment Options**: Local → Docker → Kubernetes progression

## Architecture Summary
Three progressive deployment options:
1. **Local**: stdio MCP with inprocess agents
2. **Dockerized**: REST API MCP with containerized remote agents
3. **Cloud-Native**: Kubernetes deployment with scalable agent pods
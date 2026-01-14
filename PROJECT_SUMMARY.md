# Project Summary - AI Guardians Workshop

## Directory Structure

```
ai_guardians/
├── .env                                    # Environment variables (gitignored)
├── .git/                                   # Git version control
├── .github/
│   ├── copilot-instructions.md            # GitHub Copilot workspace instructions
│   └── prompts/
│       ├── general.prompt.md              # General task definition template
│       └── generate-project-summary.md    # Reusable prompt for generating this file
├── .vscode/
│   ├── launch.json                        # Chrome debugger configuration
│   └── settings.json                      # VS Code workspace settings
├── src/
│   └── AGENT.md                           # Agent documentation (placeholder)
├── PROJECT_SUMMARY.md                      # This file - project overview
└── README.md                               # Workshop introduction
```

## File Descriptions

### Root Level
- **README.md** - Main entry point with workshop title and purpose
- **PROJECT_SUMMARY.md** - Comprehensive project structure and architecture documentation
- **.env** - Stores sensitive configuration (API keys, tokens) - not committed to git

### .github/
- **copilot-instructions.md** - Defines project conventions, development workflow, and coding standards for GitHub Copilot to follow. Includes workshop context emphasizing clarity and educational value.

### .github/prompts/
- **general.prompt.md** - Template with frontmatter configuration for creating reusable AI prompts (includes agent settings, model preferences, and tool specifications)
- **generate-project-summary.md** - Reusable prompt that automates the generation/update of this PROJECT_SUMMARY.md file

### .vscode/
- **launch.json** - Debugger configuration for attaching to Chrome on port 9222
- **settings.json** - VS Code workspace-specific settings (currently empty)

### src/
- **AGENT.md** - Placeholder for AI agent documentation and specifications

## Key Dependencies

Currently, this is an early-stage workshop project with minimal dependencies:

- **Git** - Version control
- **VS Code** - Primary development environment
- **GitHub Copilot** - AI-assisted development tool
- **Chrome Debugger** - Configured for web development debugging

## Overall Architecture Pattern

### Current State: Workshop Scaffold
This project is in its **initial setup phase** for a full-day AI development workshop. The architecture follows a **learning-oriented structure**:

1. **Documentation-First Approach** - Heavy emphasis on instructions and guidelines for workshop participants
2. **Prompt Engineering Infrastructure** - Reusable prompt templates stored in `.github/prompts/` for standardized AI interactions
3. **Configuration Layer** - Centralized environment variables and IDE settings for consistent development experience
4. **Modular Organization** - `src/` directory prepared for workshop exercises and code modules

### Design Principles
- **Clarity over Optimization** - Code prioritizes educational value
- **Progressive Complexity** - Structure supports incremental learning
- **AI-Assisted Development** - Leverages GitHub Copilot with custom instructions
- **Separation of Concerns** - Configuration, documentation, and source code clearly separated

### Future Evolution
The architecture is designed to accommodate:
- AI/ML components and model integrations
- API service integrations
- Testing frameworks for AI applications
- Data handling pipelines
- Build and deployment workflows

---
*Last Updated: January 14, 2026*

---
name: General Task Definition
description: This prompt is used to clearly define a task with all necessary details.
argument-hint: Provide a detailed task description.
agent: ask
model: GPT-5 mini
---

# Generate Project Summary

Analyze the current directory structure and create or update the file `PROJECT_SUMMARY.md` and put a concise summary that includes:

1. **A tree view of all files** - Display the complete directory structure
2. **Brief description of what each file does** - Explain the purpose and functionality of each file
3. **Key dependencies and their purposes** - List important libraries, frameworks, and tools being used
4. **Overall architecture pattern** - Describe the high-level design approach and organization

## Usage

Copy and paste this prompt into your conversation with GitHub Copilot to automatically generate or update the project summary documentation.

## Output

The result will be a comprehensive `PROJECT_SUMMARY.md` file at the root of your project that serves as quick reference documentation for understanding the codebase structure and organization.

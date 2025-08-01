# Copilot Instructions for Chatmode Prompts Repository

## Project Overview

This repository contains a collection of specialized AI assistant configurations in `.chatmode.md` format. Each file defines a distinct AI persona with specific expertise, behavioral guidelines, and tool access permissions for use in AI chat interfaces.

## Architecture Patterns

### Chatmode File Structure

All chatmode files follow this consistent YAML frontmatter + Markdown pattern:

```yaml
---
description: 'Brief persona description'
tools: ['tool1', 'tool2'] # Optional tool access list
---
```

### File Naming Convention

-   Use descriptive names with spaces: `Senior Frontend Developer.chatmode.md`
-   Names reflect the persona/role: `Business Brain.chatmode.md`, `Professor.chatmode.md`
-   Special characters in personality names: `Ninety Five.chatmode.md`, `Winston Churchill.chatmode.md`

### Content Organization Patterns

1. **Identity Declaration**: Clear role/expertise statement at the top
2. **Structured Guidelines**: Use `##` headers for major sections
3. **Behavioral Rules**: Explicit do/don't lists and response patterns
4. **Tool Integration**: Specific tool usage guidelines when applicable
5. **Response Templates**: Formatted examples for consistent outputs

## Persona Categories

### Technical Specialists

-   `Senior Frontend Developer.chatmode.md`: React Router 7, TypeScript, modern web dev
-   `Tool Builder.chatmode.md`: MCP tool development with comprehensive schemas
-   `Unit Test Analyzer.chatmode.md`: Test quality assessment and business value analysis
-   `Zod Schema Bot.chatmode.md`: TypeScript validation schema expert

### Content & Communication

-   `Blog Writer.chatmode.md`: Technical writing with narrative structure
-   `Documentation Bot.chatmode.md`: Technical documentation with precision standards
-   `Ticket Writer.chatmode.md`: User story formatting with business context

### Problem-Solving & Analysis

-   `Ninety Five.chatmode.md`: 95% confidence validation methodology
-   `Stepwise Chain of Thought.chatmode.md`: Step-by-step logical reasoning
-   `Beast Mode.chatmode.md`: Autonomous problem-solving with extensive research

### Business & Strategy

-   `Business Brain.chatmode.md`: Strategic consulting with customer value focus

### Educational & Support

-   `Professor.chatmode.md`: Interactive teaching with hands-on exercises
-   `Winston Churchill.chatmode.md`: Prompt optimization specialist

### Personality-Based

-   `Arnold Schwarzenegger.chatmode.md`: Character emulation with motivational tone

## Key Conventions

### Tool Access Patterns

-   Most technical roles include: `'codebase', 'editFiles', 'search', 'vscodeAPI'`
-   Specialized tools for specific domains (e.g., `'context7'`, `'promptBoost'`)
-   Empty array `[]` for personality/education roles that don't need code access

### Response Structure Standards

-   Use markdown formatting with clear headings
-   Include structured templates for consistent outputs
-   Implement confidence/validation systems where appropriate
-   Provide actionable next steps and clear deliverables

### Content Quality Guidelines

-   Maintain professional yet accessible tone
-   Include specific examples from relevant domains
-   Focus on practical, implementable advice
-   Reference authoritative sources and documentation

## Development Workflow

### Creating New Chatmodes

1. Start with clear persona identity and expertise area
2. Define specific behavioral guidelines and constraints
3. Include response templates for consistency
4. Specify appropriate tool access based on role needs
5. Test with example scenarios to validate behavior

### Quality Standards

-   Each persona should have a distinct voice and approach
-   Instructions must be actionable and specific to avoid generic responses
-   Include validation mechanisms for complex reasoning tasks
-   Provide clear boundaries on what the persona will/won't do

### File Organization

-   Keep all chatmode files in the repository root
-   Use descriptive filenames that clearly indicate the persona
-   Maintain consistent frontmatter structure across all files
-   Follow the established naming conventions for new additions

## Integration Notes

These chatmode files are designed for AI chat interfaces that support:

-   YAML frontmatter parsing for metadata
-   Tool access control and permissions
-   Persona switching and mode activation
-   Markdown rendering for formatted responses

When working with this repository, preserve the established patterns and ensure new chatmodes follow the documented conventions for consistency and maintainability.

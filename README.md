# Copilot Memory

## Purpose
Copilot Memory is a modular, persistent workspace designed for collaborative AI research, project management, and feature development. This repository serves as a central hub for organizing projects, sharing information, and enhancing productivity in AI-related initiatives.

## Folder Structure
- `/conversations` — Individual, versioned conversations with metadata
- `/indexes` — Cross-conversation indexes (features, decisions, summaries)
- `/modules` — Feature/function documentation & design
- `/tasks` — Project tasks and action items
- `/instructions` — Custom instructions, guardrails, handoff templates

## Workflow
1. Start a conversation: add a file to `/conversations/`
2. Log decisions/features: update `/indexes/`
3. Develop features/modules: document in `/modules/`
4. Track actionable items in `/tasks/`
5. Update instructions and guardrails in `/instructions/`
6. Maintain indexes for continuity and cross-referencing

## Extensibility
The architecture is modular—add new folders or files as your project evolves.

## Date Format
All logs and metadata use EU format: `dd-mm-yyyy`

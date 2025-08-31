# Conversation Instructions: Persistent Memory for Copilot (2025-08-31)

## Project Summary
This project creates a modular, extensible persistent memory architecture for Copilot/GitHub workflows, tailored to single-user research, development, and prompt engineering. The aim is to ensure continuity and context restoration across LLM sessions, overcoming the stateless nature of Copilot and similar systems.

## Scope & Requirements
- All persistent memory (transcripts, instructions, code, lessons) is stored in a GitHub repository.
- Modularity and extensibility for future feature sets.
- Handoff workflow: save full transcripts and key files for restoring context.
- Editable instruction file for bootstrapping new or continued conversations.
- Research mandate: document and evaluate any tools or techniques relevant to LLM context persistence with minimal dependencies.

## Handoff Protocol (For Copilot or any LLM)
- You do **not** have persistent memory. You forget everything between sessions.
- **Upon session start, the user will provide two files:**
  1. `conversation-transcript.md` — the verbatim transcript of previous conversations, including code blocks, decisions, and key exchanges.
  2. `conversation-instruction.md` — this file, containing project scope, handoff protocol, actionable instructions, and any lessons learned.
- **Your workflow:**
  - Read both files in full before proceeding. They are your only context.
  - Use the instruction file to set scope, constraints, and project goals.
  - Use the transcript to restore prior discussion, decisions, and technical details.
  - If you generate new lessons, decisions, code, or important context, append these to the appropriate files before session ends.
  - Treat these two files as the authoritative memory for the project.
- **Best practices for continuity:**
  - Confirm with the user which files are the current handoff memory before major actions.
  - Prompt user to update/append files after significant changes, research, or design decisions.
  - Be explicit about context boundaries—do not assume anything not in these files.
  - If files are missing or incomplete, ask the user to clarify or provide them.

## Next Steps
1. Update/amend `conversation-transcript.md` after each session.
2. Update/amend this instruction file as scope, decisions, or protocols evolve.
3. Research and document any new methods or tools for persistent LLM memory or Copilot workflow handoff.
4. Use these files to bootstrap future sessions by copy-pasting or referencing their contents.

---

## Outstanding Research Mandate
- Seek any browser extensions, plugins, or open-source tools for exporting/importing Copilot chat transcripts.
- Evaluate native GitHub features or APIs for supporting persistent LLM memory and handoff.
- Minimize dependencies—prefer solutions that work with only GitHub and Copilot.

---

(*Update this file as the project evolves*)
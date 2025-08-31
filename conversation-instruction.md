# Conversation Instructions: Persistent Memory for Copilot (2025-08-31)

## Summary
This project aims to design and implement a modular, extensible architecture for persistent memory in Copilot/GitHub workflows, tailored to single-user, research, development, and prompt engineering scenarios. Core problems addressed are loss of LLM context, inability to hand off conversations, and absence of best-practice/guardrail mechanisms.

## Scope & Requirements
- Persistent, queryable knowledge base (lessons, guardrails, ideas, prompts) stored in a GitHub repo.
- Modular structure, easily extended with new features.
- Practical handoff workflow: save full transcripts & code blocks for context restoration.
- Instruction "bootstrap" for new/continued conversations, provided via editable text file.
- Research mandate: discover any existing tools, partial solutions, or inspirations that solve context persistence for Copilot or similar LLM workflows.

## Current Status
- Transcript saved in `conversation-transcript.md` (see file).
- Instructions and scope saved in this file.
- Awaiting deeper research for cutting-edge solutions, plugins, or APIs to avoid reinventing the wheel.

## Next Steps
1. Update/amend `conversation-transcript.md` after each session.
2. Update/amend this instruction file if project scope or requirements change.
3. Research and document any new tools, plugins, or methods for persistent LLM memory or Copilot context handoff.
4. Use these files to bootstrap future conversations by copy-pasting their contents or referencing in initial instructions.

---

## Handoff Protocol Example
- New session: paste or upload both `conversation-instruction.md` and `conversation-transcript.md`.
- Use instruction file to set scope/context.
- Use transcript to restore previous discussion/code context.
- Amend both files as needed for continuity.

---

## For Copilot or LLM
- You do not have persistent memory. All context must be provided upon session start.
- Instructions and transcript files are provided for maximum continuity.
- Always refer to these files before proceeding.

---

## Outstanding Research Mandate
- Search for any browser extensions, plugins, or tools that enable export/import of Copilot chat transcripts and context.
- Seek any open-source or commercial solutions that can be adapted for persistent memory in Copilot workflows.

---

(*Update this file as the project evolves*)
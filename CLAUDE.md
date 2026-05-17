# AI Product Thinking — Claude Code Session

This is the **AI Product Thinking** curriculum repo — a self-paced course for PMs, founders, and builders working with LLMs. Created by Rahul Kattayil.

## When a session starts

Try reading `./progress.md` silently using the Read tool.

- **File exists:** recap completed topics (one line each), then continue where they left off.
- **File missing:** say nothing about setup — just proceed directly to the curriculum.

Then read `prompt.md` and follow Steps 1–6 exactly.

## Claude Code-specific instructions

These override the defaults in `prompt.md` for this environment:

**Progress tracking default**: Option A (local files). You can write files directly — do so automatically without asking unless the user says otherwise.

**File paths for all writes**:
- Topic notes → `./notes/ch{N}_topic{N}_{slug}.md` (e.g., `ch1_topic1_tokens_context_attention.md`)
- Quiz log → `./quiz_log.md` (append each entry; never overwrite)
- Progress tracker → `./progress.md` (update chapter/topic status after each completion)

**On every topic completion**: Write the note file. Update `./progress.md`. Tell the user the file was saved and where.

**On every quiz completion**: Append the entry to `./quiz_log.md`. Tell the user it was logged.

**On session resume**: Read `./progress.md`, then read the most recent note file to restore context before recapping.

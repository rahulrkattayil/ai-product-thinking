
# AI Product Thinking
### A self-paced curriculum for PMs, founders, and builders working with LLMs

**Created by Rahul Kattayil**

---

## What this is

A structured, adaptive curriculum that teaches the conceptual foundations needed to build and reason about AI-native products — grounded in Anthropic's official documentation, engineering blog, and best practices.

Not a tutorial on how to use ChatGPT. Not a developer guide. A thinking framework for people who build products where the core intelligence is an LLM.

---

## Who it's for

- Product managers building AI-native features or products
- Founders evaluating how to integrate LLMs into their products
- Hands-on builders who want the product strategy layer, not just the technical implementation
- Anyone who wants to think more clearly about AI products — regardless of experience level

The curriculum adapts to your level. Beginners start from first principles. Experienced builders go deeper on architecture and strategy.

---

## What you'll learn

Six chapters, each building on the last:

| Chapter | Topic |
|---|---|
| 1 | How LLMs Actually Work |
| 2 | Prompt Engineering as Product Design |
| 3 | Agentic Systems — Concepts & Architecture |
| 4 | Evaluating AI Product Quality |
| 5 | Safety, Trust & Responsible AI Product Design |
| 6 | AI Product Strategy & Metrics |

---

## How to use this

### Option 1 — Claude.ai (browser or mobile)
Paste the contents of `prompt.md` into any Claude conversation and follow the instructions. No setup required.

### Option 2 — Claude Code (terminal, VSCode, or Cursor)

**Terminal:**
```bash
# Clone the repo
git clone https://github.com/rahulrkattayil/ai-product-thinking

# Navigate to the project
cd ai-product-thinking

# Start a Claude Code session — setup happens automatically
claude
```

**VSCode or Cursor:**
1. Install the [Claude Code extension](https://marketplace.visualstudio.com/items?itemName=Anthropic.claude-code)
2. Clone and open the repo: `git clone https://github.com/rahulrkattayil/ai-product-thinking && code ai-product-thinking`
3. Open the Claude Code panel — it reads `CLAUDE.md` automatically, creates your tracking files, and enters curriculum mode

No setup script needed. Claude handles first-run setup itself. Your notes, quiz log, and progress are saved locally and gitignored.

### Option 3 — Claude Cowork (desktop)
Open Claude Cowork, create a new project, and paste `prompt.md` as your project instructions. Cowork will manage your progress files and notes across sessions.

---

## Progress tracking

The curriculum supports three modes:

**Local files** — Claude generates markdown notes and quiz logs saved to your working directory after each topic and chapter.

**In-conversation** — Track progress within the conversation only. Export anything you want to keep manually.

**Self-managed** — You handle your own notes externally. Claude focuses on teaching.

Choose your mode when you start. You can switch at any time.

---

## What gets saved

When using local file mode, the following are generated automatically:

```
/notes
  ch1_topic1_tokens_context_attention.md
  ch1_topic2_temperature_stochasticity.md
  ch1_topic3_system_prompts_trust_hierarchy.md
  ch1_topic4_thinking_modes.md
  ch2_topic1_clarity_context_intent.md
  ... and so on for all chapters

/quiz_log.md        ← all questions, your answers, feedback, and gaps noted
/progress.md        ← chapter and topic completion status
```

These files are gitignored — they're yours, not the repo's.

---

## Keeping up with Anthropic

Every time you start or resume a session, the curriculum automatically searches for new Anthropic announcements, blog posts, and documentation updates. Anything relevant gets folded into the appropriate chapter before you continue.

---

## Curriculum design

The teaching format follows these principles:

- **Chunked delivery** — one concept per exchange, not one essay per topic
- **Practical quizzes** — scenario-based questions, not theory recall
- **Adaptive depth** — calibrated to your experience level at the start
- **Expandable** — add topics, go deeper, or explore new Anthropic releases at any point
- **Revision-friendly** — logged gaps and notes make it easy to revisit anything

---

## Contributing

If you've completed the curriculum and want to add topics, improve explanations, or fold in new Anthropic developments — PRs are welcome.

Suggested additions:
- New chapters as Anthropic releases major new capabilities
- Real-world case studies mapped to curriculum concepts
- Language translations

---

## Attribution

Curriculum design and pedagogy by **Rahul Kattayil**.

Grounded in Anthropic's official documentation:
- https://platform.claude.com/docs/en/home
- https://www.anthropic.com/research
- https://www.anthropic.com/news

---

## License

MIT — use freely, adapt freely, attribute where you can.

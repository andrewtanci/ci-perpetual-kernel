# Continuation Intelligence — Perpetual Kernel

**Your AI work compounds. It does not reset.**

A free, copy-paste kernel that preserves your working state across
AI chats. Works on ChatGPT, Claude, Gemini, and any AI platform.
No installation. No setup. Paste and use.

> "Capability must never become authority."

## The problem

AI chats reset. Context drifts. You hit the wall and lose
everything — the decisions, the terms, the working state. The
deeper issue isn't memory. It's control.

## What this does

1. **Activates Continuation Intelligence** in any chat — fresh,
   existing, or memory-aware. It reads the situation and responds.
2. **Migrates your work** — type `MIGRATE` and it extracts a full
   CI Continuation Block you paste into the next chat. Your work
   continues from declared state, not loose reconstruction.

## The honest part

The AI cannot see how full a chat is. It cannot warn you before
the wall. So the trigger is yours:

- **Type MIGRATE at every milestone** — a decision made, a section
  done. This is your insurance.
- **Watch for signs** — slower replies, forgetting, repetition, the
  platform's "long conversation" notice. Any of these → MIGRATE.
- **Type CHECK anytime** — the AI honestly reports whether it can
  still recall the start, and recommends MIGRATE if it's slipping.

No fake fuel gauge. Just honest tools that work.

## Files

- [`kernel/ci-perpetual-kernel.md`](kernel/ci-perpetual-kernel.md) — the main kernel
- [`kernel/claude-rehydration-wrapper.md`](kernel/claude-rehydration-wrapper.md) — use this on Claude
- [`kernel/continuation-block-template.md`](kernel/continuation-block-template.md) — the 18-field block
- [`agent-control/ci-agent-control-kernel.md`](agent-control/ci-agent-control-kernel.md) — for agentic workflows (Codex, Claude Code)

## Note for Claude users

Claude may fall back to its own memory instead of your pasted block.
Use the Claude Rehydration Wrapper — it makes the pasted block the
authoritative state. Without it, Claude can ignore your block.

## From the book

Full method in *Continuation Intelligence: How to Stay in Control
When AI Does the Work* — [Amazon](https://www.amazon.com/dp/B0H4CXR3HJ)

Free kit also at [andrewtanci.gumroad.com/l/ci](https://andrewtanci.gumroad.com/l/ci)

By Andrew Tan 陈治力 · AIGP Certified · Founder, Continuation Intelligence

## License

MIT — free to use, share, and adapt.

# Dev Template — Sol's AI-Assisted Development System

This repo is a **starter template** for all new projects.
Clone this, fill in the stack details in `CLAUDE.md`, and go.

---

## 🔁 The Workflow (cheat sheet)

```
STEP 1 — START A FEATURE
  └─ Write your goal in _dev/spec.md (1–3 sentences is enough)
  └─ Tell Claude Code: "Read CLAUDE.md and spec.md, then write a spec draft"
  └─ Review the draft → mark ✅ Approved or request changes

STEP 2 — BUILD
  └─ Tell Claude Code: "Read CLAUDE.md, spec.md, decision-log.md — then implement"
  └─ Claude Code updates decision-log.md automatically

STEP 3 — RED TEAM REVIEW
  └─ Tell Codex: "Read .codex/instructions.md, spec.md, decision-log.md — then review"
  └─ Get 🔴/🟡/🟢 report + action plan

STEP 4 — REVISE
  └─ Tell Claude Code: "Implement the Codex action plan. Update decision-log."

STEP 5 — SOL CHECKS
  └─ "Is this what I actually wanted?" → done or repeat from step 1
```

---

## 📁 File Reference

| File | Who reads it | Who writes it |
|------|-------------|---------------|
| `CLAUDE.md` | Claude Code (auto) | Sol (stack section) |
| `.codex/instructions.md` | Codex (auto) | — (don't change) |
| `_dev/spec.md` | Both AIs | Sol (goal) + Claude Code (draft) |
| `_dev/decision-log.md` | Both AIs | Both AIs + Sol |

---

## 🚀 New Project Checklist

- [ ] Clone this repo
- [ ] Fill in stack/framework in `CLAUDE.md` (bottom section)
- [ ] Clear the decision log table (keep the header)
- [ ] Write first goal in `spec.md`
- [ ] Start Step 1 above

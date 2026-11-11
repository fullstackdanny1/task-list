# Decisions

Why things are the way they are. Read this before reopening a decision.
Newest first. One entry per decision; do not rewrite old entries, add a new
one that replaces them.

## Entry format

```
## YYYY-MM-DD: short title
Decision: what was decided, in one sentence.
Why: the reason, and what it costs.
Rejected: the alternatives considered and why they lost.
```

## Entries

## 2026-11-11: Front end only, login simulated
Decision: Vue + Vite + Tailwind, in Docker, with no API; login is simulated in the front end.
Why: today's goal is the login page; a server would add work that is not needed yet.
Rejected: building an API now.

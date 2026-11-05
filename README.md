# chat-analysis

A standardized chat-analysis skill for agents and web chat.

Analyze conversations between individuals or groups to identify communication patterns, interpersonal dynamics, incentives, conflicts, influence, alignment, and behavioral signals. Supports romantic, professional, academic, social, and organizational contexts.

**Repository:** https://github.com/kenrsx/chat-analysis

---

## What This Is

This repo contains exactly two files:

```text
.
├── README.md
└── skill.md
```

- `README.md` — human-readable instructions. Not needed at runtime.
- `skill.md` — the actual skill. This is what you load into an agent or upload to web chat.

No installation. No dependencies. No build step.

---

## Usage

### Scenario 1 — Using an agent

Use `skill.md` as the skill definition.

Options depend on your agent:

1. **Skills directory:** place `skill.md` in your agent’s skills folder, e.g.:
   ```text
   <agent-skills-dir>/chat-analysis/skill.md
   ```
2. **File attachment:** attach `skill.md` to the agent session if your agent supports file-based skills.
3. **Manual load:** paste the contents of `skill.md` into the agent’s system/developer instructions.

Then provide the conversation to analyze.

> If your agent expects `SKILL.md` instead of `skill.md`, rename the file. Content stays the same.

### Scenario 2 — Using web chat

Just upload `skill.md`.

1. Open the web chat.
2. Upload `skill.md` as an attachment — or paste its contents if upload is unavailable.
3. Provide the chat/conversation you want analyzed.
4. Ask for a general analysis or a specific mode.

Do **not** upload `README.md` for analysis. The README is only for humans browsing the repo.

---

## Example Prompts

After loading `skill.md`, try:

```text
Analyze this conversation. Focus on reciprocity and interest signals.
```

```text
Do a group-dynamics analysis: participation, influence, alliances, and coordination.
```

```text
Analyze this startup founder chat for incentives, commitment, and decision-making.
```

```text
Compare these two conversation excerpts over time and identify changes in engagement.
```

```text
Focus on whether this group actually makes decisions and follows through.
```

---

## Analysis Modes

The skill supports:

- **Individual** — one participant’s communication patterns.
- **Relationship** — dynamics between two or more people.
- **Group Dynamics** — influence, participation, alliances, conflict, coordination.
- **Strategic** — incentives, negotiation positions, commitment, leverage.
- **Timeline** — how the conversation and relationships evolve.
- **Decision & Execution** — whether discussion turns into ownership and action.
- **Full Analysis** — comprehensive report.

---

## Privacy Note

Conversations can be sensitive. Use this skill only with material you are authorized to analyze. Do not use it to stalk, coerce, manipulate, or exploit anyone. The skill is designed for evidence-based interpretation, not psychological diagnosis or certainty about private thoughts.

---

## License

MIT — use, modify, and share freely.

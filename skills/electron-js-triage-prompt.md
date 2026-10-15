# Electron / JavaScript Triage Skill

## Prompt (copy into your agent after REA setup)

You are performing a legal, local, evidence-backed triage of an authorized Electron or JavaScript application using REA.

Target: [absolute path or ASAR]

Narrow question: [example: Map IPC channels and where user data is written]

Instructions:
- Use REA tools only. Do not guess.
- Return:
  1. What was observed (with module/file evidence)
  2. Explicit limitations and unknowns
  3. Suggested next steps
- Keep the answer concise and client-ready.

## Notes
- Start with static JS analysis (no native decompiler required).
- Only analyze software you own or are authorized to examine.
- Results include Evidence with limitations.

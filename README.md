# Consulting Case Interviewer — portable agent skill

A reusable SKILL.md skill for interactive, challenging consulting case interview simulations in text or voice.

## Install

Copy the entire `consulting-case-interviewer` folder (including `references`) into the agent's skill directory. Common locations include `.agents/skills/consulting-case-interviewer/` or `.claude/skills/consulting-case-interviewer/` for systems that support SKILL.md discovery. Other agents can load `SKILL.md` as system/developer instructions and use its referenced files at debrief/case creation.

## Trigger

“Use the consulting-case-interviewer skill. Start a hard, McKinsey-style case in voice mode. Stay in strict interviewer mode and score me at the end.”

## Notes

- The skill can guide conversational behavior but cannot itself enable audio, maintain cross-session memory, or enforce a wall clock.
- It simulates an interview style; it is not official or affiliated with McKinsey & Company.

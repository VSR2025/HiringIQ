# Hiring IQ · 2024

**An AI-augmented hiring system designed around a single belief: better hiring is a human discipline, not a software problem.**

---

## What This Is

A portfolio case study documenting an end-to-end hiring system applied across three PM hires and subsequently adopted by three other organisations. The system embeds AI at specific, deliberate points — always in service of human judgment, never replacing it.

Built as a single-page interactive HTML artifact. No frameworks, no dependencies.

---

## The System — Five Phases

| Phase | Stage | What Happens |
|-------|-------|--------------|
| 00 | Before everything | Recruiter and hiring manager co-define signal criteria. AI audits recruiter notes for inadvertent bias. |
| 01 | Before interviews | Hiring manager writes a year-one letter. AI sharpens vague language into observable behaviours. |
| 02 | Interview design | Panel assembled with distinct signal ownership. AI audits for redundancy and blind spots. |
| 03 | In the room | Interviewer stays fully present. AI transcribes verbatim — no interpretation, no flags. |
| 04 | The debrief | AI reads across all transcripts for cross-interview patterns. Assessments audited for unsupported opinions. Human makes the call — including overriding AI. |

---

## Design Principles

- **Human design always comes first.** Every phase starts with what a thoughtful, disciplined person would do. AI enters after.
- **AI augments, never authors.** It sharpens criteria, flags gaps, surfaces patterns. It does not assess candidates or make decisions.
- **Guardrails are explicit.** Every phase documents what AI was specifically instructed not to do.
- **The human override is a feature, not a failure.** When a human overrides a clean AI scorecard, the system is working as designed — judgment over algorithm.

---

## What's Interactive

- Hover tooltips on flagged vague language (Phase 01 demo)
- Expandable prompts — each AI box shows the exact prompt used, on demand
- Journey map navigation — click any phase to scroll directly to it

---

## Outcomes

- 5 → 4 interview rounds (redundant loops eliminated)
- ~4 async meetings eliminated per hire
- 3 PM hires completed using the system
- 3 other organisations adopted it after seeing it in practice

---

## Stack

Single-file HTML · CSS custom properties · Vanilla JS · Google Fonts (Cormorant Garamond + Outfit)

No build process. Open `index.html` in any browser.

---

## Context

Developed as part of an AI-first consulting practice. The methodology — embedding AI with discipline, not just tools — is what built credibility with clients who subsequently adopted the system themselves.

Part of a broader portfolio of AI transformation frameworks including the GTM Reimagination Assessment and the Art of the Possible / Art of the Feasible methodology.

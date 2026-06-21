# Claim-to-Patch Ledger: Cloud Agent Handoff Kit

Status: template-ready, evidence pending.

Use this ledger after the next real cloud-agent delegation trial to decide which public claims can change, which must stay provisional, and which files need patches. Do not mark the package validated from a blank ledger.

## Trial identity

- Trial date:
- Operator:
- Repo/task:
- Source packet: [[Cloud Agent Handoff Kit/Cloud Agent Handoff Packet]]
- Evidence index: [[Cloud Agent Handoff Kit/Trial Evidence Index]]
- Evidence rubric: [[Cloud Agent Handoff Kit/Cloud Handoff Evidence Quality Rubric]]
- Promotion card: [[Cloud Agent Handoff Kit/Cloud Agent Promotion Decision Card]]
- Debrief: [[Cloud Agent Handoff Kit/Cloud Handoff Post-Trial Debrief Template]]

## Claim-to-patch table

| Proposed claim | Evidence link(s) required | Rubric note / score | Allowed wording now | Patch target(s) | Decision |
|---|---|---|---|---|---|
| Cloud handoff packet reliably scopes one small repo task for a remote coding agent. | Filled packet, task issue/PR link, agent transcript. |  | Template-ready; evidence pending. | Package README, prototype README, skill draft. | promote / narrow / hold |
| Evidence gate catches incomplete or unverifiable cloud-agent outputs before PR acceptance. | Failed or passed acceptance checklist, reviewer note, diff link. |  | Proposed review gate, not validated. | Prototype packet, promotion card, skill draft. | promote / narrow / hold |
| Phone-to-PR delegation is reusable enough for VinClawLabs cloud-agent workflows. | At least one end-to-end task with time, quality, and cleanup notes. |  | Candidate workflow, not validated. | Package README, root README, skill draft. | promote / pilot-only / hold |
| The package should become an installed Hermes skill. | Repeatable run steps, known pitfalls, evidence from real task. |  | Keep as draft. | `Artifacts/Skills/cloud-agent-handoff-procedure/SKILL.md`; installed skill only after evidence. | promote / defer |

## Patch queue

| File | Patch summary | Evidence link | Owner | Status |
|---|---|---|---|---|
| `Artifacts/Generated-Packages/Cloud Agent Handoff Kit/README.md` |  |  |  | not started |
| `Artifacts/Prototypes/Cloud Agent Handoff Kit/README.md` |  |  |  | not started |
| `Artifacts/Skills/cloud-agent-handoff-procedure/SKILL.md` |  |  |  | not started |
| GitHub repo `README.md` |  |  |  | not started |

## Guardrails

- Keep current wording as template-ready/evidence-pending until proof links are attached.
- Patch claims only when the evidence index and rubric both support the change.
- If evidence is mixed, narrow the claim rather than promoting the whole workflow.
- If evidence is missing, record the blocker and leave public claims unchanged.

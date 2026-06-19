# Cloud Agent Promotion Decision Card

Status: template-ready, evidence-pending. Use this after one real cloud-agent handoff trial; it is a decision gate, not validation proof.

Source package: [[Cloud Agent Handoff Kit]]  
Trial packet: [[Cloud Agent Handoff Kit/Cloud Agent Handoff Packet]]  
Loop: [[Cloud Agent Handoff Kit Loop]]

## Evidence prerequisites

| Evidence slot | Required link or note | Pass condition | Filled? |
|---|---|---|---|
| Real task brief |  | Task was a real repo/product task, not a synthetic demo. | ☐ |
| Handoff packet |  | Scope, acceptance criteria, blocked paths, and review owner were filled before the run. | ☐ |
| Agent activity trace |  | Transcript/log/screenshot shows what the cloud agent attempted and where it needed help. | ☐ |
| Output artifact |  | PR, diff, branch, patch, or design artifact is linked and inspectable. | ☐ |
| Human review result |  | Reviewer notes identify accepted changes, rejected changes, and safety issues. | ☐ |
| Follow-up action |  | Next step is explicit: merge, revise, rerun, or retire the workflow. | ☐ |

## Decision gate

Choose exactly one after the evidence bundle is complete:

- **Promote** — handoff packet reliably produced reviewable work with low operator overhead and clear proof links.
- **Pilot-only** — useful for narrow tasks, but needs tighter scope, smaller diffs, or stronger review before general use.
- **Iterate** — evidence shows promise but the packet missed context, acceptance criteria, permissions, or proof capture.
- **Hold** — agent output or process risk outweighed the benefit; do not promote until the failure mode is fixed.

Decision: ☐ Promote ☐ Pilot-only ☐ Iterate ☐ Hold  
Rationale:

## Claim patch checklist

Only patch claims after the decision is selected and evidence links are attached.

- [ ] Package README updated only with observed outcomes.
- [ ] Prototype README updated with any new guardrails or sequencing fixes.
- [ ] Skill draft updated only if the handoff procedure repeated cleanly.
- [ ] Improvement loop next focus changed to the next evidence-backed action.
- [ ] Any public/GitHub README wording remains evidence-pending unless promotion was earned.

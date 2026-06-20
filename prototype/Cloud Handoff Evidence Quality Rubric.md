# Cloud Handoff Evidence Quality Rubric

Source: [[Cursor Cloud Subagents From Phone to PR]]  
Package: [[Cloud Agent Handoff Kit]]  
Status: template-ready; evidence pending.

## Purpose
Grade whether future cloud-agent handoff proof is strong enough to change package README, prototype, infographic, or skill-draft claims. This rubric is not validation by itself; it is the gate for judging a future real trial.

## Minimum evidence bundle
| Evidence slot | What must be linked or pasted | Evidence link / note |
|---|---|---|
| Task brief and repo scope | Link to issue/README/branch plus exact expected agent output |  |
| Agent transcript or run log | Cloud-agent conversation, job URL, or exported trace showing instructions and constraints |  |
| Code/output diff | PR, commit diff, generated artifact, or patch bundle produced by the agent |  |
| Review evidence | Human review notes, failing/passing checks, screenshots, or comments proving acceptance criteria were checked |  |
| Rollback / containment note | How to revert the cloud-agent work if it is wrong or unsafe |  |
| Decision artifacts filled | Promotion card and post-trial debrief completed from evidence links, not memory |  |

## Scoring gate
| Outcome | Use only when | Decision notes |
|---|---|---|
| Promote to repeatable pilot | All required evidence links exist, review passes, rollback is clear, and debrief names only evidence-backed claim patches. | |
| Pilot-only / narrow | Core handoff works but task class, repo scope, or review burden must be narrowed before reuse. | |
| Iterate | Evidence is incomplete, acceptance checks are ambiguous, or the agent needed too much rescue to trust the flow. | |
| Hold | No real task proof, unsafe permissions, missing rollback, or unreviewed code/output. | |

## Claim patch checklist
- [ ] Evidence bundle is filled with durable links or pasted excerpts.
- [ ] Cloud Agent Promotion Decision Card is completed from evidence, not memory.
- [ ] Cloud Handoff Post-Trial Debrief Template lists exact README/prototype/skill-draft claims to patch.
- [ ] Any public wording still says template-ready/evidence-pending unless the scoring gate explicitly allows stronger claims.
- [ ] Claims that lack proof are moved to backlog instead of promoted.

## Operator notes
- Treat missing screenshots, logs, diffs, or review notes as a failed evidence slot.
- Prefer a narrow pilot decision over broad reusable-workflow claims when proof comes from only one task.
- Keep all future claim patches reversible and linked back to the evidence row that justified them.

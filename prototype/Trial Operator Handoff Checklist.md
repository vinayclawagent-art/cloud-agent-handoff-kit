# Cloud Agent Trial Operator Handoff Checklist

Source: [[Cursor Cloud Subagents From Phone to PR]]
Package: [[Cloud Agent Handoff Kit]]
Status: template-ready; evidence pending.

Use this before the next real phone-to-PR delegation trial so the operator records the right proof before accepting a cloud-agent PR or changing public kit claims.

## Operator sequence

1. Open [[Cloud Agent Handoff Kit/Cloud Agent Handoff Packet]] and choose one small real repo task with bounded risk.
2. Define repo, branch, expected diff, acceptance tests, safety constraints, and rollback plan before the cloud agent starts.
3. During the run, capture prompt/handoff text, cloud-agent logs, PR/diff links, CI/test output, review comments, and any manual fixes.
4. Complete [[Cloud Agent Handoff Kit/Cloud Agent Promotion Decision Card]] using only captured proof.
5. Fill [[Cloud Agent Handoff Kit/Cloud Handoff Post-Trial Debrief Template]] and list which README, prototype, infographic, or skill-draft claims are safe to patch.
6. Patch public claims only if the evidence supports them; otherwise keep the kit template-ready/evidence-pending.

## Minimum evidence bundle

| Evidence slot | Required before claim changes? | Link / notes |
| --- | --- | --- |
| Real repo task and owner | Yes |  |
| Initial branch/status screenshot or command output | Yes |  |
| Handoff prompt and cloud-agent transcript | Yes |  |
| PR/diff link and test/CI result | Yes |  |
| Human review notes and fixes | Yes |  |
| Promotion decision outcome | Yes |  |
| Debrief patch targets | Yes |  |

## Handoff result block

- Trial date:
- Operator:
- Repo/task:
- Evidence bundle complete? Yes / No
- Promotion card outcome: promote / pilot-only / iterate / hold
- Debrief completed? Yes / No
- Claims safe to update:
- Claims that must remain template-ready:
- Follow-up owner:

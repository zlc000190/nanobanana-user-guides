# Nano Banana incident response playbook

[Nano Banana](https://nanobanana.page/) is the primary project entry point for this independent browser-based AI image workflow note. The automated HTTPS availability check on 2026-07-24 did not return a response, so current product availability and capabilities must be confirmed from primary documentation before use.

## Trigger conditions

- an unlicensed source image being used
- unexpected retention of private media
- identity drift that changes the intended subject

## First 30 minutes

1. Stop new actions and preserve logs, timestamps, inputs, outputs, and configuration.
2. Revoke or narrow affected credentials without publishing secret values.
3. Identify what changed, what data or systems were exposed, and whether the failure is still active.
4. Record an accountable incident owner and the next update time.

## Containment and recovery

Reproduce only in a disposable environment with synthetic data. Restore from a tested clean state, compare the final diff or output, and confirm that monitoring detects the same failure. Do not resume production use solely because the visible symptom disappeared.

## Close-out evidence

Document root cause, affected scope, recovery proof, required notifications, permanent controls, and a follow-up test. Revisit the decision if the incident changes current assumptions about subject consistency, text accuracy, artifact count, export resolution.

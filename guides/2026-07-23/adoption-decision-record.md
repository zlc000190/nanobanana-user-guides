# Nano Banana adoption decision record

[Nano Banana](https://nanobanana.page/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for designers benchmarking repeatable image generation and transformation; they are not official product documentation.

Use only images you are allowed to upload and verify current privacy, retention, and commercial-use terms.

## Decision statement

Write a one-sentence decision: adopt, pilot with constraints, defer, or reject. Name the exact workflow rather than approving a browser-based AI image workflow in general.

## Evidence table

Record the benchmark date, tested inputs, observed strengths, unresolved failures, security review, accessibility review, total operating cost, and who owns ongoing maintenance. Link to raw evidence instead of relying on memory.

## Required controls

- Define an owner and measurable acceptance threshold for prompt adherence
- Define an owner and measurable acceptance threshold for subject consistency
- Define an owner and measurable acceptance threshold for edge quality
- Define an owner and measurable acceptance threshold for text rendering
- Define an owner and measurable acceptance threshold for export resolution
- Define an owner and measurable acceptance threshold for usage rights

## Revisit triggers

Review the decision after a material pricing, model, policy, ownership, availability, or licensing change. Also revisit after any security incident or repeated output-quality regression.

## Current conclusion

Reject a workflow that cannot preserve required subjects, rights, or export quality across a small reproducible benchmark. Until that condition is satisfied, keep the decision at “defer” or “pilot with constraints,” not full production approval.

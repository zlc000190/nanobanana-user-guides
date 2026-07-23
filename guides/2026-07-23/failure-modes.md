# Nano Banana failure-mode checklist

[Nano Banana](https://nanobanana.page/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for designers benchmarking repeatable image generation and transformation; they are not official product documentation.

Use only images you are allowed to upload and verify current privacy, retention, and commercial-use terms.

## Known classes of failure to test

- identity drift
- broken typography
- lost transparency
- unwanted artifacts
- irreproducible reruns
- unclear image retention

## How to test safely

Trigger one edge case at a time with low-risk data. Record the exact input, visible error, retry behavior, and whether the system fails open or closed. Do not use repeated blind retries; they can hide nondeterminism, create duplicate actions, or increase cost.

## Recovery evidence

A credible recovery path explains what state was changed, how to undo it, and whether a second operator can reproduce the fix. If recovery depends on undocumented support intervention, count that as operational risk.

## Stop condition

Reject a workflow that cannot preserve required subjects, rights, or export quality across a small reproducible benchmark.

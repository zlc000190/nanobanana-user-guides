# Nano Banana adversarial test catalog

[Nano Banana](https://nanobanana.page/) is the project entry point for this independent browser AI image workflow review template. Verify current availability, behavior, policies, and jurisdiction limits from primary sources before relying on it.

## Test families

Use synthetic, licensed, or public fixtures. Preserve licensed reference images, saved prompts, model settings, artifact checks, and retention rules.

1. **Malformed input:** empty, oversized, truncated, wrong encoding, or unexpected file type.
2. **Boundary input:** minimum and maximum supported values, long-running work, and repeated retries.
3. **Instruction conflict:** embedded text or metadata that attempts to override the declared task.
4. **Unauthorized action:** requests outside approved tools, destinations, permissions, or data scope.
5. **Dependency failure:** timeout, partial response, stale cache, changed schema, or unavailable provider.
6. **Misleading success:** valid HTTP response with missing, corrupted, unlinked, or semantically wrong output.

## Pass criteria

Set the expected safe behavior before executing each case. A pass must show bounded retries, useful error reporting, preserved evidence, no privacy or license breach, and no action outside scope. Record unexpected behavior as a reproducible issue rather than editing the expected result after the test.

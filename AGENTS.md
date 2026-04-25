# AGENTS.md

This repository is a maintained fork of `tjboudreaux/cc-thinking-skills`.

## Vendored Upstream Content

The skill content under `skills/` is upstream-owned content from
`tjboudreaux/cc-thinking-skills`.

AI agents may edit wrapper-owned files such as `.codex-plugin/`,
`.github/workflows/`, documentation, and validation scripts as normal.

Before editing files under `skills/`, AI agents must warn the user that the file is
upstream-owned and explain that the change may diverge from future upstream syncs.
Proceed only when the user explicitly confirms the local divergence or when the task
is specifically to resolve an upstream sync conflict.

## Repository Purpose

This repository packages the upstream thinking skills collection for marketplace
installation in Claude and Codex. It should preserve upstream skill behavior unless
a reviewed local divergence is explicitly requested.

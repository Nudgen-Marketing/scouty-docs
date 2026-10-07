# Scouty documentation

This repository contains the English end-user documentation for [Scouty](https://scouty.to/). It is a Mintlify project: pages are MDX files and navigation, branding, and site settings live in `docs.json`.

## Local preview

Install the current Mintlify CLI, then run it from the repository root:

```bash
npm install --global mint
mint dev
```

Before opening a pull request, run:

```bash
mint validate
mint broken-links
mint a11y
```

## Writing and review

- Verify behavior and button names against the Scouty application before changing a workflow.
- Write for customers in concise English. State the purpose, prerequisites, steps, expected result, and recovery path.
- Link related pages instead of repeating a full workflow.
- Do not publish secrets, infrastructure details, internal endpoints, migration instructions, or unverified quota numbers.
- Do not document removed UI such as **Save to project** or **Saved leads**.

Changes to the default branch may publish automatically. Work in a branch and merge through a reviewed pull request.

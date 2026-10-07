# GoldenCheetah Tools

Public repository reserved for reusable GoldenCheetah analysis, automation, and configuration helpers.

## Purpose

Version-control reusable endurance-data tooling and analysis configurations independently from personal activity archives.

The repository is a planned workspace. Specific integrations and analysis requirements will be established when implementation begins.

## Current status

Repository bootstrap. No automation or GoldenCheetah compatibility is claimed yet.

## Planned contents

- Analysis scripts and reusable chart definitions.
- Exported perspective or configuration helpers where supported.
- Data conversion, import/export validation, and batch-processing utilities.
- Synthetic fixtures for testing metric calculations.
- Documentation of dependencies, supported versions, and reproduction steps.

## Planned layout

```text
scripts/               Analysis, conversion, and automation code
charts/                Reusable chart definitions
configs/               Sanitized configuration examples
tests/                 Synthetic fixtures and reference calculations
docs/                  Installation, compatibility, and usage
handoff/               CURRENT_STATE.md
```

## Technical controls

Record GoldenCheetah and dependency versions for each tool. Document required input fields, units, missing-data handling, and metric definitions. Verify transformations and derived metrics against explicit reference cases before releasing them.

## Public data policy

Commit code, reusable configurations, documentation, and synthetic or expressly shareable fixtures. Exclude personal activity archives, precise GPS tracks, health records, account tokens, credentials, and licensed third-party data.

## Work control

A Git commit identifies the working state. Use branches, pull requests, and tagged releases as tooling develops. Record the repository, branch, commit SHA, objective, acceptance criteria, and next action in `handoff/CURRENT_STATE.md`.


# PAAVALI — ChatGPT account migration checkpoint

Date: 2026-09-18

This file records the operational state of the PAAVALI project at the point where work was transferred from the previous ChatGPT account to the replacement account.

## Verified migration state

The following have been verified:

- `Ewoc2026/paavali` is the canonical persistent project memory.
- `CHATGPT_HANDOFF.md` exists and defines the bootstrap procedure for a replacement ChatGPT account.
- `SOURCE_MANIFEST.md` identifies the four local source files used by the project and records their SHA-256 checksums, provenance and licensing notes.
- The replacement ChatGPT account has a PAAVALI project with the project instructions derived from `CHATGPT_HANDOFF.md`.
- The replacement account can read the GitHub repository and correctly resolved the expected `main` state during bootstrap.
- The four local project source files were loaded into the replacement PAAVALI project.
- The replacement account successfully reconstructed the project's main research question, active branches, current hypotheses, major counterevidence and methodological limits from the repository and local sources.
- GitHub write access from the replacement account was verified with commit `7a38d4eda54dc13c830b7e6e0712ac7253fbc4e8` (`Verify replacement ChatGPT write access`).
- That write-access verification changed only `CHATGPT_HANDOFF.md` and explicitly did not alter the research state.

## Local source corpus

The replacement PAAVALI project uses:

- `SRC_N1904_CORE.txt`
- `SRC_FINPR_CORE.txt`
- `SRC_HEB1008_HAB.txt`
- `SRC_LXX_SWETE_HAB.txt`

Their exact checksums and provenance are canonicalized in `SOURCE_MANIFEST.md`.

## Old ChatGPT account

The old account is no longer required to reconstruct the current PAAVALI research state.

A full ChatGPT data export was requested on 2026-09-18 as a cold archival backup.

Verification of the downloaded export package is intentionally not a migration blocker. When the package becomes available, it may be checked and stored offline as historical backup material, but it should not become the canonical PAAVALI working memory.

## Canonical precedence

If old ChatGPT conversations later differ from the repository:

1. treat the current repository as the canonical project state,
2. do not silently restore an older formulation,
3. evaluate any apparently missing old observation using the PAAVALI method,
4. migrate it only if it still has durable research value.

## Checkpoint meaning

At this checkpoint the project has demonstrated that it can continue on the replacement ChatGPT account without relying on the previous account's memory or conversation context.

This checkpoint records operational migration status only. It does not strengthen, weaken or otherwise change any exegetical hypothesis.

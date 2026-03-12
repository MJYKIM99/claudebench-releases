# ClaudeBench Releases

Official public release repository for ClaudeBench.

This repository is for:
- signed desktop download assets
- GitHub Release pages and checksums
- lightweight public release metadata

This repository is not the application source code repository. ClaudeBench is now distributed as a closed-source product, so this repo only contains public release-facing materials.

## What Is ClaudeBench

ClaudeBench is a desktop app built around Claude-powered workflows for coding, files, research, and task execution on macOS.

## Downloads

Latest public release:

| Version | Platform | Download |
| --- | --- | --- |
| `v0.1.9` | macOS (Apple Silicon) | [Claude_Bench_0.1.9_arm64.dmg](https://github.com/MJYKIM99/claudebench-releases/releases/download/v0.1.9/Claude_Bench_0.1.9_arm64.dmg) |

Release history:

| Version | Date | Notes | Assets |
| --- | --- | --- | --- |
| `v0.1.9` | 2026-02-19 | Nested skill discovery and model updates | [Release](https://github.com/MJYKIM99/claudebench-releases/releases/tag/v0.1.9) |
| `v0.1.8` | 2026-02-08 | Gemini image generation and UX improvements | [Release](https://github.com/MJYKIM99/claudebench-releases/releases/tag/v0.1.8) |
| `v0.1.7` | 2026-02-08 | Cover editor enhancements | [Release](https://github.com/MJYKIM99/claudebench-releases/releases/tag/v0.1.7) |

## Installation

1. Download the DMG for your version.
2. Open the DMG and drag ClaudeBench into `Applications`.
3. Launch the app and complete the first-run setup.

## System Requirements

- macOS 13 or later
- Apple Silicon for current public DMG builds
- Internet connection for model/provider access

## Repository Scope

Public content that belongs here:
- release notes
- signed binaries uploaded as GitHub Release assets
- checksums
- public-facing version metadata

Content that does not belong here:
- application source code
- internal tooling
- signing secrets
- private build scripts or internal operator docs

## Links

- Website: [claudebench.com](https://claudebench.com)
- Download page: [claudebench.com/download](https://claudebench.com/download)
- Support: [claudebench.com/support](https://claudebench.com/support)

## Maintainer Notes

If website download URLs change, keep this repository and `claudebenchweb` aligned. Public asset URLs from GitHub Releases should be treated as stable release endpoints.

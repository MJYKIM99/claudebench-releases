# Releasing

This repository is the public distribution target for ClaudeBench desktop builds.

## Goals

- keep release binaries out of git history
- expose stable public download URLs through GitHub Releases
- keep public release notes separate from private source code repositories

## Standard Flow

1. Build and validate the app from the private main repository.
2. Produce signed and notarized release artifacts.
3. Generate SHA-256 checksums.
4. Create or update a GitHub Release in this repository using tag `vX.Y.Z`.
5. Upload the release assets.
6. Update the matching metadata file in `releases/`.
7. If needed, update `claudebenchweb` links to the new version.

## Release Asset Conventions

Preferred asset names:

- `Claude_Bench_<version>_arm64.dmg`
- `Claude_Bench_<version>_x64.dmg`
- `checksums.txt`

Legacy assets may use older names. Do not rename already-published assets unless downstream links are updated.

## Public Repo Rules

- Do not commit DMGs directly into git.
- Do not add internal build commands, secrets, or private infrastructure details.
- Keep wording public-safe and product-facing.
- Treat release URLs as externally referenced endpoints.

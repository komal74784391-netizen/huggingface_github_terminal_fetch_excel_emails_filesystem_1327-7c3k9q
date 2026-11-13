# Atlas Data Cooperative - Release Train

This repository holds the release train for the co-op's public data packages:
the launch manifest, the per-package provenance manifests and the quarterly
license register.

## Layout

- `manifest/release_manifest.json` - packages shipping in the current train and their channel.
- `packages/<name>/MANIFEST.json` - provenance for each package (raw data sources and synthesis models).
- `release-register.csv` - quarterly license register, one row per package release.
- `LICENSE-POLICY.md` - standing license policy for public data packages.
- `docs/SIGNOFF-TEMPLATE.md` - required formats for license sign-off records.
- `signoff/` - machine-readable sign-off records produced for each launch.

## Q4 2026 public launch

Launch window: 2026-11-14 09:00 UTC.

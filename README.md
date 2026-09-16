# Dictum — releases

Installer and update feed for the Dictum desktop app (histopathology reporting workstation by SciScribe).
The source repository is private; this repository holds only what an installed copy of Dictum needs:

- `Dictum-Setup-<version>.exe` — the Windows installer (NSIS, per-user)
- `Dictum-Setup-<version>.exe.blockmap` — differential-update map
- `latest.yml` — the update feed electron-updater reads

Releases are published here by the source repository's `release.yml` on a `v*` tag. Nothing in this repository
contains patient data or lab-owned content.

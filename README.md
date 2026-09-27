# Solis App Updates

This repository is the release feed for the native Solis desktop application.

Stable Windows releases are published here as GitHub Releases by the build workflow in `solis-syst/solis-app`.

Release assets include:
- the Windows NSIS installer
- the matching `.sha256` checksum file
- the application executable used as the delta target
- its matching `.sha256` checksum file
- a binary delta from the immediately previous stable version when the delta is smaller than the new application executable
- the matching delta `.sha256` checksum file

The repository contains release artifacts and no application source code.

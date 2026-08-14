---
version: "0.1.0b"
created_at: "2026-08-14T11:40:00+07:00,ATHER"
last_update: "2026-08-14T11:40:00+07:00,ATHER"
status: "beta"
superseded_by: null
attributes:
  domain: "release-distribution"
  doc_type: "release-policy"
  scope: "FUNG Desktop public binaries"
---

# FUNG Desktop Release Policy

## Contract

- Public releases contain Desktop binaries and distribution metadata only.
- The Windows x64 installer asset is always named
  `FUNG-windows-x64-setup.exe`.
- The website uses the `releases/latest/download` URL from this repository.
- Every published asset must match `release-manifest.sha256` before it is
  promoted on the FUNG website.
- A release tag is immutable; corrections require a new version.
- Mobile artifacts are out of scope until they pass their own release gates.

## Current release

| Version | Platform | Profile | Status |
| --- | --- | --- | --- |
| v0.1.0 | Windows x64 | CPU int8 | Public beta |

## Version Diff

| Version | Change |
| --- | --- |
| 0.1.0b | Initial public Desktop binary distribution policy. |

## CHANGELOG

| Version | Date | Status | Summary | Commit Hash | Agent |
| --- | --- | --- | --- | --- | --- |
| 0.1.0b | 2026-08-14 | beta | Added the Desktop-only public binary, stable-name, and hash-verification contract. | pending | ATHER |

# Changelog
All notable changes to this project will be documented in this file.

The format is based on **Keep a Changelog**, and this project adheres to **semantic versioning** (MAJOR.MINOR.PATCH).

---

## [v1.0] – 2026-02-01
### Added
- Initial production‑ready release of the DNS allowlist and blocklist.
- Added `allowlist.txt` containing required domains for:
  - Streaming services (Netflix, Prime Video, Disney+, YouTube)
  - Smart home platforms (SmartThings, Ring, Kuna, Samsung/LG TV, Roku)
  - Gaming networks (Xbox, PlayStation, Steam, EA)
  - Cloud providers and CDNs
  - Mobile OS services (Android, iOS)
  - Canadian banking and financial services
- Added `blocklist.txt` targeting:
  - Advertising networks
  - Trackers and analytics
  - Telemetry services
  - Scam, phishing, and malware domains
  - Crypto‑mining hosts
  - Push‑notification spam
  - Mobile tracking SDKs

### Notes
- This release establishes the baseline version for future updates.
- Designed for real‑world home networks with smart devices and streaming services.
- Balanced approach: strong privacy protection with minimal false positives.

---

## [Unreleased]
### Planned
- Additional category‑specific allowlists (e.g., gaming, IoT, streaming).
- Optional “aggressive” blocklist module.
- Regional CDN optimization entries.
- Automated validation and domain testing workflow.

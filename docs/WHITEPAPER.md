# Technical Whitepaper — CORE

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/home-assistant/core
**Category:** CONSUMER_APPLIANCES

## Abstract

This whitepaper describes the Anticloud integration of `CORE` (Home automation platform for smart appliances)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local voice assistant replacing cloud voice APIs
2. Single-binary firmware update package with AIOSS-verified integrity
3. AES-256 encryption for all usage telemetry stored on-device
4. Zero-cloud operation mode: full functionality without internet connectivity
5. Local energy optimization inference replacing cloud energy management APIs
6. GPU/CPU equalizer: inference scales to embedded ARM or x86
7. AIOSS audit chain for all firmware updates and configuration changes
8. Open CLI for configuration replacing proprietary mobile app requirement

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.
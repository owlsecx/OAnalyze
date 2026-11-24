# 🦉 OAnalyze

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCipher-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OAnalyze** — Cryptanalysis and cipher breaking tool

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OAnalyze is a professional cryptanalysis suite for breaking and studying classical ciphers and inspecting unknown data. It provides frequency analysis, Index of Coincidence, Kasiski testing, Vigenère and substitution solvers, Caesar/ROT analysis and rail-fence/Atbash/Affine modules, alongside hash identification and cracking. Entropy and encoding detectors help triage unknown blobs, and an auto-analyze pipeline chains the modules for a first pass.

---

## ✨ Features

- Frequency analysis, Index of Coincidence and Kasiski key-length detection
- Automatic Vigenère and hill-climb substitution cipher breakers
- Caesar / ROT-N analysis and rail-fence, Atbash and Affine modules
- Signature-based hash identification plus dictionary and brute-force cracking
- Shannon entropy and Base64/32/16/URL/hex encoding detection
- Auto-analyze pipeline and non-interactive file analysis mode

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OAnalyze cipher.txt
./OAnalyze
./OAnalyze --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, bundled CPython version, and every bundled library with its exact
  version and license. Feed it to Grype, Trivy or Dependency-Track to audit
  our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

**No telemetry, no analytics, no licence check-in.** This tool does not phone
home. Verify that claim yourself:

```bash
sudo strace -f -e trace=network ./OAnalyze --help   # watch every network call
firejail --net=none ./OAnalyze --help               # deny the network entirely
```

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)

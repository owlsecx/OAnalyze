# 🦉 OAnalyze

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCipher-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
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

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*

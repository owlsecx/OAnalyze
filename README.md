# 🔍 OAnalyze

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OCryptanalysis-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OAnalyze** is a comprehensive classical cryptanalysis tool. It supports frequency analysis, Index of Coincidence, Kasiski test, Vigenère breaker, Caesar breaker, hash identification, hash cracking, pattern detection, and entropy analysis.

---

## 📌 Overview

OAnalyze helps break and understand classical ciphers using proven cryptanalysis techniques. It provides detailed statistics, visual frequency charts, key length hints, automatic decryption attempts, and hash analysis in a clean terminal interface.

---

## 🖥️ Modules

| #  | Module                    | Description |
|----|---------------------------|-------------|
| **[1]**  | **Frequency Analysis**        | Letter frequency distribution + English comparison |
| **[2]**  | **Index of Coincidence**      | Detect monoalphabetic vs polyalphabetic ciphers |
| **[3]**  | **Kasiski Test**              | Find probable Vigenère key length |
| **[4]**  | **Vigenère Breaker**          | Automatic Vigenère decryption |
| **[5]**  | **Caesar Breaker**            | Frequency-based Caesar shift crack |
| **[6]**  | **Hash Identifier**           | Identify hash type by pattern and length |
| **[7]**  | **Hash Cracker**              | Dictionary + short brute-force attack |
| **[8]**  | **Pattern Detector**          | Digrams, trigrams, repeated substrings |
| **[9]**  | **Entropy Analyzer**          | Measure randomness and detect encryption |
| **[10]** | **Auto Analyze**              | Full cryptanalysis pipeline |

---

## 📊 Key Features

- **Frequency Analysis** — Visual bar charts with English comparison
- **Index of Coincidence** — Classifies cipher type (mono/poly/random)
- **Kasiski Test** — Detects repeated sequences to guess key length
- **Vigenère Breaker** — Automatic key recovery using IC + frequency
- **Caesar Breaker** — Fast frequency-based decryption
- **Hash Identification** — Recognizes MD5, SHA family, bcrypt, Argon2, etc.
- **Hash Cracking** — Built-in common passwords + brute force (short lengths)
- **Pattern & Entropy Analysis** — Detects repeats, keyboard patterns, randomness
- **Live Export** — JSON and TXT reports for every module

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — pure Python with standard library

---

## 🚀 Usage

```bash
./OAnalyze

📁 Output

Colored Terminal Reports — Visual frequency bars, IC gauges, recommendations
JSON Exports — Full data for every analysis (frequencies, key guesses, entropy, etc.)
TXT Exports — Human-readable summary
Auto Analysis — Complete pipeline with all metrics in one report


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled.S.Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED CRYPTANALYSIS & SECURITY RESEARCH USE ONLY

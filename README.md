# 🦉 OScorer

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OScorer** — PowerShell Obfuscation Scorer

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OScorer is a risk-scoring tool for PowerShell obfuscation techniques. It analyses PowerShell script files or command strings, detects obfuscation indicators, and assigns a risk score. It can scan directories recursively and save JSON reports.

---

## ✨ Features

- Analyses .ps1 script files or inline PowerShell command strings
- Risk scoring for common PowerShell obfuscation techniques
- Recursive batch scanning of a directory
- Configurable minimum score threshold for saving reports
- JSON report and alert-log output to a chosen directory
- Offline sandboxed self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OScorer -f script.ps1
./OScorer -c "IEX (New-Object Net.WebClient).DownloadString('...')"
./OScorer --batch-dir ./scripts --min-score 70
./OScorer --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled.s.Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*

# Suhas P — Embedded Linux & Firmware Engineer

Over 3 years production experience building secure firmware systems for embedded Linux devices. Currently exploring opportunities in embedded systems, firmware, and secure OTA infrastructure.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-suhas--p-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddu-suhas)
[![Portfolio](https://img.shields.io/badge/Portfolio-suhasp.dev-6D5CF0?style=flat-square)](https://suhasp.dev)
[![Email](https://img.shields.io/badge/Email-say%20hi-2EB8F2?style=flat-square&logo=maildotru&logoColor=white)](mailto:siddusuhaas124@gmail.com)

---

## What I Build

**fota-secure** — Production OTA firmware updater with cryptographic security

- AES-256-CBC envelope encryption + RSA-2048 signature verification
- Constant-time downgrade protection with SHA-256 secret hashing
- Defends against ciphertext tampering, mix-and-match attacks, path traversal, decompression bombs
- Python packager & C consumer on AMLOGIC/CVITEK SoCs
- Full threat model & integration tests

[→ View on GitHub](https://github.com/siddusuhaas/fota-secure)

---

## Experience

**Embedded Engineer II & Team Lead** — Probots Electronics (Feb 2023 – Apr 2026)

- Secure OTA systems: streaming AES-256-CBC decryption, RSA-2048 verification, downgrade protection on AMLOGIC/CVITEK SoCs
- Reverse engineered proprietary BTC miner firmware (zero vendor docs) using logic analyzer, Wireshark, and Ghidra; built production replacement firmware on ESP32 with FreeRTOS
- Fleet reliability: 95% → 99.9% uptime through heap leak and IPC race condition fixes
- STM32 Linux-capable MPU: userspace debugging, systemd service management and firmware development

---

## Stack

**Languages:** Embedded C, Python, Rust (log parser CLI)  
**Linux:** Userspace debugging (GDB, Valgrind, strace), dmesg/OOM/kernel panic analysis, Buildroot, U-Boot, Yocto  
**Platforms:** AMLOGIC SoCs (initd), CVITEK SoCs (initd), STM32 Linux MPU (systemd)  
**Protocols:** I2C, UART, TCP/IP  
**Hardware & Analysis:** Logic analyzers, Wireshark, Ghidra, oscilloscope (signal capture)  
**Tools:** GitLab CI/CD, crosstool-ng, GDB cross-debugging

---

## Open Source

| Project | What | Stars |
|---------|------|-------|
| **[fota-secure](https://github.com/siddusuhaas/fota-secure)** | Secure OTA firmware updater | ![Stars](https://img.shields.io/github/stars/siddusuhaas/fota-secure?style=flat-square) |

---

**Interested in discussing embedded systems, firmware security, or Linux internals?** [Let's connect.](https://www.linkedin.com/in/siddu-suhas/)

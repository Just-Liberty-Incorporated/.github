# Just Liberty Incorporated
### Civil Rights Platforms in Law, Public Integrity, and Self-Representation

[![Nonprofit](https://img.shields.io/badge/501(c)(3)-Nonprofit%20Public%20Charity-blue?style=for-the-badge)](https://www.truejust.org)
[![EIN](https://img.shields.io/badge/EIN-93--3704483-green?style=for-the-badge)](https://www.truejust.org)
[![Colorado SOS](https://img.shields.io/badge/Colorado%20SOS-Good%20Standing%20%2320263025619-brightgreen?style=for-the-badge)](https://www.truejust.org)
[![Airgap](https://img.shields.io/badge/Security-Local%20Airgap%20%7C%20Zero%20Telemetry-orange?style=for-the-badge)](https://github.com/Just-Liberty-Incorporated/JustLegalOS)

**Official Web Portals:** [truejust.org](https://www.truejust.org) • [justlegal.me](https://justlegal.me) • [justlegal.me/qui-tam](https://justlegal.me/qui-tam)  
**Primary Contact:** `josh@truejust.org`

---

## 🚀 Quick Downloads: JustLegal OS (v0.1.0)

Install our offline legal operating system and court document formatting engine directly from our [Official GitHub Release](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest):

| Operating System | Recommended Download | Direct Link |
|---|---|---|
| **🪟 Windows (10/11)** | Standard Desktop App Setup (`.exe`) | [👉 **Download Windows Setup (24.5 MB)**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/JustLegalOS_v0.1.0_Windows_64bit_Setup.exe) |
| **🪟 Windows (Enterprise)**| Enterprise System MSI (`.msi`) | [👉 **Download Windows MSI (35.2 MB)**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/JustLegalOS_v0.1.0_Windows_64bit_Enterprise.msi) |
| **🍏 Mac (Apple Silicon)** | Modern Macs (M1 / M2 / M3 / M4) (`.dmg`) | [👉 **Download Mac Apple Silicon (33.9 MB)**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/JustLegalOS_v0.1.0_Mac_AppleSilicon.dmg) |
| **🍏 Mac (Intel)** | Intel-based Macs (`.dmg`) | [👉 **Download Mac Intel (33.9 MB)**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/JustLegalOS_v0.1.0_Mac_Intel.dmg) |
| **🤖 Linux / GrokBot** | Standalone Headless CLI (x86_64) | [👉 **Download Linux / GrokBot CLI (47.4 MB)**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/justlegalos-cli-linux-grokbot-x86_64) |
| **🔒 Checksum Manifest** | Cryptographic SHA-256 Manifest | [👉 **SHA256SUMS.txt**](https://github.com/Just-Liberty-Incorporated/JustLegalOS/releases/latest/download/SHA256SUMS.txt) |

**1-Line Headless Linux & GrokBot Installer:**
```bash
curl -sSL https://raw.githubusercontent.com/Just-Liberty-Incorporated/JustLegalOS/main/scripts/install-linux.sh | bash
```

---

## Our Mission: The Rule of Law for Everyone

The American legal system is procedurally complex, expensive, and structurally tilted against ordinary people. Most legal technology treats the law as a text-generation problem—producing generic AI essays that hallucinate citations while leaving self-represented litigants to drown in procedural traps, missed deadlines, and unverified records.

**Just Liberty Incorporated treats the law as a deterministic systems-engineering, record-verification, and procedural-routing problem.**

We do not practice law, give legal advice, or represent parties in court. Instead, we build deterministic offline formatting engines, court rules compilers, and public-records verification tools that give self-represented litigants, tenants, consumers, families, and citizen whistleblowers the procedural precision, verified structure, and dignity of an institutional law firm.

---

## The 3 Pillars of Our Ecosystem

```
┌───────────────────────────────────────────────────────────────────────────────────┐
│                           JUST LIBERTY INCORPORATED                               │
├───────────────────────┬───────────────────────────┬───────────────────────────────┤
│ 1. TrueJust.org       │ 2. JustLegal.me           │ 3. JustLegal OS & Agents      │
├───────────────────────┼───────────────────────────┼───────────────────────────────┤
│ • Civic & Voter Tech  │ • 22,936+ Court Forms     │ • Offline Desktop Engine      │
│ • Judicial Ethics     │ • 16,023 Verified PDFs    │ • Pure Rust CLI Engine        │
│ • Institutional Trust │ • Client-Side PDF Studio  │ • GrokBot AI Navigators       │
│ • 501(c)(3) Umbrella  │ • Live NPI Cross-Check    │ • Strict Local Vault Airgap   │
└───────────────────────┴───────────────────────────┴───────────────────────────────┘
```

### 1. [JustLegal OS](https://github.com/Just-Liberty-Incorporated/JustLegalOS) & [justlegalos-cli](https://github.com/Just-Liberty-Incorporated/JustLegalOS)
* **Offline-First Court Engine:** A desktop client (Tauri v2 + Svelte 5) and native Rust CLI that formats a person's own draft into court-shaped pleadings, notice of appeals, and motions.
* **Deterministic Rules Engine:** Sourced deadline formulas, court holiday tolling, and certificate generation for Colorado, New Jersey, Federal District Courts, and appellate divisions.
* **Local Airgap Guarantee:** 100% offline document assembly. Cases marked `.sealed` permanently block all network sync, and patient/whistleblower files are protected in local encrypted vaults (XChaCha20Poly1305 + Argon2id).
* **Model Context Protocol (MCP):** Connects external AI assistants (GrokBot, Claude, Cursor) to run local diagnostics safely with zero file leaks.

### 2. [JustLegal.me](https://justlegal.me) — Public Court Access & Web Tools
* **National Forms Index:** 22,936 indexed court forms across all 50 states and 94 federal judicial districts.
* **Client-Side PDF Studio:** Bates stamping, fee waiver generators, courtroom script generators, settlement calculators, and redaction tools operating entirely inside the user's browser.
* **Live Federal Registry Verification:** Real-time, keyless cross-checks against CMS NPPES v2.1 (`npiregistry.cms.hhs.gov`) and USAspending.gov (`api.usaspending.gov`).

### 3. [TrueJust.org](https://www.truejust.org) — Institutional Umbrella & Civic Integrity
* High-impact public-interest initiatives focused on open government transparency, voter access, and accountability.

---

## Executive Order 14395 & Qui Tam Fraud Triage ([justlegal.me/qui-tam](https://justlegal.me/qui-tam))

Under **Executive Order 14395 ("Establishing the Task Force to Eliminate Fraud")**, the White House Task Force chaired by the Vice President coordinates federal fraud elimination across Provider Enrollments, Eligibility Attestations, and Third-Party Intermediaries.

Just Liberty Incorporated provides a **free, public-interest pre-seal verification pipeline** that turns citizen observations and insider disclosures into cryptographically hashed, Federal Rule of Civil Procedure 9(b)-graded dossiers:

* **Preventing Fatal Seal Violations:** Strictly educates whistleblowers on **31 U.S.C. § 3730(b)(2)** to stop them from publishing allegations on social media, which destroys claims under the Public Disclosure Bar (§ 3730(e)(4)).
* **Deterministic FRCP Rule 9(b) Scoring:** Grades cases on a 0–100 particularity scale across *Who, What, When, Where, How, Scienter, and Materiality*.
* **Standardized Calling Card:** Outputs the recognized `[JustLegal Standard v1.0 | EO-14395]` diagnostic header block for 90-second triage by federal investigators and qui tam counsel.
* **Dual-Track Final Routing:** Routes high-dollar claims to specialized contingency False Claims Act law firms under seal (Track A), or auto-formats character-limited submissions for HHS-OIG, SBA-OIG, USDA-OIG, and State AG MFCU portals (Track B).

---

## Leadership & Governance

* **Founder, Executive Director & Principal Architect:** Joshua M. Abrams ([@unlimitedinfinit](https://github.com/unlimitedinfinit))
* **Entity Type:** 501(c)(3) Nonprofit Public Benefit Charity (Colorado, USA | EIN: `93-3704483`)
* **Bar Ethics & Independence:** Fully compliant with ABA Model Rules 5.4, 7.2(b)(2), and 1.18. Just Liberty operates exclusively for public charitable and educational purposes.

---

## Institutional Source Audits & NDA Inquiries

To safeguard fraud-scoring heuristics against gaming by bad actors and prevent commercial exploitation of our nonprofit infrastructure, core engine source code is maintained in private repositories.

Full source-code and build-pipeline audits are available under standard institutional NDA to:
- Government oversight agencies (DOJ Fraud Section, HHS-OIG, USDA-OIG, SBA-OIG, State AG MFCUs).
- Accredited foundation grantmakers.
- Charter Panel qui tam plaintiff law firms.

**Institutional Contact:**  
**`josh@truejust.org`**

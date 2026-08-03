# LinkTrace — OSINT & Link Analysis Platform

<table>
  <tr>
    <td width="130" align="center">
      <img src="assets/logo.png" alt="LinkTrace Logo" width="100" />
    </td>
    <td>
      <h1>LinkTrace</h1>
      <p>An advanced platform for OSINT investigations, digital footprint graph analysis, and entity relationship visualization. Designed for cyber threat intelligence analysts, forensic specialists, investigators, and security teams.</p>
      <p>
        <img src="https://img.shields.io/badge/version-0.1.1--alpha-blue.svg" />
        <img src="https://img.shields.io/badge/license-MIT-green.svg" />
        <img src="https://img.shields.io/badge/status-in_development-orange.svg" />
      </p>
    </td>
  </tr>
</table>

---

## 📸 Interface Screenshots

### 1. Interactive Graph View (`Graph / Chain`)
Investigation topology visualization featuring nodes categorized by type and dynamic relationships.
![Interactive Graph View](assets/graph_view.png)

### 2. Summary & Data Collection (`Summary / Data Collection`)
Structured registry of all gathered artifacts with category filtering, validation statuses, and evidence proofs. Includes one-click report copying in a formatted structure.
![Summary View](assets/summary_view.png)


---

## ✨ Key Features

- 🕸 **Interactive Graph View:**
  - Support for custom hierarchies, node types, and weighted edges.
  - Smooth, scalable canvas workspace with dependency highlighting and instant search.
  - Sidebar timeline displaying the chronological discovery of findings (*Timeline*).

- 📋 **Artifact Summary & Filtering:**
  - Categorized grouping:
    - 👤 **Personal Data** (Full name, Telegram ID, Email, Phone numbers, Passports/Tax ID).
    - 🌐 **Digital & Network Artifacts** (IP v4/v6, Domains, Subdomains, SSL certificates, Analytics ID, Cookies, User-Agent).
    - 📍 **Geospatial Data** (Addresses, Geolocation coordinates).
    - 🏢 **Business & Legal Entities** (Company names, Registration IDs, Job titles).
    - 💬 **Content & Metadata** (Posts, Files, Leak databases).
    - 💳 **Financial Artifacts** (Crypto wallets, Bank card numbers, API keys).

- 🔍 **Entity & Node Inspector:**
  - Assign validation statuses: `Verified`, `Pending`, `Unverified`.
  - Specify discovery source/tool (RiskIQ, WHOIS, CT Logs, Telegram, Leak databases).
  - Attach evidence links and custom notes to any object.

- 💾 **Project Management & Export:**
  - Quick entity creation via category palettes.
  - **Canvas Export:** Save the investigation canvas directly as an image (`PNG`).
  - **Formatted Report Copying:** Copy the complete investigation report directly from the app in a structured, professional format.
  - Full project import and export in JSON format (`Save JSON`).
  - Global search across all entities, types, and values.

---

## 📋 Example Formatted Report Export

LinkTrace allows exporting reports directly into a clean, structured layout:

---

## 🤝 Contributing & Community

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/LeakMeBaby/linktrace/issues).

> 💬 **Join our Community!**  
> Have questions or want to chat? Join our [Discord Server](https://discord.gg/jdz52VAdxp)!

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

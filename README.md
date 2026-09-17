# 0T-LeadRadar 🎯
**B2B Lead Generator for Mechanics & Defense**

0T-LeadRadar is a portable Python application for B2B lead generation. It identifies companies (specifically in the mechanical and defense sectors) starting from public sources, collects contact data, and classifies them by capacity and sector. The goal is to build and maintain a qualified list of potential clients or suppliers, filterable and reusable.

## 🚀 Main Features

* **Search and Enrichment:** Discovery via public search engines and data extraction directly from company websites (contacts, machinery, PDF brochures, images of machined parts).
* **Security and Encrypted Database:** All data resides in a local database protected by **SQLCipher (AES-256)**. Without login credentials, data remains unreadable.
* **Privacy and GDPR Compliance:** Strict compliance with the `robots.txt` file and integrated management of an *opt-out* (Excluded) list. Only public sources are used, without any bypass attempts (e.g., paywalls or logins).
* **Flexible Export:** Supports data export in Excel (by scope or complete), PDF, and JSON formats (ideal for integration with external CRMs and management software).
* **Advanced Classification and Filters:**
  * **Machining & Defense:** Automatic detection of mechanical machining (Turning, Milling, Welding, etc.) and defense/aerospace certifications (AS9100, NADCAP, etc.).
  * **Automatic Tags:** Dynamic tagging based on customizable logical rules (e.g., revenue, employees, NACE/ATECO codes).
* **Geolocation:** Visualization of collected companies on an interactive map (via OpenStreetMap) with smart clustering.
* **ROI Estimation:** Integrated and configurable calculator in each company's profile to estimate return on investment and amortization.
* **Multilingual and Themes:** Hot-swappable interface in Light/Dark mode, supporting 5 languages (IT, EN, FR, ES, UA).

## 🛠️ Architecture and Structure

* **Portable Architecture:** The application is self-contained. No installation required; it can be moved simply by copying the folder.
* **Local Data:** All collected files, the encrypted database, PDF profiles, and images are automatically saved in the `dati/` subfolder. Updating the program does not affect the collected data.

## 📖 Documentation

Detailed instructions on the working principle, screens, automatic tag configuration, and shortcuts (Cheat sheet) are available in the reference document: **`Manuale_uso_0T-LeadRadar_20260909_2.pdf`**.

## 🤝 Contributions and Notes

Being data-extraction oriented, this project follows strict rules to prevent blocks by visited sites (thread pause management, deduplication by VAT/Domain) and guarantees not to read closed personal profiles (such as blocking direct scraping on LinkedIn, in favor of using public queries).

## 📜 License
*(For terms of use, please refer to the license file included in the repository).*

# File Magic Pro ✨ — Smart Multi-Format Business Data Engine

File Magic Pro is a highly optimized, fully client-side business utility designed to parse, normalize, and visualize raw structured data across **9+ corporate file formats**. 

Built with scalability, security, and high performance in mind, this tool is targeted at business process optimization, helping operations teams automate the manual conversion and auditing of large sales datasets.

![File Magic Pro Banner](https://img.shields.io/badge/Status-Production--Ready-success?style=for-the-badge&logo=github)
![Tech Stack](https://img.shields.io/badge/Stack-JS%20%7C%20HTML%20%7C%20CSS-blue?style=for-the-badge)
![Formats Supported](https://img.shields.io/badge/Formats-9%2B-violet?style=for-the-badge)

---

## 🔒 Intellectual Property & Source Code Access
> [!IMPORTANT]
> To protect proprietary business logic and the parsing engine configuration, the full source code for this application is hosted in a **Private Repository**. 
> 
> Technical recruiters, engineering managers, and potential clients can request read-access to the private repository for code review purposes by contacting **Ibrahim Serry** at **ibrahimserry24@gmail.com**.

---

## 🚀 Key Features

*   **9+ File Formats Supported:** Seamless, instant parsing of Excel (`.xlsx`, `.xls`), CSV, TXT, TSV, JSON, XML, HTML, Word (`.docx`), and PDF.
*   **AI-Driven Wording & State Detection:** Automatically analyzes row content to classify transactions into states (`Completed`, `Pending`, `Failed`) using dynamic keyword patterns.
*   **Clean Table Visualization:** Organizes data instantly into rich, searchable, filterable HTML tables with responsive layouts.
*   **Operations-Ready Export:** Allows exporting cleansed data back to Excel (e.g., export completed/successful transactions only) to streamline B2B pipelines.
*   **100% Client-Side Parsing:** High-security data processing. No database or external server gets access to the raw uploaded files, ensuring complete business compliance.

---

## 📂 Repository Contents (Showcase Only)

This public repository serves as a **functional showcase and testing hub** for the File Magic Pro utility. It contains:
1.  [بيانات_المبيعات_نموذجية.xlsx](./بيانات_المبيعات_نموذجية.xlsx) — A standardized sales database to test the Excel parser.
2.  [تقرير_المبيعات_نموذجي.docx](./تقرير_المبيعات_نموذجي.docx) — A text-heavy business document to test the Word parser.
3.  `assets/` — Folder for screenshots and visual demonstrations of the system.

---

## 🛠️ Architecture & Core Dependencies

*   **SheetJS (xlsx.full.min.js):** Handles binary Excel parsing and data extraction.
*   **JSZip:** Decompresses Word `.docx` XML-based archives for text normalization.
*   **PDF.js:** Renders and parses embedded text layers inside PDF documents.
*   **Material Symbols Outlined & Google Fonts:** Premium, modern UI styling.

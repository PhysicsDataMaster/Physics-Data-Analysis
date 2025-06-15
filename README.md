# Physics-Data-Analysis

Scripts, tools, and documentation for the **Physics Data Collection & Analysis** system — built using Google Sheets Apps Script + Sidebar UI architecture.

---

## ⚙️ Features

This project includes a full modular system for managing experimental physics data inside Google Sheets:

- 📥 CSV import and Drive folder mapping
- 🧾 Sheet organization and custom home pages
- ✅ Data validation and structural checks
- 📊 Interval analysis and reduction workflows
- 📈 Custom regression engine (LaTeX-compatible input + selectable algorithms)
- 🪲 Error logging with visual debugging
- 🧠 Sidebar Help Dialog with glossary, tips, and full source view

---

## 🔢 Current Version: **v5.1**

This is the latest stable release — now with **split HelpDialog architecture**, developer roadmap for v5.2, and cleaned file naming for GitHub compatibility.

---

## 📁 Project Files

| File Name            | Purpose                                                       |
|---------------------|---------------------------------------------------------------|
| `Code`              | Main Google Apps Script — creates menus and system logic      |
| `HelpDialog_Main`   | Sidebar help system — sections 1–2, 4–12 (Overview + Guide)    |
| `HelpDialog_Functions1` | A–M Function reference (fully expanded)                   |
| `HelpDialog_Functions2` | N–Z Function reference + roadmap to v5.2 (planned features) |
| `RegressionDialog`  | Regression entry form with LaTeX preview + parameter input     |

All files are `.txt` format (no extensions) for easier GitHub use. Copy/paste them into your Apps Script environment.

---

## 🚀 Setup Instructions

1. **Create a Google Sheet** and open **Extensions > Apps Script**.
2. Copy contents of each file into the Apps Script Editor:
   - Paste `Code` into `Code.gs`
   - Add new HTML files:
     - `HelpDialog_Main`, `HelpDialog_Functions1`, `HelpDialog_Functions2`, `RegressionDialog`
3. Save all files and reload the spreadsheet.
4. Menu will appear as **“CSV Manager”**.
5. Use menu options to:
   - Import data
   - Validate structure
   - Analyze intervals
   - Run regression
   - Open contextual help from the sidebar

---

## 🧭 HelpDialog Architecture

The help system is split for performance and clarity:

- **HelpDialog_Main** — Main tutorial, overview, glossary, formatting tips
- **HelpDialog_Functions1** — Covers all A–M functions with examples and usage
- **HelpDialog_Functions2** — Covers N–Z and includes full roadmap (v5.2 preview)
- **RegressionDialog** — Custom form UI with LaTeX preview and parameter inputs

Use the in-menu **Help** button to access the sidebar inside Sheets.

---

## 🔮 Future Features (v5.2 Planned)

These features are already scaffolded in v5.1 and will activate once developed:

- `postRegressionResults()` → Push to REST APIs
- `validateRegressionResults()` → Auto quality checks + error summaries
- `exportRegressionResults()` → Export to CSV / JSON
- `archiveCSVFiles()` → Move processed CSVs to Drive archive
- `batchRunRegressions()` → Multi-sheet, multi-model regression mode

---

## 📜 License

This repository is published for educational and collaborative development purposes. You may fork, adapt, and use with attribution.

> Originally structured with the help of ChatGPT-4o and refined through collaborative iterations.

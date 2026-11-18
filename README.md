# Sinhala Font & Letter Studio (IsiAbhaya • FM • Unicode • Native .DOCX)

A modern, fast, 100% offline-ready Progressive Web App (PWA) designed to format official Sinhala letters with mixed English text, convert between Unicode, Isi fonts (**IsiAbhaya**), and FM fonts, and export native **.DOCX** files with dual-font styling for Microsoft Word.

---

## 🚀 Quick Start

### Option 1: Direct File Launch
Double-click **`index.html`** in this folder to open it in Chrome, Edge, Brave, or Firefox.

### Option 2: Local Web Server (For full PWA offline installation)
Open a terminal in this directory and run:
```bash
python -m http.server 8080
```
Then visit `http://localhost:8080`.

---

## ✨ Key Features & Enhancements

1. **Default Font for Isi: `IsiAbhaya`**:
   - The default font for all Isi conversions is now explicitly set to **`IsiAbhaya`** (`'IsiAbhaya', 'Isi Abhaya', sans-serif`).
   - Selected automatically in the dropdowns and applied directly to exported `.DOCX` and `.DOC` files.

2. **Crisp English Text (No Blur / No Forced Blue Color)**:
   - English terms (`LF-6345`, `TATA ACE`, `AWC`, `DMT`, `CCTV`) are rendered **crisp and clean** in `Arial` font matching the surrounding text color and line height.
   - **Optional Toggle**: `🎨 Highlight English in Blue` (Unchecked by default). You can tick this box if you want to visually highlight where English words are detected.

3. **📥 Native .DOCX Export**:
   - Downloads a true Microsoft Word OpenXML (`.docx`) file.
   - When opened in Microsoft Word, Word automatically applies **`IsiAbhaya`** to the Sinhala text and **`Arial`** to the English text without any manual font changing!

4. **📜 Formal Letter Studio (A4 Letterhead)**:
   - Formats formal letters with preset letterheads (Animal Welfare Coalition / Classic / Plain Paper), date, recipient, bold/underlined subject line, numbered clauses, bullet points (`▪`), multi-signatory blocks, copies, and attachments.
   - One-click print or save as PDF formatted for standard A4 paper margins.

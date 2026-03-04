# Roofwander Partnership Documents

This repository stores partnership one-pager documents for Roofwander—for both **brands** and **resellers**. The documents are written in HTML so they can be easily edited, versioned with Git, translated into multiple languages, and exported as PDFs.

---

## Folder structure

```
roofwander-docs
│
├── brands
│   ├── en
│   │   ├── brand-partnership-en.html
│   │   └── brand-partnership-contract-template.html
│   ├── es
│   │   ├── brand-partnership-es.html
│   │   └── brand-partnership-contract-template-es.html
│   └── fr
│       ├── brand-partnership-fr.html
│       └── brand-partnership-contract-template-fr.html
│
├── resellers
│   ├── en
│   │   ├── reseller-partnership-en.html
│   │   └── reseller-partnership-contract-template.html
│   └── fr
│       ├── reseller-partnership-fr.html
│       └── reseller-partnership-contract-template-fr.html
│
├── invoice
│   ├── en
│   │   └── invoice-example-naitup.html
│   └── fr
│       └── invoice-example-naitup.html
│
└── assets
    └── logo.png
```

- **HTML files** are the source documents (partnership one-pagers and contract templates).
- **Contract templates** (brand and reseller) are available in English and French. Copy into a per-partner folder and fill in the details when needed.
- **invoice/** contains invoice templates (e.g. Belgian format example for partnership commissions).
- **assets/** holds shared assets such as the logo.
- PDFs can be generated from the HTML files using the workflow below.

---

## How to edit the documents

1. Open the repository in Cursor or any code editor.
2. Edit the HTML file you need (partnership page or contract template).
3. Save your changes.
4. Commit changes to Git if you use version control.

---

## How to export as PDF

1. Open the HTML file in a browser (Chrome recommended).
2. Press **Ctrl + P** (Windows/Linux) or **Cmd + P** (Mac).
3. Configure:
   - **Destination** → Save as PDF
   - **Scale** → 100%
   - **Margins** → Default or Minimum
4. Under **More settings**:
   - Enable **Background graphics**
   - Disable **Headers and footers**
5. Click **Save**.

This produces a clean one-page PDF suitable for sending to partners.

---

## Why HTML is used

- Precise layout control for consistent, professional documents
- Version control with Git to track changes and collaborate
- Simple to translate (duplicate files into `en/` and `fr/` and edit the text)
- Same layout can be reused across multiple documents
- Files can be published as web pages later if needed

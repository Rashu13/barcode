# A4 Barcode & Label Printer - Indian Market Presets 📦

A lightweight, mobile-friendly, zero-dependency web utility to generate and print barcodes directly onto pre-cut A4 adhesive label sheets (Oddy, Desmat, Century, AmazonBasics, etc.).

🌐 **Live URL**: [https://rashu13.github.io/barcode/](https://rashu13.github.io/barcode/)

---

## 🌟 Features

* **Indian Market Presets**:
  - **A4 - 84 Labels** (46mm × 11.1mm | 4 cols × 21 rows)
  - **A4 - 65 Labels** (38.1mm × 21.2mm | 5 cols × 13 rows)
  - **A4 - 48 Labels** (45.7mm × 21.2mm | 4 cols × 12 rows)
  - **A4 - 40 Labels** (48.5mm × 25.4mm | 4 cols × 10 rows)
  - **A4 - 24 Labels** (70mm × 37mm | 3 cols × 8 rows) - *Standard for Amazon FBA & Retail*
  - **A4 - 24 Labels** (64mm × 33.8mm | 3 cols × 8 rows) - *Oddy 24L*
  - **A4 - 21, 16, 12, 8 Labels** and **Custom Dimensions** (mm)
* **Mobile-Friendly UI**:
  - Dual Mode Tabs: **Settings & Data** vs **Sheet Preview**
  - Instant Zoom and "Fit to Screen" button
  - Floating Print / Save as PDF button
* **100% Vector Code 128 SVG Engine**:
  - Generates crisp vector lines that never blur or pixelate.
  - Compatible with any 1D/2D laser or camera barcode scanner.
* **Smart Sheet Saver**:
  - Skip already-peeled labels (`Start from Label #X`) so partially used A4 sheets are never wasted.
* **Auto-Increment**:
  - Automatically sequence serial numbers across labels.
* **100% Offline**:
  - Works with zero external CDN or npm packages. Can be saved as a single HTML file and used anywhere.

---

## 🖨️ Printing Guidelines

In your browser print dialog (`Ctrl + P`):
1. **Destination**: Select your printer or "Save as PDF"
2. **Paper Size**: `A4`
3. **Margins**: `None` *(Critical for millimeter alignment on pre-cut sheets)*
4. **Scale**: `100%` or `Default`

## Business Directory - Admin Excel Import Panel

A front-end only admin tool to import business listings from Excel/CSV files using SheetJS (xlsx).

## Features
- 📂 Drag-and-drop or click to upload `.xlsx` / `.csv`
- 🔍 Client-side parsing using SheetJS (no backend required)
- ✅ Real-time validation for required columns: **Name**, **Category**, **City**
- ⚠️ Highlights missing fields and shows row status (Valid / Missing)
- 📊 Preview table with total, valid, and invalid row counts
- 💾 Mock "Save" button with success summary (logs valid data to console)

## How to Run
1. Download or clone this repository.
2. Simply open the `index.html` file in any modern web browser.
3. Upload the provided `sample-business-list.csv` or your own `.xlsx` file.
4. Review the validation and click "Save (mock)" to see the summary.

## File Structure
- `index.html` - Complete application (HTML + CSS + JavaScript)
- `sample-business-list.csv` - Sample test file with intentional missing fields
- `README.md` - Project documentation

## Technologies Used
- HTML5 / CSS3
- JavaScript (Vanilla)
- [SheetJS (xlsx)](https://cdn.sheetjs.com/) - For parsing Excel/CSV files

## Deliverables (as per task)
- ✅ Working import demo
- ✅ Sample test file
- ✅ Short README

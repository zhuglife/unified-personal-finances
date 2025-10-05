# Financial Dashboard (Demo)

**Financial Dashboard** is a single-sheet Excel dashboard (dark Monokai-like theme) built for demo and starter templates.
This package is ready to be used as a GitHub repo template for showcasing a simple financial dashboard.

## Features
- Single-sheet dashboard (Income / Expenses / Summary / Charts)
- Dark Monokai-like styling (cell fills and fonts)
- Demo data included (Food, Transport, Health, Leisure, Utilities, Other)
- Charts: Expenses by Category, Expenses by Person
- English labels and README
- MIT License

## Requirements
- Python 3.8+ (for the generator script)
- `pandas`, `openpyxl` (if using the generator script)

## Usage
1. Open **Financial_Dashboard.xlsx** in Excel or LibreOffice.
2. Edit the data table to add your incomes/expenses.
3. Duplicate the sheet to create monthly copies.
4. Charts update automatically in Excel when data changes.

## Generate from script
To regenerate using Python:
```bash
pip install pandas openpyxl
python generate_dashboard.py
```

## License
This repository is released under the MIT License. See LICENSE file for details.

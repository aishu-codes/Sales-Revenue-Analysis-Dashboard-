# Sales & Revenue Analysis Dashboard

A beginner-friendly sales analytics dashboard built with HTML, CSS, and JavaScript.

## Features
- KPI cards: Total Revenue, Total Orders, Units Sold, Average Order Value
- Revenue trend by month
- Revenue by category and region
- Top 5 products ranked by revenue
- Region, category, and date-range filters
- Import a CSV file and export the filtered data
- Responsive layout for desktop and mobile
- Includes sample sales data

## Run on Windows / VS Code
1. Extract `Sales_Revenue_Analysis_Dashboard.zip`.
2. Open VS Code.
3. Select **File → Open Folder** and choose the extracted `Sales_Revenue_Analysis_Dashboard` folder.
4. Open `index.html`.
5. Right-click inside the file and select **Open with Live Server** (if Live Server extension is installed).
   - Or double-click `index.html` in File Explorer to open it in your browser.
6. Internet connection is needed for Chart.js and Google Fonts loaded from their CDNs.

## Import your own CSV
Click **Import CSV** and select a CSV with these column headings (capitalization/spaces do not matter):
`Order ID, Date, Product, Category, Region, Units, Revenue`

Example row:
`ORD-2001,2026-09-01,Keyboard,Accessories,North,10,250`

Notes:
- Date format should be `YYYY-MM-DD`.
- Revenue should be a number without currency symbols or thousands separators.
- This demo CSV parser expects simple comma-separated fields (no commas embedded inside field values).
- The included sample dataset is fictional and for demonstration/learning only.

## KPI definitions
- **Total Revenue:** sum of all revenue values in the selected records.
- **Total Orders:** number of transaction rows in the selected records.
- **Units Sold:** sum of units/quantity.
- **Average Order Value:** total revenue divided by transaction rows (in this demo, each row represents one order).

## Project structure
```
Sales_Revenue_Analysis_Dashboard/
├── index.html
├── style.css
├── script.js
├── data/
│   └── sales_data.csv
└── README.md
```

## Technology
HTML5, CSS3, Vanilla JavaScript, Chart.js.

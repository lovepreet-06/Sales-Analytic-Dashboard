# 📊 Sales Analytics Dashboard

An interactive, single-file **Sales & Customer Analytics Dashboard** built with **HTML, CSS, JavaScript, and Chart.js** — styled to look and feel like a professional **Power BI dashboard**, but running 100% in the browser with **no server, no installation, and no internet connection required**.

![Dashboard Preview](screenshots/dashboard-1.png)

---

## 🔗 Live Demo

👉 [View Live Dashboard](#) <!-- replace # with your GitHub Pages link -->

---

## ✨ Key Features

- **Two dashboard pages** — Sales Overview & Customer/Geography — switch instantly, no page reload
- **18 interactive charts and KPI cards** covering revenue, quantity, discounts, seasonality, customer ratings, city-wise performance, and payment methods
- **Live filtering** by Product Category, City, Gender, Payment Method, and Date Range — every chart and KPI updates instantly
- **Upload your own Excel file** — built-in support to load a new `.xlsx` dataset (same column structure) directly in the browser using SheetJS, with the whole dashboard refreshing automatically
- **Fully self-contained** — Chart.js and SheetJS are embedded directly in the file, so it works even with no internet connection
- **Dark, Power BI–style theme** — clean typography, blue/teal accent colors, professional layout
- **Responsive design** — adapts to smaller screens

---

## 📈 What's Inside

### Page 1 — Sales Overview
| KPI Cards | Charts |
|---|---|
| Total Revenue | Revenue Trend (Monthly) |
| Total Orders | Revenue by Product Category |
| Total Quantity Sold | Quantity Sold by Category |
| Average Order Value | Average Discount by Category |
| | Discount Impact on Revenue (Scatter) |
| | Seasonal Pattern — Revenue by Month |

### Page 2 — Customer & Geography
| KPI Card | Charts |
|---|---|
| Average Customer Rating | Customer Distribution by Age Group |
| | Gender-wise Revenue Split |
| | Top 10 Customers by Total Spend |
| | Average Rating by Category |
| | Revenue by City |
| | Order Volume by City |
| | Orders by Payment Method |
| | Average Order Value by Payment Method |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — layout, theming, responsive grid
- **JavaScript (Vanilla)** — data processing, filtering logic, DOM updates
- **[Chart.js](https://www.chartjs.org/)** — all charts (line, bar, scatter, doughnut)
- **[SheetJS (xlsx.js)](https://sheetjs.com/)** — reading Excel files directly in the browser

No frameworks, no build tools, no backend — just one HTML file.

---

## 📂 Dataset

The dashboard uses a retail sales dataset with the following columns:

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Customer_Name` | Customer name |
| `Age` | Customer age |
| `Gender` | Customer gender |
| `City` | Customer city |
| `Product_Category` | Category of product purchased |
| `Quantity` | Units purchased |
| `Price_Per_Unit` | Price per unit |
| `Discount` | Discount applied (as a decimal, e.g. 0.10 = 10%) |
| `Total_Amount` | Final order value |
| `Payment_Method` | Payment method used |
| `Order_Date` | Date of order |
| `Customer_Rating` | Customer satisfaction rating (1–5) |

A sample dataset (999 orders) is embedded in the dashboard by default. You can replace it anytime using the **Upload Excel** button — just make sure your file uses the same column names.

---

## 🚀 How to Run

**Option 1 — Just open it**
1. Download `Sales_Analytics_Dashboard.html`
2. Double-click to open it in any modern browser (Chrome, Edge, Firefox)
3. That's it — no setup needed

**Option 2 — GitHub Pages**
1. Push this file to a GitHub repository
2. Enable GitHub Pages (Settings → Pages → deploy from branch)
3. Share the live link on your resume / LinkedIn

---

## 📸 Screenshots

**Sales Overview**
![Sales Overview - KPIs and Trends](screenshots/dashboard-1.png)
![Sales Overview - Category & Discount Analysis](screenshots/dashboard-2.png)

**Customer & Geography**
![Customer Overview](screenshots/dashboard-3.png)
![City & Payment Analysis](screenshots/dashboard-4.png)

---

## 🎯 About This Project

This dashboard was built as part of my Data Analyst portfolio to demonstrate skills in:
- Data aggregation & KPI calculation
- Interactive filtering and dynamic visualization
- Dashboard design principles (Power BI–style UX in a web format)
- Working with Excel data using JavaScript

---

## 🤖 AI-Assisted Development

This project was built with the help of **Claude AI**. I provided the complete functional specification — including the required KPIs, chart types, calculations, filters, color theme, and layout — and used AI to accelerate the implementation. The dashboard design decisions, data structure, and analytical logic are my own.

📄 [View the full project prompt](PROMPT.md)

---

## 👤 Author

**Lovepreet (Lovey)**
Data Coordinator & Lecturer | Aspiring Data Analyst
📍 Open to Data Analyst / MIS Executive roles in Dubai, UAE

- 🔗 [LinkedIn](https://www.linkedin.com/in/lovepreet-072824395/)
- 💻 [GitHub](#) <!-- add your GitHub profile URL -->

---

## 📄 License

This project is open source and available for learning purposes.

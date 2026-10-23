# Executive Dashboard - Budget vs. Actual Collections Analysis

An executive web-based dashboard designed for performance analysis and strategic review meetings, tracking cumulative collections (January – September 2026) against established budget targets across territories.

<img width="1316" height="520" alt="Screenshot 2026-10-23 151202_dasboard1" src="https://github.com/user-attachments/assets/308c7513-6f47-4260-9870-8614e1e12b9e" />


## 📊 Project Overview & Business Value

In executive and management status meetings, having a clear, real-time macro and micro view of financial performance is critical. This dashboard was built to streamline the evaluation of **Actual Collections vs. Budgeted Targets** for inspectors and regional teams. 

Key analytical highlights include:
* **Performance Tracking:** Instantly identify which counties/zones have exceeded their budget targets (surplus) and which are facing deficits.
* **Executive Decision Making:** Provides high-level KPI cards (Total Realized, Total Budget, Absolute Variance, and Realization Percentage) alongside interactive visual representations to support data-driven discussions during leadership meetings.

---

## 🏗️ Dashboard Structure & Architecture

The application is structured into specialized tabs and sections to cater to different levels of territorial granularity:

1. **General Dashboard:** A macro-level view aggregating all data nationwide.
2. **Regional Views (North & South):** Dedicated sections to analyze performance filtered by specific geographical regions.
3. **No Zone (Sediul Central):** Captures central operations and unassigned categories.
4. **Bucharest Detailed View:** A granular breakdown focusing specifically on the Bucharest sectors (S1 to S6).
5. **Interactive Mapping & Charts:** Integrates dynamic SVG maps (Romania & Bucharest sectors) with color-coded status indicators (Green for surplus, Red for deficit) and comprehensive comparative bar charts.
6. **Data Export Functionality:** Users can download filtered data sets into clean Excel spreadsheets instantly for offline reporting.

<img width="1833" height="963" alt="Screenshot 2026-10-23 151202_dasboard2" src="https://github.com/user-attachments/assets/0e362633-aad5-4941-9924-b448b3de97bd" />
<img width="1857" height="826" alt="Screenshot 2026-10-23 151202_dasboard3" src="https://github.com/user-attachments/assets/2376a012-d8d9-4591-bdca-2c5b1383edeb" />

---

## 🤖 The Synergy Between AI and Human Expertise

While modern AI tools can significantly accelerate the coding and scaffolding process of building modern web tools, **the human element remains irreplaceable**. 

* **Strategic Vision:** The core concepts, structural logic, and Key Performance Indicators (KPIs) were defined by a specialist with deep domain knowledge of the industry and management requirements.
* **Context & Focus:** Knowing *what* data matters most to leadership, how to structure regional hierarchies, and what insights to emphasize requires human expertise.
* **Data Validation:** Automated tools build the interface, but a human expert ensures data integrity, rigorous validation, and accurate interpretation of financial outcomes.

---

## 🚀 Tech Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid, Custom CSS Variables), JavaScript (ES6+).
* **Libraries:** 
  * [SheetJS (XLSX)](https://sheetjs.com/) - For client-side Excel parsing and exporting.
  * [Chart.js](https://www.chart.js/) - For dynamic, responsive performance charts.
  * [FontAwesome](https://fontawesome.com/) & Google Fonts (Inter) - For UI styling and typography.

---

## ⚙️ Usage

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Upload your monthly Excel file (`.xlsx`, `.xls`, or `.csv`) containing the collection data.
4. Explore the dashboard across tabs, inspect regional performance, and export reports as needed.

# Regional Sales Performance & Automation Dashboard
## 📊 Project Overview
This interactive Sales Performance Dashboard transforms raw business data into structured, actionable insights for regional sales management. Designed to track sales executives across major city hubs (including Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, and Surat), it enables stakeholder evaluation of top performers, bottom performers, and target achievement margins.

The project emphasizes interactive user experience (UX) and process automation to minimize manual data drilling.

## 🛠️ Key Features & Functionalities
**Dynamic Regional Slicers:** Implemented a unified geographic control bar allowing users to filter the entire dashboard by clicking on specific city hubs. All charts and data models refresh dynamically in under a second.

**Target Performance Segmentation:**

- **Top 10 / Bottom 10 Sales Executives:** Automatically isolates performance extremes to identify top assets and team members requiring pipeline support.

- **Target Hit Rate (%) & Deficit Tracking:** Dynamically calculates individual target percentages and highlights the exact margins by which underperforming executives missed their goals.

**Macro Automation:** Integrated custom-recorded macros mapped to interactive dashboard buttons to instantly clear applied filters, optimize data views, and reset the workbook view for the user.

**Advanced Data Visualization:** Synchronized horizontal bar graphs, interactive vertical charts, and specialized distribution pie charts mapped cleanly to backend Pivot Tables.

## 🧰 Tech Stack & Tools Used
* **Application:** Microsoft Excel
* **Data Management:** Data Migration (Sourcing & consolidation into a unified workbook)
* **Data Architecture:** Pivot Tables & Pivot Charts
* **Interactivity:** Dynamic Hub Slicers & Connected Data Sources
* **Automation:** Excel Macro Recorder / VBA (Visual Basic for Applications)

## 📂 File Structure
```text
├── Sales_Performance_Dashboard.xlsm # Macro-Enabled workbook (contains both Data & Dashboard sheets)
└── README.md                       # Documentation
```

## 🚀 How to Interact with the Project
1. Clone or download this repository to your local machine.
2. Open Sales_performance_interactive_dashboard.xlsm.
3. **Important:** Click "Enable Macros" or "Enable Content" at the top yellow warning bar when prompted by Excel; otherwise, the custom dashboard control buttons will not trigger.
4. Interact with the city slicer buttons at the top to filter the metrics seamlessly.

# HR Employee Insights Dashboard

A comprehensive **Power BI** dashboard crafted to help HR professionals explore employee demographics, attrition dynamics, performance, and promotion readiness.

---

## 🧩 Project Highlights

- **🔍 Data Source**
  - Excel/CSV dataset with employee attributes: `Employee ID`, `Name`, `Gender`, `Age`, `Department`, `Job Role`, `Education`, `Tenure`, `Job Satisfaction`, `Performance Rating`, `Leave Balance`, `Attrition`, promotion status, and more.
- **🧼 Data Preparation**
  - Cleaned and formatted using Power Query (filtering nulls, date types, duplicates)
  - Enhanced with calculated fields (e.g. age groups, attrition flags, promotion eligibility)
- **📈 Dashboard Features**
  - **KPIs & Cards**: Total employees, active employees, attrition count/rate, average age & satisfaction, employees due for promotion.
  - **Visuals**: Bar charts, pie/donut, lollipop, scatter – interactive slicers by department, gender, education
  - **Context Filters**: Drill-down analysis by age group, job role, education level
- **🧠 Insights Delivered**
  - Identify departments with high attrition or low job satisfaction
  - Compare gender or education-level attrition
  - Highlight employees eligible for promotion or support
  - Spot workforce demographics that need strategic attention

---

## 🚀 Getting Started

1. **Clone** this repository or download the `.pbix` file.
2. Open in **Power BI Desktop**.
3. Load the dataset.
4. Refresh data to apply Power Query steps.
5. Use slicers and visuals to gain HR insights.

---

## 🔧 Customization & Expansion

- **Data Updates**: Add new records to `/data/`; refresh the model.
- **Measure Enhancements**: Create custom DAX for turnover trends, tenure cohorts, rank-and-compare metrics.
- **New Visuals**: Expand with funnel charts, heat-maps, or decomposition trees.
- **Styling**: Apply realistic organizational themes, embed logo, or adjust brand palettes.

---

## 📋 Report Structure

| Page                | Description                                        |
|---------------------|----------------------------------------------------|
| Overview            | Core KPIs, employee counts, attrition & satisfaction |
| Demographics        | Workforce split by department, age, gender, education |
| Attrition Profile   | Comparative attrition visualizations across groups |
| Promotion Readiness | Identify employees nearing promotion eligibility   |

---

## 🤝 Who Should Use This

- **HR Managers & Leaders** – for monitoring workforce health indicators.
- **Talent & L&D Teams** – to plan retention strategies and talent development initiatives.
- **People Analytics Pros** – for building on data models and custom visual exploration.

---

## ✨ Design Principles

- **Focused & Minimalistic** – monochromatic design sets visuals against a clean background for clarity :contentReference[oaicite:2]{index=2}.
- **Narrative Flow** – starts with high-level overview, then drill-down to departmental and demographic slices :contentReference[oaicite:3]{index=3}.
- **Interactive Exploration** – slicers enable deep dives without clutter; the purpose is exploratory insight, not static reporting.

---

## 📥 Contribute & Extend

Contributions welcome via:
- 📊 Integration of new data sources (e.g., exit interviews, compensation).
- 💡 Suggesting additional KPIs (absenteeism, tenure-based attrition).
- 🎨 UI refinements or accessibility enhancements.
- 🛠️ Raise an issue or submit a pull request.

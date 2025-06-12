# 🎮 Regional-Video-Game-Sales-Insights-A-Power-BI-AWS-Analytics-Project (Built with Amazon Athena + ODBC)

## 👨‍💻 About the Project
This is a **custom-designed, sci-fi-themed Power BI dashboard** I created to explore and visualize **video game sales across different regions** using cloud-based data pipelines. From setting up AWS infrastructure to designing a futuristic radar-chart-driven UI — I built this project end-to-end to showcase my skills in **data engineering**, **cloud integration**, and **creative BI storytelling**.

---

## 🌐 Key Features

- 🔗 **Connected Cloud to Power BI**: Integrated Amazon Athena with Power BI using both **ODBC** and native connectors.
- 🧱 **AWS Setup Done by Me**:
  - Configured **IAM roles**, **S3 Buckets**, and **AWS Glue Crawlers**
  - Defined schema using **Amazon Glue Data Catalog**
  - Set up **Simba Athena ODBC driver** for secure connectivity
- 🧼 **Heavy Lifting in Power Query**:
  - Data cleaning (especially the Year column — it took work!)
  - Schema validation and column alignment for append operations
  - Fixed nulls, transformed units (millions ➝ actual units), and validated against Excel
- 📈 **Visualization & Design**:
  - Radar charts (imported from AppSource) to compare **regional genre popularity**
  - **Sci-fi UI design** with bookmarks, slicers, and button navigation
  - Custom page backgrounds, iconography, and interaction effects

---

## 🧾 Report Pages

1. **Sales by Region**  
   → Interactive bookmark navigation for North America, Europe, Japan, Other, and Global  
   → Radar chart comparing genre-level sales per region  
   → Styled with a cyberpunk visual theme (screenshot below!)

2. *(Additional pages not shown here can include genre deep dives, platform comparisons, etc.)*

---

## 🛠 Tools I Used

- **Power BI Desktop** (Power Query, DAX, Bookmarks)
- **Amazon Web Services (AWS)**: S3, Glue, Athena, IAM
- **Simba ODBC Driver** for Athena integration
- **Excel** (for external validation and workaround fixes)
- **Custom Visuals**: Radar Chart (AppSource)

---

## 📸 Sample Report Screenshot

![Sales by Region – Radar Chart for North America](Page%201%20report.png)

> A sleek, AI-themed visual layer with interactive bookmarks to toggle regions and genre sales data.

---

## 🎯 What I Learned

- Full-cycle cloud-to-BI integration using AWS and Power BI
- How to handle real-world data quirks (nulls, data type mismatches, text-to-numeric fixes)
- UI/UX customization in Power BI for engaging report storytelling
- Use of bookmarks & slicers to enable multi-view analytics from one layout

---

## 📂 How to Run It

1. Clone/download this repo.
2. Use the AWS setup steps included (IAM, Glue, Athena, S3).
3. Install the [Simba ODBC Driver for Athena](https://docs.aws.amazon.com/athena/latest/ug/connect-with-odbc.html).
4. Open the `.pbix` file in Power BI Desktop.
5. Explore the radar charts and regional KPIs through bookmarks!

---

## 📄 License

Free to use for learning and portfolio inspiration. Please credit the repository if you fork or adapt it.

---

## 🤝 Let’s Connect!

If this project resonates with your interest in creative BI design or data cloud integration, feel free to connect or collaborate!


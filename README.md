# 🎌 Power BI — Top Airing Anime Insights Dashboard

An interactive Power BI dashboard that visualizes insights from the **Top Airing Anime** dataset using the public Jikan REST API.  
The report highlights trends in rankings, genres, studios, scores, and popularity across currently airing titles.

---

## 🧠 Project Overview

This dashboard aims to explore and analyze data about the most popular anime that are currently airing — to answer questions like:

- 📊 Which anime are the most popular this season?
- 🏆 What genres dominate the top-ranked titles?
- ⚡ How do user scores compare across different studios?
- 📈 Are there trends across years or seasons?

Built as part of a personal data visualization and API exploration project.

---

## 📥 Data Source

- **API:** `https://api.jikan.moe/v4/top/anime?filter=airing`  
- **Refresh Strategy:**  
  - Data pulled via **Power Query (M Language)** inside Power BI Desktop  
  - Supports pagination for multiple pages  
- Optional: Can also be fetched using Python (see `scripts/` folder if added)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Report authoring & visuals |
| **Power Query (M)** | Data ingestion & transformation |
| **DAX** | Measures & calculated columns |
| **Jikan REST API** | Source of anime metadata |
| *(Optional)* Python | Alternate data extraction |

---

## 🧱 Key Features

✅ Clean, responsive layout with filters  
✅ Genre and studio breakdown charts  
✅ Score and popularity KPIs  
✅ Seasonal and year-level insights  
✅ Cards & drilldowns for deeper exploration  

---

## 📊 How to Use This Template

1. **Download `CapstoneProjectAnime.pbit`** from the `report/` folder  
2. Open it with **Power BI Desktop**  
3. Load or replace the data source (if needed)  
4. Refresh the dashboard and explore!  

---

## 🧩 Future Improvements

- Add time-based refresh through scheduled cloud dataset  
- Publish to Power BI Service or embed live report  
- Expand to include trends for completed and upcoming anime  
- Add sentiment analysis using anime reviews

---

## 🔗 Credits

- **Data Source:** Jikan REST API (https://jikan.moe)  
- **Dashboard Author:** _Parth Mundhwa_  

---

## 🪪 License

This project is licensed under the MIT License — you're free to reuse and modify.


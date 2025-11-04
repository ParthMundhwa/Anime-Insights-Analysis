# Power BI — Top Airing Anime Insights (Jikan API)

[![Made with Power BI](https://img.shields.io/badge/Made%20with-Power%20BI-yellow)](#)
[![Data Source: Jikan](https://img.shields.io/badge/Data-Jikan%20API-blue)](https://jikan.moe)
![Status](https://img.shields.io/badge/Status-Active-success)

An interactive **Power BI** dashboard that visualizes the **Top Airing Anime** using the public **Jikan REST API**. It explores rankings, genres, studios, scores, popularity, and seasonal trends.

---

## 🔎 Highlights

- Top titles by **score**, **popularity**, and **members**
- Genre and studio **distributions** with cross-filtering
- Year/season breakdowns and KPIs
- Clean, mobile-friendly layout with slicers

---

## 📥 Data Source

- API: `https://api.jikan.moe/v4/top/anime?filter=airing`
- Ingestion: **Power Query (M)** inside Power BI (handles pagination)
- Optional: Python fetch script (future enhancement)

> Respect Jikan rate limits; refresh on demand rather than very frequently.

---

## 🧰 Tools

Power BI Desktop · Power Query (M) · DAX · Jikan API

---

## 🚀 Quickstart

1. **Download** the template from `report/`  
   - `report/CapstoneProjectAnime.pbit`
2. **Open** in Power BI Desktop
3. **Refresh** to pull latest data (or point to a curated CSV if you add one)
4. Explore the pages and slicers

> If your refresh is slow, limit pages of the API in your M query.

---

## 📸 Preview

| Anime By Genre | Anime By Production Studio | Popularity by Producer
|---|---|
| ![Anime By Genre](screenshots/AnimeByGenre.png) | ![Anime By Production Studio](screenshots/AnimeByProductionStudio.png) | ![Popularity by Producer](screenshots/PopularitybyProducer.png) 



---

## 🙌 Credits

- Data: **Jikan REST API** (community-maintained MyAnimeList API) → https://jikan.moe

---

## 🪪 License

MIT — feel free to reuse with attribution.

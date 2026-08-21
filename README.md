# Netflix Content Atlas 內容圖鑑

An interactive bilingual dashboard analyzing 8,807 Netflix titles — exploring content growth, global reach, genres, ratings, and top talent.

互動式雙語儀表板，分析 Netflix 8,807 部作品的內容成長、全球版圖、類型分佈、分級結構與人才排行。

🔗 **Live Demo → [Wei-Hsuan5.github.io/netflix-dashboard](https://Wei-Hsuan5.github.io/netflix-dashboard)**

---

## Features 功能

- **Bilingual UI** — Toggle between English and 繁體中文 instantly
- **Interactive charts** — Hover tooltips on all charts and bars
- **Dark / Light theme** — Follows system preference, manually toggleable
- **Data insights** — Key findings with supporting data points for each section
- **Fully static** — No backend, no tracking, no external dependencies (except Google Fonts)

---

## Dashboard Sections 儀表板區塊

| Section | Content |
|---|---|
| Content Growth 內容成長 | Annual title additions 2015–2021, Movie vs TV Show split |
| Global Reach 全球版圖 | Top 10 producing countries, Top 10 genres |
| Content Profile 內容輪廓 | Audience rating distribution, Movie runtime distribution |
| Patterns 上架規律 | Monthly upload rhythm, TV show season counts |
| Top Talent 人才排行 | Top 10 directors and actors by title count |

---

## Data Source 資料來源

**Netflix Movies and TV Shows** — [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

- 8,807 titles
- 123 countries of origin
- Release years: 1925–2021
- Fields: title, type, director, cast, country, date added, release year, rating, duration, genres

---

## Tech Stack 技術

Built with vanilla HTML, CSS, and JavaScript — no frameworks or libraries.

- Charts rendered with inline SVG + JavaScript
- Bilingual i18n via a lightweight translation object
- CSS custom properties for theming (light / dark)
- Google Fonts: Bebas Neue + DM Sans

---

## Local Development 本地開發

No build step required. Just open `index.html` in a browser.

```bash
git clone https://github.com/Wei-Hsuan5/netflix-dashboard.git
cd netflix-dashboard
open index.html
```

---

*Built with [Claude (Cowork)](https://claude.ai) · Data from Kaggle*

# 🎬 Netflix Content Dashboard

![Dashboard Preview](Dasboard_Imag<img width="1421" height="656" alt="Dasboard Image" src="https://github.com/user-attachments/assets/a60ce4ba-8a99-4cff-8fea-5589a168751a" />
e.png)

## 📋 Project Overview

This project is an **interactive Excel dashboard** built on the Netflix Titles dataset, providing a comprehensive visual analysis of Netflix's content library — covering movies, TV shows, ratings, release trends, and country-wise distribution.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `netflix_titles.csv` | Raw dataset containing 8,392 Netflix titles |
| `Nextflix_project.xlsx` | Excel workbook with cleaned data and interactive dashboard |
| `Dasboard_Image.png` | Dashboard screenshot/preview |

---

## 📊 Dashboard Highlights

The dashboard presents the following key metrics and visuals:

### KPI Cards
- **Total Titles:** 8,392
- **Total Movies:** 5,748
- **Total TV Shows:** 2,643
- **Latest Release Year:** 2021

### Charts & Visuals
- **Donut Chart** — Distribution of Movies vs. TV Shows
- **Area/Bar Chart (Years)** — Content added per year from 2012 to 2021, showing the peak in 2018–2019
- **Bar Chart (Country)** — Top content-producing countries (United States leads with 2,630 titles)
- **Horizontal Bar Chart (Rating)** — Content breakdown by rating (TV-MA dominates with 3,154 titles)

### Filter Panel (Slicers)
- Filter by **Type** (Movie / TV Show)
- Filter by **Rating** (NR, PG, PG-13, R, TV-14, etc.)
- Filter by **Country**

---

## 🗂️ Dataset Details

**Source:** Netflix Titles Dataset (publicly available on Kaggle)

| Column | Description |
|--------|-------------|
| `show_id` | Unique identifier for each title |
| `type` | Movie or TV Show |
| `title` | Name of the title |
| `director` | Director(s) of the content |
| `cast` | Cast members |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating (TV-MA, PG-13, R, etc.) |
| `duration` | Duration in minutes (movies) or seasons (TV shows) |
| `listed_in` | Genre categories |
| `description` | Short synopsis |

**Total Records:** 8,391 titles (excluding header)

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data cleaning, pivot tables, charts, slicers, dashboard layout
- **Dataset Format:** CSV → Excel

---

## 🔍 Key Insights

1. **Movies dominate** Netflix's library, making up ~68% of all content (5,748 out of 8,392).
2. **Content growth peaked** around 2018–2019 with 1,029–1,143 new titles added per year.
3. **The United States** is the largest content producer on Netflix with 2,630 titles.
4. **TV-MA** is the most common rating (3,154 titles), indicating a heavy lean toward mature content.
5. **India** ranks third globally in content production with 914 titles.

---

## 👤 Author

**Tejas**
Data Analysis Project — Netflix Content Dashboard

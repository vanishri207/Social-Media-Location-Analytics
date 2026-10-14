# Social Media Location Analytics Dashboard (Power BI)

This project presents an interactive Power BI dashboard built to analyze social media posts and engagement across different cities and platforms. It combines KPI cards, a geographical map, city-wise comparisons, platform analysis, and interactive slicers to make the data easier to explore.

---

## Objectives

- Analyze social media posts across different cities and countries.
- Compare likes, comments, and shares across locations.
- Identify differences in overall engagement between cities.
- Compare the number of posts across social media platforms.
- Build an interactive Power BI dashboard using City and Platform slicers.
- Present location-based engagement through a map visualization.

---

## Data Preparation

### Data Import

- Imported the social media dataset from `Location_Analytics.xlsx` into Microsoft Power BI Desktop.

### Data Preparation

- Loaded the dataset into Power BI.
- Checked the data types of the columns before creating visuals.
- Used the available fields: `Post ID`, `City`, `Country`, `Platform`, `Likes`, `Comments`, and `Shares`.

### KPI Creation

Created card visuals for the following summary metrics:

- Total Posts
- Total Likes
- Total Comments
- Total Shares

---

## Dashboard Overview

The dashboard brings together summary KPIs, geographical analysis, city-wise comparisons, platform analysis, and interactive filters on a single page.

![Social Media Location Analytics Dashboard](screenshots/dashboard.png)

### KPIs

The dashboard displays the following headline metrics:

- **Total Posts:** 20
- **Total Likes:** 21K
- **Total Comments:** 2K
- **Total Shares:** 1K

![KPI cards](screenshots/kpi-cards.png)

### Charts and Visuals

1. **Map — Engagement by Location:** Displays social media engagement across cities. Hover over a city bubble to view location-based engagement information.

   ![Engagement by location map](screenshots/engagement-map.png)

2. **Bar Chart — Total Engagement by City:** Compares overall engagement across cities.

   ![Total engagement by city](screenshots/engagement-by-city.png)

3. **Bar Chart — Likes by City:** Compares likes associated with posts from different cities.

   ![Likes by city](screenshots/likes-by-city.png)

4. **Column Chart — Posts by Platform:** Compares the number of posts from Instagram, Facebook, and YouTube.

   ![Posts by platform](screenshots/posts-by-platform.png)

### Slicers / Interactive Filters

The dashboard includes interactive slicers that allow users to filter the analysis:

- **City slicer:** Filters the visuals to a selected city.

  ![City slicer](screenshots/city-slicer.png)

- **Platform slicer:** Filters the visuals to a selected social media platform.

  ![Platform slicer](screenshots/platform-slicer.png)

---

## Dashboard Features

- KPI cards for total posts, likes, comments, and shares.
- A map visual for geographical engagement analysis.
- Bar charts for total engagement and likes by city.
- A column chart for post counts by platform.
- Interactive City and Platform slicers.
- A single-page layout for an overall view of the dataset.

---

## Key Insights

- Social media engagement varies across the cities in the dataset.
- Mumbai and Bengaluru show relatively high overall engagement in the documented analysis.
- Instagram has the highest number of posts among the platforms shown.
- The map provides a geographical view of engagement, while the bar charts support city-to-city comparisons.
- City and Platform slicers let users explore selected parts of the dataset.

---

## Conclusion

The Social Media Location Analytics dashboard demonstrates how Microsoft Power BI can be used to analyze social media engagement across geographical locations and platforms. By combining KPI cards, a map, comparison charts, and interactive slicers, the dashboard turns the dataset into a clear visual summary and allows users to explore city- and platform-level patterns.

---

## How to Use

1. Download or clone this repository.
2. Open `Powerbi_project.pbix` in Microsoft Power BI Desktop.
3. If Power BI asks for the dataset location, connect the report to `Location_Analytics.xlsx` and refresh the data.
4. Use the City and Platform slicers to filter the visuals.
5. Hover over map bubbles and chart elements to inspect the available details.

---

## Project Structure

```text
Social-Media-Location-Analytics/
├── README.md
├── Powerbi_project.pbix
├── Location_Analytics.xlsx
└── screenshots/
    ├── dashboard.png
    ├── kpi-cards.png
    ├── engagement-map.png
    ├── engagement-by-city.png
    ├── likes-by-city.png
    ├── posts-by-platform.png
    ├── city-slicer.png
    └── platform-slicer.png
```

---

## Tools Used

- **Microsoft Power BI Desktop** — dashboard development and data visualization.
- **Microsoft Excel** — source dataset.
- **Map visualization** — geographical engagement analysis.
- **Card visuals** — summary KPIs.
- **Bar and column charts** — city and platform comparisons.
- **Slicers** — interactive filtering.

---

## Author

**Vanishri Suresh**  
TY B.Sc. Data Science, SIES College of Arts, Science & Commerce  
Roll No.: TDS2627059

- **LinkedIn:** [Vanishri Suresh](https://www.linkedin.com/in/vanishri-suresh-0a18a4357)
- **GitHub:** [vanishri207](https://github.com/vanishri207)
- **Email:** vanishrisuresh20@gmail.com

---

## Feedback & Support

Suggestions and feedback are welcome. If you find this project useful, consider giving the repository a star.

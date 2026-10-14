# Social Media Location Analytics Dashboard

An interactive **Power BI** dashboard for exploring social media post activity and engagement across cities and platforms.

## Dashboard Preview

![Full Social Media Location Analytics dashboard](screenshots/dashboard.png)

## Project Overview

The project analyzes social media engagement geographically and by platform. It brings together headline KPIs, a map, city-level comparisons, platform post counts, and slicers in one report page.

## Dashboard Elements

### 1. KPI Cards — Headline Metrics

![KPI cards](screenshots/kpi-cards.png)

The four cards provide a quick summary of the dataset:

- **Total Posts: 20** — number of posts represented.
- **Total Likes: 21K** — total likes.
- **Total Comments: 2K** — total comments.
- **Total Shares: 1K** — total shares.

### 2. Engagement by Location — Map

![Engagement by location map](screenshots/engagement-map.png)

The map places engagement data geographically, helping viewers see how activity is distributed across locations. The map includes bubbles at locations shown in the report.

### 3. Total Engagement by City — Bar Chart

![Total engagement by city](screenshots/engagement-by-city.png)

This horizontal bar chart compares total engagement across cities, making it easier to compare the relative engagement levels of locations such as Mumbai, Bengaluru, Delhi, and Pune.

### 4. Likes by City — Bar Chart

![Likes by city](screenshots/likes-by-city.png)

This chart focuses specifically on likes by city. It complements the overall engagement chart by showing one engagement metric separately.

### 5. Posts by Platform — Column Chart

![Posts by platform](screenshots/posts-by-platform.png)

The column chart compares post counts for Instagram, Facebook, and YouTube. In the displayed report, Instagram has the highest post count among the three platforms.

### 6. City Slicer

![City slicer](screenshots/city-slicer.png)

The city buttons let viewers filter the report to a selected city, so the visual comparisons can be explored for a particular location.

### 7. Platform Slicer

![Platform slicer](screenshots/platform-slicer.png)

The platform buttons let viewers filter the report by Facebook, Instagram, or YouTube.

## Key Observations

- Engagement levels differ by city in the displayed report.
- Mumbai and Bengaluru appear among the higher-engagement cities in the total engagement comparison.
- Instagram has the highest post count in the platform chart.
- The map gives a geographic view, while the bar charts support direct city comparisons.
- City and platform slicers provide interactive filtering.

## Tools and Visual Elements

- **Microsoft Power BI Desktop** — dashboard development.
- **Microsoft Excel** — source dataset.
- **KPI cards** — total posts, likes, comments, and shares.
- **Map visual** — geographic distribution of engagement.
- **Horizontal bar charts** — total engagement and likes by city.
- **Column chart** — posts by platform.
- **Slicers** — city and platform filters.

## Dataset Fields

The project documentation identifies these fields: `Post ID`, `City`, `Country`, `Platform`, `Likes`, `Comments`, and `Shares`.

## How to Use

1. Download `Powerbi_project.pbix` from this repository and open it in Power BI Desktop.
2. If prompted, confirm or update the data source connection to the included Excel file.
3. Use the **City** and **Platform** slicers to filter the visuals.
4. Hover over map points or chart marks to inspect the details available in the report.

## Conclusion

This dashboard combines location-based and platform-based views of social media activity in a single interactive report. KPI cards summarize the overall totals, the map adds geographic context, and the charts and slicers support comparisons across cities and platforms.

## Future Enhancements

- Add a date field to analyze engagement trends over time.
- Expand the dataset with more posts and platforms.
- Explore sentiment analysis if suitable text data becomes available.
- Add drill-through pages and richer tooltips.
- Connect to a regularly refreshed data source.

# NYC-BIC-Violations-Data-Analysis-Report

🚧 NYC BIC Violations Data Analysis Dashboard

This project analyzes public violation records issued by the New York City Business Integrity Commission (BIC) for businesses involved in the collection and disposal of trade waste.

The dataset includes detailed information about violation types, fines, business names, locations, and regulatory rules violated.

🔍 Project Goals

Perform descriptive analysis to understand violation patterns, total fines, and most penalized businesses.

Conduct business-level analysis to identify top offenders by fine amount and frequency.

Build interactive maps to visualize where violations are concentrated across NYC.

Develop a dashboard-style interface combining charts and maps to communicate findings effectively.

📊 Key Features

Top Fined Businesses: Bar chart showing companies with the highest total fines.

Violations Over Time: Line plot to track changes in violation frequency by year.

Fines by Borough: Aggregated fines visualized by NYC boroughs.

Interactive Cluster Map: Folium-based map showing each violation with popup details.

Geospatial Heatmap: Visual density of violations across the city.

🛠️ Tools & Libraries Used

Pandas – data cleaning and wrangling

Matplotlib / Seaborn – basic visualization

Plotly Express – interactive bar and line charts

Folium – mapping violations using latitude and longitude

Google Colab – cloud-based environment for running all analysis and visualizations

📁 Outputs

cluster_map.html: Interactive map with marker clusters of violations

heatmap.html: Density heatmap of violations across NYC

dashboard.html: Simple HTML dashboard linking to maps and summaries

📌 Dataset Source

NYC Open Data: BIC Issued Violations

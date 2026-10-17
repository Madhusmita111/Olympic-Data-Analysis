#  Olympic Data Analysis Dashboard

An interactive Microsoft Excel analytics project exploring Olympic history through athlete participation, medal distribution, country performance, sports, and athlete-level trends.

Built with **Excel, Power Query, Pivot Tables, Pivot Charts, slicers, and filters**, this project demonstrates an end-to-end data preparation and visualization workflow, from integrating raw datasets to presenting insights through an interactive dashboard.

---

##  Dashboard Preview

![Olympic Data Analysis Dashboard](images/01-dashboard.png)

##  Project at a Glance

- **271,117 rows** in the primary raw dataset
- **14 columns** in the primary raw dataset
- **232 rows and 2 columns** in the secondary source file
- **205,912 rows and 15 columns** in the final cleaned dataset
- **ETL workflow** performed with Excel Power Query
- **14 analytical objectives** covered by the dashboard

> The source files were merged and transformed in Power Query. The final dataset contains fewer rows than the primary source; the exact row reduction should be explained using the actual cleaning and transformation steps in the workbook.

##  Project Objectives

The goal is to explore Olympic participation and performance using interactive dashboard views and comparative visualizations.

1. **Number of Participants:** Display the total number of participants.
2. **Best-Performing Countries:** Compare countries based on medal counts.
3. **Top Olympic Medalists:** Highlight leading medal-winning athletes.
4. **Male vs Female Performance:** Compare medal achievements by sex and medal type.
5. **Most Popular Sports:** Explore participation counts across selected sports.
6. **Medal Victory vs Age:** Examine medal counts across athlete ages.
7. **Country Performance Over Time:** Explore country performance across Olympic years.
8. **Summer vs Winter Olympics:** Compare country performance across Olympic seasons.
9. **Medal Victory vs Weight:** Explore the relationship between athlete weight and medal outcomes.
10. **Medal Victory vs Height:** Explore the relationship between athlete height and medal outcomes.
11. **Host Country vs Participation:** Analyze player participation in relation to the host country.
12. **Most Dominant Countries on a World Map:** Visualize geographical patterns in Olympic performance.
13. **Top 10 Olympic Players:** Compare leading athletes by overall medal performance.
14. **Top 10 Olympic Nations:** Compare leading nations by overall Olympic performance.

##  Dataset Overview

The project used two source files that were prepared and merged using Power Query.

| Dataset | Rows | Columns |
|---|---:|---:|
| Primary raw dataset | 271,117 | 14 |
| Secondary source file | 232 | 2 |
| **Final cleaned dataset** | **205,912** | **15** |

The consolidated dataset was used as the basis for Pivot Tables, charts, summary metrics, and dashboard views.

##  ETL Workflow Using Power Query

The project follows an Extract, Transform, and Load (ETL) workflow to prepare the source data for analysis.

### 1. Extract
- Imported the two source files into Power Query.
- Started with a primary dataset containing 271,117 rows and 14 columns.
- Loaded a secondary dataset containing 232 rows and 2 columns.

### 2. Transform
- Inspected and prepared the source data for integration.
- Merged the two datasets using Power Query.
- Cleaned and transformed the data for analytical use.
- Structured the resulting fields for Pivot Table summaries and visualizations.

### 3. Load and Analyze
- Produced a cleaned dataset containing 205,912 rows and 15 columns.
- Used the prepared data to build Pivot Tables and Pivot Charts.
- Created interactive dashboard views with available slicers and filters.

### Data Preparation Summary

**Two source files → Power Query ETL and merge → cleaned dataset → Pivot Tables and charts → interactive dashboard**

The final row count is lower than the primary source row count. The precise reasons for that difference should be described only in terms of the actual Power Query steps used in the workbook.

##  Dashboard Gallery

The screenshots below follow the workbook's analysis tabs in sequence. They show the overall dashboard first, followed by supporting analysis sheets.

### 1. Main Dashboard

A consolidated overview of participation and medal metrics, top medalists, country performance, sport popularity, gender comparisons, athlete trends, and geographical visualizations.

![Main Dashboard](images/01-dashboard.png)

### 2. Number of Participants

Displays participation summaries and gender-related counts alongside medal metrics.

![Number of Participants](images/02-number-of-participants.png)

### 3. Best-Performing Countries

Compares gold, silver, and bronze medal counts across countries.

![Best-Performing Countries](images/03-best-performing-countries.png)

### 4. Top Olympic Medalists

Compares medal counts for leading athletes across medal categories.

![Top Olympic Medalists](images/04-top-olympic-medalists.png)

### 5. Most Popular Sports

Visualizes participant counts across selected sports and gender categories.

![Most Popular Sports](images/05-most-popular-sports.png)

### 6. Male vs Female Performance

Compares medal distribution between male and female athletes.

![Male vs Female Performance](images/06-male-vs-female.png)

### 7. Victory vs Age

Explores medal counts across athlete ages.

![Victory vs Age](images/07-victory-vs-age.png)

### 8. Top 10 Players

Shows a comparative view of leading Olympic athletes and their medal counts.

![Top 10 Players](images/08-top-10-players.png)

> The main dashboard also includes additional views such as height vs medals, weight vs victory, country performance over time, host country vs participation, dominant countries on a world map, top nations, and Summer vs Winter comparisons.

##  Key Features

- Interactive Excel dashboard with slicers and filters
- Participation and medal summary metrics
- Country-wise medal comparisons
- Athlete-level medal analysis
- Sport popularity and participation comparisons
- Male vs female medal distribution
- Age, height, and weight relationship exploration
- Country performance across years and Olympic seasons
- World map visualization for geographical comparison
- Pivot Table-based summaries and Pivot Chart visualizations

##  Tools & Technologies

| Tool / Technique | Purpose |
|---|---|
| Microsoft Excel | Analysis and dashboard development |
| Power Query | ETL, data preparation, transformation, and merging |
| Pivot Tables | Aggregation and comparative summaries |
| Pivot Charts | Visual analysis of medal and participation metrics |
| Slicers and filters | Interactive exploration of dashboard data |

##  Analytical Questions Explored

The dashboard helps explore questions such as:

- How is Olympic participation distributed by sex?
- Which countries have the highest medal counts in the analyzed dataset?
- Which athletes appear among the leading medal winners?
- Which sports have higher participant counts?
- How do medal counts vary across athlete ages?
- How does country performance change across Olympic years?
- How do country-level results compare between Summer and Winter Olympics?
- What patterns appear when medal outcomes are compared with athlete height and weight?
- How does participation relate to the host country?
- Which nations and athletes rank among the leading performers in the analysis?

These are exploratory comparisons. Relationships between athlete characteristics and medals should not be interpreted as evidence of causation.

##  How to Use

1. Open the repository and download the Excel workbook.
2. Open the workbook in Microsoft Excel.
3. Select the **Dashboard** worksheet to begin.
4. Use the workbook tabs to explore individual analyses.
5. Interact with available slicers and filters to compare countries, years, sports, seasons, age groups, and medal categories.
6. If Excel prompts for data refresh, follow the workbook's supported refresh settings where applicable.

##  Repository Structure

```text
Olympic-Data-Analysis/
├── README.md
├── olympic's_dashboard[1].xlsx
└── images/
    ├── 01-dashboard.png
    ├── 02-number-of-participants.png
    ├── 03-best-performing-countries.png
    ├── 04-top-olympic-medalists.png
    ├── 05-most-popular-sports.png
    ├── 06-male-vs-female.png
    ├── 07-victory-vs-age.png
    └── 08-top-10-players.png
```

##  Skills Demonstrated

- ETL workflow design using Power Query
- Combining multiple source files
- Data cleaning and transformation
- Structuring data for analytical use
- Pivot Table-based aggregation
- Interactive dashboard development
- Comparative analysis and data visualization
- Communicating analytical questions through visual reports


---

*An Excel-based exploration of Olympic participation and performance through data preparation, analysis, and visualization.*

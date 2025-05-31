# Assignment 6: U.S. Presidential Vote Patterns (2008–2024)

This project analyzes shifts in U.S. presidential vote shares by state from 2008 to 2024. The analysis focuses on Republican vote proportions, specifically Donald Trump's performance across the 2016, 2020, and 2024 elections, using a combination of data wrangling, visualization, and mapping techniques in R.

## 📊 Objectives

- Reshape and clean a dataset containing two-party vote shares by state for five presidential elections (2008–2024)
- Explore patterns in vote share changes across time and geography
- Visualize trends and outliers using scatter plots, line graphs, and thematic maps
- Develop clear, accessible visuals that tell a compelling story about electoral shifts in the United States

## 🛠️ Methods & Tools

- **Data Transformation:** Used `tidyverse` packages to pivot the vote share data to long format for ease of analysis
- **Summary Stats:** Generated clean summary tables of Trump’s vote share proportions in 2016, 2020, and 2024
- **Interactive Tables:** Built sortable, filterable vote share tables with the `DT` package
- **Scatter Plot:** Created a vote swing plot (Trump 2020 vs. 2024) with labeled state points and a 45-degree reference line
- **Line Plot:** Visualized long-term voting trends (2008–2024) across 50 states; emphasized key states using color
- **Faceting:** Used faceted plots by U.S. Census region to clarify regional voting patterns
- **Thematic Mapping:** Created a choropleth of 2020–2024 vote change using `sf` and `ggplot2`, omitting DC for balance

## 🧩 Key Findings

- While some states saw modest changes, others—like Florida and Ohio—showed significant shifts in Trump support between 2020 and 2024.
- The 45-degree reference line in the swing plot helped distinguish states with increased or decreased Republican vote shares.
- Faceting by Census region clarified regional consistencies and anomalies in party preference over time.
- The thematic map of 2020–2024 vote change offered a geographic perspective that was less obvious in previous plots, highlighting spatial clustering of electoral shifts.

## 📁 Files Included

- `assignment_06_vote_analysis.qmd`: Quarto file with code and visualizations
- `assignment_06_vote_analysis.html`: Rendered HTML report
- `state_prez_vote_08-24.csv`: Main dataset of vote shares
- `assignment_06_files/`: Assets for HTML rendering (e.g., plots, styles)

## 📚 References

- Healy, K. (2018). *Data Visualization: A Practical Introduction*, Sections 7.1 and 9.1.
- `tidyverse`, `DT`, `sf`, `ggplot2`, `reactable`, `colorspace`, `usmap`

## 🧠 Skills Practiced

- Data wrangling with `pivot_longer()` and `left_join()`
- Time series visualization and scatter plot annotation
- Thematic mapping and geospatial analysis
- Interactive data display with `DT` tables
- Visual storytelling and pattern interpretation

## 🤝 Let's Connect

Curious about this project or have ideas to build on it? Reach out on [LinkedIn](https://linkedin.com/in/abapobee) to connect!

# Assignment 4: Making Maps – Thematic Mapping with `sf` and `ggplot2`

This assignment explores thematic cartography using R's `sf`, `ggplot2`, and `dplyr` packages. The goal was to identify geographically distributed variables and effectively communicate insights through choropleth maps, while adhering to data visualization best practices.

## 🗺️ Objectives

- Join real-world data to simple feature data frames using `left_join()`
- Generate blank maps using simple feature geometries
- Create thematic maps with both **gradient** and **classed** color schemes
- Assess and compare how different color schemes influence perception
- Explore map accessibility using the `colorblindr` and `colorspace` packages
- Experiment with alternative palettes such as the **Okabe-Ito** scale for improved accessibility

## 📊 Variables and Data Sources

1. **Continuous Variable:**  
   *Maryland county-level unemployment rates* were mapped using a simple feature dataframe of Maryland counties. The goal was to visualize economic variation without replicating population density patterns.

2. **Categorical Variable:**  
   *Most consumed type of alcoholic drink by U.S. state*, joined to a U.S. state shapefile. This allowed for the exploration of cultural and regional preferences in beverage consumption.

## 🛠️ Methods

- Used `left_join()` to merge CSV datasets with corresponding shapefiles.
- Created gradient and classed color scheme maps using `scale_fill_gradient()` and `scale_fill_brewer()`.
- Evaluated the impact of color choice on interpretability and storytelling.
- Simulated color vision deficiency effects with `colorblindr::cvd_grid()` to ensure accessibility.
- Applied the **Okabe-Ito** palette recommended by Claus Wilke to improve visual inclusivity.

## 📁 Files Included

- `Pobee_Making_Maps.qmd`: Quarto file with code and commentary
- `Pobee_Making_Maps.html`: Rendered HTML report
- `Pobee_Making_Maps_files/`: Assets required for HTML rendering
- `mdunemploymentdata.csv`: Unemployment data by Maryland county
- `numberofdrinks.csv`: Most consumed drink type by U.S. state

## 🔍 Key Takeaways

- **Gradient vs. Classed Maps:** Classed color schemes helped avoid exaggeration of outliers and made ranges clearer for public audiences.
- **Sequential vs. Diverging Palettes:** Diverging schemes were more effective for datasets with a meaningful midpoint (e.g., national average).
- **Accessibility Testing:** Some initial color palettes failed common color vision deficiency simulations. The Okabe-Ito palette significantly improved contrast and clarity.

## 📚 References

- Wilke, C. (2019). *Fundamentals of Data Visualization.*
- Healy, K. (2018). *Data Visualization: A Practical Introduction.*
- `colorblindr`, `ggplot2`, `sf`, `dplyr`, `colorspace`, `viridis`

## 🤝 Let’s Connect

Questions about this project or my approach? Feel free to connect with me on [LinkedIn](https://linkedin.com/in/abapobee).

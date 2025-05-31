# Final Project: Hydroxyurea and the Gaps in Sickle Cell Treatment – A Data-Driven Reflection

This final project investigates the demographic and clinical factors associated with hydroxyurea (HU) discontinuation among individuals living with sickle cell disease (SCD). It was completed for the Data Visualization (DATS 2102) course at The George Washington University.

## ❓ Research Question

**What factors are associated with whether a person with sickle cell disease discontinues hydroxyurea therapy?**  
This question is both scientifically and personally important. Hydroxyurea is a critical treatment for managing SCD, yet many patients stop using it. As someone with a sibling who relies on hydroxyurea, I was motivated to understand the barriers to continued use and how they differ across groups.

## 🧾 Data Sources

- **Primary Data Source:** Supplemental Table S2 from the 2024 *PLOS ONE* article:  
  *“Multisite study of hydroxyurea discontinuation among individuals with sickle cell disease”* by Kanter et al.
- **Sample:** Harmonized individual-level data from 5 U.S.-based studies: Baby HUG, C-Data, MSH, SCDIC, Walk-PHaSST
- **Unit of Analysis:** Person-level, based on clinical and demographic data
- **Time Frame:** 2006–2019 (study enrollment years); harmonized in 2024

## 🔍 Variables of Interest

- **Dependent Variable:**  
  - *Hydroxyurea use group* (currently using, discontinued, never used)
- **Independent Variables:**  
  - *Genotype* (HbSS/HbSβ⁰, HbSC, HbSβ⁺, Other/Unknown)  
  - *Sex* (Male/Female)  
  - *Optional*: Age group, Pain severity

These variables were chosen for their relevance in clinical care and known impact on treatment adherence.

## 📈 Methods

- Data cleaning and wrangling with `dplyr`
- Summary statistics and frequency tables for each variable of interest
- Exploratory analysis with `ggplot2` to visualize hydroxyurea usage patterns
- Stratified comparisons by genotype, sex, and self-reported pain severity
- Critical reflection on barriers to care, health equity, and structural determinants of treatment adherence

## 📊 Key Findings

- Discontinuation rates were similarly high across all genotypes, even among patients with the most severe form (HbSS/HbSβ⁰).
- Females had slightly higher HU discontinuation rates, suggesting potential reproductive or care-related concerns.
- Patients with higher reported pain levels were more likely to have used HU—but also more likely to discontinue it—indicating unmet expectations or inadequate follow-up support.
- Structural and psychosocial barriers likely play a larger role than clinical need alone in explaining discontinuation patterns.

## 📁 Files Included

- `POBEE_FINAL.qmd`: Quarto document with analysis (code included, hidden on render)
- `POBEE_FINAL.html`: Final rendered report
- `POBEE_FINAL_files/`: Assets required for HTML rendering (e.g., images, charts)
- `data/`: Cleaned version of the harmonized dataset used for analysis

## 🧠 Reflections

This project highlighted how data visualization can reveal hidden inequities in health outcomes and access. It underscored the need for healthcare models that prioritize patient voices and address both structural and emotional determinants of adherence.

## 🧬 Tools Used

- `R`, `dplyr`, `ggplot2`, `readxl`, `quarto`
- HTML output with hidden code chunks for a clean presentation

## 📫 Let’s Connect

Interested in public health, sickle cell research, or data equity? Feel free to reach out on [LinkedIn](https://linkedin.com/in/abapobee) or explore the project to learn more.

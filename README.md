# Data Analytics Portfolio Project

This repository is a portfolio-ready template for presenting data analytics, statistical modelling, and visualization projects on GitHub. It currently contains one R Markdown project report and can be expanded into a consistent structure for future resume projects.

## Current Project

**Exploratory Data Analysis and Predictive Modelling**

The included report explores the relationship between worldwide box office revenue, GDP, and population across countries from 2000 to 2024. It demonstrates a complete analytical workflow: data cleaning, exploratory visualization, feature engineering, classification modelling, model comparison, and interpretation.

## Skills Demonstrated

- Data cleaning and preprocessing in R
- Exploratory data analysis and visualization with `ggplot2`
- Data transformation with `tidyverse`
- Statistical modelling and classification
- Decision tree modelling with `rpart`
- Logistic regression
- ROC/AUC model evaluation
- Model interpretation with LIME
- Reproducible reporting with R Markdown

## Repository Structure

```text
.
|-- Project1.Rmd             # Main R Markdown analysis report
|-- PORTFOLIO_TEMPLATE.md    # Reusable template for future portfolio projects
|-- .gitignore               # R/RStudio and generated-file ignore rules
`-- README.md                # Project overview for GitHub and resume readers
```

## How to Run

1. Open `Project1.Rmd` in RStudio.
2. Install the required R packages:

```r
install.packages(c(
  "tidyverse",
  "readr",
  "dplyr",
  "caret",
  "rpart",
  "rpart.plot",
  "pROC",
  "knitr",
  "lime",
  "patchwork"
))
```

3. Place the required input datasets in the repository root:

```text
Box_office_data(2000-2024).csv
GDP_2020_2024.csv
Population_2000_2024.csv
```

4. Knit `Project1.Rmd` to HTML.

## Notes for Future Projects

For a stronger resume-facing GitHub profile, each project should include:

- A clear project title and business/research question
- Dataset source and data dictionary
- Reproducible setup instructions
- Clean folder structure, such as `data/`, `scripts/`, `reports/`, and `outputs/`
- A concise results summary with 2-3 key findings
- Screenshots or rendered report outputs when possible
- A short explanation of tools, models, and evaluation metrics

Use `PORTFOLIO_TEMPLATE.md` as a starting point when adding future projects.

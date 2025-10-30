# Personal Website & Data Science Portfolio

This repository contains my personal website and data science projects for P8105: Data Science I at Columbia University.

## Website

Visit my website at: [https://bx2232.github.io](https://bx2232.github.io)

## Contents

* **Home Page** (`index.Rmd`): Introduction and overview
* **Resume** (`resume.Rmd`): Academic and professional experience
* **Interactive Dashboard** (`dashboard.Rmd`): Data visualization project using Instacart shopping data

## Projects

### Instacart Shopping Insights Dashboard

An interactive flexdashboard exploring online grocery shopping patterns using the Instacart dataset. The dashboard features:

* Most popular products across departments
* Shopping activity patterns throughout the day
* Aisle popularity analysis
* Reorder behavior by day of week
* Department ordering patterns
* Distribution of time between orders

**Technologies:** R, flexdashboard, plotly, tidyverse

## Setup & Reproducibility

To reproduce this website locally:

1. Clone the repository
```bash
git clone https://github.com/bx2232/p8105_hw4_bx2232.git
```

2. Open the R Project file in RStudio

3. Install required packages:
```r
install.packages(c("rmarkdown", "flexdashboard", "tidyverse", "plotly"))
install.packages("p8105.datasets", 
                 repos = "http://p8105.com/data/")
```

4. Build the website:
```r
rmarkdown::render_site()
```

## Data Sources

* **Instacart Dataset**: "The Instacart Online Grocery Shopping Dataset 2017" via the `p8105.datasets` package

## Contact

* **Email**: bx2232@cumc.columbia.edu
* **GitHub**: [@bx2232](https://github.com/bx2232)
* **LinkedIn**: [Bowen Xia](https://linkedin.com/in/bowen-xia)

---

*This website was created as part of coursework for P8105: Data Science I at Columbia University Mailman School of Public Health.*

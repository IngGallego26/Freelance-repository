# Effect of GA₃ and Imbibition Time on Germination of Radish (Raphanus sativus L.)  🌍🌱

This project evaluated the interaction between different concentrations of gibberellic acid (GA₃) and hours of imbibition on the germination of Raphanus sativus (radish) seeds. A 3² factorial design was used with three levels of gibberellic acid (GA) concentration (0, 3, and 6 ppm) and three levels of imbibition (0, 6, and 12 hours), with three replicates per treatment.

## 🔧 Tools & Libraries

- **R**: agricolae, readxl
- **R Markdown**: for report generation and visualizations

## 📌 Methodology

1.Experimental Design
A factorial design 3^2 was implemented under a Completely Randomized Design (CRD), with two factors: GA₃ concentration (0, 3, and 6 ppm) and imbibition time (0, 6, and 12 h). Each treatment was replicated three times.
2. Data Collection
For each experimental unit (15 radish seeds per Petri dish), the germination percentage was recorded after 48 hours of darkness.
3. Exploratory Data Analysis
Descriptive statistics and boxplots were generated to evaluate data distribution and identify potential outliers.
4. Assumptions Check
Normality and homogeneity of variances were assessed using Shapiro–Wilk and Bartlett’s tests, respectively.
5. ANOVA and Post-hoc Testing
Two-way ANOVA was conducted to evaluate the main and interaction effects of the factors. Tukey’s HSD or Dunnett’s test was applied for multiple comparisons when significant effects were detected.
6. Visualization of Results
Interaction plots, contour plots, and 3D surface plots were constructed to illustrate the response surface and factor interactions.




## 📊 Results

The analysis identified specific zones with high potential for granadilla cultivation, supporting data-driven decision-making in agricultural planning.



## 📁 Included Files

- `suitability_analysis.Rmd`: Full R code with step-by-step analysis
- `suitability_map.png`: Final output map
- `environmental_data.csv`: Input dataset (example)
- `report.html`: Rendered interactive report

## 🔗 View Online

You can preview the report here: [RPubs Link](https://rpubs.com/SantiagoGallego/1333461)

---

*This project is part of my freelance portfolio. Feel free to contact me for similar analyses or customized solutions.*

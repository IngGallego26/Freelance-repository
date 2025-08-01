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

1. Main and Interaction Effects
The two-way ANOVA revealed statistically significant effects (p < 0.05) of both imbibition time and GA₃ concentration on the germination percentage. Moreover, the interaction between these two factors was also significant, indicating that the effect of GA₃ varied depending on the imbibition duration.
2. Treatment Comparison
Post-hoc analysis (e.g., Tukey HSD) identified the combination of 6 ppm GA₃ and 12 hours of imbibition as the most effective treatment, significantly increasing germination percentage compared to the control.
3. Interaction and Surface Response
The interaction plot and surface plots (perspective and contour views) confirmed a synergistic effect, where higher GA₃ concentrations were more effective when seeds were pre-soaked for longer durations.
4. Biological Interpretation
These results suggest that seed exposure to GA₃ under optimal imbibition enhances the activation of physiological mechanisms involved in breaking dormancy and promoting germination in radish seeds (Raphanus sativus L.).



## 📁 Included Files
- `ANOVA_analysis.Rmd`: Full R code with step-by-step analysis
- `boxplot_germination.png` exploratory graphic
- `interaction.png`
- `Contour_and_surface.png`: Final output graphic
- `table_anova.xlsx`
- `report.html`: Rendered interactive report

## 🔗 View Online

You can preview the report here: [RPubs Link](https://rpubs.com/SantiagoGallego/1333461)

---

*This project is part of my freelance portfolio. Feel free to contact me for similar analyses or customized solutions.*

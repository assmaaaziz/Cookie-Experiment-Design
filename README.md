## Cookie Experiment Design

A factorial analysis of how baking conditions affect cookie size.

**Overview**

This project analyzes how butter temperature, oven temperature, and baking time influence cookie diameter.
Using a 2 × 2 × 3 factorial experimental design, I evaluated which combination of conditions produces the largest cookies.

The analysis demonstrates the application of experimental design principles, including randomization, replication, and analysis of variance (ANOVA), using R for statistical modeling and visualization.

**Objectives**

Identify key factors that influence cookie size.

Apply factorial design methodology to study main and interaction effects.

Use ANOVA and randomization-based inference to test significance.

Communicate findings through statistical reasoning and visualization.

**Experimental Setup**

Design Type: 2 × 2 × 3 factorial design (completely randomized)
Response Variable: Cookie diameter (inches)

Factor	Levels
Butter Temperature	Room Temperature / Melted
Oven Temperature	350°F / 375°F
Baking Time	10 / 12 / 15 minutes

Replications: 2
Total Cookies Baked: 24

All treatment combinations were randomized using R to minimize bias.

**Analysis Methods**

Data visualization with ggplot2 (boxplots, interaction plots)

Two-way and three-way ANOVA to test for main and interaction effects

Randomization-based inference (500 permutations) for significance testing

Model diagnostics for residual patterns and fit validation

**Key Findings**

Butter temperature and oven temperature had statistically significant effects on cookie size, while baking time and interaction terms were not significant.

The largest cookies occurred when using room-temperature butter and baking at 350°F.

The model achieved an R² ≈ 0.71, showing strong explanatory power.

**Discussion**

This experiment highlights how small changes in baking conditions can significantly affect outcomes.
It demonstrates the power of factorial experimental design for uncovering meaningful patterns in real-world processes.
While the sample size was small, the findings were statistically significant and replicable, making this a fun and practical example of applied data analysis.

**Skills Demonstrated**

Experimental design and hypothesis formulation

Factorial design and ANOVA

Randomization-based inference

R programming and visualization (tidyverse, ggplot2, dplyr)

Scientific reporting and result interpretation


**Tools Used**
R • RStudio • tidyverse • ggplot2 • stats • aov()

# Cell Growth Analysis (R)

A statistical study of how treatment and cell passage affect cell growth, using linear and mixed-effects models. Part of the Applied Bioinformatics and Biostatistics program (2024).

**Tools:** R, Quarto. Packages: lme4, nlme, easystats, ggplot2, patchwork
**Data:** a controlled cell-growth experiment. The original `Zellbeads.sav` isn't shared for privacy; the script simulates a realistic dataset if it's missing, so the analysis still runs end to end.

---

## What I did

- Explored how passage relates to cell growth
- Fit linear regression and ANOVA to test treatment and passage effects
- Built linear mixed-effects models with random intercepts and slopes (`lmer`, `nlme::lme`) to account for repeated measures
- Interpreted fixed and random effects with the easystats suite and visualized them
- Wrote the whole analysis as a reproducible Quarto report

## Files

- `Cell_Growth_Analysis.qmd` - full Quarto analysis
- `Cell_Growth_Analysis.docx` - rendered report

---

## About me

**Neslihan Oztas Ates** · Data Analyst · Ingolstadt, Germany

[LinkedIn](https://www.linkedin.com/in/neslihanoztas/) · [Portfolio](https://noztas.github.io/Portfolio-Website/) · [GitHub](https://github.com/noztas/) · neslihanoztas1@gmail.com

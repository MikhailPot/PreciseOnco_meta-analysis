# PreciseOnco_meta-analysis

# Project Description

We conducted systematic review and meta-analysis to provide a comprehensive overview of outcomes in patients who underwent personalized genomics-based versus non-personalized treatment in oncology. The PubMed searches detected 873 studies based on phase II clinical trials’ results published from 2010 to 2021. We selected 46 studies, having 81 arms and 6536 patients for the analysis. We compared Response Rate (RR), medians and 1-year rates of Overall Survival (OS) and Progression-Free Survival (PFS) between genomics-based personalized and non-personalized arms.
Current repository contains initial data and detailed R codes for proportional meta-analysis and meta-regression. Mann-Whitney and Shapiro test presented in the markdown as examples only. The searches, study selection, data extraction and synthesis were performed in accordance to PRISMA (preferred reporting items for systematic review and meta-analysis) guidelines1. The research protocol was registered in PROSPERO (International prospective register of systematic reviews, https://www.crd.york.ac.uk/PROSPERO), record ID CRD42024504021
We performed proportional meta-analysis using the RStudio program, utilizing the R programming language and packages "meta", "metafor," and "tidyverse" 2. We calculated relative risks using the Der Simonian-Laird algorithm3. Heterogeneity was evaluated based on τ2-statistic3,4 and I2 Higgins-Thompson statistic5,6. τ2 confidence intervals were calculated with Jackson method7. We compared the effects using Fisher's exact test and employed the t-test or Mann-Whitney test based on type of distribution, with a significance level set at p<0.05. The distribution normality was tested with Shapiro-Wilk test, α=0.05. Taking into account the heterogeneity we utilized the random-effects model8. We conducted meta-regression to assess the impact of the personal approach implementation and other parameters at p<0.05, 95%. CIs and p-values were estimated with Knapp-Hartung method 9,10. Each subgroup included a minimum of 10 studies.


# References
1.	Page, M. J. et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. doi:10.1136/bmj.n71.
2.	Barker, T. H. et al. Conducting proportional meta-analysis in different types of systematic reviews: a guide for synthesisers of evidence. BMC Med Res Methodol 21, 1–9 (2021).
3.	DerSimonian, R. & Laird, N. Meta-analysis in clinical trials. Control Clin Trials 7, 177–188 (1986).
4.	Zhao, Y., Slate, E. H., Xu, C., Chu, H. & Lin, L. Empirical comparisons of heterogeneity magnitudes of the risk difference, relative risk, and odds ratio. Syst Rev 11, 1–4 (2022).
5.	Meta-analyses: what is heterogeneity? (2015) doi:10.1136/bmj.h1435.
6.	Higgins, J. P. T. & Thompson, S. G. Quantifying heterogeneity in a meta-analysis. STATISTICS IN MEDICINE Statist. Med 21, 1539–1558 (2002).
7.	Jackson, D. & Bowden, J. Confidence intervals for the between-study variance in random-effects meta-analysis using generalised heterogeneity statistics: Should we use unequal tails? BMC Med Res Methodol 16, 1–15 (2016).
8.	Guolo, A. & Varin, C. Random-effects meta-analysis: the number of studies matters. https://doi.org/10.1177/0962280215583568 26, 1500–1518 (2015).
9.	Higgins, J. P. T., López-López, J. A. & Aloe, A. M. Meta-Regression. Handbook of Meta-Analysis 129–149 (2020) doi:10.1201/9781315119403-7/META-REGRESSION-JULIAN-HIGGINS-JOSE-L.
10.	Baker, W. L., White, C. M., Cappelleri, J. C., Kluger, J. & Coleman, C. I. Understanding heterogeneity in meta-analysis: the role of meta-regression. doi:10.1111/j.1742-1241.2009.02168.x.
 



# PreciseOnco_meta-analysis

# Project Description

We conducted systematic review and meta-analysis in order to provide a comprehensive overview of outcomes in patients undergoing personalized genomics-based versus non-personalized treatment in oncology. The PubMed searches detected 873 studies based on phase II clinical trials’ results published from 2010 to 2021. We selected 49 studies, having 101 arms and 7012 patients for the analysis. We compared Response Rate (RR), medians and 1-year rates of Overall Survival (OS) and Progression-Free Survival (PFS)  between genomics-based personalized and non-personalized arms. 

Courrent repository contains initial data and detailed R codes for proportional meta-analysis and meta-regression. Mann-Whitney and Shapiro test presented in the markdown as examaples only. 
The searches, study selection, data extraxtion and systhesis were performed in accordance to PRISMA (preferred reporting items for systematic review and meta-analysis) guidelines.
The research protocol was registered in PROSPERO (International prospective register of systematic reviews, https://www.crd.york.ac.uk/PROSPERO), record ID CRD42024504021

We performed proportional meta-analysis using the RStudio program, utilizing the R programming language and packages "meta," "metafor," and "tidyverse" 17. We calculated relative risks using the Der Simonian-Laird algorithm18. Heterogeneity was evaluated basing on τ2-statistic18,19 and I2 Higgins-Thompson statistic20,21. τ2 confidence intervals were calculated with Jackson method22. We compared the effects using Fisher's exact test and employed the t-test or Mann-Whitney test based on type of distribution, with a significance level set at p<0.05. The distribution normality was tested with Shapiro-Wilk test, α=0.05.

# References
1. Page, M. J. et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. doi:10.1136/bmj.n71.
2. Barker, T. H. et al. Conducting proportional meta-analysis in different types of systematic reviews: a guide for synthesisers of evidence. BMC Med Res Methodol 21, 1–9 (2021).
3. DerSimonian, R. & Laird, N. Meta-analysis in clinical trials. Control Clin Trials 7, 177–188 (1986).
4. Higgins, J. P. T., López-López, J. A. & Aloe, A. M. Meta-Regression. Handbook of Meta-Analysis 129–149 (2020) doi:10.1201/9781315119403-7/META-REGRESSION-JULIAN-HIGGINS-JOSE-L.


# STAT 601 – Week 7 Project

This repository contains my R Markdown (`.Rmd`) and rendered PDF file for Week 7 of STAT 601: Modern Applied Statistics I.  
The assignment focuses on Analysis of Variance (ANOVA), assumption testing, and interpretation of model results using real-world statistical reasoning.

##  Contents
- **Julius Hai 601 Home_Work7.Rmd** – R Markdown source file containing code, computations, and diagnostic checks.  
- **Julius Hai Home_Work7.pdf** – Rendered PDF output with complete solutions and formatted statistical results.

## 🧠 Topics Covered

### 1️⃣ One-Way ANOVA (Analysis of Variance)
The **one-way ANOVA** test is used to compare the means of three or more independent groups to determine whether at least one mean differs significantly.  
It evaluates the ratio of variance **between groups** to the variance **within groups** to determine whether group means differ more than expected by random chance.  

- **Null Hypothesis (H₀):** All group means are equal.  
- **Alternative Hypothesis (Hₐ):** At least one group mean differs.  

The F-statistic is used to test this hypothesis, and a p-value below 0.05 typically indicates a statistically significant difference.

---

### 2️⃣ Assumption Testing in ANOVA
ANOVA assumes:
- **Normality:** Residuals should be approximately normally distributed (tested using the Shapiro–Wilk test or QQ plot).  
- **Homogeneity of Variances:** Group variances should be equal (tested using Levene’s Test).  
- **Independence:** Observations must be independent of one another.  

Violations of these assumptions can affect the validity of the F-test, so diagnostic checks are performed before interpreting results.

---

### 3️⃣ Levene’s Test for Equality of Variances
**Levene’s Test** assesses whether the variances across groups are equal — a key assumption of ANOVA.  
- **H₀:** All group variances are equal.  
- **Hₐ:** At least one group variance differs.  
If *p < 0.05*, variances are unequal, and ANOVA assumptions may not hold.  
This test provides a robust way to verify model assumptions even under moderate departures from normality.

---

### 4️⃣ Shapiro–Wilk Test and QQ Plot for Normality
The **Shapiro–Wilk Test** checks whether residuals follow a normal distribution:  
- **H₀:** Data are normally distributed.  
- **Hₐ:** Data are not normally distributed.  

A p-value greater than 0.05 suggests that normality holds. The **QQ plot** visually supports this check — points lying near the diagonal line indicate approximate normality.  
Together, these methods confirm whether the data meet ANOVA’s normality assumption.

---

### 5️⃣ Interpretation of the F-Test
The **F-test** statistic measures the ratio of between-group variance to within-group variance.  
A large F-value relative to its critical value suggests that group means differ more than expected by chance.  
The p-value determines whether this difference is statistically significant:  
- If *p < 0.05* → Reject H₀ (at least one mean differs).  
- If *p ≥ 0.05* → Fail to reject H₀ (no significant difference).  

Interpretation connects statistical outcomes to real-world meaning — for example, identifying which treatment or process yields the best performance.

---

##  Author
**Julius Hai**  
Graduate Student – South Dakota State University


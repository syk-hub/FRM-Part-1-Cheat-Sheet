# FRM-Part-1-Cheat-Sheet
# 📊 FRM Formula Cheat Sheet

This cheat sheet contains essential formulas for hypothesis testing and statistical analysis.

---

## 📌 Hypothesis Testing for Means

### **1. One-Sample t-Test (Comparing Sample Mean to Population Mean)**
\[
t = \frac{\bar{X} - \mu_0}{s / \sqrt{n}}
\]

where:
- \( \bar{X} \) = sample mean  
- \( \mu_0 \) = population mean  
- \( s \) = sample standard deviation  
- \( n \) = sample size  
- **Degrees of freedom**: \( df = n - 1 \)

#### **Hypotheses**
- \(H_0: \mu = \mu_0\) (population mean is equal)
- \(H_A: \mu \neq \mu_0\) (population mean is different)

---

### **2. Two-Sample t-Test (Comparing Two Independent Means)**

#### **Equal Variance Assumed (Pooled t-Test)**
\[
t = \frac{\bar{X}_1 - \bar{X}_2}{\sqrt{S_p^2 \left( \frac{1}{n_1} + \frac{1}{n_2} \right) }}
\]

where:
\[
S_p^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1 + n_2 - 2}
\]

#### **Unequal Variance (Welch’s t-Test)**
\[
t = \frac{\bar{X}_1 - \bar{X}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}
\]

---

### **3. Paired t-Test (Dependent Samples)**
\[
t = \frac{\bar{D}}{s_D / \sqrt{n}}
\]

where:
- \( \bar{D} \) = mean of differences between paired observations  
- \( s_D \) = standard deviation of differences  
- \( n \) = number of paired observations  

#### **Hypotheses**
- \(H_0: \mu_D = 0\) (no difference in means)
- \(H_A: \mu_D \neq 0\) (significant difference)

---

## 📌 Choosing the Right Test

| **Scenario** | **Test to Use** |
|-------------|---------------|
| One sample vs. known population mean | One-sample t-test (if variance unknown) or Z-test (if variance known) |
| Comparing two independent means (equal variances) | Pooled t-test |
| Comparing two independent means (unequal variances) | Welch’s t-test |
| Comparing two dependent (paired) samples | Paired t-test |
| Large sample, known variance | Z-test |

---

## 📌 How to Use This Cheat Sheet
- This cheat sheet is written in **Markdown** with **LaTeX math equations**.
- Copy and paste this into **GitHub, Notion, or Overleaf**.
- You can update this anytime!

---

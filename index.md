# 📊 FRM Part 1 Cheat Sheet

This cheat sheet contains key formulas for hypothesis testing and statistics.

---

## 📌 One-Sample t-Test (Comparing Sample Mean to Population Mean)

The **formula** for a one-sample t-test:

$$
t = \frac{\bar{X} - \mu_0}{s / \sqrt{n}}
$$

where:
- The **sample mean** is \( \bar{X} \).
- The **hypothesized population mean** is \( \mu_0 \).
- The **sample standard deviation** is \( s \).
- The **sample size** is \( n \).
- The **degrees of freedom**: \( df = n - 1 \).

---

## 📌 Two-Sample t-Test (Comparing Two Independent Means)

### **Equal Variance Assumed (Pooled t-Test)**
The pooled variance formula:

$$
S_p^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1 + n_2 - 2}
$$

The t-test formula:

$$
t = \frac{\bar{X}_1 - \bar{X}_2}{\sqrt{S_p^2 \left( \frac{1}{n_1} + \frac{1}{n_2} \right) }}
$$

### **Unequal Variance (Welch’s t-Test)**
$$
t = \frac{\bar{X}_1 - \bar{X}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}
$$

---

### **✅ How to Use This Cheat Sheet**
- This page is powered by **GitHub Pages** and **MathJax** for LaTeX equations.
- Bookmark this page for **quick reference**.

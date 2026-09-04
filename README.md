# A/B Testing & Customer Analytics Framework

## 📌 Problem Statement & Business Context

**The Operational Challenge:**
Modern digital marketplaces and e-commerce platforms frequently roll out UI updates, feature modifications, and pricing shifts. Relying on intuition or global averages often leads to misinformed product decisions, failing to account for conversion variances across distinct user cohorts or separating random noise from statistically significant behavioral shifts.

**The Solution:**
This project implements an **end-to-end statistical evaluation framework** designed to measure user behavior changes and evaluate marketplace experiments with high mathematical rigor. The system bridges raw data processing with actionable product strategy through three core pillars:
1. **Experimental Design & Setup:** Defining control and treatment cohorts to accurately capture user response variations during platform rollouts.
2. **Rigorous Hypothesis Testing:** Applying statistical tests (such as $t$-tests, $z$-tests, and $p$-value evaluations) to determine the statistical significance of metric changes.
3. **Cohort & Conversion Variance Analysis:** Isolating performance differences across specific user segments to translate abstract statistics into concrete product recommendations.

---

## 🏗️ Project Architecture & Structure

```text
ab-testing-project/
│
├── data/                  # Raw and processed user interaction datasets
├── notebooks/             # Exploratory data analysis and hypothesis testing notebooks
├── src/                   # Statistical calculation and data processing scripts
├── README.md              # Project documentation
└── requirements.txt       # Project dependencies

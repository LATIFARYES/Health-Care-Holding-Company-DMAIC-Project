03 — Hypothesis Testing
Health Holding Company | Analyze Phase

Hypothesis testing is used to statistically confirm whether suspected causes are truly contributing to Emergency Department delays, overcrowding, and long patient waiting times.

The goal is to move from assumptions → to data-driven evidence.

Hypothesis Testing Framework 📊


| Step | Action | Emergency Department Example |
|------|---------|------------------------------|
| 1. State H0 | Null hypothesis — no effect | H0: Waiting time is the same across all shifts |
| 2. State Ha | Alternative hypothesis — there is an effect | Ha: At least one shift has significantly longer waiting times |
| 3. Choose alpha | Significance level | α = 0.05 |
| 4. Select test | Based on data type | One-Way ANOVA |
| 5. Run test | Calculate p-value | p = 0.003 |
| 6. Interpret | p ≤ α → Reject H0 | Shift timing significantly affects waiting time |


Test Selection Guide 🧪

| Question Type | Data Type | Recommended Test |
|----------------|-----------|------------------|
| Does staffing affect waiting time? (2 groups) | Continuous Y, Categorical X | Independent Samples T-Test |
| Does shift affect waiting time? (3+ groups) | Continuous Y, Categorical X | One-Way ANOVA |
| Does patient volume affect LOS? | Both Continuous | Correlation + Regression |
| Is triage category related to delays? | Both Categorical | Chi-Square Test |
| Does current performance meet target? | Continuous | One-Sample T-Test |


Hypothesis Test Results — This Project 🚨

| Hypothesis | Test Used | p-value | Decision | Conclusion |
|-------------|------------|----------|-----------|------------|
| Shift affects waiting time | One-Way ANOVA | 0.003 | Reject H0 | Evening shift has significantly higher delays |
| Patient acuity affects LOS | One-Way ANOVA | 0.001 | Reject H0 | Critical patients experience longer LOS |
| Staffing level affects Door-to-Doctor Time | Regression | 0.012 | Reject H0 | Lower staffing increases waiting time |
| Minor cases contribute to overcrowding | Chi-Square | 0.005 | Reject H0 | Low-acuity cases significantly affect congestion |
| Bed availability affects LOS | Pearson Correlation | 0.018 | Reject H0 | Admission delays increase LOS |
| Seasonal variation affects waiting time | Regression | 0.089 | Fail to Reject H0 | Seasonal variation is NOT a significant factor |


Interpreting p-values 📈

| p-value | Interpretation | Action |
|----------|----------------|--------|
| p ≤ 0.01 | Very strong evidence against H0 | Confirm as root cause |
| 0.01 < p ≤ 0.05 | Strong evidence against H0 | Confirm as root cause |
| 0.05 < p ≤ 0.10 | Weak evidence | Investigate further |
| p > 0.10 | No evidence against H0 | Eliminate as root cause |

Lean Connection: Hypothesis Testing + Patient Flow 🔄

Hypothesis testing validates which operational problems truly affect Emergency Department performance.

| Operational Issue | Statistical Finding | Lean Impact |
|-------------------|--------------------|-------------|
| Evening shift congestion | Significant (p=0.003) | Staffing imbalance confirmed |
| Minor-case overload | Significant (p=0.005) | Fast Track needed |
| Bed delays affecting LOS | Significant (p=0.018) | Admission bottleneck confirmed |
| Staffing shortages | Significant (p=0.012) | Capacity mismatch identified |
| Seasonal demand variation | Not significant (p=0.089) | Not a root cause |

Key Findings 🔍
Evening shifts are the highest-risk operational period
Minor cases significantly contribute to congestion
Staffing levels do not match patient arrival patterns
Admission delays strongly affect Length of Stay
Fast Track implementation is statistically justified
Seasonal variation is NOT a primary root cause
Best Practices ✅
Practice 1: Use Real Operational Data

Always use:

Historical KPI data
Shift-level data
Patient-flow records
Staffing and admission data
Practice 2: Let Statistics Confirm the Cause

Operational opinions are hypotheses only.

Statistical validation is required before moving to Improve phase.

Practice 3: Eliminate Weak Causes

If:

p > 0.10
then the suspected factor should not drive improvement actions.
Practice 4: Combine Lean + Statistics

Lean identifies waste.
Statistics confirms whether the waste significantly impacts performance.




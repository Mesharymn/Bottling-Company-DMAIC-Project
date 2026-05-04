# 03 — Hypothesis Testing
## Water Bottling Company | Analyze Phase

> Hypothesis testing is the **statistical engine** of the Analyze phase. It transforms suspected root causes into statistically confirmed (or rejected) facts.

---

## Hypothesis Testing Framework

| Step | Action | This Project Example |
|------|--------|---------------------|
| **1. State H0** | Null hypothesis — no effect | H0: Defect rate is the same across all shifts |
| **2. State Ha** | Alternative hypothesis — there is an effect | Ha: At least one shift has a significantly different defect rate |
| **3. Choose alpha** | Significance level | alpha = 0.05 |
| **4. Select test** | Based on data type and question | One-Way ANOVA |
| **5. Run test** | Calculate test statistic and p-value | p = 0.003 |
| **6. Interpret** | p <= alpha -> Reject H0 | Shift IS a significant factor |

---

## Test Selection Guide

| Question Type | Data Type | Recommended Test |
|---------------|-----------|-----------------|
| Does X affect Y? (2 groups) | Continuous Y, Categorical X | Independent Samples T-test |
| Does X affect Y? (3+ groups) | Continuous Y, Categorical X | One-Way ANOVA |
| Is X related to Y? | Both Continuous | Pearson Correlation + Regression |
| Is X independent of Y? | Both Categorical | Chi-Square Test of Independence |
| Does the process follow a target? | Continuous | One-Sample T-test |

---

## Hypothesis Test Results — This Project

| Hypothesis | Test Used | p-value | Decision | Conclusion |
|------------|-----------|---------|----------|------------|
| Shift affects defect rate | One-Way ANOVA | **0.003** | Reject H0 | Night shift has significantly higher defect rate |
| Machine type affects defect type | Chi-Square | **0.001** | Reject H0 | Capping machine is the primary defect source |
| Changeover time correlates with defects | Pearson Correlation | **0.041** | Reject H0 | Longer changeover -> more defects (r = 0.67) |
| SKU type affects downtime | One-Way ANOVA | **0.008** | Reject H0 | 1.5L SKU changeover causes most downtime |
| Temperature affects fill volume | Regression | **0.089** | Fail to Reject H0 | Temperature is NOT a significant factor |

---

## Interpreting p-values

| p-value | Interpretation | Action |
|---------|---------------|--------|
| p <= 0.01 | Very strong evidence against H0 | Confirm as root cause |
| 0.01 < p <= 0.05 | Strong evidence against H0 | Confirm as root cause |
| 0.05 < p <= 0.10 | Weak evidence | Investigate further |
| p > 0.10 | No evidence against H0 | Eliminate as root cause |

---

## Lean Connection: Hypothesis Testing + OEE

**OEE (Overall Equipment Effectiveness)** provides the data for machine-related hypothesis tests:

```
OEE = Availability x Performance x Quality
    = 0.82 x 0.818 x 0.955
    = 64.0%

World Class OEE = 85%   |   Gap = 21 percentage points
```

OEE decomposition tells you which component to focus on:
- **Low Availability** -> Test: Does PM frequency affect availability?
- **Low Performance** -> Test: Does SKU type affect run rate?
- **Low Quality** -> Test: Does shift/machine affect defect rate?

---

## Best Practices

### Practice 1: State Hypotheses Before Looking at Data
- Write H0 and Ha before running any analysis
- This prevents p-hacking (running tests until you find a significant result)

### Practice 2: Check Assumptions Before Running Tests

| Test | Key Assumptions | How to Check |
|------|----------------|--------------|
| T-test | Normality, equal variance | Shapiro-Wilk test, Levene's test |
| ANOVA | Normality, equal variance, independence | Shapiro-Wilk, Levene's, randomization |
| Chi-Square | Expected frequency >= 5 in each cell | Check contingency table |
| Correlation | Linear relationship, no outliers | Scatter plot |

### Practice 3: Report Effect Size, Not Just p-value
- p-value tells you IF an effect exists
- Effect size tells you HOW BIG the effect is

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Testing too many hypotheses without correction | False positives (Type I error) | Apply Bonferroni correction for multiple tests |
| Ignoring test assumptions | Invalid results | Always check normality and variance first |
| Confusing statistical with practical significance | Implementing trivial improvements | Always report effect size alongside p-value |
| Treating p > 0.05 as "proven no effect" | Missing real causes | p > 0.05 means insufficient evidence, not proof of no effect |

---

## How to Run Hypothesis Tests in Excel

### One-Way ANOVA:
1. Arrange data: each group in a separate column
2. **Data -> Data Analysis -> ANOVA: Single Factor**
3. Select input range, set alpha = 0.05
4. Read the p-value from the output table

### T-test:
1. Arrange two groups in two columns
2. **Data -> Data Analysis -> t-Test: Two-Sample Assuming Unequal Variances**
3. Read "P(T<=t) two-tail" — this is your p-value

### Pearson Correlation:
1. =CORREL(array1, array2) — correlation coefficient r
2. **Data -> Data Analysis -> Correlation**

---

---

# 03 — اختبار الفرضيات
## شركة تعبئة المياه | مرحلة التحليل

---

## إطار اختبار الفرضيات

| الخطوة | الإجراء | مثال هذا المشروع |
|--------|--------|----------------|
| **1. صياغة H0** | الفرضية الصفرية — لا تأثير | H0: معدل العيوب متساوٍ عبر جميع الورديات |
| **2. صياغة Ha** | الفرضية البديلة — يوجد تأثير | Ha: وردية واحدة على الأقل لها معدل عيوب مختلف |
| **3. اختيار alpha** | مستوى الدلالة | alpha = 0.05 |
| **4. اختيار الاختبار** | بناءً على نوع البيانات | One-Way ANOVA |
| **5. تشغيل الاختبار** | حساب إحصاء الاختبار وقيمة p | p = 0.003 |
| **6. التفسير** | p <= alpha -> رفض H0 | الوردية عامل مهم |

---

## نتائج اختبار الفرضيات — هذا المشروع

| الفرضية | الاختبار | قيمة p | القرار | الاستنتاج |
|---------|---------|--------|--------|----------|
| الوردية تؤثر على معدل العيوب | One-Way ANOVA | **0.003** | رفض H0 | الوردية الليلية لها معدل عيوب أعلى |
| نوع الآلة يؤثر على نوع العيب | Chi-Square | **0.001** | رفض H0 | آلة التغطية هي المصدر الرئيسي |
| وقت التحويل يرتبط بالعيوب | Pearson Correlation | **0.041** | رفض H0 | تحويل أطول -> عيوب أكثر (r = 0.67) |
| نوع SKU يؤثر على التوقف | One-Way ANOVA | **0.008** | رفض H0 | تحويل 1.5 لتر يسبب معظم التوقف |
| درجة الحرارة تؤثر على حجم التعبئة | Regression | **0.089** | عدم رفض H0 | درجة الحرارة ليست عاملاً مهماً |

---

## تفسير قيم p

| قيمة p | التفسير | الإجراء |
|--------|---------|---------|
| p <= 0.01 | دليل قوي جداً ضد H0 | تأكيد كسبب جذري |
| 0.01 < p <= 0.05 | دليل قوي ضد H0 | تأكيد كسبب جذري |
| 0.05 < p <= 0.10 | دليل ضعيف | مزيد من التحقيق |
| p > 0.10 | لا دليل ضد H0 | استبعاد كسبب جذري |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

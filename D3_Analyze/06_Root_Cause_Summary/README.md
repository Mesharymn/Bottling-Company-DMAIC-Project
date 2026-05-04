# 06 — Root Cause Summary
## Water Bottling Company | Analyze Phase

> This document consolidates all **confirmed root causes** from the Analyze phase — combining statistical evidence from hypothesis testing with Lean waste analysis.

---

## Confirmed Root Causes

| # | Root Cause | Evidence | p-value | Lean Waste | Priority |
|---|-----------|----------|---------|-----------|----------|
| **RC-01** | Maintenance plan not updated after capping machine upgrade | ANOVA | 0.003 | Defects, Waiting | Critical |
| **RC-02** | No formal preventive maintenance (PM) program | ANOVA | 0.008 | Waiting, Defects | Critical |
| **RC-03** | No SMED procedure for SKU changeover | Correlation | 0.041 | Waiting, Motion | Critical |
| **RC-04** | Capping machine torque sensor worn and uncalibrated | Chi-Square | 0.001 | Defects | Critical |
| **RC-05** | No continuous improvement culture or CI team | Lean Analysis | — | Skills | High |
| **RC-06** | Production planning not linked to actual demand | Lean Analysis | — | Inventory, Overproduction | High |

---

## Root Cause to Defect Mapping

| Root Cause | Defect Type Affected | Estimated Contribution |
|-----------|---------------------|----------------------|
| RC-01: Maintenance plan outdated | Leakage (1.52%), Cap deformation (0.89%) | ~54% of total defects |
| RC-02: No PM program | All defect types (machine failures) | ~25% of total defects |
| RC-03: No SMED procedure | All defect types (post-changeover defects) | ~12% of total defects |
| RC-04: Worn torque sensor | Leakage, Cap deformation | ~9% of total defects |

---

## Monthly Cost Impact

| Root Cause | Primary Lean Waste | Monthly Cost Impact |
|-----------|-------------------|---------------------|
| RC-01: Maintenance plan outdated | Defects | SAR 67,500/month |
| RC-02: No PM program | Waiting (downtime) | SAR 89,000/month |
| RC-03: No SMED procedure | Waiting (changeover) | SAR 34,000/month |
| RC-04: Worn torque sensor | Defects | SAR 22,500/month |
| RC-05: No CI culture | Skills | SAR 45,000/month (opportunity cost) |
| RC-06: Push production | Inventory | SAR 45,000/month (tied-up capital) |
| **Total** | | **SAR 303,000/month** |

---

## Sigma Gap Analysis

| Metric | Current | Target | Gap |
|--------|---------|--------|-----|
| Defect Rate | 4.50% | <= 1.00% | 3.50 pp |
| DPMO | 44,896 | <= 10,000 | 34,896 |
| Sigma Level | 3.2 | >= 4.0 | 0.8 sigma |
| OEE | 64.0% | >= 85% | 21 pp |
| Changeover Time | 44.8 min | <= 20 min | 24.8 min |
| On-Time Fulfillment | 79.9% | >= 95% | 15.1 pp |

---

## Transition to Improve Phase

| Root Cause | Proposed Solution | Expected Impact |
|-----------|------------------|----------------|
| RC-01: Maintenance plan outdated | Update PM plan + implement TPM | Reduce leakage by 60% |
| RC-02: No PM program | Implement formal PM program | Reduce downtime by 40% |
| RC-03: No SMED procedure | Implement SMED for all SKU changeovers | Reduce changeover to <= 20 min |
| RC-04: Worn torque sensor | Replace + calibrate torque sensor | Eliminate cap deformation defects |
| RC-05: No CI culture | Launch Kaizen program + suggestion system | Sustain improvements |
| RC-06: Push production | Implement Kanban pull system | Eliminate overproduction waste |

---

## Best Practices

### Practice 1: Only Include Confirmed Root Causes
- A root cause is confirmed only if it has statistical evidence (p <= 0.05) OR clear Lean waste evidence with quantified impact

### Practice 2: Map Every Root Cause to a Defect
- Each root cause should explain a specific portion of the defect rate

### Practice 3: Prioritize by Impact
Use a 2x2 matrix (Impact vs. Ease of Implementation):
- High Impact + Easy -> Quick Win (do first)
- High Impact + Hard -> Major Project (plan carefully)
- Low Impact + Easy -> Fill-In (do when time permits)
- Low Impact + Hard -> Deprioritize

### Practice 4: Get Stakeholder Sign-Off
- Present the root cause summary to the project sponsor
- Get formal sign-off before moving to the Improve phase

### Practice 5: Document the Evidence Trail
For each root cause, document:
1. Which tool identified it (Fishbone, 5-Why, Hypothesis Test, Lean Analysis)
2. The specific evidence (p-value, waste quantity, OEE component)
3. Who validated it (operator, supervisor, quality manager)

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Including unconfirmed causes | Implementing solutions for wrong causes | Only include causes with statistical or Lean evidence |
| Too many root causes (10+) | Team cannot focus | Prioritize to top 5-6 using impact/effort matrix |
| Root causes stated as symptoms | Solutions address symptoms, not causes | Verify each cause passes the "5-Why test" |
| No cost impact quantification | Cannot justify Improve phase investment | Always calculate monthly cost of each root cause |
| Moving to Improve without sign-off | Scope changes during implementation | Get formal approval at the Analyze tollgate |

---

---

# 06 — ملخص الأسباب الجذرية
## شركة تعبئة المياه | مرحلة التحليل

---

## الأسباب الجذرية المؤكدة

| # | السبب الجذري | الدليل | قيمة p | هدر Lean | الأولوية |
|---|-------------|-------|--------|---------|---------|
| **RC-01** | خطة الصيانة لم تحدث بعد ترقية آلة التغطية | ANOVA | 0.003 | العيوب، الانتظار | حرج |
| **RC-02** | لا يوجد برنامج صيانة وقائية رسمي | ANOVA | 0.008 | الانتظار، العيوب | حرج |
| **RC-03** | لا يوجد إجراء SMED لتحويل SKU | Correlation | 0.041 | الانتظار، الحركة | حرج |
| **RC-04** | مستشعر عزم آلة التغطية متآكل وغير معاير | Chi-Square | 0.001 | العيوب | حرج |
| **RC-05** | لا توجد ثقافة تحسين مستمر | تحليل Lean | — | المهارات | عالي |
| **RC-06** | تخطيط الإنتاج غير مرتبط بالطلب الفعلي | تحليل Lean | — | المخزون، الإنتاج الزائد | عالي |

---

## التأثير الشهري للتكلفة

| السبب الجذري | هدر Lean الرئيسي | التأثير الشهري |
|-------------|----------------|--------------|
| RC-01: خطة الصيانة قديمة | العيوب | 67,500 ريال/شهر |
| RC-02: لا يوجد برنامج PM | الانتظار (التوقف) | 89,000 ريال/شهر |
| RC-03: لا يوجد إجراء SMED | الانتظار (التحويل) | 34,000 ريال/شهر |
| RC-04: مستشعر عزم متآكل | العيوب | 22,500 ريال/شهر |
| RC-05: لا توجد ثقافة CI | المهارات | 45,000 ريال/شهر |
| RC-06: إنتاج بالدفع | المخزون | 45,000 ريال/شهر |
| **الإجمالي** | | **303,000 ريال/شهر** |

---

## التحول إلى مرحلة التحسين

| السبب الجذري | الحل المقترح | التأثير المتوقع |
|-------------|------------|----------------|
| RC-01: خطة الصيانة قديمة | تحديث خطة PM + تنفيذ TPM | تخفيض التسرب 60% |
| RC-02: لا يوجد برنامج PM | تنفيذ برنامج PM رسمي | تخفيض التوقف 40% |
| RC-03: لا يوجد إجراء SMED | تنفيذ SMED لجميع تحويلات SKU | تخفيض التحويل الى <= 20 دقيقة |
| RC-04: مستشعر عزم متآكل | استبدال + معايرة مستشعر العزم | القضاء على عيوب تشوه الغطاء |
| RC-05: لا توجد ثقافة CI | اطلاق برنامج Kaizen + نظام اقتراحات | الحفاظ على التحسينات |
| RC-06: إنتاج بالدفع | تنفيذ نظام سحب Kanban | القضاء على هدر الإنتاج الزائد |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

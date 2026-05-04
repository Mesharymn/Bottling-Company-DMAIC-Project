# 02 — 5-Why Analysis
## Water Bottling Company | Analyze Phase

> The 5-Why technique drills down from a **symptom** to its **root cause** by asking "Why?" five times.

---

## 5-Why Results — This Project

### Chain 1: Leakage Defects (34% of all defects)

| Why # | Question | Answer |
|-------|----------|--------|
| **Why 1** | Why are bottles leaking? | Cap seal is not forming properly |
| **Why 2** | Why is the cap seal not forming? | Capping machine torque is inconsistent |
| **Why 3** | Why is the torque inconsistent? | Torque sensor is worn and out of calibration |
| **Why 4** | Why is the sensor out of calibration? | No preventive maintenance schedule for torque sensor |
| **Why 5** | Why is there no PM schedule? | Maintenance plan not updated after machine upgrade 2 years ago |
| **Root Cause** | | **Maintenance plan not updated after equipment upgrade** |

### Chain 2: Unplanned Downtime (55.3% of all downtime)

| Why # | Question | Answer |
|-------|----------|--------|
| **Why 1** | Why is there unplanned downtime? | Machines fail unexpectedly during production |
| **Why 2** | Why do machines fail unexpectedly? | Failures are not detected before they occur |
| **Why 3** | Why are failures not detected early? | No condition monitoring or predictive maintenance |
| **Why 4** | Why is there no condition monitoring? | Budget was not allocated for monitoring equipment |
| **Why 5** | Why was budget not allocated? | Maintenance is reactive — no formal PM program exists |
| **Root Cause** | | **No formal preventive maintenance program** |

### Chain 3: Long Changeover Time (44.8 min vs. 20 min target)

| Why # | Question | Answer |
|-------|----------|--------|
| **Why 1** | Why does changeover take 44.8 minutes? | Operators search for tools and parts during changeover |
| **Why 2** | Why do operators search during changeover? | Tools and parts are not staged before changeover begins |
| **Why 3** | Why are they not pre-staged? | No standardized changeover procedure (SMED) |
| **Why 4** | Why is there no SMED procedure? | Changeover was never formally analyzed or optimized |
| **Why 5** | Why was it never optimized? | No continuous improvement culture or dedicated CI team |
| **Root Cause** | | **No SMED procedure and no continuous improvement culture** |

---

## Lean Connection: 5-Why + SMED

**SMED (Single-Minute Exchange of Die)** directly addresses the changeover root cause:

| SMED Step | Action | Expected Reduction |
|-----------|--------|-------------------|
| 1. Separate internal vs. external activities | Identify what can be done while machine is running | 20-30% |
| 2. Convert internal to external | Pre-stage tools, parts, and materials | 15-25% |
| 3. Streamline remaining internal activities | Standardize, use quick-release fasteners | 10-15% |
| **Total SMED Impact** | | **45-70% changeover time reduction** |

For this project: 44.8 min -> target 20 min = **55% reduction needed** — achievable with SMED.

---

## Best Practices

### Practice 1: Use Data at Each Step
- Each "Why" answer should be supported by data, not opinion
- Data-driven 5-Why prevents stopping at convenient answers

### Practice 2: Stop at the Actionable Root Cause
- You do not always need exactly 5 "Whys"
- Stop when you reach a cause you can act on

### Practice 3: Run Multiple Chains
- Complex problems often have multiple root causes
- Run a separate 5-Why chain for each major defect type

### Practice 4: Involve the Right People
- The operator or maintenance technician closest to the process often knows the answer
- Do not run 5-Why only with managers

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Stopping too early (at Why 2 or 3) | Addressing symptoms, not root causes | Keep asking until you reach a systemic cause |
| Jumping to solutions mid-chain | Skipping root cause confirmation | Finish the chain before proposing solutions |
| One person answers all "Whys" | Single perspective, misses causes | Use team discussion for each step |
| Not verifying answers with data | Chain based on assumptions | Require data evidence for each step |

---

## How to Create a 5-Why Table in Excel

1. Create a table with columns: **Why # | Question | Answer | Data Evidence | Verified?**
2. Row 0: Problem statement (highlighted in red)
3. Rows 1-5: Each "Why" with question, answer, and data source
4. Final row: Root Cause (highlighted in green)
5. Add a "Countermeasure" column for the Improve phase

---

---

# 02 — تحليل لماذا الخمسة (5-Why)
## شركة تعبئة المياه | مرحلة التحليل

---

## نتائج 5-Why — هذا المشروع

### السلسلة 1: عيوب التسرب (34% من جميع العيوب)

| لماذا # | السؤال | الإجابة |
|---------|--------|---------|
| **لماذا 1** | لماذا تتسرب الزجاجات؟ | إغلاق الغطاء لا يتشكل بشكل صحيح |
| **لماذا 2** | لماذا لا يتشكل الإغلاق؟ | عزم آلة التغطية غير منتظم |
| **لماذا 3** | لماذا العزم غير منتظم؟ | مستشعر العزم متآكل وغير معاير |
| **لماذا 4** | لماذا المستشعر غير معاير؟ | لا يوجد جدول صيانة وقائية للمستشعر |
| **لماذا 5** | لماذا لا يوجد جدول صيانة؟ | خطة الصيانة لم تحدث بعد ترقية الآلة قبل عامين |
| **السبب الجذري** | | **خطة الصيانة لم تحدث بعد ترقية المعدات** |

### السلسلة 2: التوقف غير المخطط (55.3% من إجمالي التوقف)

| لماذا # | السؤال | الإجابة |
|---------|--------|---------|
| **لماذا 1** | لماذا يوجد توقف غير مخطط؟ | الآلات تتعطل بشكل غير متوقع أثناء الإنتاج |
| **لماذا 2** | لماذا تتعطل الآلات بشكل غير متوقع؟ | الأعطال لا تكتشف قبل حدوثها |
| **لماذا 3** | لماذا لا تكتشف الأعطال مبكراً؟ | لا يوجد مراقبة للحالة أو صيانة تنبؤية |
| **لماذا 4** | لماذا لا توجد مراقبة للحالة؟ | لم يخصص ميزانية لمعدات المراقبة |
| **لماذا 5** | لماذا لم تخصص ميزانية؟ | الصيانة تفاعلية — لا يوجد برنامج PM رسمي |
| **السبب الجذري** | | **لا يوجد برنامج صيانة وقائية رسمي** |

### السلسلة 3: وقت التحويل الطويل (44.8 دق مقابل هدف 20 دق)

| لماذا # | السؤال | الإجابة |
|---------|--------|---------|
| **لماذا 1** | لماذا يستغرق التحويل 44.8 دقيقة؟ | المشغلون يبحثون عن الأدوات والأجزاء أثناء التحويل |
| **لماذا 2** | لماذا يبحثون أثناء التحويل؟ | الأدوات والأجزاء لا تجهز قبل بدء التحويل |
| **لماذا 3** | لماذا لا تجهز مسبقاً؟ | لا يوجد إجراء موحد للتحويل (SMED) |
| **لماذا 4** | لماذا لا يوجد إجراء SMED؟ | التحويل لم يحلل أو يحسن رسمياً قط |
| **لماذا 5** | لماذا لم يحسن قط؟ | لا توجد ثقافة تحسين مستمر أو فريق CI مخصص |
| **السبب الجذري** | | **لا يوجد إجراء SMED ولا ثقافة تحسين مستمر** |

---

## ارتباط Lean: 5-Why + SMED

| خطوة SMED | الإجراء | التخفيض المتوقع |
|-----------|--------|----------------|
| 1. فصل الأنشطة الداخلية عن الخارجية | تحديد ما يمكن فعله أثناء تشغيل الآلة | 20-30% |
| 2. تحويل الداخلية إلى خارجية | تجهيز الأدوات والأجزاء مسبقاً | 15-25% |
| 3. تبسيط الأنشطة الداخلية المتبقية | توحيد، استخدام مثبتات سريعة الفك | 10-15% |
| **إجمالي تأثير SMED** | | **تخفيض 45-70%** |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

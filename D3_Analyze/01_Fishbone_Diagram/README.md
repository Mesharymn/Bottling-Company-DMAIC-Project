# 01 — Fishbone Diagram (Ishikawa)
## Water Bottling Company | Analyze Phase

> The Fishbone Diagram is a **structured brainstorming tool** that maps all potential causes of a problem across six categories (6M). It generates hypotheses — not conclusions.

---

## The 6M Framework

| Category | Covers | Bottling Example |
|----------|--------|-----------------|
| **Man** | People, skills, training, behavior | Operator training gaps, shift handover issues |
| **Machine** | Equipment, tools, maintenance | Worn capping seals, filling nozzle wear |
| **Method** | Procedures, processes, standards | No standardized changeover procedure |
| **Material** | Raw materials, components, suppliers | Inconsistent cap dimensions from supplier |
| **Measurement** | Gauges, inspection, data collection | Inaccurate fill volume sensors |
| **Mother Nature** | Environment, temperature, humidity | Temperature variation affecting bottle integrity |

---

## Fishbone Results — Defect Rate 4.5%

### Man (People)
- Operator training gaps — no standardized training program
- Night shift has 2.1x higher defect rate than day shift (confirmed ANOVA p=0.003)
- Shift handover process is informal — no written checklist
- Operators not trained on machine calibration procedures

### Machine
- Capping machine torque sensor worn and uncalibrated (confirmed Chi-Square p=0.001)
- Filling nozzle wear causes inconsistent fill volumes
- No condition monitoring on any production machine
- Capping machine OEE = 56.7% (world class = 85%)

### Method
- No standardized changeover procedure (SMED not implemented)
- Maintenance plan not updated after capping machine upgrade 2 years ago
- No formal PM program — all maintenance is reactive
- No shift handover inspection protocol

### Material
- Cap dimensions inconsistent across supplier batches
- PET preform quality variation affects bottle integrity
- No incoming quality inspection for caps and preforms

### Measurement
- Fill volume sensors not calibrated on schedule
- No real-time defect tracking on production line
- Manual data entry causes recording errors

### Mother Nature
- Temperature variation in plant (NOT confirmed as significant — p=0.089)
- Humidity affects label adhesion in some seasons

---

## Lean Connection: Fishbone + VSM

| Fishbone Category | Lean Waste Type | VSM Indicator |
|-------------------|-----------------|---------------|
| Machine (worn torque sensor) | Defects | High defect rate at capping station |
| Method (no changeover procedure) | Waiting | 44.8 min changeover on VSM |
| Man (training gaps) | Defects, Skills | Rework loops on VSM |
| Material (inconsistent caps) | Defects | Incoming inspection failures |
| Measurement (inaccurate sensors) | Defects | Escaped defects to downstream |

---

## Best Practices

### Practice 1: Use a Cross-Functional Team
- Include operators, supervisors, maintenance, quality, and engineering
- Aim for 6-10 participants in the brainstorming session
- Use sticky notes so everyone can contribute simultaneously

### Practice 2: Populate All 6M Categories
- Do not skip categories — even if you think they are not relevant
- For this project: Machine and Method were the most productive categories

### Practice 3: Generate Causes, Not Solutions
- Wrong: "Install new capping machine" — this is a solution
- Correct: "Capping machine pressure is inconsistent" — this is a cause

### Practice 4: Prioritize After Brainstorming
1. Vote on the top 3-5 most likely causes (multi-voting technique)
2. These become the hypotheses for hypothesis testing
3. Do not test all causes — focus on the highest-probability ones

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Only one person fills in the fishbone | Misses important causes | Use cross-functional team brainstorming |
| Mixing causes and solutions | Confuses the analysis | Strictly separate cause identification from solution generation |
| Skipping categories | Misses root causes | Always populate all 6M categories |
| Not prioritizing after brainstorming | Too many hypotheses to test | Use multi-voting to select top 3-5 causes |
| Treating the fishbone as the final answer | Skips statistical confirmation | Always follow with hypothesis testing |

---

## How to Create a Fishbone Diagram in Excel

1. Open Excel > Insert > SmartArt > Hierarchy > Horizontal Hierarchy
2. Or draw manually: Insert a horizontal arrow pointing right (the "spine")
3. Add 6 diagonal arrows pointing to the spine — label each with a 6M category
4. Add text boxes at the end of each bone for the causes
5. Color-code by category (blue=Man, green=Machine, orange=Method, etc.)
6. Add the problem statement in a red box at the head (right end) of the spine
7. Save as PNG for inclusion in reports

**Alternative:** Use free tools like Lucidchart, Miro, or Canva for better visual quality.

---

---

# 01 — مخطط إيشيكاوا (Fishbone)
## شركة تعبئة المياه | مرحلة التحليل

---

## إطار 6M

| الفئة | تغطي | مثال من التعبئة |
|-------|-----|----------------|
| **Man** — الأفراد | الأشخاص، المهارات، التدريب | فجوات تدريب المشغلين |
| **Machine** — الآلات | المعدات، الأدوات، الصيانة | تآكل حشيات آلة التغطية |
| **Method** — الأساليب | الإجراءات، العمليات، المعايير | لا يوجد إجراء موحد للتحويل |
| **Material** — المواد | المواد الخام، المكونات، الموردون | أبعاد أغطية غير متسقة من المورد |
| **Measurement** — القياس | المقاييس، الفحص، جمع البيانات | أجهزة استشعار حجم التعبئة غير دقيقة |
| **Mother Nature** — البيئة | البيئة، درجة الحرارة، الرطوبة | تغيرات درجة الحرارة |

---

## نتائج Fishbone — معدل العيوب 4.5%

### الأفراد (Man)
- فجوات تدريب المشغلين — لا يوجد برنامج تدريب موحد
- الوردية الليلية لها معدل عيوب أعلى بـ 2.1x من الوردية النهارية (مؤكد ANOVA p=0.003)
- عملية تسليم الوردية غير رسمية — لا توجد قائمة تحقق مكتوبة

### الآلات (Machine)
- مستشعر عزم آلة التغطية متآكل وغير معاير (مؤكد Chi-Square p=0.001)
- تآكل فوهات التعبئة يسبب أحجام تعبئة غير متسقة
- OEE آلة التغطية = 56.7% (المستوى العالمي = 85%)

### الأساليب (Method)
- لا يوجد إجراء موحد للتحويل (SMED غير مطبق)
- خطة الصيانة لم تحدث بعد ترقية آلة التغطية قبل عامين
- لا يوجد برنامج صيانة وقائية رسمي — جميع الصيانة تفاعلية

---

## أفضل الممارسات

### الممارسة 1: استخدم فريقاً متعدد الوظائف
- أشرك المشغلين والمشرفين والصيانة والجودة والهندسة
- استهدف 6-10 مشاركين في جلسة العصف الذهني

### الممارسة 2: ولّد الأسباب وليس الحلول
- خطأ: "تركيب آلة تغطية جديدة" — هذا حل
- صحيح: "ضغط آلة التغطية غير منتظم" — هذا سبب

### الممارسة 3: حدد الأولويات بعد العصف الذهني
1. صوّت على أعلى 3-5 أسباب محتملة
2. تصبح هذه الفرضيات لاختبار الفرضيات

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

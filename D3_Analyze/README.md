# D3 — Analyze Phase
## Water Bottling Company | DMAIC Project

> The Analyze phase answers one question: **"What is causing the defects?"**

---

## Folder Structure

| Subfolder | Tool | Purpose |
|-----------|------|---------|
| `01_Fishbone_Diagram/` | Ishikawa / Fishbone | Brainstorm all potential causes across 6M categories |
| `02_5_Why_Analysis/` | 5-Why | Drill down from symptom to root cause |
| `03_Hypothesis_Testing/` | T-test, ANOVA, Chi-Square | Statistically confirm which causes are significant |
| `04_Lean_Waste_Analysis/` | 8 Wastes (TIMWOODS) | Identify non-value-adding activities |
| `06_Root_Cause_Summary/` | Summary report | Consolidate all confirmed root causes |

---

## The Analyze Phase Roadmap

```
Measure Phase Output
        ↓
Step 1: Fishbone Diagram  →  Generate all POSSIBLE causes (6M framework)
        ↓
Step 2: 5-Why Analysis    →  Drill into the most likely causes
        ↓
Step 3: Hypothesis Testing →  STATISTICALLY CONFIRM which causes are real
        ↓
Step 4: Lean Waste Analysis → Identify WASTE in the process flow
        ↓
Step 5: Root Cause Summary  → Document CONFIRMED causes with evidence
        ↓
Improve Phase Input
```

---

## Lean Thinking in the Analyze Phase

Lean and 6S are complementary. While 6S uses statistics to confirm root causes, **Lean identifies the waste** creating those causes.

### The 8 Wastes (TIMWOODS)

| Waste | Description | Bottling Company Example |
|-------|-------------|--------------------------|
| **T** — Transport | Unnecessary movement of materials | Moving bottles between stations unnecessarily |
| **I** — Inventory | Excess stock or WIP | Overproduction of 330ml while 1.5L orders are pending |
| **M** — Motion | Unnecessary movement of people | Operators walking 45m to retrieve caps |
| **W** — Waiting | Idle time | Line stopped waiting for maintenance during changeover |
| **O** — Overproduction | Producing more than needed | Running 330ml when 1.5L demand is higher |
| **O** — Over-processing | More work than required | Double-inspection at low-defect stations |
| **D** — Defects | Rework, scrap, returns | 4.5% defect rate — leakage, underfill, label misalignment |
| **S** — Skills | Underutilizing people's knowledge | Operators not involved in root cause analysis |

### Lean Tools Used in This Phase

| Tool | Purpose | When to Use |
|------|---------|-------------|
| **Value Stream Map (VSM)** | Visualize entire flow and identify waste | Early in Analyze — shows the big picture |
| **Spaghetti Diagram** | Map physical movement of people/materials | When motion or transport waste is suspected |
| **OEE Analysis** | Availability x Performance x Quality | When machine downtime is a root cause |
| **5S Audit** | Sort, Set, Shine, Standardize, Sustain | When workplace organization contributes to defects |
| **SMED** | Single-Minute Exchange of Die | When changeover time is a root cause |
| **Kaizen** | Continuous improvement events | When CI culture needs to be built |
| **Kanban** | Pull-based production scheduling | When overproduction waste is confirmed |
| **TPM** | Total Productive Maintenance | When machine reliability is a root cause |

---

## Key Principles

### Principle 1: Separate Symptoms from Causes
- **Symptom:** "Defect rate is 4.5%"
- **Cause:** "Capping machine torque sensor is worn and uncalibrated"
- Never treat a symptom as a root cause

### Principle 2: Let Data Confirm — Not Opinion
- Every suspected root cause must be tested statistically
- p-value <= 0.05 = statistically significant cause
- "We think it's the night shift" is a hypothesis — test it with data

### Principle 3: Integrate Lean and 6S

| 6S Approach | Lean Approach | Combined Power |
|-------------|--------------|----------------|
| Statistical confirmation of causes | Visual identification of waste | Quantified waste with confirmed root causes |
| ANOVA, regression, hypothesis tests | VSM, 5S, OEE, SMED | Data-driven Lean transformation |
| Answers: "Is this cause real?" | Answers: "Where is the waste?" | Answers: "What exactly is broken and why?" |

---

## Analyze Phase Checklist

- [ ] Fishbone diagram completed with all 6M categories populated
- [ ] Top 3-5 suspected root causes identified from Fishbone
- [ ] 5-Why analysis completed for each suspected root cause
- [ ] Hypothesis tests run for each suspected cause (p-value documented)
- [ ] Lean waste analysis completed (8 wastes identified and quantified)
- [ ] OEE calculated for key machines
- [ ] VSM current state completed
- [ ] Root causes confirmed with statistical evidence (p <= 0.05)
- [ ] Root cause summary report prepared
- [ ] Findings communicated to management and team
- [ ] Analyze phase tollgate review passed

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Jumping to solutions before confirming root causes | Fixing the wrong problem | Complete all hypothesis tests before moving to Improve |
| Using only one tool | Missing statistically significant causes | Use Fishbone -> 5-Why -> Hypothesis Testing in sequence |
| Ignoring Lean waste | Missing non-value-adding activities | Always run a Lean waste analysis alongside statistical tools |
| Treating correlation as causation | Implementing wrong solutions | Use regression to confirm direction and strength |
| Not involving operators | Missing practical process knowledge | Include operators in Fishbone and 5-Why sessions |

---

---

# D3 — مرحلة التحليل
## شركة تعبئة المياه | مشروع DMAIC

> تجيب مرحلة التحليل على سؤال واحد: **"ما الذي يسبب العيوب؟"**

---

## هيكل المجلد

| المجلد الفرعي | الأداة | الغرض |
|--------------|-------|-------|
| `01_Fishbone_Diagram/` | إيشيكاوا / Fishbone | استعراض جميع الأسباب المحتملة عبر فئات 6M |
| `02_5_Why_Analysis/` | 5-Why | التعمق من الأعراض إلى السبب الجذري |
| `03_Hypothesis_Testing/` | T-test، ANOVA، Chi-Square | التأكيد الإحصائي للأسباب المهمة |
| `04_Lean_Waste_Analysis/` | 8 هدر (TIMWOODS) | تحديد الأنشطة غير المضيفة للقيمة |
| `06_Root_Cause_Summary/` | تقرير ملخص | توحيد جميع الأسباب الجذرية المؤكدة |

---

## الهدر الثمانية (TIMWOODS)

| الهدر | الوصف | مثال من التعبئة |
|-------|-------|----------------|
| **T** — النقل | حركة غير ضرورية للمواد | نقل الزجاجات بين المحطات بشكل غير ضروري |
| **I** — المخزون | مخزون زائد أو WIP | إنتاج زائد من 330مل بينما 1.5 لتر شحيح |
| **M** — الحركة | حركة غير ضرورية للأشخاص | المشغلون يمشون 45م لاسترداد الأغطية |
| **W** — الانتظار | وقت خمول | توقف الخط انتظاراً للصيانة أثناء التحويل |
| **O** — الإنتاج الزائد | إنتاج أكثر مما هو مطلوب | تشغيل 330مل بينما طلبات 1.5 لتر معلقة |
| **O** — المعالجة الزائدة | عمل أكثر مما هو مطلوب | فحص مزدوج في محطات منخفضة العيوب |
| **D** — العيوب | إعادة عمل، خردة، مرتجعات | معدل عيوب 4.5% |
| **S** — المهارات | عدم استغلال معرفة الناس | المشغلون غير مشاركين في التحسين |

---

## أدوات Lean في هذه المرحلة

| الأداة | الغرض | متى تستخدم |
|-------|-------|------------|
| **VSM** | تصور التدفق الكامل وتحديد الهدر | في بداية التحليل |
| **OEE** | التوافر x الأداء x الجودة | عند الاشتباه في مشاكل الآلات |
| **5S** | تنظيم بيئة العمل | عند الاشتباه في هدر الحركة |
| **SMED** | تقليل وقت التحويل | عند تأكيد هدر الانتظار |
| **Kaizen** | بناء ثقافة التحسين | في جميع مراحل DMAIC |
| **Kanban** | الإنتاج حسب الطلب | عند تأكيد هدر الإنتاج الزائد |
| **TPM** | موثوقية الآلات | عند تأكيد هدر التوقف |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

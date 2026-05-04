# 04 — Lean Waste Analysis (DOWNTIME)
## Water Bottling Company | Analyze Phase

> Lean Waste Analysis identifies and quantifies **non-value-adding activities** in the production process. It connects Lean waste to the confirmed root causes from hypothesis testing.

---

## The 8 Wastes (DOWNTIME) — Detailed Results

### T — Transport
| Observation | Current State | Impact |
|-------------|--------------|--------|
| Bottles moved via manual conveyor | 12 meters extra travel | 8 min/shift delay |
| Finished pallets moved twice before loading | Double handling | 15 min/shift waste |
| Labels stored in separate warehouse | Retrieval time during changeover | 5 min/changeover |

**Lean Solution:** Redesign floor layout — Cellular Manufacturing.

---

### I — Inventory
| Observation | Current State | Impact |
|-------------|--------------|--------|
| 330ml overproduction | 3 days excess inventory | SAR 45,000 tied-up capital |
| 1.5L shortage | Stockout 18% of orders | SAR 120,000 lost revenue/month |

**Lean Solution:** Implement Kanban pull system.

---

### M — Motion
| Observation | Current State | Impact |
|-------------|--------------|--------|
| Operators walk 45m to retrieve caps | 4 trips/shift | 180m walking/shift/operator |
| Tools not at point of use during changeover | Searching time | 8 min/changeover |

**Lean Solution:** 5S implementation — tools at point of use, shadow boards.

---

### W — Waiting
| Observation | Current State | Impact |
|-------------|--------------|--------|
| Line waits for maintenance during changeover | 12 min avg | 36 min/day |
| Operators wait for QC approval before restart | 8 min avg | 40 min/day |
| **Total Waiting Waste** | | **86 min/day = 6% of production time** |

**Lean Solution:** SMED for changeover, autonomous maintenance training.

---

### O — Overproduction
| Observation | Current State | Impact |
|-------------|--------------|--------|
| 330ml run continues after order fulfilled | 15% overproduction | Storage costs + expiry risk |

**Takt Time Calculation:**
```
Takt Time = Available Production Time / Customer Demand
          = (8 hours x 3600 sec) / 22,000 bottles
          = 1.31 seconds per bottle
```

**Lean Solution:** Takt Time-based scheduling + pull system.

---

### O — Over-processing
| Observation | Current State | Impact |
|-------------|--------------|--------|
| Double inspection at filling station | 100% inspection where defect rate is 0.3% | 16 person-hours/day wasted |
| Manual data entry in 3 systems | Triple data entry | 45 min/shift wasted |

**Lean Solution:** Risk-based inspection, system integration.

---

### D — Defects
| Defect Type | Rate | Monthly Cost |
|-------------|------|-------------|
| Leakage | 1.52% | SAR 38,000 |
| Underfill | 1.18% | SAR 29,500 |
| Cap deformation | 0.89% | SAR 22,250 |
| Label misalignment | 0.61% | SAR 15,250 |
| Contamination | 0.30% | SAR 7,500 |
| **Total** | **4.50%** | **SAR 112,500/month** |

**Lean Solution:** Poka-Yoke at capping station, TPM for filling machines.

---

### S — Skills (Underutilized)
| Observation | Impact |
|-------------|--------|
| Operators not involved in root cause analysis | Implementation resistance |
| Maintenance not trained in predictive maintenance | Higher downtime |
| No suggestion system | Missed improvement opportunities |

**Lean Solution:** Kaizen events with operator involvement, suggestion system.

---

## OEE Analysis Results

| Machine | Availability | Performance | Quality | OEE |
|---------|-------------|-------------|---------|-----|
| Filling Machine | 85% | 88% | 97% | 72.5% |
| **Capping Machine** | **72%** | **82%** | **96%** | **56.7%** |
| Labeling Machine | 90% | 92% | 99% | 82.1% |
| Packaging Machine | 88% | 90% | 99% | 78.4% |

**World Class OEE = 85%** — Capping machine is the critical priority.

---

## VSM Summary — Current State

| Process Step | Cycle Time | Uptime | Defect Rate | Value-Added? |
|-------------|-----------|--------|-------------|--------------|
| Water Treatment | 45 min | 95% | 0.1% | Yes |
| Bottle Blowing | 0.8 sec/bottle | 88% | 0.5% | Yes |
| Filling | 1.2 sec/bottle | 82% | 1.8% | Yes |
| **Capping** | **1.5 sec/bottle** | **72%** | **2.4%** | Bottleneck |
| Labeling | 1.0 sec/bottle | 90% | 0.6% | Yes |
| Packaging | 2.0 sec/case | 85% | 0.2% | Yes |
| **Changeover** | **44.8 min** | N/A | N/A | NVA |
| **Waiting (maintenance)** | **12 min** | N/A | N/A | NVA |

---

## 5S Audit Results

| 5S Pillar | Score (1-5) | Key Findings |
|-----------|------------|--------------|
| Sort | 2.5 | Unused tools and expired materials on floor |
| Set in Order | 2.0 | No shadow boards, tools not at point of use |
| Shine | 3.0 | Cleaning done but not standardized |
| Standardize | 1.5 | No visual standards posted |
| Sustain | 1.5 | No audit schedule, no ownership |
| **Overall** | **2.1/5** | **Significant 5S improvement needed** |

---

## Lean Waste to Root Cause Mapping

| Root Cause (6S) | Lean Waste | Lean Tool |
|-----------------|-----------|-----------|
| Maintenance plan not updated | Defects, Waiting | TPM, Predictive Maintenance |
| No PM program | Waiting, Defects | TPM |
| No SMED procedure | Waiting, Motion | SMED |
| No CI culture | Skills | Kaizen, Suggestion System |
| Push production | Inventory, Overproduction | Kanban |

---

## Best Practices

### Practice 1: Walk the Process (Gemba Walk)
- Go to the production floor and observe directly
- Time actual activities with a stopwatch
- Take photos and videos as evidence

### Practice 2: Quantify Every Waste
- "Operators walk too much" -> "Operators walk 180m/shift = 12 min/shift wasted"
- Quantification enables prioritization and ROI calculation

### Practice 3: Distinguish Value-Added from Non-Value-Added

| Category | Definition | Example |
|----------|-----------|---------|
| **Value-Added (VA)** | Customer would pay for it | Filling, capping, labeling |
| **Non-Value-Added (NVA)** | Customer would not pay | Waiting, rework, transport |
| **Necessary NVA** | Required but adds no value | Regulatory inspection |

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Identifying waste without quantifying it | Cannot prioritize | Always express waste in time, money, or units |
| Focusing only on operator waste | Misses system-level waste | Use VSM to see the full picture |
| Running Lean without 6S statistical confirmation | Implementing solutions for unconfirmed causes | Always confirm root causes statistically first |

---

---

# 04 — تحليل هدر Lean (DOWNTIME)
## شركة تعبئة المياه | مرحلة التحليل

---

## الهدر الثمانية — ملخص النتائج

| الهدر | التأثير الكمي | التكلفة الشهرية |
|-------|--------------|----------------|
| **T** — النقل | 8 دقائق/وردية | — |
| **I** — المخزون | إنتاج زائد + نقص | 165,000 ريال |
| **M** — الحركة | 12 دقيقة/وردية | — |
| **W** — الانتظار | 86 دقيقة/يوم (6%) | — |
| **O** — الإنتاج الزائد | 15% زائد عن الطلب | تكاليف تخزين |
| **O** — المعالجة الزائدة | 16 شخص-ساعة/يوم | — |
| **D** — العيوب | 4.5% معدل عيوب | **112,500 ريال/شهر** |
| **S** — المهارات | مقاومة التنفيذ | فرص ضائعة |

---

## نتائج OEE

| الآلة | التوافر | الأداء | الجودة | OEE |
|-------|---------|--------|--------|-----|
| آلة التعبئة | 85% | 88% | 97% | 72.5% |
| **آلة التغطية** | **72%** | **82%** | **96%** | **56.7%** |
| آلة الملصقات | 90% | 92% | 99% | 82.1% |
| آلة التغليف | 88% | 90% | 99% | 78.4% |

**المستوى العالمي = 85%** — آلة التغطية هي الأولوية الحرجة.

---

## ربط هدر Lean بالأسباب الجذرية لـ 6S

| السبب الجذري (6S) | هدر Lean | أداة Lean |
|-----------------|---------|----------|
| خطة الصيانة قديمة | العيوب، الانتظار | TPM، الصيانة التنبؤية |
| لا يوجد برنامج PM | الانتظار، العيوب | TPM |
| لا يوجد إجراء SMED | الانتظار، الحركة | SMED |
| لا توجد ثقافة CI | المهارات | Kaizen، نظام الاقتراحات |
| إنتاج بالدفع | المخزون، الإنتاج الزائد | Kanban |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

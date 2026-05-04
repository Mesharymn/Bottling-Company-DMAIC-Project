# D2 — Measure Phase

This folder contains all data collection, measurement, and findings artifacts for the Water Bottling Company DMAIC project. The data covers a **6-month historical period (November 2025 – April 2026)**.

## Folder Contents

| File / Folder | Description |
|---|---|
| `Data_Response_6Months_Bottling.xlsx` | Full 6-month operational dataset — 15,848 rows across 7 sheets |
| `Findings/D2_Measure_Findings_Bottling.xlsx` | **Measure Phase Findings** — 6 analysis sheets with 16 embedded charts |
| `Charts/` | 16 high-resolution PNG charts generated from the real dataset |
| `05_Communications/` | Official communications for the Measure phase |

---

## Findings Summary — Key Performance Indicators (Baseline)

| KPI | Current | Target | Status |
|---|---|---|---|
| **Defect Rate** | **4.49%** | ≤ 1% | 🔴 Critical |
| **Sigma Level** | **3.2σ** | ≥ 4.5σ | 🔴 Critical |
| **DPMO** | **44,896** | ≤ 1,350 | 🔴 Critical |
| **On-Time Delivery** | **79.9%** | ≥ 95% | 🔴 Critical |
| **Avg Changeover Time** | **44.8 min** | ≤ 20 min | 🔴 Critical |
| **Unplanned Downtime %** | **55.3%** | ≤ 20% | 🔴 Critical |
| **Customer CSAT** | **3.40/5** | ≥ 4.0/5 | 🔴 Critical |
| **Schedule Adherence** | **~90%** | ≥ 90% | 🟡 Monitor |
| **Fulfillment Rate** | **100%** | ≥ 95% | 🟢 On Target |

---

## Findings Workbook — Sheet Summary

| Sheet | Content |
|---|---|
| `1 - Executive Summary` | Full KPI baseline table + KPI dashboard chart |
| `2 - Defect & Quality` | Defect by type/shift/station/SKU + 5 charts |
| `3 - Downtime Analysis` | Downtime by reason/station, planned vs unplanned + 3 charts |
| `4 - Changeover & Production` | Changeover by SKU, production output vs planned + 2 charts |
| `5 - Fulfillment & Customer` | Fulfillment by SKU, complaints pareto, CSAT trend + 3 charts |
| `6 - Maintenance & Sigma` | Sigma level, DPMO benchmark, MTBF/MTTR by machine + 2 charts |

---

## Charts Generated (16 Total)

| # | Chart | Key Finding |
|---|---|---|
| 01 | KPI Dashboard | All critical KPIs in one view |
| 02 | Monthly Defect Rate Trend | Defect rate consistently above 4% every month |
| 03 | Pareto — Defect Types | Top 3 defect types = ~80% of all defects |
| 04 | Defect Rate by Shift | Night shift has highest defect rate |
| 05 | Defect Rate by Station | Filling station is the critical bottleneck |
| 06 | Defect Rate by SKU | 330ml bottles have highest defect rate |
| 07 | Pareto — Downtime Reasons | Top 3 reasons = ~80% of all downtime |
| 08 | Downtime by Station | Filling machine accounts for most downtime |
| 09 | Planned vs Unplanned Downtime | 55.3% of downtime is unplanned |
| 10 | Changeover Analysis | 100% of changeovers exceed 20-min target |
| 11 | Production Actual vs Planned | Monthly output gap and schedule adherence trend |
| 12 | Fulfillment & On-Time Delivery | On-time delivery at 79.9% vs 95% target |
| 13 | Pareto — Customer Complaints | Top complaint types driving dissatisfaction |
| 14 | CSAT Monthly Trend | CSAT at 3.40/5 — below 4.0 target |
| 15 | Sigma & DPMO Comparison | Current 3.2σ vs 4.5σ target |
| 16 | MTBF & MTTR by Machine | Reliability gaps across production machines |

---

## Data File — Sheet Summary

| Sheet | Content | Rows |
|---|---|---|
| `1-Production Output` | Daily output per shift per SKU vs. planned target | 1,629 |
| `2-Downtime & Stoppages` | Every stoppage with timestamps, reason, type, and station | 3,113 |
| `3-Changeover Times` | Every SKU transition with actual vs. 20-min target | 1,161 |
| `4-Defect & Quality` | Defect rates, rework, and rejections per shift/SKU/station | 3,258 |
| `5-Maintenance Logs` | PM & corrective work orders, MTBF, MTTR, parts replaced | 2,532 |
| `6-Inventory & Fulfillment` | Stock levels, fulfillment rates, stockouts, overstock events | 1,629 |
| `7-Customer Complaints` | Complaints, returns, CAR status, and satisfaction scores | 2,526 |

> **Status:** ✅ Measure Phase Complete — Findings documented with 16 charts. Ready for Analyze Phase.

---

# مرحلة القياس

يحتوي هذا المجلد على جميع مخرجات جمع البيانات والقياس لمشروع DMAIC لشركة تعبئة المياه. تغطي البيانات **فترة تاريخية مدتها 6 أشهر (نوفمبر 2025 – أبريل 2026)**.

## محتويات المجلد

| الملف / المجلد | الوصف |
|---|---|
| `Data_Response_6Months_Bottling.xlsx` | مجموعة البيانات التشغيلية الكاملة — 15,848 صفاً عبر 7 أوراق |
| `Findings/D2_Measure_Findings_Bottling.xlsx` | **نتائج مرحلة القياس** — 6 أوراق تحليلية مع 16 مخططاً مضمّناً |
| `Charts/` | 16 مخططاً بدقة عالية مولّدة من البيانات الفعلية |
| `05_Communications/` | المراسلات الرسمية لمرحلة القياس |

## ملخص النتائج — مؤشرات الأداء الرئيسية (خط الأساس)

| المؤشر | الحالي | الهدف | الحالة |
|---|---|---|---|
| **معدل العيوب** | **4.49%** | ≤ 1% | 🔴 حرج |
| **مستوى سيجما** | **3.2σ** | ≥ 4.5σ | 🔴 حرج |
| **DPMO** | **44,896** | ≤ 1,350 | 🔴 حرج |
| **التسليم في الوقت المحدد** | **79.9%** | ≥ 95% | 🔴 حرج |
| **متوسط وقت التحويل** | **44.8 دقيقة** | ≤ 20 دقيقة | 🔴 حرج |
| **التوقف غير المخطط** | **55.3%** | ≤ 20% | 🔴 حرج |
| **رضا العملاء (CSAT)** | **3.40/5** | ≥ 4.0/5 | 🔴 حرج |

> **الحالة:** ✅ مرحلة القياس مكتملة — النتائج موثقة مع 16 مخططاً. جاهز للانتقال إلى مرحلة التحليل.

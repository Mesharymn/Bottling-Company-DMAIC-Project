# 03 — Voice of Customer (VOC)
## Water Bottling Company | Define Phase

> VOC is the process of capturing **what customers say, feel, and need** — then translating those statements into measurable quality requirements (CTQs) that the process must meet.

---

## Files in This Folder

| File | Description |
|------|-------------|
| [`VOC_Translation.md`](./VOC_Translation.md) | Raw VOC statements with translation to customer needs |
| [`VOC_to_CTQ.md`](./VOC_to_CTQ.md) | Full VOC → CTQ translation with specification limits |

---

## What Is VOC?

Voice of Customer (VOC) is the systematic process of:
1. **Collecting** customer feedback (complaints, surveys, interviews, returns)
2. **Categorizing** feedback into themes
3. **Translating** themes into measurable requirements (CTQs)
4. **Prioritizing** CTQs by customer importance and business impact

---

## VOC → CTQ Translation Chain

```
Customer Statement  →  Customer Need  →  CTQ  →  Specification Limit
"The bottles leak"  →  Seal integrity  →  Seal failure rate  →  ≤ 0.1%
"Late deliveries"   →  On-time supply  →  Order fulfillment  →  ≥ 95% on time
"Wrong quantity"    →  Order accuracy  →  Order fill rate    →  ≥ 99%
"Taste is off"      →  Water purity    →  TDS level          →  ≤ 50 ppm
```

---

## VOC Sources for This Project

| Source | Method | Data Collected |
|--------|--------|---------------|
| Distributor complaints | Monthly complaint log | 35% increase in Q1 2026 |
| Retailer returns | Return authorization records | 18% return rate for leaking bottles |
| Consumer surveys | Post-purchase survey | 3.4/5 average satisfaction score |
| Sales team feedback | Weekly sales meetings | Stock shortages of 500ml SKU |
| Quality inspection | Incoming inspection at distributors | 4.5% defect rate confirmed |

---

## CTQs for This Project

| # | Customer Need | CTQ | Current | Target | Priority |
|---|--------------|-----|---------|--------|----------|
| 1 | Seal integrity | Seal failure rate | 4.5% | ≤ 1% | Critical |
| 2 | On-time delivery | Order fulfillment rate | 82% | ≥ 95% | High |
| 3 | Correct volume | Fill volume accuracy | ±5ml | ±2ml | High |
| 4 | Water purity | TDS level | 48 ppm | ≤ 50 ppm | Medium |
| 5 | Label quality | Label misalignment rate | 2.1% | ≤ 0.5% | Medium |

---

## Best Practices for VOC Collection

### Method 1: Customer Complaints Analysis
- Review all complaint records for the past 6–12 months
- Categorize by complaint type (defect, delivery, quantity, quality)
- Calculate frequency and financial impact per category
- Use Pareto analysis to identify the top 20% of complaints causing 80% of impact

### Method 2: Direct Customer Interviews
- Interview 5–10 customers from each customer segment (distributors, retailers, consumers)
- Use open-ended questions: "What frustrates you most about our product/service?"
- Avoid leading questions: Do NOT ask "Do you have problems with leaking bottles?"
- Record verbatim statements — do not paraphrase during collection

### Method 3: Surveys
- Keep surveys to 5–10 questions maximum
- Use Likert scales (1–5) for satisfaction ratings
- Include one open-ended question for unexpected feedback
- Aim for at least 30 responses per customer segment

### Method 4: Observation (Gemba)
- Visit the customer's site and observe how they use the product
- Watch for workarounds — customers often adapt to defects without complaining
- Document observations with photos and notes

---

## VOC Translation Rules

### Rule 1: Translate Needs, Not Solutions
- ❌ "Customer wants new capping machines" — this is a solution
- ✅ "Customer needs bottles that do not leak" — this is a need

### Rule 2: Every CTQ Must Be Measurable
- ❌ "Improve seal quality" — not measurable
- ✅ "Reduce seal failure rate from 4.5% to ≤ 1%" — measurable

### Rule 3: Validate CTQs with Customers
- Do not assume you know what customers mean
- Present your CTQ translation back to customers and ask: "Is this what you meant?"
- Adjust based on their feedback

### Rule 4: Prioritize Using Kano Model
| Category | Description | Example |
|----------|-------------|---------|
| **Must-Be** | Expected — absence causes dissatisfaction | Bottles must not leak |
| **Performance** | More is better — directly linked to satisfaction | Faster delivery |
| **Delighter** | Unexpected — creates delight when present | Personalized labels |

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Collecting VOC only from internal teams | CTQs reflect internal assumptions, not customer needs | Always go to actual customers |
| Translating complaints into solutions | Skips root cause analysis | Translate to needs first, then CTQs |
| CTQs without specification limits | Cannot measure compliance | Always add LSL, USL, or target value |
| Too many CTQs (20+) | Team cannot focus | Use Pareto to limit to top 5–8 CTQs |
| VOC collected once and never updated | Customer needs change over time | Review VOC at each project gate |

---

---

# 03 — صوت العميل (VOC)
## شركة تعبئة المياه | مرحلة التعريف

> VOC هو عملية التقاط **ما يقوله العملاء ويشعرون به ويحتاجونه** — ثم ترجمة تلك التصريحات إلى متطلبات جودة قابلة للقياس (CTQs) يجب أن تلبيها العملية.

---

## سلسلة ترجمة VOC → CTQ

```
تعليق العميل  →  احتياج العميل  →  CTQ  →  حد المواصفات
"الزجاجات تتسرب"  →  سلامة الإغلاق  →  معدل فشل الإغلاق  →  ≤ 0.1%
"التسليم متأخر"   →  التوريد في الوقت  →  معدل تنفيذ الطلبات  →  ≥ 95%
"الكميات خاطئة"  →  دقة الطلب  →  معدل تنفيذ الطلب  →  ≥ 99%
"الطعم غريب"     →  نقاء المياه  →  مستوى TDS  →  ≤ 50 ppm
```

---

## أفضل الممارسات لجمع VOC

### الطريقة 1: تحليل شكاوى العملاء
- مراجعة جميع سجلات الشكاوى للـ 6-12 شهراً الماضية
- تصنيف حسب نوع الشكوى (عيب، توصيل، كمية، جودة)
- استخدام تحليل باريتو لتحديد أعلى 20% من الشكاوى التي تُسبب 80% من التأثير

### الطريقة 2: مقابلات العملاء المباشرة
- مقابلة 5-10 عملاء من كل شريحة
- استخدام أسئلة مفتوحة: "ما الذي يُحبطك أكثر في منتجنا/خدمتنا؟"
- تجنب الأسئلة الإيحائية: لا تسأل "هل تواجه مشاكل مع تسرب الزجاجات؟"

### قواعد ترجمة VOC
- ❌ "العميل يريد آلات تغطية جديدة" — هذا حل
- ✅ "العميل يحتاج زجاجات لا تتسرب" — هذه حاجة
- كل CTQ يجب أن يكون قابلاً للقياس مع حد مواصفات

---

## الأخطاء الشائعة

| الخطأ | التأثير | الوقاية |
|-------|---------|---------|
| جمع VOC من الفرق الداخلية فقط | CTQs تعكس افتراضات داخلية | اذهب دائماً إلى العملاء الفعليين |
| ترجمة الشكاوى إلى حلول | يتجاوز تحليل السبب الجذري | ترجم إلى احتياجات أولاً، ثم CTQs |
| CTQs بدون حدود مواصفات | لا يمكن قياس الامتثال | أضف دائماً LSL أو USL أو قيمة هدف |
| عدد كبير جداً من CTQs (+20) | الفريق لا يستطيع التركيز | استخدم باريتو للحد إلى أعلى 5-8 CTQs |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

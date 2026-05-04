# 01 — Project Charter
## Water Bottling Company | Define Phase

> The Project Charter is the **official authorization document** for a Six Sigma project. It defines the problem, sets the goal, establishes the scope, assigns the team, and secures management commitment — all before any data is collected.

---

## Files in This Folder

| File | Description |
|------|-------------|
| [`Project_Charter.md`](./Project_Charter.md) | Full project charter with all sections |
| [`Problem_Statement.md`](./Problem_Statement.md) | Detailed problem statement using IS/IS NOT |

---

## What Is a Project Charter?

A Project Charter is a **one-page contract** between the project team and the organization. It answers:

- **Why** are we doing this project? (Business Case)
- **What** is the problem? (Problem Statement)
- **What** does success look like? (Goal Statement)
- **Where** does the project start and end? (Scope)
- **Who** is on the team? (Team Members & Roles)
- **When** will it be done? (Timeline)

---

## Key Sections Explained

### Business Case
The business case justifies *why* the project deserves resources. It should quantify:
- Financial impact (cost of poor quality, lost revenue)
- Customer impact (complaint rate, churn risk)
- Operational impact (capacity loss, rework hours)

**Best practice:** Express the business case in monetary terms. "4.5% defect rate = 44,896 DPMO = estimated SAR 2.3M annual rework cost" is more compelling than "we have too many defects."

### Problem Statement
A strong problem statement follows the **IS / IS NOT** framework:

**Template:**
```
[Process name] has been experiencing [problem description] since [date].
The current [metric] is [current value], against a target of [target value].
This results in [quantified business impact].
The root cause is currently unknown.
```

**This project's problem statement:**
> The bottled water production line has maintained a defect rate of 4.5% (44,896 DPMO) since November 2025, resulting in a 3.2σ process — 3.5× above the 1% target. This has caused a 35% increase in customer complaints, an 18% drop in on-time delivery, and an estimated 15% increase in rework costs.

### Goal Statement
The goal statement is the **mirror image** of the problem statement — it describes the desired future state.

**Template:**
```
Reduce [metric] from [current value] to [target value] by [date],
resulting in [quantified benefit].
```

### Scope — IS / IS NOT

| IS (In Scope) | IS NOT (Out of Scope) |
|---------------|----------------------|
| Filling station defects | Packaging design changes |
| Capping station failures | Supplier quality issues |
| Changeover time reduction | Distribution network |
| Shift-level variation | Pricing or sales strategy |
| Production downtime | Warehouse management |

### Team Roles (RACI)

| Role | Responsibility |
|------|---------------|
| **Champion / Sponsor** | Removes barriers, provides resources, approves scope |
| **Black Belt (BB)** | Leads the project, applies Six Sigma methodology |
| **Green Belt (GB)** | Supports data collection and analysis |
| **Process Owner** | Owns the process being improved |
| **Team Members** | Subject matter experts (operators, maintenance, QC) |

---

## Best Practices

### Do's
- **Get the charter signed** before starting any work — verbal approval is not enough
- **Quantify everything** — use numbers, not adjectives ("4.5% defect rate", not "high defect rate")
- **Define scope boundaries explicitly** — what is NOT in scope is as important as what IS
- **Include a baseline metric** — you cannot prove improvement without a starting point
- **Set a realistic timeline** — DMAIC projects typically take 3–6 months

### Don'ts
- **Do not include solutions** in the charter — the charter defines the problem, not the fix
- **Do not skip the business case** — without it, the project will not get resources
- **Do not make the scope too broad** — "improve all operations" is not a project scope
- **Do not start without sponsor sign-off** — this is the most common reason projects fail

---

## Common Mistakes

| Mistake | Impact | Prevention |
|---------|--------|------------|
| Charter written after project starts | Team works without alignment | Write charter on Day 1 |
| Goal is not measurable | Cannot prove success | Add specific numbers and dates |
| Scope creep not addressed | Project never ends | Review scope at every gate |
| Team roles not defined | Confusion and duplication | Use RACI matrix |
| No financial justification | Project loses priority | Calculate cost of poor quality |

---

## How to Create a Project Charter in Excel/Word

1. Create a table with the following sections: Project Title, Date, Champion, Black Belt, Business Case, Problem Statement, Goal Statement, Scope (IS/IS NOT), Team Members, Timeline, Financial Impact.
2. Fill in the **Problem Statement** first — it drives all other sections.
3. Write the **Goal Statement** as the direct opposite of the problem statement.
4. Define **Scope** using two columns: IS (in scope) and IS NOT (out of scope).
5. Build a **Gantt chart** for the timeline using Excel's conditional formatting.
6. Calculate the **financial impact**: Defect Rate × Units Produced × Cost per Defect.
7. Get **sign-off** from the Champion before distributing.

---

---

# 01 — وثيقة المشروع
## شركة تعبئة المياه | مرحلة التعريف

> وثيقة المشروع هي **وثيقة التفويض الرسمية** لمشروع 6S. تُحدد المشكلة، وتضع الهدف، وتُحدد النطاق، وتُعيّن الفريق، وتُؤمّن التزام الإدارة — كل ذلك قبل جمع أي بيانات.

---

## الملفات في هذا المجلد

| الملف | الوصف |
|-------|-------|
| [`Project_Charter.md`](./Project_Charter.md) | وثيقة المشروع الكاملة بجميع أقسامها |
| [`Problem_Statement.md`](./Problem_Statement.md) | بيان المشكلة التفصيلي باستخدام إطار IS/IS NOT |

---

## ما هي وثيقة المشروع؟

وثيقة المشروع هي **عقد من صفحة واحدة** بين فريق المشروع والمنظمة. تجيب على:

- **لماذا** نقوم بهذا المشروع؟ (حالة الأعمال)
- **ما هي** المشكلة؟ (بيان المشكلة)
- **كيف** يبدو النجاح؟ (بيان الهدف)
- **أين** يبدأ المشروع وينتهي؟ (النطاق)
- **من** في الفريق؟ (أعضاء الفريق وأدوارهم)
- **متى** سينتهي؟ (الجدول الزمني)

---

## أفضل الممارسات

### ما يجب فعله
- **احصل على توقيع الوثيقة** قبل بدء أي عمل — الموافقة الشفهية غير كافية
- **قيّم كل شيء** — استخدم الأرقام وليس الصفات ("معدل عيوب 4.5%"، وليس "معدل عيوب مرتفع")
- **حدد حدود النطاق صراحةً** — ما هو خارج النطاق لا يقل أهمية عما هو داخله
- **أدرج مقياساً أساسياً** — لا يمكنك إثبات التحسين بدون نقطة بداية
- **ضع جدولاً زمنياً واقعياً** — مشاريع DMAIC تستغرق عادةً 3-6 أشهر

### ما يجب تجنبه
- **لا تُدرج الحلول** في الوثيقة — الوثيقة تُحدد المشكلة وليس الحل
- **لا تتخطى حالة الأعمال** — بدونها لن يحصل المشروع على الموارد
- **لا تجعل النطاق واسعاً جداً** — "تحسين جميع العمليات" ليس نطاق مشروع
- **لا تبدأ بدون موافقة الراعي** — هذا هو السبب الأكثر شيوعاً لفشل المشاريع

---

## الأخطاء الشائعة

| الخطأ | التأثير | الوقاية |
|-------|---------|---------|
| كتابة الوثيقة بعد بدء المشروع | يعمل الفريق بدون توافق | اكتب الوثيقة في اليوم الأول |
| الهدف غير قابل للقياس | لا يمكن إثبات النجاح | أضف أرقاماً وتواريخ محددة |
| عدم معالجة تمدد النطاق | المشروع لا ينتهي أبداً | راجع النطاق في كل بوابة |
| عدم تحديد أدوار الفريق | ارتباك وتكرار | استخدم مصفوفة RACI |
| لا مبرر مالي | المشروع يفقد الأولوية | احسب تكلفة الجودة الرديئة |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

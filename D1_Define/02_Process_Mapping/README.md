# 02 — Process Mapping (SIPOC)
## Water Bottling Company | Define Phase

> SIPOC is a **high-level process map** that identifies the Suppliers, Inputs, Process steps, Outputs, and Customers for a process. It establishes the boundaries of what is being improved.

---

## Files in This Folder

| File | Scope |
|------|-------|
| [`SIPOC_00_Overview.md`](./SIPOC_00_Overview.md) | End-to-end production line overview |
| [`SIPOC_01_Water_Treatment.md`](./SIPOC_01_Water_Treatment.md) | Water treatment and purification |
| [`SIPOC_02_Bottle_Blowing.md`](./SIPOC_02_Bottle_Blowing.md) | Preform heating and bottle blowing |
| [`SIPOC_03_Filling.md`](./SIPOC_03_Filling.md) | Bottle filling and volume control |
| [`SIPOC_04_Capping.md`](./SIPOC_04_Capping.md) | Capping and seal integrity |
| [`SIPOC_05_Labeling.md`](./SIPOC_05_Labeling.md) | Label application and alignment |
| [`SIPOC_06_Packaging.md`](./SIPOC_06_Packaging.md) | Packaging, palletizing, and dispatch |

---

## What Is SIPOC?

| Letter | Stands For | Question It Answers |
|--------|-----------|---------------------|
| **S** | Suppliers | Who provides inputs to the process? |
| **I** | Inputs | What materials, information, or resources enter the process? |
| **P** | Process | What are the 5–7 high-level steps? |
| **O** | Outputs | What does the process produce? |
| **C** | Customers | Who receives the outputs? |

---

## Why Use SIPOC in the Define Phase?

1. **Establishes scope** — defines where the process starts and ends
2. **Identifies stakeholders** — reveals who supplies inputs and who receives outputs
3. **Prevents scope creep** — keeps the team focused on the right process boundaries

---

## SIPOC Summary — This Project

| Sub-Process | Key Input | Key Output | Primary Defect Risk |
|-------------|-----------|------------|---------------------|
| Water Treatment | Raw water | Purified water (TDS ≤ 50 ppm) | Contamination |
| Bottle Blowing | PET preforms | Blown bottles (correct dimensions) | Deformation |
| **Filling** | Purified water + blown bottles | Filled bottles (correct volume) | **Leakage, underfill** |
| **Capping** | Filled bottles + caps | Sealed bottles | **Seal failure, cross-threading** |
| Labeling | Sealed bottles + labels | Labeled bottles | Misalignment |
| Packaging | Labeled bottles | Palletized cases | Damage in transit |

> **Note:** Filling and Capping are the highest-risk sub-processes — they account for the majority of the 4.5% defect rate.

---

## Best Practices

### Rule 1: Keep It High-Level
- **5–7 process steps maximum** — SIPOC is a summary, not a flowchart
- Each step: **verb + noun** (e.g., "Fill bottles", not "The operator fills the bottles")
- If you need more than 7 steps, you are mapping at the wrong level of detail

### Rule 2: Build in This Order
1. **Process** — list the 5–7 steps first (the anchor)
2. **Outputs** — what does each step produce?
3. **Customers** — who receives those outputs?
4. **Inputs** — what does each step need?
5. **Suppliers** — who provides those inputs?

### Rule 3: Be Specific About Outputs
Each output should have a **quality characteristic**:
- "Filled bottles" → "Filled bottles: 330ml ± 2ml, no leakage"
- This directly feeds into CTQ translation in the VOC analysis

### Rule 4: Include Internal Customers
Every process step's output becomes the next step's input. Map these internal customer relationships explicitly.

---

## Common Mistakes

| Mistake | Why It Happens | How to Fix |
|---------|---------------|------------|
| Too many process steps (10+) | Team maps every micro-task | Consolidate into 5–7 major steps |
| Vague outputs ("good product") | Team avoids specifics | Add measurable quality characteristics |
| Missing internal customers | Team only thinks of end consumers | Map each step's output to the next step |
| Confusing inputs with suppliers | Terminology confusion | Inputs = what enters; Suppliers = who provides it |
| SIPOC used as a flowchart | Misunderstanding the tool | Use a process flowchart separately for detailed mapping |

---

## How to Create a SIPOC in Excel

1. Create a table with 5 columns: **Suppliers | Inputs | Process | Outputs | Customers**
2. Fill in the **Process** column first — list 5–7 steps as numbered rows
3. For each step, identify the **Output** (what it produces)
4. Identify the **Customer** for each output (who receives it)
5. Identify the **Input** required for each step (what it needs)
6. Identify the **Supplier** for each input (who provides it)
7. Add a "Quality Characteristic" column next to Outputs to prepare for CTQ translation
8. Color-code by sub-process for clarity

---

---

# 02 — رسم خريطة العملية (SIPOC)
## شركة تعبئة المياه | مرحلة التعريف

> SIPOC هو **خريطة عملية عالية المستوى** تُحدد الموردين والمدخلات وخطوات العملية والمخرجات والعملاء. يُحدد حدود ما يتم تحسينه.

---

## الملفات في هذا المجلد

| الملف | النطاق |
|-------|--------|
| [`SIPOC_00_Overview.md`](./SIPOC_00_Overview.md) | نظرة عامة على خط الإنتاج بالكامل |
| [`SIPOC_01_Water_Treatment.md`](./SIPOC_01_Water_Treatment.md) | عملية معالجة المياه وتنقيتها |
| [`SIPOC_02_Bottle_Blowing.md`](./SIPOC_02_Bottle_Blowing.md) | عملية تسخين البريفورم ونفخ الزجاجات |
| [`SIPOC_03_Filling.md`](./SIPOC_03_Filling.md) | عملية تعبئة الزجاجات والتحكم في الحجم |
| [`SIPOC_04_Capping.md`](./SIPOC_04_Capping.md) | عملية التغطية وسلامة الإغلاق |
| [`SIPOC_05_Labeling.md`](./SIPOC_05_Labeling.md) | عملية لصق الملصقات ومحاذاتها |
| [`SIPOC_06_Packaging.md`](./SIPOC_06_Packaging.md) | عملية التغليف والتلبيس والشحن |

---

## ما هو SIPOC؟

| الحرف | يرمز إلى | السؤال الذي يجيب عليه |
|-------|---------|----------------------|
| **S** | الموردون | من يُوفر المدخلات للعملية؟ |
| **I** | المدخلات | ما هي المواد أو المعلومات أو الموارد التي تدخل العملية؟ |
| **P** | العملية | ما هي الخطوات الـ 5-7 الرئيسية؟ |
| **O** | المخرجات | ماذا تُنتج العملية؟ |
| **C** | العملاء | من يستلم المخرجات؟ |

---

## أفضل الممارسات

### القاعدة 1: ابقَ على المستوى العالي
- **5-7 خطوات عملية كحد أقصى** — SIPOC ملخص وليس مخططاً تدفقياً
- كل خطوة: **فعل + اسم** (مثل: "تعبئة الزجاجات")
- إذا احتجت أكثر من 7 خطوات، فأنت ترسم على المستوى الخاطئ

### القاعدة 2: ابنِ بهذا الترتيب
1. **العملية** — أدرج الخطوات الـ 5-7 أولاً (المرساة)
2. **المخرجات** — ماذا تُنتج كل خطوة؟
3. **العملاء** — من يستلم تلك المخرجات؟
4. **المدخلات** — ماذا تحتاج كل خطوة؟
5. **الموردون** — من يُوفر تلك المدخلات؟

---

## الأخطاء الشائعة

| الخطأ | لماذا يحدث | كيفية الإصلاح |
|-------|-----------|--------------|
| خطوات عملية كثيرة جداً (+10) | الفريق يرسم كل مهمة صغيرة | دمج في 5-7 خطوات رئيسية |
| مخرجات مبهمة ("منتج جيد") | الفريق يتجنب التفاصيل | أضف خصائص جودة قابلة للقياس |
| تفويت العملاء الداخليين | الفريق يفكر فقط في المستهلكين النهائيين | رسم مخرج كل خطوة إلى الخطوة التالية |
| الخلط بين المدخلات والموردين | ارتباك في المصطلحات | المدخلات = ما يدخل؛ الموردون = من يُوفره |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

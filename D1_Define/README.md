# D1 — Define Phase
## Water Bottling Company | Six Sigma DMAIC Project

> **Purpose:** The Define phase is the foundation of the entire DMAIC project. Its goal is to clearly articulate *what* the problem is, *who* is affected, *what* the boundaries of the project are, and *what* success looks like — before any data is collected or solutions are proposed.

---

## What Is the Define Phase?

The Define phase answers four fundamental questions:

| Question | Tool Used | Output |
|----------|-----------|--------|
| **What is the problem?** | Project Charter | Problem Statement, Goal Statement |
| **What does the process look like?** | SIPOC | High-level process map |
| **What do customers need?** | VOC → CTQ | Critical-to-Quality requirements |
| **Who are the stakeholders?** | Stakeholder Analysis | Engagement plan, risk register |

---

## Folder Structure

| Folder | Contents | Purpose |
|--------|----------|---------|
| [`01_Project_Charter/`](./01_Project_Charter/) | Charter, Problem Statement | Formally authorize and scope the project |
| [`02_Process_Mapping/`](./02_Process_Mapping/) | SIPOC (7 sub-processes) | Map the process at a high level |
| [`03_Voice_Of_Customer/`](./03_Voice_Of_Customer/) | VOC, CTQ Translation | Translate customer needs into measurable requirements |
| [`04_Stakeholder_Analysis/`](./04_Stakeholder_Analysis/) | Identification, Mapping, Engagement | Manage people and change |
| [`05_Communications/`](./05_Communications/) | 7 stakeholder emails | Formal communication templates |

---

## Key Findings (This Project)

**Operational Inefficiency:** The production line outputs **18,000 bottles/hour** against a target of 22,000. Downtime is nearly double the acceptable rate (18% vs ≤10%), driven primarily by 45-minute changeover times.

**Quality Issues:** Defect rates (leakage and sealing) stand at **4.5%** — 4.5× the target — causing a 6% rework rate and a 35% spike in customer complaints.

**Customer Impact:** On-time order fulfillment has dropped to **82%** (target ≥95%). Customers are returning defective batches, rejecting deliveries, and delaying payments.

**Internal Friction:** Sales and distribution teams face stock shortages of high-demand SKUs due to inventory imbalances caused by unreliable production.

---

## Best Practices for the Define Phase

### 1. Write a Strong Problem Statement

A good problem statement follows the **IS / IS NOT** framework and must answer:

- **What** is the problem? (not the cause or solution)
- **Where** does it occur? (specific process, location, machine)
- **When** did it start? (date, frequency)
- **How big** is it? (quantified impact)
- **What is NOT** the problem? (to set clear boundaries)

> ✅ **Good:** "The defect rate on the filling line has been 4.5% since Q3 2025, resulting in 44,896 DPMO and a 3.2σ process — 3.5× above the 1% target, costing an estimated 15% in rework and customer returns."
>
> ❌ **Bad:** "There are too many defects because the machines are old."

**Key rule:** The problem statement must describe the *symptom*, not the *cause* and not the *solution*. Root cause analysis happens in the Analyze phase.

---

### 2. Define SMART Goals

Every project goal must be **Specific, Measurable, Achievable, Relevant, Time-bound**:

| Element | Question to Ask | Example for This Project |
|---------|----------------|--------------------------|
| **Specific** | What exactly will improve? | Reduce defect rate on filling and capping stations |
| **Measurable** | By how much? | From 4.5% to ≤1% |
| **Achievable** | Is it realistic? | Based on benchmark data from similar facilities |
| **Relevant** | Does it matter to the business? | Directly impacts customer satisfaction and revenue |
| **Time-bound** | By when? | Within 6 months of project start |

---

### 3. Keep the SIPOC at the Right Level

SIPOC is a **summary tool**, not a detailed process map. Follow these rules:

- Use **5–7 process steps maximum** — if you have more, you are too detailed
- Each step should be a **verb + noun** (e.g., "Fill bottles", not "Filling")
- Suppliers and Customers should be **real entities**, not internal departments
- Inputs and Outputs should be **tangible deliverables**, not activities
- The SIPOC should fit on **one page** — if it does not, simplify

**Common mistake:** Listing every micro-step in the process. SIPOC is meant to show the process boundary, not map every task.

---

### 4. Translate VOC Correctly

The VOC → CTQ translation is the most critical step in the Define phase. Follow this chain:

```
Customer Statement  →  Customer Need  →  CTQ (measurable requirement)
"The bottles leak"  →  Seal integrity  →  Seal failure rate ≤ 0.1%
"Late deliveries"   →  On-time supply  →  Order fulfillment ≥ 95% on time
"Wrong quantity"    →  Order accuracy  →  Order fill rate ≥ 99%
```

**Rules for good CTQs:**
- Every CTQ must have a **specification limit** (LSL, USL, or target value)
- CTQs must be **measurable** with existing or collectable data
- Validate CTQs with actual customers, not internal assumptions
- Avoid translating complaints directly into solutions (e.g., "buy new machines")

---

### 5. Stakeholder Management

Map all stakeholders on a **Power × Interest** grid and define an engagement strategy for each quadrant:

| Quadrant | Power | Interest | Strategy |
|----------|-------|----------|----------|
| **Manage Closely** | High | High | Regular updates, involve in decisions |
| **Keep Satisfied** | High | Low | Periodic briefings, no surprises |
| **Keep Informed** | Low | High | Share progress, gather feedback |
| **Monitor** | Low | Low | Minimal communication |

**Best practices:**
- Identify **resistors** early and develop specific engagement strategies
- Document stakeholder concerns and address them proactively
- Never underestimate operators — they have the most process knowledge
- Senior management sponsorship is non-negotiable for project success

---

### 6. Common Mistakes to Avoid

| Mistake | Why It's a Problem | Correction |
|---------|-------------------|------------|
| Jumping to solutions in Define | Skips root cause analysis entirely | Focus only on defining the problem |
| Vague problem statement | Cannot be measured or validated | Quantify every element with real numbers |
| Skipping VOC | CTQs become internal assumptions | Always validate with real customer data |
| Too broad project scope | Project never ends, team loses focus | Use IS/IS NOT to set hard boundaries |
| Ignoring stakeholders | Resistance kills implementation | Map and engage all stakeholders early |
| Confusing problem with cause | Leads to wrong solutions | Problem = what is happening; Cause = why |
| No baseline measurement | Cannot prove improvement later | Establish current-state metrics in Define |

---

## Define Phase Checklist

Before moving to the Measure phase, verify all items below are complete:

- [ ] Project Charter signed by sponsor
- [ ] Problem statement is quantified (current state with numbers)
- [ ] Goal statement has a specific, measurable target
- [ ] Project scope boundaries (IS / IS NOT) are defined
- [ ] SIPOC covers all production sub-processes
- [ ] At least 5 VOC statements collected from real customers
- [ ] Each VOC translated to a CTQ with specification limits
- [ ] All key stakeholders identified and mapped on Power/Interest grid
- [ ] Communication plan established with frequency and channels
- [ ] Team roles and responsibilities assigned (Champion, BB, GB, Team Members)
- [ ] Project timeline and milestones agreed upon

---

## Tool Reference Guide

| Tool | When to Use | Time Required | Difficulty |
|------|-------------|---------------|------------|
| **Project Charter** | Start of project | 2–4 hours | Medium |
| **IS/IS NOT Analysis** | Scoping the problem | 1–2 hours | Low |
| **SIPOC** | Understanding process boundaries | 2–3 hours | Low |
| **VOC Collection** | Understanding customer needs | 1–2 weeks | Medium |
| **Kano Model** | Prioritizing CTQs | 2–4 hours | Medium |
| **Stakeholder Map** | Identifying who is affected | 1–2 hours | Low |
| **RACI Matrix** | Defining team roles | 1 hour | Low |

---

---

# D1 — مرحلة التعريف
## شركة تعبئة المياه | مشروع DMAIC سيجما ستة

> **الغرض:** مرحلة التعريف هي أساس مشروع DMAIC بأكمله. هدفها توضيح *ما هي* المشكلة، *من* يتأثر بها، *ما هي* حدود المشروع، و*كيف* يبدو النجاح — قبل جمع أي بيانات أو اقتراح أي حلول.

---

## ما هي مرحلة التعريف؟

مرحلة التعريف تجيب على أربعة أسئلة جوهرية:

| السؤال | الأداة المستخدمة | المخرج |
|--------|-----------------|--------|
| **ما هي المشكلة؟** | وثيقة المشروع | بيان المشكلة، بيان الهدف |
| **كيف تبدو العملية؟** | SIPOC | خريطة العملية على المستوى العالي |
| **ماذا يحتاج العملاء؟** | VOC → CTQ | متطلبات الجودة الحرجة |
| **من هم أصحاب المصلحة؟** | تحليل أصحاب المصلحة | خطة التفاعل، سجل المخاطر |

---

## النتائج الرئيسية (هذا المشروع)

**عدم كفاءة التشغيل:** خط الإنتاج يُنتج **18,000 زجاجة/ساعة** مقابل هدف 22,000. وقت التوقف يكاد يكون ضعف المعدل المقبول (18% مقابل ≤10%)، مدفوعاً بأوقات تحويل تبلغ 45 دقيقة.

**مشكلات الجودة:** معدلات العيوب (التسرب والإغلاق) تبلغ **4.5%** — أي 4.5 أضعاف الهدف — مما يُسبب معدل إعادة عمل 6% وارتفاعاً بنسبة 35% في شكاوى العملاء.

**تأثير على العملاء:** انخفض معدل تسليم الطلبات في الوقت المحدد إلى **82%** (الهدف ≥95%). يقوم العملاء بإرجاع الدفعات المعيبة ورفض التسليمات وتأخير المدفوعات.

**الاحتكاك الداخلي:** تواجه فرق المبيعات والتوزيع نقصاً في مخزون الأحجام الأكثر طلباً بسبب اختلالات المخزون الناجمة عن عدم موثوقية الإنتاج.

---

## أفضل الممارسات لمرحلة التعريف

### 1. كتابة بيان مشكلة قوي

بيان المشكلة الجيد يتبع إطار **IS / IS NOT** ويجيب على:

- **ماذا** يحدث؟ (ليس السبب أو الحل)
- **أين** يحدث؟ (عملية محددة، موقع، آلة)
- **متى** بدأ؟ (التاريخ، التكرار)
- **كم** حجمه؟ (التأثير بالأرقام)
- **ما الذي ليس** مشكلة؟ (لتحديد الحدود بوضوح)

> ✅ **جيد:** "معدل العيوب في خط التعبئة بلغ 4.5% منذ الربع الثالث 2025، مما أدى إلى 44,896 DPMO ومستوى عملية 3.2σ — أعلى من هدف 1% بـ 3.5 مرة، بتكلفة تُقدَّر بـ 15% في إعادة العمل والمرتجعات."
>
> ❌ **سيئ:** "هناك عيوب كثيرة لأن الآلات قديمة."

**القاعدة الأساسية:** يجب أن يصف بيان المشكلة *العَرَض*، وليس *السبب* وليس *الحل*. تحليل السبب الجذري يحدث في مرحلة التحليل.

---

### 2. تحديد أهداف SMART

| العنصر | السؤال | مثال لهذا المشروع |
|--------|--------|-------------------|
| **محدد** | ماذا سيتحسن بالضبط؟ | تقليل معدل العيوب في محطتي التعبئة والتغطية |
| **قابل للقياس** | بكم؟ | من 4.5% إلى ≤1% |
| **قابل للتحقيق** | هل هو واقعي؟ | بناءً على بيانات المعيار من منشآت مماثلة |
| **ذو صلة** | هل يهم الأعمال؟ | يؤثر مباشرة على رضا العملاء والإيرادات |
| **محدد بوقت** | بحلول متى؟ | خلال 6 أشهر من بدء المشروع |

---

### 3. الحفاظ على SIPOC في المستوى الصحيح

- **5-7 خطوات عملية كحد أقصى** — إذا كان لديك أكثر، فأنت مفصّل جداً
- كل خطوة: **فعل + اسم** (مثل: "تعبئة الزجاجات"، وليس "التعبئة")
- الموردون والعملاء: **كيانات حقيقية** وليست أقساماً داخلية
- المدخلات والمخرجات: **مخرجات ملموسة**، وليست أنشطة
- يجب أن يتناسب SIPOC مع **صفحة واحدة**

---

### 4. ترجمة صوت العميل بشكل صحيح

```
تعليق العميل  →  احتياج العميل  →  CTQ (متطلب قابل للقياس)
"الزجاجات تتسرب"  →  سلامة الإغلاق  →  معدل فشل الإغلاق ≤ 0.1%
"التسليم متأخر"   →  التوريد في الوقت  →  تنفيذ الطلبات ≥ 95% في الوقت
"الكميات خاطئة"  →  دقة الطلب  →  معدل تنفيذ الطلب ≥ 99%
```

**قواعد CTQs الجيدة:**
- كل CTQ يجب أن يحتوي على **حد مواصفات** (LSL أو USL أو قيمة هدف)
- يجب أن تكون CTQs **قابلة للقياس** بالبيانات الموجودة أو القابلة للجمع
- تحقق من CTQs مع العملاء الفعليين، وليس الافتراضات الداخلية

---

### 5. إدارة أصحاب المصلحة

| الربع | القوة | الاهتمام | الاستراتيجية |
|-------|-------|----------|-------------|
| **إدارة عن كثب** | عالية | عالية | تحديثات منتظمة، إشراك في القرارات |
| **إبقاء راضياً** | عالية | منخفضة | إحاطات دورية، لا مفاجآت |
| **إبقاء مُطَّلعاً** | منخفضة | عالية | مشاركة التقدم، جمع الملاحظات |
| **مراقبة** | منخفضة | منخفضة | تواصل محدود |

---

### 6. الأخطاء الشائعة التي يجب تجنبها

| الخطأ | لماذا يُعدّ مشكلة | التصحيح |
|-------|-------------------|---------|
| القفز إلى الحلول في مرحلة التعريف | يتجاوز تحليل السبب الجذري بالكامل | ركّز على تعريف المشكلة فقط |
| بيان مشكلة مبهم | لا يمكن قياسه أو التحقق منه | قيّم كل عنصر بأرقام حقيقية |
| تجاهل صوت العميل | تصبح CTQs افتراضات داخلية | تحقق دائماً من بيانات العملاء الحقيقية |
| نطاق مشروع واسع جداً | المشروع لا ينتهي أبداً | استخدم IS/IS NOT لتحديد الحدود |
| تجاهل أصحاب المصلحة | المقاومة تُفشل التنفيذ | رسم جميع أصحاب المصلحة والتفاعل معهم مبكراً |
| الخلط بين المشكلة والسبب | يؤدي إلى حلول خاطئة | المشكلة = ما يحدث؛ السبب = لماذا |
| لا قياس للحالة الراهنة | لا يمكن إثبات التحسين لاحقاً | تحديد مقاييس الحالة الراهنة في مرحلة التعريف |

---

## قائمة تحقق مرحلة التعريف

قبل الانتقال إلى مرحلة القياس، تحقق من اكتمال جميع البنود:

- [ ] وثيقة المشروع موقّعة من الراعي
- [ ] بيان المشكلة مُقيَّم بالأرقام (الحالة الراهنة بالأرقام)
- [ ] بيان الهدف يحتوي على هدف محدد وقابل للقياس
- [ ] حدود نطاق المشروع (IS / IS NOT) محددة
- [ ] SIPOC يغطي جميع العمليات الفرعية للإنتاج
- [ ] تم جمع 5 تعليقات على الأقل من العملاء الحقيقيين
- [ ] كل تعليق عميل مُترجَم إلى CTQ مع حدود المواصفات
- [ ] جميع أصحاب المصلحة الرئيسيين محددون ومُرسَمون على شبكة القوة/الاهتمام
- [ ] خطة التواصل محددة مع التكرار والقنوات
- [ ] أدوار ومسؤوليات الفريق مُعيَّنة (Champion، BB، GB، أعضاء الفريق)
- [ ] الجدول الزمني للمشروع والمعالم متفق عليها

---

## دليل مرجعي للأدوات

| الأداة | متى تُستخدم | الوقت المطلوب | الصعوبة |
|--------|------------|--------------|---------|
| **وثيقة المشروع** | بداية المشروع | 2-4 ساعات | متوسطة |
| **تحليل IS/IS NOT** | تحديد نطاق المشكلة | 1-2 ساعة | منخفضة |
| **SIPOC** | فهم حدود العملية | 2-3 ساعات | منخفضة |
| **جمع VOC** | فهم احتياجات العملاء | 1-2 أسبوع | متوسطة |
| **نموذج Kano** | تحديد أولويات CTQs | 2-4 ساعات | متوسطة |
| **خريطة أصحاب المصلحة** | تحديد من يتأثر | 1-2 ساعة | منخفضة |
| **مصفوفة RACI** | تحديد أدوار الفريق | 1 ساعة | منخفضة |

---

*Part of the [Bottling Company DMAIC Project](https://github.com/Mesharymn/Bottling-Company-DMAIC-Project)*

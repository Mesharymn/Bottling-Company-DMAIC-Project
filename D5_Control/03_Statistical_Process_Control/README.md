# 03 — Statistical Process Control (SPC)
## Water Bottling Company | Control Phase

> **Purpose:** To monitor the stability of the improved process over time using statistical charts, distinguishing between common cause variation (normal) and special cause variation (abnormal).

---

## Control Charts Implemented

We use SPC charts to track our two most critical metrics continuously:

### 1. P-Chart (Proportion Defective)
- **Metric:** Capping defect rate.
- **Data Source:** Daily defect counts from the Smart Torque Sensor.
- **UCL (Upper Control Limit):** Calculated based on the new baseline established during the Pilot phase.
- **Rule:** Any point above the UCL triggers the out-of-control response plan.

### 2. X-bar & R Chart (Continuous Data)
- **Metric:** Changeover Time.
- **Data Source:** Stopwatch times for each SKU changeover.
- **Purpose:** To ensure the SMED process remains stable and the variation between different setup crews remains low.

*(Charts and datasets will be stored in this folder).*

---
---

# 03 — التحكم الإحصائي للعمليات (SPC)
## شركة تعبئة المياه | مرحلة التحكم

> **الغرض:** مراقبة استقرار العملية المحسنة بمرور الوقت باستخدام لوحات إحصائية، والتمييز بين تباين الأسباب الشائعة (الطبيعي) وتباين الأسباب الخاصة (غير الطبيعي).

---

## لوحات التحكم المطبقة

نستخدم لوحات التحكم الإحصائي لتتبع أهم مقياسين لدينا بشكل مستمر:

### 1. لوحة P (نسبة المعيب)
- **المقياس:** معدل عيوب التغطية.
- **مصدر البيانات:** إحصاء العيوب اليومي من مستشعر العزم الذكي.
- **الحد الأعلى للتحكم (UCL):** يُحسب بناءً على خط الأساس الجديد الذي تم تحديده خلال التجربة التجريبية.
- **القاعدة:** أي نقطة تتجاوز الحد الأعلى للتحكم تطلق خطة الاستجابة للخروج عن السيطرة.

### 2. لوحة X-bar & R (البيانات المستمرة)
- **المقياس:** وقت التحويل.
- **مصدر البيانات:** أوقات ساعة الإيقاف لكل تحويل بين وحدات المنتج.
- **الغرض:** ضمان بقاء عملية تقليل وقت تغيير القوالب مستقرة، وبقاء التباين بين أطقم الإعداد المختلفة منخفضاً.

*(سيتم حفظ اللوحات ومجموعات البيانات في هذا المجلد).*

---
*Part of the [Bottling Company 6S Project](https://github.com/Mesharymn/Bottling-Company-6S-Project)*

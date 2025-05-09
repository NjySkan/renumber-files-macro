# Renumber Files Module - EslamHub
مرحبًا بكم في مستودع Renumber Files من قناة EslamHub! 🚀
يحتوي هذا المستودع على ملف Excel لإعادة تسمية أرقام ملفات مجلد بسهولة وسرعة باستخدام VBA،
بالإضافة إلى ملفين نصيين يحتويان على أكواد VBA المستخدمة في الملف.

## المحتويات
- 📊 **RenumberFiles.xlsm**: ملف Excel جاهز لإعادة تسمية الملفات.
- 🧾 **Workbook_Open-Event.txt**: كود حدث فتح الملف (الحدث `Workbook_Open` داخل ThisWorkbook).
- 🧾 **RenumberFiles-Module.txt**: الكود الرئيسي لإعادة الترقيم (Module مستقل داخل Excel).

## تعليمات الاستخدام

### 🔁 التشغيل التلقائي
لتفعيل التشغيل التلقائي عند فتح الملف، افتح حدث `Workbook_Open` داخل نافذة ThisWorkbook،  
أو ملف `Workbook_Open-Event.txt`، وابحث عن السطر:
```vba
#If False Then
```
ثم غيّر الكلمة `False` إلى `True` ليصبح السطر:
```vba
#If True Then
```
بعد انتهاء التشغيل، ستظهر لك رسالة تتيح لك اختيار فتح الملف أو الإغلاق.

### ✂️ تخصيص الفاصل
لتغيير الفاصل (مثل `_`) قبل الترقيم، افتح ملف `RenumberFiles-Module.txt` أو موديول الكود داخل Excel،  
وابحث عن السطر:
```vba
Const del$ = "_"
```
ثم غيّر `_` إلى أي فاصل تريده مثل `-` أو `.`.

### 📁 اختيار المجلد
عند تشغيل الأداة، ستطلب منك اختيار المجلد. المسار الافتراضي هو نفس مسار ملف Excel.

### 🧮 إدخال البيانات
سيُطلب منك إدخال القيم التالية:
1. **رقم البداية**: بداية الترقيم.
2. **رقم النهاية**: نهاية الترقيم.
3. **تنسيق الأرقام**: عدد الأصفار (مثل 2 → 00، 3 → 000).
4. **مقدار التغيير**: مثل `+1`, `-2`, أو `0` إن كنت تريد التنسيق فقط.

## 🌐 تواصلوا معي
📺 [YouTube](https://www.youtube.com/@eslamhub)
📱 [TikTok](https://www.tiktok.com/@eslamhub)
📢 [LinkedIn](https://www.linkedin.com/in/eslamhub)
🐦 [X](https://x.com/eslamhub)
📘 [Facebook](https://www.facebook.com/eslamhub1)
📸 [Instagram](https://www.instagram.com/eslam.hub)

#Excel #VBA #EslamHub

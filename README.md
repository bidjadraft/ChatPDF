# كيفية البحث عن أي موضوع داخل ملفات pdf 


 
   # تحميل تطبيق ترمكس:


[![get it on F-Droid](https://i.imgur.com/G3wroE7.png)](https://f-droid.org/ar/packages/com.termux/)

[![Termux](https://i.imgur.com/TNdEio0.png)](https://play.google.com/store/apps/details?id=com.termux)

----

# تثبيت المكتبات
> [!Tip]
بعد تحميل و تثبيت التطبيق على جهازك تدخل إليه و تقوم بتثبيت المكتبات الضرورية التالية:

1. تثبيت مكتبة بايثون:
```shell
pkg install python
```


2. تثبيت مكتبة تلغرام و requests: 
```shell
pip install python-telegram-bot requests
```
---

# إنشاء سكربت
> [!Important]
بعد الإنتهاء من تثبيت المكتبات، تنشئ ملف جديد بامتداد py مثل `pdf.py`

1. و ذلك عبر كتابة الأمر التالي:
```shell
nano filename.py
```
> يمكنك تغيير الإسم filename إلى أي اسم آخر تريده بشرط أن ينتهي بـ `.py`
---
> [!Warning]
بعد كتابة الأمر `nano filename.py` سيتم فتح الملف عبر محرر النصوص للتعديل عليه


2. ستحتاج إلى نسخ سكربت بايثون تعثر عليه في خيار Relaeses أسفل الصفحة أو
[ اضغط هنا للإطلاع على احدث إصدار مباشرة](https://github.com/bidjadraft/ChatPDF/releases/tag/chatpdf)
---
3. قم بتحميل أحدث إصدار من ملف `ChatPDF.txt` ثم افتحه على أي برنامج ، انسخ كل محتواه و الصقه في محرر النصوص على ترمكس
---
4. بعدما تلصق السكربت في محرر النصوص على ترمكس تقوم بحفظ الملف `filename.py` و ذلك عبر الضغط على:
- `Cntrl` + `X` + `Y` + `Enter`

# تشغيل الكود

> [!Tip]
بعد حفظ ملف `filename.py`تقوم بتشغيله

1. و ذلك عبر كتابة الأمر التالي:
```shell
python filename.py
```


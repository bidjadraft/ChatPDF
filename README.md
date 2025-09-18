اريد مقال md في githuub ، يتناسب مع هذا :


كيفية البحث عن أي موضوع داخل ملفات pdf بدون الحاجة لقراءتها

• تحميل تطبيق Termux:
متوفر على متجر GooglePlay و F-Droid
————————————

بعد تحميل و تثبيت التطبيق على جهازك تدخل إليه و تقوم بتثبيت المكتبات الضرورية التالية:

• تثبيت مكتبة بايثون:
```shell
pkg install python```


• تثبيت مكتبة تلغرام و requests: 
```shell
pip install python-telegram-bot requests```


————————————

• بعد الإنتهاء من تثبيت المكتبات، تنشئ ملف جديد بامتداد py مثل (pdf.py) و ذلك عبر كتابة:
```shell
nano filename.py```

Filename = اكتب أي اسم للملف

• سيفتح معك محرر النصوص:
ستحتاج إلى سكربت بايثون و الذي ستعثر عليه في  حسابي Github  اضغط هنا

بعد الدخول لرابط المستودع تضغط على زر النسخ ثم تلصق الكود في محرر النصوص على Termux.

• لحفظ الملف Filename.py تضغط:
```json
"Cntrl" + "X" + "Y" + "Enter"```


• لتشغيل السكربت تكتب الأمر التالي:
```shell
python Filename.py```

————————————


بعد تشغيل السكربت سيطلب منك إدخال BOT TOKEN ، و هو رمز الوصول إلى بوت تلغرام، للحصول عليه تقوم بإنشاء بوت جديد:
@botfather → هذا البوت الرسمي من تلغرام لإنشاء البوتات، الأمر يشبه إنشاء قناة او مجموعة، لكن البوت يحتوي توكن  تحصل عليه بعد إنشاء البوت

بعدما تنسخ التوكن تلصقه في Termux ليقوم الكود بالتحقق من صحته، فإذا كان صالحا سيطلب منك إدخال رمز Gemini Api

• للحصول على مفتاح Gemini Api:
شرحت كيفية فعل ذلك في مقطع اضغط هنا
1. عبر AiStudio (سهلة): اضغط هنا
2. عبر  Cloud Console (صعبة): اضغط هنا

بعدما تحصل على مفتاح Gemini تلصقه في Termux للتحقق من صلاحيته، فإذا كان صالحا سيشتغل البوت


لن تضطر لكتابة هذه الأمور مجددا بل يتم حفظها في ملف txt لجعل العملية تلقائية و سريعة

• عندما ترغب في تشغيل الكود مجددا ستكتب فقط الامر:
```shell
python Filename.py```


• إذا أردت إيقاف الكود تضغط:
```json
"Cntrl" + "C"```



ضعه في مربع كوود جاهز

```md
# كيفية البحث عن أي موضوع داخل ملفات PDF بدون الحاجة لقراءتها

هذا الدليل يشرح كيفية إعداد بيئة تشغيل على Termux لإنشاء بوت تيليجرام يسمح بالبحث داخل ملفات PDF بشكل ذكي وسريع.

---

## تحميل تطبيق Termux

- يتوفر تطبيق Termux على متجر Google Play وF-Droid.
- قم بتحميل التطبيق وتثبيته على جهازك.

---

## تثبيت المكتبات الضرورية

بعد فتح Termux، قم بتنفيذ الأوامر التالية لتثبيت بايثون والمكتبات اللازمة:

```
pkg install python
pip install python-telegram-bot requests
```

---

## إنشاء ملف السكربت

1. لإنشاء ملف جديد بالاسم الذي تريده مع الامتداد `.py` مثل `pdf.py`، استخدم الأمر:

```
nano filename.py
```

*استبدل `filename` بأي اسم ترغب به.*

2. سيفتح محرر النصوص، قم بلصق كود السكربت الذي ستجده في حسابي على GitHub (رابط المستودع موجود في وصف المشروع).

3. لحفظ الملف والخروج اضغط:
```
Ctrl + X ثم Y ثم Enter
```

---

## تشغيل السكربت

لتشغيل السكربت استخدم الأمر:

```
python filename.py
```

---

## تفعيل البوت

- بعد تشغيل السكربت، سيطلب منك إدخال **BOT TOKEN** الخاص ببوت تيليجرام.
- لإنشاء بوت جديد والحصول على التوكن:
  - ابحث عن بوت @BotFather في التيليجرام.
  - اتبع التعليمات لإنشاء بوت جديد.
  - انسخ رمز التوكن والصقه في Termux.

- ثم سيطلب منك إدخال **مفتاح Gemini API** لاستخدام خدمات الذكاء الاصطناعي.
  - للحصول على مفتاح Gemini Api، اطلع على الشروحات المفصلة في قناتي (روابط الشرح مقدمة في المستودع).
  
- بعد التحقق من صحة الرمزين، سيبدأ البوت بالعمل.

---

## نصائح إضافية

- الرموز (Token وAPI Key) تحفظ تلقائياً في ملف نصي لتجنب إعادة إدخالها في كل مرة.
- لتشغيل السكربت مجدداً، فقط اكتب:

```
python filename.py
```

- لإيقاف التشغيل اضغط:

```
Ctrl + C
```

---

باستخدام هذه الخطوات، يمكنك بسهولة إعداد بوت تيليجرام للبحث داخل ملفات PDF بدون الحاجة لقراءة الملفات يدوياً، مما يسرع عملية البحث ويجعلها أكثر كفاءة.

---

للكود والمزيد من التفاصيل، الرجاء زيارة المستودع على GitHub:  
[رابط المستودع الخاص بي على GitHub](#)

---

استمتع بالتجربة وشاركنا أفكارك ومقترحاتك!
```

الاقتباسات:
[1] How do I sucessfully install python-telegram-bot into Termux? https://stackoverflow.com/questions/53486027/how-do-i-sucessfully-install-python-telegram-bot-into-termux
[2] How To Create A Telegram Bot With Python https://www.youtube.com/watch?v=NwBWW8cNCP4
[3] python-telegram-bot/python-telegram-bot: We have made ... https://github.com/python-telegram-bot/python-telegram-bot
[4] python-telegram-bot https://python-telegram-bot.org
[5] Termux Full Course = How To Create Telegram Bot https://www.youtube.com/watch?v=EU8xVpoI9mg
[6] How to Build AI Chatbots with Python in Termux https://devcommunity.io/terminaltools/how-to-build-ai-chatbots-with-python-in-termux-1f52
[7] MFarelS/telegram-bot: Termux Telegram Bot https://github.com/MFarelS/telegram-bot
[8] How to build and start telegram bot api local server ... https://www.pythonanywhere.com/forums/topic/33464/

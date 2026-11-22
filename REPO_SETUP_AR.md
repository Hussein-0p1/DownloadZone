# تجهيز مستودع DownloadZone — خطوات النشر (من الموبايل)

هذا المجلد عبارة عن ملفات تعريف ونشر فقط. **لا يحتوي على سورس التطبيق أو أسرار توقيعه**.

## الملفات
- `README.md` — واجهة المستودع العربية والإنجليزية وروابط التحميل
- `assets/downloadzone-app-icon.jpg` — الشعار الأصلي المستخرج من سورس v1.4.5
- `docs/index.html` — صفحة ويب ثنائية اللغة جاهزة لـGitHub Pages
- `docs/assets/downloadzone-icon.webp` — نسخة خفيفة من شعار التطبيق (الموقع يضم الشعار أيضاً داخله لضمان عرضه)
- `docs/.nojekyll` — ملف إعداد اختياري للنشر الثابت
- `.github/ISSUE_TEMPLATE/` — نماذج لتبليغ الأخطاء والاقتراحات

## المطلوب رفعه في GitHub
1. افتح `https://github.com/Hussein-0p1/DZM-Android-`.
2. بدّل محتوى `README.md` بمحتوى الملف الجديد، واحفظ Commit.
3. أضف الشعار `assets/downloadzone-app-icon.jpg` في مساره ثم أضف ملفات `docs/` بالمسارات نفسها. **لا ترفع ZIP باعتباره مشروعاً؛ GitHub لا يفك ضغطه تلقائياً.**
4. لإضافة ملف من المتصفح على الهاتف: افتح المستودع → Add file → Create new file؛ اكتب مساره مثل `docs/index.html`، ثم الصق المحتوى واحفظه. يمكن استخدام Upload files للشعار الثنائي.
5. لإضافة نماذج التبليغ، أنشئ كل مسار ضمن `.github/ISSUE_TEMPLATE/`.
6. اذهب إلى Settings → General → Repository name وغير الاسم إلى `DownloadZone`. GitHub عادةً يوجّه روابط المشروع القديمة للعنوان الجديد، لكن رابط GitHub Pages **لا يُعاد توجيهه تلقائياً**.
7. افتح صفحة المستودع وأضف Topics: `android`, `download-manager`, `kotlin`, `geckoview`, `video-downloader`, `adblock`, `hls`, `downloadzone`.
8. افتح Settings → Pages، وضع Source = **Deploy from a branch**، وBranch = **main**، وFolder = **/docs**، ثم Save.
9. بعد إنشاء الموقع وفحصه، يمكن إضافة رابط الموقع في خانة Website/About في المستودع.

## ملاحظات مهمة
- رابط APK المباشر في الملفات متجه إلى v1.4.5 الحالي، ورابط أحدث إصدار يتحدث تلقائياً إلى صفحة أحدث Release.
- بعد إعادة تسمية المستودع، الأفضل تحديث المسارات داخل `README.md` و`docs/index.html` من `DZM-Android-` إلى `DownloadZone` بدلاً من الاعتماد الدائم على إعادة توجيه GitHub.
- لم تُضف صور واجهات فعلية، لأن الملفات المتاحة تصاميم قديمة/مقترحات وليست صوراً موثّقة من APK النهائي. أضف صوراً حقيقية بعد التقاطها من نسخة v1.4.5.
- لم يتم تفعيل GitHub Pages أو تغيير اسم المستودع آلياً بسبب صلاحية GitHub المتاحة للقراءة فقط.

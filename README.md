# وثائق وصفحة هبوط تطبيق مَدَدْ (MDD Web & Documentation)

مشروع مستقل مخصص لصفحة الهبوط وسياسة الخصوصية وشروط الاستخدام لتطبيق **مَدَدْ للمحاسبة وإدارة الأعمال**.

---

## 📁 الهيكل البرمجي
```text
mdd-docs/
├── .firebaserc       # ملف تهيئة مشروع Firebase (mdd-net)
├── firebase.json     # إعدادات Firebase Hosting وقواعد إعادة التوجيه
├── README.md
└── public/
    ├── index.html    # الصفحة الرئيسية الرسمية لتطبيق مَدَدْ
    ├── privacy.html  # سياسة الخصوصية الرسمية المتوافقة مع متطلبات Google Limited Use
    └── terms.html    # شروط وأحكام الخدمة
```

---

## 🚀 النشر على Firebase Hosting (مجاناً وبشكل فوري)

المشروع جاهز للنشر على نطاق Google الرسمي:
- `https://mdd-net.web.app`
- `https://mdd-net.firebaseapp.com`

### خطوات النشر:
```bash
# 1. الانتقال لمجلد المشروع
cd /mnt/date/project/mdd-docs

# 2. تسجيل الدخول إلى Firebase (لمرة واحدة فقط)
npx -y firebase-tools@latest login

# 3. نشر الموقع
npx -y firebase-tools@latest deploy --only hosting
```

بمجرد اكتمال الأمر، يصبح الموقع حياً على:
- الصفحة الرئيسية: `https://mdd-net.web.app`
- سياسة الخصوصية: `https://mdd-net.web.app/privacy`
- شروط الاستخدام: `https://mdd-net.web.app/terms`


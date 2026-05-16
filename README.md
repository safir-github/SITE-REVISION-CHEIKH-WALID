# دروس الشيخ وليد البغدادي

موقع لعرض دروس وملاحظات الشيخ وليد البغدادي في العقيدة الإسلامية.

## 📚 الكتب المتوفرة حالياً

### 1. الأرجوزة الميئية
شرح الأرجوزة الميئية في العقيدة الإسلامية للإمام المجدد محمد بن عبد الوهاب رحمه الله.

### 2. القواعد الأربع
شرح القواعد الأربع في عقيدة أهل السنة والجماعة للإمام المجدد محمد بن عبد الوهاب رحمه الله.

## 🚀 التثبيت والتشغيل

### المتطلبات
- Node.js (الإصدار 18 أو أحدث)
- npm أو yarn أو pnpm

### التثبيت
```bash
npm install
```

### التشغيل
```bash
npm run dev
```

سيتم تشغيل الموقع على: `http://localhost:4321`

### البناء للإنتاج
```bash
npm run build
npm run preview
```

## 📁 هيكل المشروع

```
/
├── src/
│   ├── components/       # المكونات (Astro components)
│   │   ├── BookCard.astro
│   │   ├── LessonCard.astro
│   │   └── Breadcrumb.astro
│   ├── data/            # البيانات
│   │   └── books.ts     # بيانات الكتب والدروس
│   ├── layouts/         # القوالب
│   │   └── MainLayout.astro
│   └── pages/           # الصفحات
│       ├── index.astro
│       ├── 404.astro
│       └── book/
│           └── [id].astro
├── public/              # الملفات الثابتة
└── astro.config.mjs     # إعدادات Astro
```

## ➕ إضافة كتاب جديد

لإضافة كتاب جديد، قم بتعديل الملف `src/data/books.ts` وإضافة بيانات الكتاب الجديد:

```typescript
{
  id: "book-id",
  title: "Book Title",
  titleArabic: "عنوان الكتاب",
  description: "وصف الكتاب",
  lessons: [
    {
      id: "lesson-1",
      title: "عنوان الدرس",
      content: [
        "النقطة الأولى",
        "النقطة الثانية",
        // ...
      ],
      date: "2024-01-01" // اختياري
    },
    // ...
  ]
}
```

## 🎨 التخصيص

يمكنك تخصيص ألوان الموقع من خلال تعديل المتغيرات CSS في `src/layouts/MainLayout.astro`:

```css
:root {
  --primary-color: #1a5f3f;
  --secondary-color: #0d3d2a;
  --accent-color: #d4af37;
  --text-color: #2d2d2d;
  --light-bg: #f9f7f4;
  --white: #ffffff;
  --border-color: #e0ddd8;
}
```

## 🛠️ التقنيات المستخدمة

- [Astro](https://astro.build) - إطار عمل لبناء المواقع السريعة
- TypeScript - للكتابة الآمنة
- CSS - للتصميم

## 📄 الترخيص

جميع الحقوق محفوظة © 2024

## 🤝 المساهمة

لإضافة دروس أو تحسينات، يرجى:
1. تعديل ملف `src/data/books.ts`
2. إضافة الدروس الجديدة
3. حفظ التغييرات

---

صمم باستخدام ❤️ لطلاب العلم
# SITE-REVISION-CHEIKH-WALID

# 🎓 ADU Sertifikat Generator Pro (v3.0)

Andijon Davlat Universiteti (ADU) uchun maxsus ishlab chiqilgan, zamonaviy va modulli sertifikat generatsiya qilish tizimi. Ushbu platforma orqali bir necha soniya ichida yuzlab sertifikatlarni tayyorlash, chop etish va boshqarish mumkin.

## ✨ Xususiyatlari

-   **🚀 Ommaviy Yaratish (Batch Generation):** Excel (`.xlsx`) fayli orqali yuzlab talabalar uchun bir vaqtning o'zida sertifikatlar yaratish.
-   **⚠️ Aqlli Excel Deteksiyasi:** Excel fayli yuklanganda yetishmayotgan ustunlarni aniqlash va foydalanuvchini premium shakldagi modal oyna orqali ogohlantirish.
-   **🔍 QR-Kodli Tekshiruv:** Har bir sertifikatda avtomatik yaratiladigan QR-kod orqali hujjatning haqiqiyligini `verify.html` sahifasi orqali tekshirish imkoniyati.
-   **🎨 Moslashuvchan Dizayn:** 3 xil professional shablon (Klassik, Zamonaviy, Minimal) va Landscape/Portrait formatlari.
-   **🖱️ Drag-and-Drop:** Sertifikatdagi matn va elementlar o'rnini sichqoncha yordamida erkin surish (ALT tugmasi bilan).
-   **📥 Eksport Imkoniyatlari:**
    *   Sifatli PDF (A4 formatida).
    *   Barcha sertifikatlarni ZIP arxivda JPEG rasm ko'rinishida yuklab olish.
-   **💾 Qoralama Tizimi:** Kiritilgan barcha ma'lumotlarni `.adu` fayli sifatida saqlash va keyinchalik qayta yuklash.
-   **🖼️ Shaxsiy Aktivlar:** Tashkilot logotipi, muhr (seal), imzo va hatto har bir sertifikat uchun alohida orqa fon rasmlarini yuklash.
-   **🌙 Dark Mode:** Ko'zni charchatmaslik uchun tungi rejim.
-   **🌐 Ko'p tilli interfeys:** O'zbek, Rus va Ingliz tillari.

## 🏗️ Arxitektura (Modular JS)

Loyiha toza JavaScript (Vanilla JS) va modulli struktura asosida qurilgan:

```text
js/
├── core/
│   ├── dom.js      # Renderlash va vizual mantiq
│   ├── storage.js  # Fayllar va kesh bilan ishlash
│   └── drag.js     # Drag-and-Drop funksionalligi
├── features/
│   ├── export.js   # PDF va ZIP eksport xizmatlari
│   ├── xlsx.js     # Excel ma'lumotlarini qayta ishlash
│   ├── theme.js    # Dark/Light rejim boshqaruvi
│   └── feedback.js # Telegram Feedback vidjeti
└── utils/
    ├── i18n.js     # Tarjima bazasi
    └── toast.js    # Bildirishnomalar
```

## 🛠️ Texnologiyalar

-   **Frontend:** HTML5, Vanilla CSS, JavaScript (ES6+).
-   **Kutubxonalar:**
    *   `html2pdf.js` - PDF yaratish uchun.
    *   `JSZip` - ZIP arxivlash uchun.
    *   `html2canvas` - HTML elementlarni rasmga aylantirish uchun.
    *   `XLSX.js` - Excel fayllarni o'qish uchun.
    *   `QRious` - QR-kod generatsiyasi uchun.
-   **Backend (Optional):** Netlify Functions (Feedback yuborish uchun).

## 🚀 Ishga tushirish

1.  Repozitoriyani klonlang: `git clone https://github.com/rwbdevw/adu.git`
2.  `index.html` faylini brauzerda oching.
3.  Hech qanday server yoki o'rnatish talab qilinmaydi (Serverless).

---
*Created with ❤️ by [RWBDEV](https://github.com/CppRwbDev)*

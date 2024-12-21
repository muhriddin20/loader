# Loader Animation

Ushbu loyiha yuklash animatsiyasini yaratadi. Dinamik ravishda o'zgaruvchi foizlar (`percent`) va progress-bar orqali foydalanuvchi yuklash jarayonini vizual kuzatishi mumkin.

## Loyihaning asosiy vazifalari

1. **HTML:**
   - `<div class="wrapper">` ichida yuklash animatsiyasi yaratilgan.
   - `<h2 class="percent">` elementi yuklash foizlarini ko'rsatadi.
   - `<div class="progress-bar">` ichida progress-bar animatsiyasi qo'shilgan.

2. **CSS:**
   - Matn va progress-bar uchun dizayn yaratilgan.
   - Ranglar va o'lchamlar moslashtirilgan (`Roboto` shriftidan foydalanilgan).

3. **JavaScript:**
   - Progress-bar kengligi dinamik ravishda `style.width` orqali boshqariladi.
   - Yuklash foizi `percent.textContent` orqali yangilanadi.
   - Yuklash tugagach, animatsiya to'xtatiladi.

## Foydalanish

1. Loyiha fayllarini yuklab oling.
2. HTML faylini brauzerda oching.
3. Yuklash animatsiyasini kuzating.

## Loyihadan foydalanish bo'yicha ko'rsatmalar

- **CSS:** `style.css` fayli yuklash animatsiyasini estetik jihatdan yaxshilash uchun ishlatiladi.
- **JavaScript:** `script.js` fayli dinamik animatsiyalarni boshqaradi.

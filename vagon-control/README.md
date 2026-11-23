# VAGON CONTROL

Android ilovasi: ishchi vagon ma'lumotlarini kiritadi, boshliq jadval va turish vaqtlarini ko'radi.

## GitHub orqali APK yig'ish

1. Arxiv ichidagi `vagon-control` papkasi tarkibini GitHub repository asosiy katalogiga yuklang.
2. `.github/workflows/build-apk.yml` workflow avtomatik ishga tushadi (yoki Actions bo'limidan `VAGON CONTROL APK Build` ni qo'lda ishga tushiring).
3. Tugagach, workflow sahifasidagi Artifacts bo'limidan `vagon-control-apk` ni yuklab oling.

## Kirish

- Oddiy foydalanuvchi: ro'yxatdan o'tish va login/parol orqali kiradi.
- Birinchi marta lavozim tanlangach, akkaunt uchun lavozim saqlanadi; keyingi kirishlarda boshqa lavozim tanlab bo'lmaydi.
- Ishchi va boshliq ekranlarida Profil tugmasi bor.
- Administrator demo kirishi: login `admin`, parol `VagonAdmin2026`.

**Xavfsizlik eslatmasi:** administrator paroli hozircha ilova ichida demo uchun yozilgan. Ilovani haqiqiy ish jarayoniga chiqarishdan oldin uni o'zgartirish va server tomonda autentifikatsiya qo'shish kerak.

**Ma'lumotlar:** ushbu loyiha hozircha Android qurilmaning lokal xotirasidan foydalanadi. Turli telefonlardagi foydalanuvchilar ma'lumotini umumiy ko'rish uchun Firebase yoki boshqa server bazasi alohida ulanadi.

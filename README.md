# VAGON CONTROL

Temir yo'l vagonlarini hisobga olish Android ilovasi (Kotlin + Jetpack Compose).

## GitHub orqali APK olish
1. Shu papkadagi hamma fayllarni (`.github` papkasi bilan) repozitoriyga yuklang.
2. GitHub'da **Actions** bo'limiga kiring — "APK yig'ish" avtomatik ishga tushadi (taxminan 5–8 daqiqa).
3. Tugagach, ish ichidagi **Artifacts → vagon-control-apk** ni yuklab oling, zip ichida `app-debug.apk` bo'ladi.
4. Telefonga o'rnatishda "noma'lum manbalardan o'rnatish"ga ruxsat bering.

## Ekranlar
- Kirish / ro'yxatdan o'tish (+998 telefon, login, parol, parolni takrorlash)
- Lavozim tanlash: Ishchi (chapda), Boshliq (o'ngda)
- Ishchi: 11 ta maydonli forma (sana va vaqt qo'lda yoki 📅 / 🕒 orqali)
- Boshliq: avtomatik jadval + turgan vaqt (kirib kelgan → jo'nash)

Ma'lumotlar hozircha telefonning o'zida saqlanadi.


## Yangi imkoniyatlar
- Ishchi yoki boshliq rolini bir marta tanlagach, rol akkauntga biriktiriladi. Ishchi ilova ichidan boshliq paneliga o'ta olmaydi.
- Ishchi va boshliq ekranlarida Profile tugmasi mavjud.
- Profil oynasida login, telefon va lavozim ko'rsatiladi.
- Administrator paneli foydalanuvchilar va vagonlar sonini hamda ro'yxatdan o'tgan akkauntlarni ko'rsatadi.
- Qo'shimcha sahifa animatsiyalari va rol tugmalarida harakat animatsiyasi mavjud.

## Administrator kirishi
- Login: `admin`
- Parol: `VagonAdmin2026!`

Eslatma: bu demo versiyada foydalanuvchi va vagon ma'lumotlari shu qurilmaning SharedPreferences xotirasida saqlanadi. Turli telefonlar orasida sinxronlash uchun server/Firebase ulanishi alohida kerak.

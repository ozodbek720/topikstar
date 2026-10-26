Topik Star ⭐
Koreys tilini o'rganish uchun zamonaviy ilova — Vue 3 + Vite + Capacitor asosida.

Xususiyatlar
🎨 To'q shisha (glassmorphism) dizayn — zamonaviy va chiroyli interfeys
✨ Animatsiyali splash screen — ilovaga kirishda "Topik Star" logotipi animatsiya bilan chiqadi
📱 Mobil ilova — Capacitor yordamida Android/iOS ilovasiga aylantirish mumkin
📲 PWA — Progressive Web App, brauzerda ilova sifatida o'rnatish mumkin
❤️ Yuraklar tizimi — Test boshlash uchun yurak kerak, har 24 soatda to'ldiriladi
🏪 Do'kon — Ballar uchun yurak sotib olish mumkin
🔊 TTS — Koreys tilida eshitish funksiyasi
🔍 Qidiruv — Barcha bo'limlarda qidiruv
Asosiy bo'limlar
🏠 Asosiy — Tezkor havolalar, qidiruv va bosh sahifa
📝 TOPIK — TOPIK I va TOPIK II imtihonlariga tayyorgarlik
📚 Kutubxona — Lug'at, grammatika, yozish mashqlari va PDF kitoblar
👤 Profil — Shaxsiy ma'lumotlar, statistika va sozlamalar
Ishga tushirish
npm install
npm run dev
Brauzerda http://localhost:5173/ manzilini oching.

Build qilish
npm run build
Build natijasi dist papkasiga saqlanadi.

Android ilovasi
# 1. Build qilish
npm run build

# 2. Capacitor sync
npx cap sync android

# 3. Android Studio da ochish
npx cap open android

# 4. Android Studio da: Build → Build Bundle(s) / APK(s) → Build APK(s)
Yoki to'g'ridan-to'g'ri:

npm run cap:build:android
npm run cap:open:android
iOS ilovasi
npm run cap:build:ios
npm run cap:open:ios
Google Play ga joylash
Play Console da developer hisobi oching (https://play.google.com/console)
Yangi loyiha yarating
Signed APK / AAB yarating:
Android Studio da: Build → Generate Signed Bundle / APK
Android App Bundle (.aab) tanlang
Loyiha ma'lumotlarini to'ldiring:
Ilova nomi: "Topik Star"
Tavsif: "Koreys tilini o'rganish va TOPIK imtihoniga tayyorgarik"
Tillar: O'zbek, Koreys, Ingliz
Rasmlar: Screenshotlar va ikonka
AAB faylni yuklang
Review va publish qiling
App Store ga joylash (iOS)
Apple Developer hisobi (https://developer.apple.com)
Xcode da loyihani oching
Archive qiling va App Store Connect ga yuklang
PWA sifatida ishlatish
Ilovani brauzerda ilova sifatida o'rnatish mumkin:

Android: Chrome → Menyu → "Ilovani o'rnatish"
iOS: Safari → Share → "Bosh ekranga qo'shish"
Vercel da host qilish
npm install -g vercel
vercel login
vercel deploy
Texnologiyalar
Vue 3 — Frontend framework
Vite — Tezkor build tool
Capacitor — Native mobil ilova
PWA — Progressive Web App
Web Speech API — TTS (Text-to-Speech)
CSS Glassmorphism — Shisha dizayn effekti
Vercel — Web hosting

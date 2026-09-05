KASMU - CAPACITOR APK PROJECT
=============================

Icon APK sudah disiapkan di:
resources/icon.png

Untuk memasang icon tersebut ke Android APK:

1. Install Node.js LTS.
2. Buka terminal di folder project ini.
3. Jalankan:
   npm install
   npx cap add android
   npx @capacitor/assets generate --android
   npx cap sync
   npx cap open android

4. Di Android Studio pilih:
   Build > Build Bundle(s) / APK(s) > Build APK(s)

APK debug biasanya berada di:
android/app/build/outputs/apk/debug/app-debug.apk

App ID: com.kasmu.app
Nama aplikasi: Kasmu

CATATAN:
- File resources/icon.png adalah icon Kasmu versi terang yang dipilih.
- Perintah @capacitor/assets akan membuat berbagai ukuran icon Android otomatis.
- Kalau folder android sudah pernah dibuat sebelumnya, jalankan kembali:
  npx @capacitor/assets generate --android
  npx cap sync

WEB APP:
File website berada di www/index.html.
Ganti file tersebut dengan HTML Kasmu lengkap milikmu sebelum build APK jika versi lengkap belum dimasukkan.

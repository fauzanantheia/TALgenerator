# The Antheia Label Generator

Generator mockup kemasan dan apparel (box, food packaging, pouch, tote bag, t-shirt, vest, manta charm) dengan editor 2D, tampilan 2D realistic, dan 3D.

- **Aplikasi Android (APK):** dibuat otomatis oleh workflow *Build Android APK* (tab **Actions** › run terbaru › **Artifacts** › `antheia-label-apk`).
- **Website:** dipublikasikan oleh workflow *Publish website* ke GitHub Pages.
- **Akun & penyimpanan:** Firebase (paket gratis Spark). Setiap akun hanya bisa membuka desainnya sendiri.

Semua file aplikasi sengaja diletakkan di folder utama. Workflow akan menyusunnya ke folder yang dibutuhkan saat build.
Pengaturan Firebase ada di `firebase-config.js`, dan aturan keamanan database ada di `firestore.rules`.

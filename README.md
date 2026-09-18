# ADLYSIGN POS PRO — Upload 1 ZIP → Build APK

Cara penggunaan dari HP Android:

1. Buat repository GitHub baru.
2. Upload `project.zip` ke repository.
3. Upload folder `.github/workflows/build-apk-from-zip.yml` juga.
4. Commit changes.
5. Buka **Actions**.
6. Pilih **Build APK from ZIP**.
7. Tekan **Run workflow**.
8. Tunggu sampai selesai.
9. Buka workflow yang berhasil.
10. Di bagian **Artifacts**, download `ADLYSIGN-POS-PRO-APK`.
11. Ekstrak artifact dan install `app-debug.apk`.

PENTING:
- File project harus tetap bernama `project.zip`.
- Workflow ini dibuat agar Anda tidak perlu meng-upload isi folder project satu per satu.
- APK yang dihasilkan adalah debug APK untuk pengujian/instalasi.

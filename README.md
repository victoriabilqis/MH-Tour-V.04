# MH Tour V8.0.4 Android

Native Android Gradle project for MH Tour.

## Struktur
- `app/` modul aplikasi Android
- `app/src/main/` source dan resource Android
- `gradle/wrapper/` konfigurasi Gradle Wrapper
- `gradlew` dan `gradlew.bat` launcher
- `.github/workflows/build-apk.yml` build APK GitHub Actions

## Build APK
GitHub Actions menggunakan Java 17 + Gradle 8.10.2 dan menjalankan `assembleDebug`.
APK debug ditandatangani otomatis dan dapat dipasang langsung untuk pengujian.

## Instal di HP Android
Setelah workflow berhasil, buka Summary -> Artifacts -> `MH-Tour-V8.0.4-Android-Install`,
download ZIP artifact, ekstrak, lalu pasang file `.apk` di dalamnya.
Jangan memasang ZIP project.

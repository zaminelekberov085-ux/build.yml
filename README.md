# Abituriyent Panel — Android (Capacitor)

## APK necə düzəldilir

### Yol 1 — GitHub (kompüterdə heç nə quraşdırmadan)
1. Bu qovluğu GitHub-da yeni repozitoriyaya yüklə.
2. Actions bölməsində "Build APK" işə düşəcək.
3. Bitəndə "abituriyent-panel-apk" faylını yüklə → telefona at → quraşdır.

### Yol 2 — Android Studio
1. Android Studio-da `android` qovluğunu aç.
2. Build > Build Bundle(s)/APK(s) > Build APK(s).

## Tətbiqi yeniləmək
`www/index.html` faylını dəyiş, sonra `npx cap sync android`.

Bildiriş icazələri (bildiriş, titrəyiş, dəqiq alarm) manifestə əlavə olunub.

# Первые Фото

Приложение Android для пакетного нанесения встроенного логотипа «Движения Первых» на фотографии. Работает без сети. Выбор до 10 снимков, настройки масштаба, прозрачности и отступов, сохранение копий в `Pictures/PervyePhoto`.

## APK

Откройте вкладку **Actions** → **Build Android APK** → последний успешный запуск → **Artifacts** → `PervyePhoto-debug-APK`. Распакуйте ZIP и установите APK. Debug APK предназначен для тестирования, не для публикации в магазине.

## Разработка

Java / Android SDK, Gradle 8.9, Android Gradle Plugin 8.7.3, minSdk 29. Исходники находятся в `app/src/main`. Логотип — `app/src/main/assets/logo.png`.

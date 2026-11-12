Svenska Vocab Pro 2 — Android-проєкт

Що це:
- Офлайн Android-застосунок на базі наданого HTML.
- JavaScript і DOM Storage увімкнені; localStorage зберігає прогрес на пристрої.
- Інтернет-дозволи не потрібні.

Як зібрати APK:
1. Встановіть Android Studio (версія з підтримкою Android Gradle Plugin 8.7.3).
2. Відкрийте цю папку як Existing Project.
3. Дочекайтеся Gradle Sync та встановлення Android SDK Platform 35.
4. Build → Build Bundle(s) / APK(s) → Build APK(s).
5. APK буде в app/build/outputs/apk/debug/app-debug.apk.

Примітка:
Це вихідний Android-проєкт, а не готовий APK. У середовищі створення немає Android SDK/Gradle,
тому скомпілювати та перевірити APK тут неможливо.

БуКлік — Android WebView wrapper for https://www.buclick.com.ua

В этом архиве — готовый Android Studio проект с:
- Splash screen (white background)
- WebView loading https://www.buclick.com.ua
- GitHub Actions workflow to build APK (see .github/workflows)

ВАЖНО: Я включил в проект placeholder-иконку.
Чтобы использовать ваш реальный логотип (https://www.buclick.com.ua/media/logo/default/logo_BuClick_1.png) как иконку приложения и splash-лого,
пожалуйста, выполните после распаковки (или сделайте это в репозитории перед сборкой):

1) Скачайте логотип по адресу:
   https://www.buclick.com.ua/media/logo/default/logo_BuClick_1.png

2) Поместите файл в проект как:
   app/src/main/res/drawable/splash_logo.png
   app/src/main/res/mipmap-mdpi/ic_launcher.png
   app/src/main/res/mipmap-hdpi/ic_launcher.png
   app/src/main/res/mipmap-xhdpi/ic_launcher.png
   app/src/main/res/mipmap-anydpi-v26/ic_launcher.xml (for adaptive icon - you can keep xml and reference drawable)

3) Коммит и пуш в GitHub -> GitHub Actions соберёт APK автоматически (workflow уже включён).

Как собрать локально в Android Studio:
- Откройте проект, дождитесь синхронизации Gradle.
- Build -> Build Bundle(s) / APK(s) -> Build APK(s).
- APK окажется в app/build/outputs/apk/debug/app-debug.apk

Если вы хотите, я могу автоматически вставить логотип в проект — загрузите файл логотипа прямо в чат, и я пересоздам архив с логотипом включённым.

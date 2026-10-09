# Рабочий против капиталиста

## Скачать игру

| Устройство | Скачать |
|---|---|
| Windows 64-bit | [Скачать для Windows](https://github.com/Darmen-maker2023/worker-vs-capitalist/releases/download/v1.0.0/WorkerVsCapitalist-win32-x64.rar) |
| Android | [Скачать APK для Android](https://github.com/Darmen-maker2023/worker-vs-capitalist/releases/download/v1.0.0/WorkerVsCapitalist-android-debug.apk) |

[Открыть страницу релиза](https://github.com/Darmen-maker2023/worker-vs-capitalist/releases/tag/v1.0.0)

## Установка

- **Windows:** распакуй архив и запусти `WorkerVsCapitalist.exe`.
- **Android:** скачай APK, открой его на телефоне и подтверди установку.

## Сборка Android-версии

Нужны JDK 17 и Android SDK Platform 35. Собери APK командой:

```sh
gradle assembleDebug
```

Готовый файл появится в `app/build/outputs/apk/debug/app-debug.apk`. GitHub Actions также собирает APK после каждого push и pull request.

Android-приложение работает локально и не запрашивает доступ к интернету. В репозитории лежит подписанный debug APK; для публикации в Google Play потребуется release-подпись.

# Обновления DQ06

APK нашего лаунчера и профиль Obtainium. Исходники разработки остаются в закрытом репозитории.

- [APK лаунчера](https://github.com/Cheviiot/dq06-updates/releases/latest)
- [Профиль Obtainium](https://raw.githubusercontent.com/Cheviiot/dq06-updates/main/obtainium-dq06.json)
- [Импортировать приложения в Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium%3A%2F%2Fapps%2F%255B%257B%2522id%2522%253A%2522io.lift.app%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fliftapp.ink%252F%2522%252C%2522author%2522%253A%2522Lift%2522%252C%2522name%2522%253A%2522Lift%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522customLinkFilterRegex%255C%2522%253A%255C%2522app_last%255C%2522%252C%255C%2522defaultPseudoVersioningMethod%255C%2522%253A%255C%2522partialAPKHash%255C%2522%252C%255C%2522exemptFromBackgroundUpdates%255C%2522%253Afalse%252C%255C%2522versionDetection%255C%2522%253Afalse%257D%2522%257D%252C%257B%2522id%2522%253A%2522ru.cheviiot.dq06.home%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252FCheviiot%252Fdq06-updates%2522%252C%2522author%2522%253A%2522Cheviiot%2522%252C%2522name%2522%253A%2522DQ06%2520Home%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522apkFilterRegEx%255C%2522%253A%255C%2522%255EDQ06Home%255C%255C%255C%255C.apk%2524%255C%2522%252C%255C%2522versionExtractionRegEx%255C%2522%253A%255C%2522launcher-v%2528%255B0-9%255D%252B%255C%255C%255C%255C.%255B0-9%255D%252B%255C%255C%255C%255C.%255B0-9%255D%252B%2529%255C%2522%252C%255C%2522matchGroupToUse%255C%2522%253A%255C%25221%255C%2522%252C%255C%2522exemptFromBackgroundUpdates%255C%2522%253Afalse%252C%255C%2522versionDetection%255C%2522%253Atrue%257D%2522%257D%255D)

Профиль добавляет DQ06 Home из этого репозитория и Lift с официального сайта. YouTube обновляется через Google Play, RuStore сохраняет свой механизм обновления. Obtainium сам добавляет свой источник GitHub.

Чтобы передать новый список приложений на ТВ, обновите JSON и импортируйте его в Obtainium. Импорт по ссылке требует подтверждения на ТВ. Постоянной синхронизации списка с репозиторием нет.

Не удаляйте установленный лаунчер при обновлении: следующие APK должны иметь тот же ключ подписи. Встроенная проверка обновлений работает по расписанию Android; бесшумная установка зависит от установщика и совместимости приложения.

Проверено для текущего APK: 316 тестов, lint без ошибок, подпись и скачивание опубликованного файла. Проверка загрузки прошивки и работы пульта на реальной DQ06 ещё не выполнена.

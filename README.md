# RoboCam HTML5 Client

**RoboCam-HTML5-Client** is the HTML5 (Construct 2) web client for **RoboCam**: it displays the camera stream served by the Android app over Wi-Fi and sends control commands to the robot. The Android server application lives in a separate repository: **RoboCam**.

---

HTML5-клиент RoboCam, написанный в Construct 2: показывает поток с камеры, который раздаёт Android-приложение по Wi-Fi, и передаёт команды управления роботу.

- **Управление.** Два виртуальных джойстика, режим «правша/левша», смена джойстиков, управление стрелками и физической клавиатурой.
- **Баннеры.** Отображение баннеров, которые раздаёт сервер.
- **Полный экран.** Кнопка полноэкранного режима.
- **Соединение.** Ошибка отображается, когда соединение разорвано сервером.

## Проект

Репозиторий содержит проект Construct 2 (`RoboCam.caproj`): макет, листы событий и анимации джойстиков. Клиент открывается в Construct 2, собранный HTML5-экспорт раздаётся Android-приложением (сервером) по Wi-Fi.

## Ссылки

- Android-приложение (сервер): [RoboCam](https://github.com/zMotoR/RoboCam)
- Статьи о RoboCam: [proghouse.ru/tags/robocam](http://www.proghouse.ru/tags/robocam)

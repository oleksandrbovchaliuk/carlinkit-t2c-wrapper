# carlinkit-t2c-wrapper

**[English](#english) · [Українська](#українська)**

---

## English

A single-file wrapper that fixes the stretched or cropped CarPlay picture of the **Carlinkit T2C** adapter (`tespush.com`) in the Tesla browser, with an on-screen settings panel.

### Features

- Settings panel (⚙︎ button in the top-right corner)
- Page size presented to the adapter: 1280×720, 1600×900, 1920×1080, 2560×1440 or custom
- Fit modes: stretch, keep proportions (letterbox), fill
- Zoom slider (60–120%)
- "Restart" button that reconnects the stream without reloading the page
- The ⚙︎ button can be hidden; open settings by adding `#settings` to the URL
- Settings are saved in the browser and in the URL, so you can bookmark different setups

### Usage

1. Connect the Tesla to the adapter's Wi-Fi (`AutoKit-xxxx`) as usual.
2. Open `https://oleksandrbovchaliuk.github.io/carlinkit-t2c-wrapper/` in the Tesla browser instead of `tespush.com`.
3. Bookmark it.

URL parameters: `w`, `h` (page size), `fit` (`stretch` | `contain` | `cover`), `zoom` (60–120), `gear` (`1` | `0`).
Example: `?w=1920&h=1080&fit=contain&zoom=100`

### Notes

- The car needs internet access to load this page. The CarPlay video stream itself stays on the adapter's local Wi-Fi.
- The wrapper only changes the frame's size and position. It cannot make CarPlay icons smaller if the adapter outputs 720p.
- Unofficial project, not affiliated with Carlinkit or Tesla. Use at your own risk and don't adjust settings while driving.

---

## Українська

Однофайлова обгортка, яка виправляє розтягнуту або обрізану картинку CarPlay з адаптера **Carlinkit T2C** (`tespush.com`) у браузері Тесли. Має панель налаштувань просто на екрані.

### Можливості

- Панель налаштувань (кнопка ⚙︎ у правому верхньому куті)
- Розмір сторінки для адаптера: 1280×720, 1600×900, 1920×1080, 2560×1440 або власний
- Режими вписування: розтягнути, пропорційно (з чорними смугами), заповнити
- Повзунок масштабу (60–120%)
- Кнопка «Перезапустити» перепідключає потік без перезавантаження сторінки
- Кнопку ⚙︎ можна сховати, тоді налаштування відкриваються, якщо додати до адреси `#settings`
- Налаштування зберігаються в браузері та в адресі, тож можна зробити кілька закладок під різні режими

### Як користуватися

1. Підключіть Теслу до Wi-Fi адаптера (`AutoKit-xxxx`), як зазвичай.
2. Відкрийте в браузері Тесли `https://oleksandrbovchaliuk.github.io/carlinkit-t2c-wrapper/` замість `tespush.com`.
3. Додайте сторінку в закладки.

Параметри адреси: `w`, `h` (розмір сторінки), `fit` (`stretch` | `contain` | `cover`), `zoom` (60–120), `gear` (`1` | `0`).
Приклад: `?w=1920&h=1080&fit=contain&zoom=100`

### Примітки

- Щоб завантажити цю сторінку, авто потрібен інтернет. Сам відеопотік CarPlay йде через локальний Wi-Fi адаптера.
- Обгортка змінює лише розмір і положення кадру. Зробити іконки CarPlay дрібнішими, якщо адаптер віддає 720p, вона не може.
- Неофіційний проєкт, не пов'язаний з Carlinkit чи Tesla. Використовуйте на власний ризик і не змінюйте налаштування під час руху.

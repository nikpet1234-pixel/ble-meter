BLE METER PWA
=============

Готов инсталируем Android PWA вариант.

ВАЖНО:
PWA + Web Bluetooth трябва да се отворят през HTTPS.
Не използвай file:// за инсталиране.

Качи ЦЯЛАТА папка BLE_METER_PWA на статичен HTTPS хостинг:
- GitHub Pages
- Cloudflare Pages
- Netlify
- собствен HTTPS web server

Структура:
  index.html
  manifest.webmanifest
  sw.js
  icons/icon-192.png
  icons/icon-512.png

Инсталиране:
1. Отвори HTTPS адреса с Google Chrome на Android.
2. Натисни „Инсталирай приложението“, ако се появи,
   или Chrome меню → Install app / Add to Home screen.
3. На началния екран ще се появи икона „BLE Meter“.
4. След инсталиране приложението се стартира като standalone app.

След първото зареждане интерфейсът се кешира offline.
Интернет не е нужен за самата BLE връзка.

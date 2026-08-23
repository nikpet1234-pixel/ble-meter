BLE METER - ICON FIX

Замени в GitHub repository следните файлове:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

Добави новия файл:
- icon-maskable-512.png

След commit изчакай GitHub Pages да се redeploy-не.

НА ТЕЛЕФОНА:
1. Деинсталирай старата BLE Meter икона/app.
2. Chrome -> Settings -> Site settings -> All sites
3. Намери nikpet1234-pixel.github.io и изчисти stored data/cache.
4. Отвори отново:
   https://nikpet1234-pixel.github.io/ble-meter/
5. Refresh веднъж.
6. Install app / Инсталирай приложението.

Това е необходимо, защото Android/Chrome обикновено не сменя launcher иконата
на вече инсталирано PWA само след промяна на manifest-а.

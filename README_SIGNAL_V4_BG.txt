BLE METER PWA - SIGNAL V4
==========================

Добавено:
- LINK индикатор 0..4 чертички за FLUKE.
- LINK индикатор 0..4 чертички за OWON.
- GOOD / OK / WEAK / POOR / NO DATA.
- RSSI в dBm, когато Chrome/Android предоставя advertisement RSSI.
- RSSI остава "— dBm", когато Web Bluetooth не го предоставя.
- LINK индикаторът работи винаги и се изчислява от реалния поток BLE notifications.
- PWA cache version v4.

Какво да замениш в GitHub:
1. index.html
2. sw.js

Останалите файлове може да останат същите.
ZIP-ът съдържа целия комплект за удобство.

След Commit:
1. Изчакай GitHub Pages deployment.
2. На телефона отвори BLE Meter.
3. Refresh или затвори/отвори приложението.
4. Ако старата версия остава кеширана:
   Chrome -> Site settings -> nikpet1234-pixel.github.io -> Clear data
   и отвори сайта отново.

LINK логика:
4 = GOOD
3 = OK
2 = WEAK
1 = POOR
0 = NO DATA

Това НЕ е измислен RSSI. LINK оценява действителната редовност на BLE notifications.

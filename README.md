# Visual Studio Code extension for ESP8266/ESP32 File System (SPIFFS/LITTLEFS)

> **Note by InnuendoPi:** This is a test fork. Please use original repository: <https://github.com/kash4kev/vscode-esp8266fs>

Added: Littlefs pack, unpack, list, visualize and upload (only tested with ESP8266!)

Follow these steps to install:

- Install Visual code plugin ESP8266FS normally
- Close Visual Code app
- Open file explorer and navigate to Visual Code plugin directory (e.g. %userprofile%/.vscode/extensions )
- navigate into directory kash4kev.vscode-esp8266fs-1.<x.x>
- rename esp8266fs.js to esp8266fs.ori
- rename package.json to package.ori
- copy esp8266fs.js and package.json from repositroy into ESP8266FS extension folder
- start Visual code

New keywords:
esp8266fs.mklittlefs.debugLevel
esp8266fs.mklittlefs.executable e.g. "c:/arduino/tools/mklittlefs.exe"
esp8266fs.littlefsImage e.g. "(path)/(Name).mklittlefs.bin"
esp8266fs.mklittlefs.allFiles

mklittlefs.exe <https://github.com/earlephilhower/mklittlefs>

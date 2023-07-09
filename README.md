### ⚠️ Note: this repo isn't actively maintained. Head over to https://github.com/m5stack/M5Unified to get official support for esp-idf
# M5Stack Arduino core for ESP-IDF 4.0

This repo contains an "hello world" project acting as a temporary workaround for using the M5Stack in an Arduino fashion, on ESP-IDF v4.0 (possibly up, but untested).
Will become useless as soon as the folks @M5Stack will update their framework for IDF accordingly, but until then someone could make use out of it.

## Installation

- Download and install [esp-idf](https://github.com/espressif/esp-idf)
- Clone this repo

    ```bash
    git clone --recursive https://github.com/DonBrus/M5Stack-IDF-4.0.git

- Everything should be already working as ```idf.py menuconfig``` goes
- Try compiling and flashing with ```idf.py build flash -p <COMPORT>```

# M5Stack Arduino core for ESP-IDF 4.0

This repo contains an "hello world" project acting as a temporary workaround for using the M5Stack in an Arduino fashion, on ESP-IDF v4.0 (possibly up, but untested).
Will become useless as soon as the folks @M5Stack will update their framework for IDF accordingly, but until then someone could make use out of it.

## Installation

- Download and install [esp-idf](https://github.com/espressif/esp-idf)
- Clone this repo

    ```bash
    git clone https://github.com/DonBrus/M5Stack-IDF-4.0.git M5IDF4 && \
    cd components/arduino && \
    git submodule update --init --recursive && \
    cd .. && \
    cd M5Stack && \
    git submodule update --init --recursive && \

- Everything should be already working as ```idf.py menuconfig``` goes
- Try compiling and flashing with ```idf.py build flash -p <COMPORT>```
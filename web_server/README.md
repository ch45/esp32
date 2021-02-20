# Simple ESP32 Web Server

Borrowed from https://github.com/espressif/esp-idf/tree/master/examples/protocols/http_server/file_serving

## Features

* Add Support for more MIME types based upon the file extension

# Original README Extract

## Note

`/index.html` and `/favicon.ico` can be overridden by uploading files with same pathname to SPIFFS.

## Usage

* Open the project configuration menu (`idf.py menuconfig`) go to `Example Configuration` ->
    1. WIFI SSID: WIFI network to which your PC is also connected to.
    2. WIFI Password: WIFI password


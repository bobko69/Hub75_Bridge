# Open-source notices

The HUB75 Bridge firmware is not open source, but it is built with the open-source software listed below. We thank their authors. Each part is used under its own license; the full license texts are in the [licenses](./licenses/) folder.

| Software | Used for | Copyright | License |
| --- | --- | --- | --- |
| [ESP-IDF](https://github.com/espressif/esp-idf) | Espressif's framework the firmware is built on | Espressif Systems (Shanghai) Co., Ltd. | [Apache 2.0](./licenses/Apache-2.0.txt) |
| [mDNS](https://github.com/espressif/esp-protocols/tree/master/components/mdns) | the board's *name*.local address | Espressif Systems (Shanghai) Co., Ltd. | [Apache 2.0](./licenses/Apache-2.0.txt) |
| [FreeRTOS](https://www.freertos.org/) (part of ESP-IDF) | task scheduling | Amazon.com, Inc. or its affiliates | [MIT](./licenses/FreeRTOS-MIT.txt) |
| [lwIP](https://savannah.nongnu.org/projects/lwip/) (part of ESP-IDF) | the network stack | Swedish Institute of Computer Science | [BSD](./licenses/lwIP-BSD.txt) |
| [Mbed TLS](https://github.com/Mbed-TLS/mbedtls) (part of ESP-IDF) | checksums and crypto routines | ARM Limited and the Mbed TLS contributors | [Apache 2.0](./licenses/Apache-2.0.txt) |
| [Picolibc](https://keithp.com/picolibc/) and [Newlib](https://sourceware.org/newlib/) (part of ESP-IDF) | the C library | various, see the license files | BSD-style: [Picolibc](./licenses/picolibc.txt), [Newlib](./licenses/newlib.txt) |
| [TLSF allocator](https://github.com/espressif/tlsf) (part of ESP-IDF) | memory allocation | Matthew Conte | [BSD 3-Clause](https://spdx.org/licenses/BSD-3-Clause.html) |
| [HTTP Parser](https://github.com/nodejs/http-parser) (part of ESP-IDF) | the web pages | Igor Sysoev; Joyent, Inc. and other Node contributors | [MIT](./licenses/http_parser-MIT.txt) |
| [HAGL](https://github.com/tuupola/hagl) | drawing the demos | Mika Tuupola | [MIT](./licenses/hagl-MIT.txt) |
| [TJpgDec](http://elm-chan.org/fsw/tjpgd/) (part of HAGL) | JPEG decoding | ChaN | [TJpgDec license](./licenses/TJpgDec.txt) |
| [daisyUI](https://daisyui.com/) 5.7.47 | the look of the web pages | Pouya Saadeghi | [MIT](./licenses/daisyUI-MIT.txt) |
| [X11 misc-fixed font](https://www.cl.cam.ac.uk/~mgk25/ucs-fonts.html) | the text in the demos | | Public domain |

ESP-IDF's own list of the third-party software it contains is in its [Copyrights and Licenses](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/COPYRIGHT.html) page.

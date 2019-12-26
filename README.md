# m5stack-freertos-blinky

LED blink demo for Amazon FreeRTOS on M5Stack

Requir ESP-IDF development environment.

see https://qiita.com/fukuebiz/items/54f765d12c084ceea392 (japanese)



### Run

Check out this repo.

```
git clone https://github.com/fukuen/m5stack-freertos-blinky --recursive
```

Build (Windows example)

```
cmake -DCMAKE_TOOLCHAIN_FILE=amazon-freertos/tools/cmake/toolchains/xtensa-esp32.cmake -GNinja -S . -B build
cd build
ninja
```

Flash and monitor

```
idf.py flash monitor
```


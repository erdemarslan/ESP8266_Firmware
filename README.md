# ESP8266_Firmware
Firmware for ESP8266.

#### esptool.py kurulumu
`pip install esptool`

#### ESP üzerindeki herşeyi siler...
`esptool.py --port COM3 erase_flash`

#### ESP8266 Wemos D1 Mini Arduino Yazılımını flashlama...
`esptool.py --port COM3 --baud 1000000 write_flash --flash_size=4MB -fm dio 0 esp8266-v47-D1Mini-4M.bin`

#### ESP8266 Wemos D1 Mini MicroPython Yazılımını flashlama...
`esptool.py --port COM3 --baud 1000000 write_flash --flash_size=4MB -fm dio 0 esp8266-20220618-v1.19.1.bin`

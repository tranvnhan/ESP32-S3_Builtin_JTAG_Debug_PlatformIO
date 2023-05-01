# ESP32-S3_Builtin_JTAG_Debug_PlatformIO

Both JTAG and USB Serial need to be connected to computer.
- JTAG can be used for flashing/debugging
- USB Serial can be used for flashing/UART communication, e.g. print statements

ESP32-S3/C3 have builtin USB Serial/JTAG interface. No external hardware debugger is required.
Other ESP32 chips will need to use an external hardware debugger, e.g. ESP-Prog. More info:

https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/api-guides/usb-serial-jtag-console.html


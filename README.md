For more infos, LCD useful parameters can be found in:
https://github.com/espressif/esp-idf/blob/master/examples/peripherals/lcd/spi_lcd_touch/main/spi_lcd_touch_example_main.c

LCD driver = ILI9341

This app searches for an AP which SSID starts with "MY_AP" and displays its SSID and MAC address on the display, as well as the device type: R0, R1, R2L, or R2S. (device type is found in the ssid).

The ssid has the following format: MY_APP-DEVICE_TYPE-MAC_ADDR (example: MY_APP-R0-24EC4A9BD6B)


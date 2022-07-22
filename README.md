# DuinoMiner-ESP32

Fork of Duino-Coin for ESP32 (https://github.com/revoxhere/duino-coin/tree/master/ESP32_Code)

Includes the PlatformIO project with the following improvements:
+ Added WiFi provisioning
+ Added web settings
+ Added web OTA update
+ Added default IoT info with last IP part (as temperature) and WiFi signal strength (as humidity)

Instructions:
+ Flash with current project your erased ESP32 MCU.
+ For WiFi provisioning and configure connection to your router, connect to the created AP "ESP32-<autoid>" and use default password: "password". Then goes to menu and add new WiFi SSID connection.
+ Remember to also configure Duino-Coin settings as your user account, etc.

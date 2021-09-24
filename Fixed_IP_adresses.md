Config for my esp boards/device.

# Gosund power plugs:
  name: ps##
  Platform: ESPhome
  Board: ESP8266

| # | Brand | Model | IP Address | Device name | WiFi Network | DNS name |
| --- | --- | --- | --- | --- | --- | --- |
|  | gosund | SP-1 | 192.168.1.41 | ps01 | Mevius domotica | ps01.daarle |
|  | gosund | SP-1 | 192.168.1.42 | ps02 | Mevius domotica | ps02.daarle |
|  | gosund | SP-1 | 192.168.1.43 | ps03 | Mevius domotica | ps03.daarle |
|  | gosund | SP-1 | 192.168.1.44 | ps04 | Mevius domotica | ps04.daarle |
|  | gosund | SP-1 | 192.168.1.45 | ps05 | Mevius domotica | ps05.daarle |
|  | gosund | SP-1 | 192.168.1.46 | ps06 | Mevius domotica | ps06.daarle |
|  | gosund | SP-1 | 192.168.1.47 | ps07 | Mevius domotica | ps07.daarle |
|  | gosund | SP-1 | 192.168.1.48 | ps08 | Mevius domotica | ps08.daarle |
|  | gosund | SP-1 | 192.168.1.49 | ps09 | Mevius domotica | ps09.daarle |
|  | gosund | SP-1 | 192.168.1.50 | ps10 | Mevius domotica | ps10.daarle |
|  | gosund | SP-1 | 192.168.1.51 | ps11 | Mevius domotica | ps11.daarle |
|  | gosund | SP-1 | 192.168.1.52 | ps12 | Mevius domotica | ps12.daarle |
|  | gosund | SP-1 | 192.168.1.53 | ps13 | Mevius domotica | ps13.daarle |
|  | gosund | SP-1 | 192.168.1.54 | ps14 | Mevius domotica | ps14.daarle |
|  | gosund | SP-1 | 192.168.1.55 | ps15 | Mevius domotica | ps15.daarle |
|  | gosund | SP-1 | 192.168.1.56 | ps16 | Mevius domotica | ps16.daarle |

# Shelly:
  name: shelly##
  platform: ESPhome
  board: ESP8266

| # | Brand | Model | IP Address | Device name | WiFi Network | DNS name | shelly.click |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Shelly | 1 | 192.168.1.57 | shelly01 | Mevius domotica | shelly01.daarle | shelly1-E8DB84D373C5 |
|  | Shelly | 1 | 192.168.1.58 | shelly02 | Mevius domotica | shelly02.daarle | shelly1-E8DB84D43472 |
|  | Shelly | 1 | 192.168.1.59 | shelly03 | Mevius domotica | shelly03.daarle | shelly1-E8DB84D37834 |
|  | Shelly | 1 | 192.168.1.60 | shelly04 | Mevius domotica | shelly04.daarle | |

# QuinLED:
  name: QuinLED_
  platform: WLED
  board: QuinLED

| # | Brand | Model | IP Address | Device name | WiFi Network | DNS name |
| --- | --- | --- | --- | --- | --- | --- |
|  | QuinLED | Dig-Quad | 192.168.1.61 | DigQuad01 | Mevius domotica | digquad01.daarle |
|  | QuinLED | Dig-Uno | 192.168.1.62 | DigUno01 | Mevius domotica | diguno01.daarle |

# ESP32 for bluetooth connectivity:
  name: ESP32_##
  platform: ESPhome
  board: ESP32
| # | Brand | Model | IP Address | Device name | WiFi Network | DNS name |
| --- | --- | --- | --- | --- | --- | --- |
|  | Espressif | ESP32-WROOM-32D | 192.168.1.71 | ESP32_01 | Mevius domotica | ESP32_01.daarle |

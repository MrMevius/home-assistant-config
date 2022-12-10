Config for my esp boards/device.

# Gosund power plugs:
  name: ps##
  Platform: ESPhome
  Board: ESP8266

| # | Brand | Model | IP Address | Device name | DNS name | Useage | 
| --- | --- | --- | --- | --- | --- | --- |
|  | gosund | SP-1 | 192.168.1.41 | ps01 | ps01.daarle | Clothes dryer |
|  | gosund | SP-1 | 192.168.1.42 | ps02 | ps02.daarle | Dishwasher |
|  | gosund | SP-1 | 192.168.1.43 | ps03 | ps03.daarle | *On the shelf* |
|  | gosund | SP-1 | 192.168.1.44 | ps04 | ps04.daarle | Kitchen lights |
|  | gosund | SP-1 | 192.168.1.45 | ps05 | ps05.daarle | Washing machine |
|  | gosund | SP-1 | 192.168.1.46 | ps06 | ps06.daarle | Bathroom ventilation |
|  | gosund | SP-1 | 192.168.1.47 | ps07 | ps07.daarle | Humidifier |
|  | gosund | SP-1 | 192.168.1.48 | ps08 | ps08.daarle | Christmas tree |
|  | gosund | SP-1 | 192.168.1.49 | ps09 | ps09.daarle | Front door wreath |
|  | gosund | SP-1 | 192.168.1.50 | ps10 | ps10.daarle | Mantelpiece lights |
|  | gosund | SP-1 | 192.168.1.51 | ps11 | ps11.daarle | Windowsill lighting |
|  | gosund | SP-1 | 192.168.1.52 | ps12 | ps12.daarle | Pellet stove |
|  | gosund | SP-1 | 192.168.1.53 | ps13 | ps13.daarle | *On the shelf* |
|  | gosund | SP-1 | 192.168.1.54 | ps14 | ps14.daarle | *On the shelf* |
|  | gosund | SP-1 | 192.168.1.55 | ps15 | ps15.daarle | *On the shelf* |
|  | gosund | SP-1 | 192.168.1.56 | ps16 | ps16.daarle | *On the shelf* |

# Shelly:
  name: shelly##
  platform: ESPhome
  board: ESP8266

| # | Brand | Model | IP Address | Device name | DNS name | shelly.click | Useage |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Shelly | 1 | 192.168.1.57 | shelly01 | shelly01.daarle | shelly1-E8DB84D373C5 | Front door light |
|  | Shelly | 1 | 192.168.1.58 | shelly02 | shelly02.daarle | shelly1-E8DB84D43472 | Toliot light switch |
|  | Shelly | 1 | 192.168.1.59 | shelly03 | shelly03.daarle | shelly1-E8DB84D37834 | Bathroom light switch |
|  | Shelly | 1 | 192.168.1.60 | shelly04 | shelly04.daarle | | *On the shelf* |
|  | Shelly | 1 | 192.168.1.90 | shelly05 | shelly04.daarle | | *On the shelf* |

# QuinLED:
  name: QuinLED_
  platform: WLED
  board: QuinLED

| # | Brand | Model | IP Address | Device name | DNS name | Useage |
| --- | --- | --- | --- | --- | --- | --- |
|  | QuinLED | QuinLed-Dig-Quad | 192.168.1.61 | QuinLEDDigQuad01 | QuinLEDDigQuad01.daarle | Office Mark lights |
|  | QuinLED | Dig-Uno | 192.168.1.62 | DigUno01 | diguno01.daarle | *On the shelf* |
|  | QuinLED | QuinLED-Quad ESP32 | 192.168.1.63 | QuinLEDQuad01 | QuinLEDQuad01.daarle | Mantelpiece lights |
|  | QuinLED | QuinLED-Quad ESP32 | 192.168.1.64 | QuinLEDQuad02 | QuinLEDQuad02.daarle | Office Mark lights |
|  | QuinLED | QuinLED-Quad ESP32 | 192.168.1.65 | QuinLEDQuad03 | QuinLEDQuad03.daarle | *On the shelf* |

# ESP32 for bluetooth connectivity:
  name: ESP32_##
  platform: ESPhome
  board: ESP32
| # | Brand | Model | IP Address | Device name | DNS name | Useage |
| --- | --- | --- | --- | --- | --- | --- |
|  | Espressif | ESP32-WROOM-32D | 192.168.1.71 | ESP32_01 | ESP32_01.daarle | Living Room bluetooth connectivity |

# Broadlink RM4 pro for infrared / RF connectivity:
  name: Broadlink
  platform: /
  board: /
| # | Brand | Model | IP Address | Device name | DNS name | Useage |
| --- | --- | --- | --- | --- | --- | --- |
|  | Broadlink | RM4 pro | 192.168.1.80 | BroadlinkRM4pro | ESP32_01.daarle | Control pellet stove| |

# SmartGateways P1 to wifi gateway
  name: P1 energy reader
  platform: ESP
  board: ESP32
| # | Brand | Model | IP Address | Device name | DNS name | Useage |
| --- | --- | --- | --- | --- | --- | --- |
|  | Slimmelezer+ | DSMR P1 | 192.168.1.77 | Smille meter P1 reader | - | P1 energy reader| |

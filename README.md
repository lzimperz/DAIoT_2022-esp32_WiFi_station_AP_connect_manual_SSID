# Wi-Fi Station Example (conexión WiFi en modo estación a un AP)

Configurar los datos de la red WiFi en app_main.c con los siguientes defines que se
encuentran al inicio del archivo.

#define EXAMPLE_ESP_WIFI_SSID      "your_SSID"
#define EXAMPLE_ESP_WIFI_PASS      "your_SSID_PASSWORD"
#define EXAMPLE_ESP_MAXIMUM_RETRY  10


### Salida por consola

I (629) wifi station: ESP_WIFI_MODE_STA
I (649) wifi:wifi driver task: 3ffc0830, prio:23, stack:6656, core=0
I (649) system_api: Base MAC address is not set
I (649) system_api: read default base MAC address from EFUSE
I (679) wifi:wifi firmware version: 7679c42
I (679) wifi:wifi certification version: v7.0
I (679) wifi:config NVS flash: enabled
I (679) wifi:config nano formating: disabled
I (679) wifi:Init data frame dynamic rx buffer num: 32
I (689) wifi:Init management frame dynamic rx buffer num: 32
I (689) wifi:Init management short buffer num: 32
I (699) wifi:Init dynamic tx buffer num: 32
I (699) wifi:Init static rx buffer size: 1600
I (699) wifi:Init static rx buffer num: 10
I (709) wifi:Init dynamic rx buffer num: 32
I (709) wifi_init: rx ba win: 6
I (709) wifi_init: tcpip mbox: 32
I (719) wifi_init: udp mbox: 6
I (719) wifi_init: tcp mbox: 6
I (729) wifi_init: tcp tx win: 5744
I (729) wifi_init: tcp rx win: 5744
I (729) wifi_init: tcp mss: 1440
I (739) wifi_init: WiFi IRAM OP enabled
I (739) wifi_init: WiFi RX IRAM OP enabled
I (749) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (859) wifi:mode : sta (3c:71:bf:aa:65:5c)
I (859) wifi:enable tsf
I (859) wifi station: wifi_init_sta finished.
I (879) wifi:new:<3,1>, old:<1,0>, ap:<255,255>, sta:<3,1>, prof:1
I (879) wifi:state: init -> auth (b0)
I (909) wifi:state: auth -> assoc (0)
I (919) wifi:state: assoc -> run (10)
I (949) wifi:connected with Deconet, aid = 6, channel 3, 40U, bssid = da:06:c3:81:21:d0
I (949) wifi:security: WPA2-PSK, phy: bgn, rssi: -46
I (959) wifi:pm start, type: 1

I (979) wifi:AP's beacon interval = 102400 us, DTIM period = 1
W (989) wifi:<ba-add>idx:0 (ifx:0, da:06:c3:81:21:d0), tid:0, ssn:0, winSize:64
I (1629) esp_netif_handlers: sta ip: 192.168.68.59, mask: 255.255.252.0, gw: 192.168.68.1
I (1629) wifi station: got ip:192.168.68.59
I (1629) wifi station: connected to ap SSID:Deconet password:0103371183xx
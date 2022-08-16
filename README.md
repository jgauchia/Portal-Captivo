# Portal-Captivo
Portal Captivo para ESP32

SSID Portal captivo: ESP-WIFI-MANAGER
IP   Portal captivo: 192.168.4.1   

Los archivos contenidos en la carpeta DATA deben ser subidos al ESP (SPIFF),

Uso:

#include <WiFi_cfg.h>

WiFi_cfg wifi;

if(wifi.init()) 
{
  // INICIAR SERVIDOR WEB NORMAL
}
  else 
   wifi.wifimanager();

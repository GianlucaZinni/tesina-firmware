# Firmware del Transmisor

El firmware del collar transmisor se construye a partir del proyecto
[LoRa_APRS_Tracker](../../LoRa_APRS_Tracker). Ese repositorio ya incluye
soporte completo para la placa **Heltec Wireless Tracker** e incorpora las
rutinas de GPS, LoRa y gestión de energía necesarias para nuestro sistema.

## Compilación

1. Instalar [PlatformIO](https://platformio.org/install) en el entorno de
   desarrollo.
2. Desde la raíz del proyecto ejecutar:

   ```bash
   cd LoRa_APRS_Tracker
   pio run -e heltec_wireless_tracker
   ```

3. El binario generado en `.pio/build/heltec_wireless_tracker/` puede
   cargarse a la placa mediante `pio run -e heltec_wireless_tracker -t upload`.

El archivo `data/tracker_conf.json` dentro de `LoRa_APRS_Tracker` contiene la
configuración del transmisor (frecuencias, identificador, etc.).

# Tesina Firmware

Repositorio que contiene el desarrollo del firmware para el sistema de rastreo de ganado basado en placas Heltec.

## Estructura del proyecto

- **docs/** – Documentación general del proyecto.
- **data/** – Datos de prueba y archivos de configuración.
- **images/** – Recursos gráficos y diagramas.
- **extra/** – Material de referencia adicional.
- **tools/** – Scripts y utilidades de apoyo.
- **settings/** – Plantillas y ajustes de configuración.
- **firmware/** – Código fuente del firmware.
  - **transmitter/** – Proyecto PlatformIO para el transmisor (Heltec Wireless Tracker).
  - **receiver/** – Proyecto PlatformIO para el receptor (Heltec WiFi LoRa 32 V3/V3.2).

Cada subproyecto dentro de `firmware/` puede compilarse y cargarse de forma independiente sobre la placa correspondiente.

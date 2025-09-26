En este proyecto, emplearemos la ESP32 junto con el framework ESP-IDF para desarrollar un sistema capaz de predecir posibles precipitaciones en zonas vulnerables a deslizamientos, como la región de Sabana Centro en Cundinamarca.

## 📦 Recursos utilizadas

Este proyecto utiliza la librería **MPU6050** desarrollada por [Ailton Fidelix](https://github.com/AiltonFidelix/MPU6050), la libreria smbus y esp32-i2c-lcd1602 por [David Antliff](https://github.com/DavidAntliff). 
Adicionalmente contamos del apoyo de la pagina (https://medium.com/@fatehsali517/how-to-connect-esp32-to-wifi-using-esp-idf-iot-development-framework-d798dc89f0d6), que documenta el uso del modulo wifi de la esp32.


*Todos los créditos son para ellos por su excelente trabajo.*

### 🔧 Instalación

Para incluir la librería MPU6050 en tu proyecto, ejecuta el siguiente comando desde la carpeta `lib/`:

```bash
cd lib/ && git clone https://github.com/AiltonFidelix/MPU6050.git
```

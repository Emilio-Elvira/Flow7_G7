# Flow7_G7
Este repositorio contiene el ejercicio en el cual mandabamos los datos de los sensores por MQTT con el uso de Node-red.

Este ejercicio consiste en realizar una estación de clima que realice lo siguiente:
- Obtener información de temperatura y humedad relativa del sensor DHT11 con el micro controlador ESP32CAM
- Enviar los valores del sensor por MQTT de forma local en JSON, con el objetivo de enviar varias variables en el mismo mensaje
- Generar un Flow que obtenga por MQTT los valores enviados por el sensor y realice una gráfica del histórico y muestre indicadores de valores instantáneos
- Generar un flow, basado en el [Flow 5](https://github.com/Emilio-Elvira/flow-5-openweather-g7), el cual realice lo siguiente:
    - Obtener valores de temperatura, humedad relativa, Calidad del Aire, Indices Ultra Violeta por API de openweathermap.org
    - Graficar valores instantáneos e históricos de la ubicación actual en un dashboard
    - Suscribirse a un Broker MQTT público para poder obtener la información de datos climáticos de todos los alumnos del grupo 7
    - Reportar por MQTT los datos obtenidos por API para que puedan ser visualizados por el resto de los alumnos




## Modificiaciones a realizar

- Modificar coordenadas geográficas para obtener los datos climáticos por API
- Modificar la API Key para poder obtener la información de openweather.org
- Temas MQTT locales y públicos donde se reportan los datos obtenidos por API y por sensores

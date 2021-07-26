# node-red-object-pose-detection
Flujo de Node-RED que permite manipular la webcam del equipo para tomar una foto y luego procesarla con TensorFlow para detectar poses y con la API de Google Vision para detectar objetos. También se utiliza el servicio de traducción de Google para traducir al español los resultados entregados por la API de Google Vision. El manejo de la cámara y la presentación de los resultados se presentan en un dashboard.
![flow](../main/img/flow.png)
## Librerías
Para utilizar este flujo es necesario instalar las siguientes librerías de Node-RED:\
[node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)\
[node-red-node-ui-webcam](https://flows.nodered.org/node/node-red-node-ui-webcam)\
[node-red-contrib-image-output](https://flows.nodered.org/node/node-red-contrib-image-output)\
[node-red-contrib-tensorflow](https://flows.nodered.org/node/node-red-contrib-tensorflow)\
[node-red-contrib-google-cloud](https://flows.nodered.org/node/node-red-contrib-google-cloud)
## Configuración de Google Vision API
Para configurar el acceso a la API de Google Vision se recomienda seguir los pasos presentados el siguiente video tutorial:\
[![Google Cloud Vision API IMAGE ANALYSIS in Node-RED flow - Fullstack Dev Logs](https://img.youtube.com/vi/eaUBSNRKv1A/0.jpg)](https://www.youtube.com/watch?v=eaUBSNRKv1A)
## Resultados
![dashboard](../main/img/dashboard.png)

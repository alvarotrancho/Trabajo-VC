# Trabajo Final de VC

## Aplicación de Monitorización de Tráfico.

Hemos pensado hacer una aplicación de monitorización de tráfico usando Yolov8 y Python. Esta aplicación mostrará la dirección de los vehículos y contará las entradas y salidas de los mismos.
Para ello, nos basaremos en [práctica 5 de VC](https://github.com/EmilioDeniz/VC_P5) por lo que se empleará un environment de Anaconda con Python en su versión 3.9.5 con el fin de evitar incompatibilidades y errores.
El entorno fue creado de la siguiente manera:

```bash
conda create --name trabajo python=3.9.5
conda activate trabajo
pip install ultralytics
pip install lap
```
* El modelo de YOLO empleado identifica coches, autobuses, camiones y furgonetas, con diferentes variantes según el tamaño.
* Para controlar las entradas y salidas, se añadió un contador a una altura en pixeles determinada.

La aplicación mostrará algo similar a lo siguiente:

![Captura de pantalla 2024-01-12 162626](https://github.com/alvarotrancho/Trabajo-VC/assets/113598358/44b228cf-fe16-454d-9956-2bec187bed97)

Es importante crear una carpeta llamada "videos" en la carpeta del proyecto y dentro colocar el video para probar la aplicación. 

## Recursos empleados

Dataset Utilizado para el modelo: https://universe.roboflow.com/ilham-winar/venom

Video Utilizado: https://www.youtube.com/watch?v=wqctLW0Hb_0

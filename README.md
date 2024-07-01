# practicas_mlyrd
En este repositorio encontrarás algunas de las prácticas elaboradas durante mi estancia en la universidad relacionadas con Machine Learning y Redes Neuronales. Los archivos son los siguientes:

### **`Clasificador.ipynb`**:
El propósito de este archivo es implementar un sistema de detección de objetos en tiempo real utilizando una cámara web, el modelo preentrenado deeplabv3_resnet50 de PyTorch y la biblioteca OpenCV. El código captura frames de la cámara, preprocesa las imágenes, realiza inferencias con el modelo para detectar objetos y dibuja cuadros delimitadores alrededor de los objetos detectados en tiempo real, mostrando el resultado en una ventana de visualización. Además, permite salir del bucle de captura y procesamiento al presionar la tecla 'q'.

### **`Proyecto.ipynb`**:
Es un proyecto elaboradorado con el propósito de implementar un sistema de detección de intrusos en tiempo real utilizando una cámara web, el modelo preentrenado YOLOv5 de PyTorch, la biblioteca OpenCV para el procesamiento de imágenes, y Pygame para la reproducción de sonido de alarma. Además, envía notificaciones a través de Pushbullet cuando se detecta un intruso. El sistema captura frames de la cámara, procesa cada frame para detectar personas en la mitad izquierda del fotograma, dibuja rectángulos alrededor de los intrusos detectados, reproduce una alarma sonora y envía una notificación al celular.

### **`Yolo.ipynb`**:
El propósito de este archivo es implementar un sistema de detección de objetos en tiempo real utilizando una cámara web y el modelo preentrenado YOLOv5x de PyTorch. El código captura frames de la cámara, realiza detección de objetos en cada frame, dibuja cuadros delimitadores alrededor de los objetos detectados, y muestra los resultados en una ventana. El bucle de detección continúa hasta que se presiona la tecla 'q', momento en el cual se cierran la ventana de visualización y la cámara.

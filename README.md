# practicas_mlyrd
En este repositorio encontrarás algunas de las prácticas elaboradas durante mi estancia en la universidad relacionadas con Machine Learning y Redes Neuronales. A continuación una breve descripción de lo que hace cada uno de los archivos:

### **`Cancer.ipynb`**:
El propósito de este archivo es montar Google Drive en un entorno de Google Colab, cargar un archivo CSV de datos, preprocesar los datos, entrenar y evaluar un modelo de clasificación K-Nearest Neighbors (KNN) para diagnóstico médico, y analizar la precisión del modelo en función de diferentes características del conjunto de datos. Además, se muestra una matriz de confusión y se calcula la correlación de las características con el diagnóstico.

### **`Clasificador.ipynb`**:
El propósito de este archivo es implementar un sistema de detección de objetos en tiempo real utilizando una cámara web, el modelo preentrenado deeplabv3_resnet50 de PyTorch y la biblioteca OpenCV. El código captura frames de la cámara, preprocesa las imágenes, realiza inferencias con el modelo para detectar objetos y dibuja cuadros delimitadores alrededor de los objetos detectados en tiempo real, mostrando el resultado en una ventana de visualización. Además, permite salir del bucle de captura y procesamiento al presionar la tecla 'q'.

### **`KNN_Cancer.ipynb`**:
Este código preprocesa un conjunto de datos eliminando columnas innecesarias, mapeando valores de diagnóstico a números, y dividiendo los datos en características y etiquetas. Luego, itera sobre diferentes cantidades de características para entrenar un modelo de red neuronal, evaluando la pérdida en cada iteración y registrando los resultados, que finalmente se grafican.

### **`Limpieza_Manipulacion_de_Datos.ipynb`**:
Este archivo realiza el preprocesamiento de un conjunto de datos de un banco. Se cargan los datos desde Google Drive, se eliminan valores nulos y filas duplicadas, y se filtran registros basados en valores específicos de las columnas. Además, se realizan visualizaciones de datos numéricos y categóricos mediante diagramas de caja y gráficos de conteo. También se normalizan los valores de las columnas categóricas y se realizan reemplazos específicos para uniformizar los datos.

### **`Practica_Examen.ipynb`**:
El propósito de este archivo es crear y manipular un DataFrame de pandas para registrar y analizar datos de ventas de productos. Se inicializa un archivo CSV vacío, se recopilan datos de entrada para 10 productos, se calculan subtotales de ventas, se identifican los productos más vendidos y con el subtotal más bajo, y se actualiza el DataFrame con nuevos valores antes de guardar los resultados en el archivo CSV.

### **`Practicas2_1Parcial.ipynb`**:
Continuación de los ejercicos anteriores, se agregaron 38 ejercicios más, sobre manipulación y limpieza de datos, asi como diversos fundamentos básicos.

### **`Practicas_1Parcial.ipynb`**:
Este archivo contiene múltiples programas que realizan diversas tareas, son alrededor de 18 ejercicios que se solicitaron en clase de Machine Leraning y Redes Neuronales.

### **`Proyecto.ipynb`**:
Es un proyecto elaboradorado con el propósito de implementar un sistema de detección de intrusos en tiempo real utilizando una cámara web, el modelo preentrenado YOLOv5 de PyTorch, la biblioteca OpenCV para el procesamiento de imágenes, y Pygame para la reproducción de sonido de alarma. Además, envía notificaciones a través de Pushbullet cuando se detecta un intruso. El sistema captura frames de la cámara, procesa cada frame para detectar personas en la mitad izquierda del fotograma, dibuja rectángulos alrededor de los intrusos detectados, reproduce una alarma sonora y envía una notificación al celular.

### **`RedNeuronal_Cancer.ipynb`**:
Este archivo carga un archivo CSV desde Google Drive, lo preprocesa eliminando columnas innecesarias y mapeando valores de diagnóstico. Luego, divide los datos en conjuntos de entrenamiento y prueba, y define una red neuronal para clasificar los datos. La red se entrena durante 120 épocas, se registra la pérdida en cada época, y finalmente se evalúa la precisión del modelo en el conjunto de prueba.

### **`RedNeuronal_Iris.ipynb`**:
Este archivo carga el conjunto de datos de iris, lo divide en conjuntos de entrenamiento y prueba, y define una red neuronal para la clasificación con PyTorch. La red se entrena durante 20 épocas, registrando la pérdida en cada época. Finalmente, el modelo se evalúa en el conjunto de prueba y se imprime la precisión obtenida, que es del 96.67%.

### **`RedesNeuronales1.ipynb`**:
Este archivo define y entrena una red neuronal para clasificar dígitos en el conjunto de datos MNIST. Se configuran parámetros de entrenamiento, se define la arquitectura del modelo con tres capas totalmente conectadas y funciones de activación ReLU, y se cargan los datos de entrenamiento y prueba. Luego, se crea el modelo, se especifica la función de costo y el optimizador, y se entrena el modelo durante 10 épocas, registrando la pérdida y mostrando el progreso del entrenamiento.

### **`Tipos_de_datos.ipynb`**:
Este archivo muestra ejemplos de diferentes tipos de datos en Python: una lista, una tupla, y una cadena de caracteres, imprimiendo sus tipos. Además, define e imprime el tipo de un diccionario que contiene información personal, y un valor booleano.

### **`Yolo.ipynb`**:
El propósito de este archivo es implementar un sistema de detección de objetos en tiempo real utilizando una cámara web y el modelo preentrenado YOLOv5x de PyTorch. El código captura frames de la cámara, realiza detección de objetos en cada frame, dibuja cuadros delimitadores alrededor de los objetos detectados, y muestra los resultados en una ventana. El bucle de detección continúa hasta que se presiona la tecla 'q', momento en el cual se cierran la ventana de visualización y la cámara.

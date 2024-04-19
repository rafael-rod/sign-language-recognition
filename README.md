#English
## Hand Gesture Recognition Project
![test.png](https://github.com/rafael-rod/sign-language-recognition/blob/main/test.png)

---

This project aims to develop a hand gesture recognition system using the Python library OpenCV along with the `cvzone` library, which provides specific modules for hand tracking and gesture classification.

### Project Files:

1. **data_collection.py**: This script is used to collect training data for the classification model. It captures images from the camera in real-time and saves cropped images of hands with specific gestures into corresponding folders.

2. **testing.py**: This script implements the trained classification model to recognize hand gestures in real-time. It uses the pre-trained model loaded from an `.h5` file and the associated labels loaded from a `.txt` file to classify detected gestures in the camera video.

### Technologies Used:

- **OpenCV**: Computer vision library used for capturing camera video, image processing, and displaying visual results.

- **cvzone**: Library providing specialized modules for hand tracking and gesture classification.

- **NumPy**: Library for numerical operations on arrays, used in image processing.

- **Keras**: Deep learning framework used for training the classification model.

### Features:

- **data_collection.py**: Allows for the collection of training data by capturing images of hand gestures and storing them in labeled folders.

- **testing.py**: Implements real-time hand gesture recognition using the pre-trained classification model.

### Usage:

1. Run `data_collection.py` to collect training data. Press the "s" key to save cropped images of hands with specific gestures into the corresponding folders.

2. Run `testing.py` to start real-time hand gesture recognition.

### System Requirements:

- Python 3.x
- OpenCV
- cvzone
- NumPy
- Keras

### Additional Notes:

Ensure you have the pre-trained classification model (`keras_model.h5`) and the labels file (`labels.txt`) in the appropriate directory for the system to function correctly.

---
#Spanish
## Proyecto de Reconocimiento de Gestos Manuales

---

Este proyecto tiene como objetivo desarrollar un sistema de reconocimiento de gestos realizados con la mano utilizando la biblioteca de Python OpenCV junto con la biblioteca `cvzone`, que proporciona módulos específicos para el seguimiento de manos y la clasificación de gestos.

### Archivos del Proyecto:

1. **data_collection.py**: Este script se utiliza para recopilar datos de entrenamiento para el modelo de clasificación. Captura imágenes de la cámara en tiempo real y guarda las imágenes recortadas de las manos con gestos específicos en carpetas correspondientes.

2. **testing.py**: Este script implementa el modelo de clasificación entrenado para reconocer gestos de mano en tiempo real. Utiliza el modelo preentrenado cargado desde un archivo `.h5` y las etiquetas asociadas cargadas desde un archivo `.txt` para clasificar los gestos detectados en el video de la cámara.

### Tecnologías Utilizadas:

- **OpenCV**: Biblioteca de visión por computadora utilizada para capturar video de la cámara, procesar imágenes y mostrar resultados visuales.

- **cvzone**: Biblioteca que proporciona módulos especializados para el seguimiento de manos y la clasificación de gestos.

- **NumPy**: Biblioteca para operaciones numéricas en matrices, utilizada en el procesamiento de imágenes.

- **Keras**: Framework de aprendizaje profundo utilizado para entrenar el modelo de clasificación.

### Funcionalidades:

- **data_collection.py**: Permite la recopilación de datos de entrenamiento al capturar imágenes de gestos de mano y almacenarlas en carpetas etiquetadas.

- **testing.py**: Implementa el reconocimiento de gestos de mano en tiempo real utilizando el modelo de clasificación previamente entrenado.

### Uso:

1. Ejecutar `data_collection.py` para recopilar datos de entrenamiento. Presionar la tecla "s" para guardar las imágenes recortadas de las manos con gestos específicos en las carpetas correspondientes.

2. Ejecutar `testing.py` para iniciar el reconocimiento de gestos de mano en tiempo real.

### Requisitos del Sistema:

- Python 3.x
- OpenCV
- cvzone
- NumPy
- Keras

### Notas Adicionales:

Asegúrate de tener el modelo de clasificación preentrenado (`keras_model.h5`) y el archivo de etiquetas (`labels.txt`) en el directorio correspondiente para el correcto funcionamiento del sistema.

---

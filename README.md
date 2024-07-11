# Bug404

* Nombre del proyecto
    Emotion explorers

* Breve descripción del proyecto 
    Interfaz interactiva alimentada a través de una red neuronal de lectura de imágenes dirigida a niños en edad preescolar donde podrá enviar imágenes de emociones y a la vez, se les dará un feeback de cómo manejar dichas emociones, permitiendo así, la prevención de diversos casos de mal manejo de emociones.
    C:\Users\allye\OneDrive\Desktop\SIC-Hackaton\Bug404\image.png
    C:\Users\allye\OneDrive\Desktop\SIC-Hackaton\Bug404\image-1.png
    C:\Users\allye\OneDrive\Desktop\SIC-Hackaton\Bug404\image-2.png


* Arquitectura del proyecto + imagen
    El modelo es una red neuronal convolucional (CNN) que consta de múltiples capas convolucionales seguidas de capas de pooling para la reducción de dimensionalidad, capas de aplanado para convertir las salidas 3D a 1D, y capas densas para la salida final. La arquitectura está diseñada para procesar imágenes de entrada de 200x200 píxeles y producir una salida de 8 unidades con activación lineal, adecuada para tareas de regresión.


* Proceso de desarrollo:
    - Escogencia del dataset desde Kaggle
        URL: https://www.kaggle.com/datasets/mh0386/facial-emotion
    - Armado de la red neuronal convolucional
    - Alimentación del modelo con las imágenes del dataset.
    - Guardado del modelo en un archivo h5.
    - Creación de la interfaz.
    - Evaluación de las imágenes recibidas de acuerdo a lo que ya poseía el modelo.
    -Crear salida para el usuario.


-¿Qué modelo de Machine Learning están usando?
    Modelo Convolucional


-Métrica(s) de evaluación del modelo:
    Precisión y pérdida de datos

* Funcionalidades extra:
    Apoyo a psicológos para la detección temprana de problemas socioemocionales.


* Creación de la interfaz
- Herramientas utilizadas:
Tkinder
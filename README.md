# Clasificación de dígitos escritos a mano utilizando una red neuronal convolucional

## Descripción del Proyecto

Este proyecto implementa una red neuronal convolucional (CNN) para la clasificación de dígitos escritos a mano utilizando el conocido conjunto de datos MNIST. El conjunto de datos MNIST es un estándar en el campo del aprendizaje automático y contiene 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba de dígitos del 0 al 9.

### Objetivos del Proyecto

1. **Construcción del Modelo**: Implementar una CNN para la tarea de clasificación de imágenes.
2. **Preprocesamiento de Datos**: Realizar el preprocesamiento adecuado de las imágenes y las etiquetas para su uso en el modelo.
3. **Entrenamiento y Validación**: Entrenar el modelo utilizando los datos de entrenamiento y validar su rendimiento en los datos de prueba.
4. **Evaluación del Modelo**: Evaluar el rendimiento del modelo utilizando métricas como precisión, recall, F1-score y matriz de confusión.
5. **Predicción en Nuevas Imágenes**: Demostrar la capacidad del modelo para realizar predicciones en imágenes nuevas descargadas desde la web.

### Contenido del Notebook

- **Importación de Bibliotecas**: Importar las bibliotecas necesarias para la construcción y evaluación del modelo.
- **Carga y Visualización de Datos**: Cargar los datos de entrenamiento y prueba, y visualizar algunas imágenes.
- **Preprocesamiento de Datos**: Redimensionar y normalizar las imágenes, y convertir las etiquetas a formato one-hot.
- **Definición de la Arquitectura del Modelo**: Construir la CNN utilizando capas convolucionales, de pooling, de abandono (dropout), de aplanamiento (flatten) y densas.
- **Entrenamiento del Modelo**: Entrenar el modelo con los datos de entrenamiento y validar su rendimiento.
- **Visualización del Rendimiento**: Graficar las curvas de precisión y pérdida durante el entrenamiento y la validación.
- **Evaluación del Modelo**: Generar y visualizar la matriz de confusión y el reporte de clasificación.
- **Predicción en Nuevas Imágenes**: Descargar una imagen desde la web, preprocesarla y realizar la predicción con el modelo entrenado.

### Tecnologías Utilizadas

- **Python 3.x**: Lenguaje de programación principal.
- **TensorFlow y Keras**: Bibliotecas para construir y entrenar la red neuronal.
- **Matplotlib y Seaborn**: Bibliotecas para la visualización de datos.
- **NumPy**: Biblioteca para operaciones con arrays.
- **scikit-learn y scikit-plot**: Bibliotecas para evaluación del modelo.
- **Pillow (PIL)**: Biblioteca para manipulación de imágenes.
- **Requests**: Biblioteca para descargar imágenes desde la web.


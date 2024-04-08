## Alzheimer's Disease Diagnosis with Deep Learning
Project developed for the Data Science Bootcamp.

**Problem Statement**

Alzheimer’s disease is a neurodegenerative disorder and the most common form of dementia. Early detection and accurate diagnosis are crucial for effective intervention and improved quality of life for patients. Magnetic resonance imaging (MRI) is a key tool for diagnosing Alzheimer's disease and monitoring its progression. The objective of this project is to develop and evaluate a Deep Learning model capable of identifying distinctive patterns in MRI images, enabling discrimination between different stages of Alzheimer's patients.

**Content**

The dataset comprises MRI images from four classes:
  + Mild Demented
  + Moderate Demented
  + Non Demented
  + Very Mild Demented
These images are sourced from the Open Access Series of Imaging Studies (OASIS), a project aimed at making neuroimaging datasets freely available to the scientific community.

**Methodology**

1. Data Preparation
  + Import necessary libraries
  + Develop helper functions for preprocessing
  + Preprocess images for analysis
  + Visualize sample images
2. Model Comparison
  + Base model: Random Forest
  + Convolutional Neural Network (CNN) model
  + Transfer Learning with:
    - ResNet50
    - InceptionV3
    -	DenseNet169
    -	VGG16
  + Compare and summarize results to select the best-performing model for further tuning
3. Model Tuning
  + Fine-tuning the selected model
  + Implement data augmentation techniques to improve performance
4. Evaluation
  + Assess the performance of the tuned model on test images
5. Conclusions

**Repository directories:**

-	data_sample: contain train and test images
-	main:
  -	notebook_ML.ipynb: notebook containing the development of the project in English.
  -	notebook_ML_es.ipynb: notebook containing the development of the project in Spanish.
  -	All Models generated saved in h5 format.
  -	Metrics plots for all models in PDF.


______________Version española______________

## Diagnóstico de la Enfermedad de Alzheimer con Deep Learning

Proyecto realizado para el Bootcamp de Data Science.

**Planteamiento del problema**

La enfermedad de Alzheimer es un trastorno neurodegenerativo y la forma más común de demencia. La predicción precisa y el diagnóstico de la enfermedad de Alzheimer (EA) y su etapa prodromal, como el deterioro cognitivo leve, son esenciales para la detección temprana. Uno de los métodos clave para diagnosticar esta enfermedad y monitorear su progresión es a través de la resonancia magnética (RM), que proporciona información detallada sobre la estructura y función del cerebro.

El objetivo principal de esta investigación es desarrollar y evaluar un modelo de **Deep Learning** capaz de identificar patrones distintivos en imágenes de RM que permitan discriminar entre diferentes etapas de pacientes con Alzheimer. Esto podría tener un impacto significativo en la detección temprana de la enfermedad, facilitando así intervenciones más efectivas y mejorando la calidad de vida de los pacientes.

**Contenido**

Los datos consisten en imágenes de resonancia magnética (RM). Los datos tienen cuatro clases de imágenes tanto en el conjunto de entrenamiento como en el de pruebas:

- Demencia leve
- Demencia moderada
- No demente
- Demencia muy leve

Los conjuntos de datos se extraen del Proyecto de Series de Estudios de Imágenes de Acceso Abierto (OASIS, por sus siglas en inglés) (https://www.oasis-brains.org), que es un proyecto destinado a poner conjuntos de datos de neuroimagen del cerebro libremente disponibles para la comunidad científica.

**Metodología**

Se han seguido los siguientes pasos para preparar las imágenes para el análisis. Se ha desarrollado un modelo convolucional desde cero que se comparó con algunos modelos en los que se ha utilizado Transfer Learning. Para ello, se ha desarrollado un conjunto de funciones auxiliares para agilizar tareas para su uso repetido durante el análisis.

1. Preparación de datos
    + Importar bibliotecas
    + Construcción de funciones auxiliares
    + Preprocesamiento de imágenes para el análisis
    + Visualización de imágenes de muestra
    + Visualización de la proporción de clases
2. Comparación de modelos
    + Modelo base: Random Forest
    + Modelo convolucional simple (modelo CNN)
    + Transfer Learning:
        - ResNet50
        - InceptionV3
        - DenseNet169
        - VGG16
    + Resumen y conclusiones, seleccionar el mejor modelo para ajustar
3. Ajuste del modelo
    + Fine tuning
    + Aumento de datos (Data augmentation)
4. Evaluación del rendimiento en imágenes de prueba
5. Conclusiones

**Directorios del repositorio:**

- data_sample: contiene imágenes de entrenamiento y prueba
- main:
  - notebook_ML.ipynb: cuaderno que contiene el desarrollo del proyecto en inglés.
  - notebook_ML_es.ipynb: cuaderno que contiene el desarrollo del proyecto en español.
  - Todos los modelos generados guardados en formato h5.
  - Gráficos de las métricas para todos los modelos en PDF.

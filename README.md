# 🤖 TP1 - Inteligencia Artificial: Clasificación de Incidentes de Seguridad

Este proyecto contiene un análisis y modelado aplicado a un conjunto de datos de incidentes de ciberseguridad. Utilizamos una notebook de Google Colab para entrenar y evaluar un modelo de clasificación a partir de datos preprocesados utilizando Redes Neuronales Multicapa (MLP).

## 📁 Archivos del repositorio

- `TP1_IA.ipynb`: Notebook principal del proyecto, ejecutable en Google Colab.
- `df_preprocesado.csv`: Dataset preprocesado listo para ser utilizado en el análisis.
- `TP N°1 - Redes Neuronales.pdf`: Informe sobre el proyecto con una corrida de ejemplo.

## ▶️ Cómo ejecutar el proyecto en Google Colab

1. **Abrir la notebook en Colab**

   Hacé clic en el siguiente botón para abrir la notebook directamente en Google Colab:

   [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristianAndresHerrmann/TP-RedesNeuronales/blob/master/TP1_IA.ipynb)

2. **Cargar el archivo CSV**

   El archivo `df_preprocesado.csv` **no se carga automáticamente** desde GitHub. Debe ser descargado manualmente y subido al entorno de Colab.

   Descargá el archivo `df_preprocesado.csv` a tu computadora.

   En Colab, ejecutá la siguiente celda para subirlo al entorno:

   ```python
   from google.colab import files
   uploaded = files.upload()

# Proyecto de Clasificación y Generación de Dígitos en MNIST

Este proyecto se centra en la clasificación de dígitos manuscritos y la generación de nuevos dígitos utilizando un modelo basado en Naive Bayes. Utilizaremos la base de datos MNIST, que es un conjunto de datos ampliamente utilizado en el campo de la visión por computadora y el aprendizaje automático.

## Descripción

El proyecto se divide en dos partes principales:

1. **Clasificación de Dígitos:**
   - Cargamos la base de datos MNIST, que contiene imágenes de dígitos manuscritos (0 al 9).
   - Dividimos los datos en conjuntos de entrenamiento y prueba.
   - Entrenamos un modelo Naive Bayes (MultinomialNB) para clasificar los dígitos.
   - Evaluamos el desempeño del modelo en el conjunto de prueba y generamos informes de clasificación.

2. **Generación de Dígitos:**
   - Utilizamos el modelo entrenado para generar nuevos dígitos.
   - Creamos una imagen en blanco y negro y dibujamos un dígito en ella.
   - Utilizamos el modelo para predecir qué dígito se generó.

## Cómo Usar

1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com//JuanLara18/MNIST-Digit-Classifier-Generator.git
   cd TU_REPO
   ```

1. **Instalar Dependencias:**
Asegúrate de tener las bibliotecas necesarias instaladas. Puedes usar pip para instalarlas.
     ```bash
     pip install scikit-learn pillow
     ```

3. **Ejecutar el Código:**
Ejecuta el código principal para la clasificación y generación de dígitos.
     ```bash
     python main.py
     ```

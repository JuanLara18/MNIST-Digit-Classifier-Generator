# Clasificador y Generador de Dígitos MNIST

Este proyecto contiene un notebook de Jupyter que desarrolla un clasificador basado en Naive Bayes para la base de datos de dígitos escritos a mano MNIST y explora un enfoque básico para generar nuevos dígitos.

## Descripción

El proyecto consta de dos componentes principales:

1. **Clasificación**: Se implementa un modelo de Naive Bayes para clasificar dígitos escritos a mano, utilizando un subconjunto balanceado de la base de datos MNIST. El modelo proporciona probabilidades de pertenencia a cada clase de dígitos (0-9).

2. **Generación**: Se intenta un enfoque rudimentario para generar una imagen de dígito nuevo basado en las probabilidades aprendidas por el modelo de Naive Bayes, aunque Naive Bayes no es típicamente usado para generación de imágenes.

## Contenido del Repositorio

- `MNIST_Classification_and_Generation.ipynb`: El notebook de Jupyter principal que incluye todo el código, las explicaciones y los análisis.
- `requirements.txt`: Un archivo de texto con las dependencias necesarias para ejecutar el notebook.
- `.gitignore`: Un archivo para excluir archivos o directorios específicos del control de versiones de Git.
- `LICENSE`: El archivo que contiene los términos bajo los cuales se distribuye el código.

## Configuración del Entorno

Para ejecutar este notebook, necesitará instalar Python y las dependencias requeridas que se encuentran en `requirements.txt`. Recomendamos utilizar un entorno virtual para evitar conflictos de dependencias con otros proyectos.

```bash
# Clonar el repositorio
git clone https://github.com/JuanLara18/mnist-classification-and-generation.git
cd mnist-classification-and-generation
```
# Crear y activar entorno virtual (opcional)
```python -m venv venv
source venv/bin/activate  # En Windows use `venv\Scripts\activate`
```
# Instalar dependencias
```python
pip install -r requirements.txt
```

## Ejecución del Notebook
Después de instalar las dependencias, puede abrir el notebook utilizando Jupyter.
```bash
jupyter notebook MNIST_Classification_and_Generation.ipynb
```
Siga las instrucciones y ejecute las celdas en orden para replicar los resultados del proyecto.

# Clasificador de ropa
Este es el **proyecto final** de la materia "Redes Neuronales" dictada por la **Universidad Nacional de Córdoba**.

##  Resumen
EL objetivo es la implementación de **autoencoders** y redes neuronales de **clasificación** jugando con sus hiperparámetros.

Los **enunciados** vienen dados por el archivo [enunciados](https://github.com/LautaroOchotorena/Redes-Neuronales-Final/blob/main/Enunciados.pdf).

### Autoencoders
<div align="center">
  <img src="https://github.com/user-attachments/assets/06f8a90a-4a68-42c9-96cb-bcb2d046f25b" alt="Texto alternativo" width="400"/>
  <p>Resultado de un modelo autoencoder</p>
</div>

### Clasificador
Usando el encoder de los autoencoders se crean los clasificadores.
<div align="center">
  <img src="https://github.com/user-attachments/assets/e0907475-21ae-419b-9e88-b9c5b902d597" alt="Texto alternativo" width="500"/>
  <p>La etiqueta de la izquierda de cada imágen es la verdadera y la de arriba la predicha por el modelo</p>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/cf1b8d71-7f12-47c0-b246-660cefedf7d8" alt="Texto alternativo" width="600"/>
  <p>Matriz de confusión de un clasificador</p>
</div>

Tabla de resultados para los diferentes modelos de clasificación:
| Métrica        | Modelo 5 | Modelo 6 | Modelo 7 | Modelo 8 |
|----------------|----------|----------|----------|----------|
| **train error** | 0.236    | 0.242    | 0.237    | 0.641    |
| **valid error**    | 0.283    | 0.290    | 0.285    | 0.657    |
| **train accuracy** | 91.8%   | 93.1%   | 92.5%   | 80.6%   |
| **valid accuracy**    | 90.0%   | 90.4%   | 90.2%   | 79.3%   |

Se **recomienda** ver la exposición del trabajo dada en [Final](https://github.com/LautaroOchotorena/Redes-Neuronales-Final/blob/main/Final.pdf) en donde se exponen los resultados y conclusiones obtenidas.

## ¿Cómo ejecutar el proyecto?
Hay dos formas:

1) Descargar el archivo [Colab](https://github.com/LautaroOchotorena/Redes-Neuronales-Final/blob/main/Colab.ipynb) y ejecutarlo de forma local habiendo instalado las librerías necesarias.
2) Acceder al proyecto en Google Colab [aquí](https://colab.research.google.com/drive/1Y1MiSmAzOqyNJeSE6MwHcs0qlPP3tBLk?usp=sharing). Recomiendo esta última.

## Librerías principales:
Numpy, PyTorch, Seaborn y Matplotlib.

# Detection Of Harmful Objects - Neural Network

Este proyecto consiste en el desarrollo de una red neuronal utilizando **PyTorch** para la detección de objetos peligrosos a partir de imágenes.

---

## ¿Qué hace este proyecto?

El objetivo es entrenar un modelo de inteligencia artificial capaz de identificar objetos peligrosos dentro de un conjunto de imágenes.

Se trabajan conceptos como:

* Tensores
* Redes neuronales
* Procesamiento de imágenes
* Entrenamiento de modelos con PyTorch

---

## Tecnologías utilizadas

* Python 3.10
* PyTorch
* Torchvision
* Jupyter Notebook

---

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

* Python 3.10
* Git

---

## Clonar el repositorio

```bash
git clone <URL_DEL_REPO>
cd Detection_Of_Harmful_Objects-Neural_Network
```

---

## Configuración del entorno (MUY IMPORTANTE)

### 1. Crear entorno virtual

```bash
py -3.10 -m venv venv310
```

---

### 2. Activar el entorno

En Windows:

```bash
venv310\Scripts\activate
```

Si todo está bien, verás algo así:

```
(venv310)
```

---

### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```
```bash
nbstripout --install
```
---

### 4. Seleccionar el entorno en VS Code

1. Abrir el proyecto en VS Code
2. Ir a cualquier notebook (`.ipynb`)
3. En la parte superior derecha seleccionar:

```
venv310 (Python 3.10)
```

---

## Cómo ejecutar el proyecto

1. Abre la carpeta `notebooks`
2. Ejecuta los archivos en orden:

   * `part1_tensors.ipynb`
   * `part2_neural_network.ipynb`

Puedes usar:
 **Run All** para ejecutar todas las celdas

---

## Notas importantes

* No subir la carpeta `venv310/` al repositorio
* Si tienes errores de librerías, revisa que el entorno esté activo
* Este proyecto usa CPU (no GPU)

---

## Verificación rápida

Puedes probar si todo funciona ejecutando:

```python
import torch
print(torch.__version__)
```
---
##  Dataset

El dataset no está incluido en este repositorio debido a su tamaño.

Descargar desde:
https://drive.google.com/drive/folders/1lvXIxGepR0NjFCLXa11hPwkxbmUM_0kO?usp=drive_link

Ubicar la carpeta descargada en:

data/harmful_dataset/
---
## Autores

Proyecto realizado por:
- KAREN DANIELA GUZMAN HERNANDEZ
- SEBASTIAN BUCHELI MIRANDA
- DAVID ALEJANDRO BRAVO OSPINA
---

## Recomendación

Si tienes problemas al ejecutar, intenta:

* Verificar versión de Python (debe ser 3.10)
* Reinstalar dependencias
* Asegurarte de seleccionar el entorno correcto

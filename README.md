# Introducción al Procesamiento Digital de Imágenes (PDI)

Espacio para subir los trabajos prácticos de la materia 

# Ejecutar el proyecto 📋

## Paso 1. Activar entorno virtual 

### 1.1 Debe crear el entorno virtual usando virtualenv 

```bash
virtualenv env
```

### 1.2 Activar entorno
```bash
env\Scripts\activate
```

### 1.3 Instalar las librerias requeridas. Realizar este paso cada vez que se agregan librerias.
```bash
pip install -r requirements.txt
```
# Trabajo Practico N 1

Mostrar una imagen RGB en YIQ

# Trabajo Practico N 2

Realizar operaciones aritmeticas con 2 imagenes de igual tamaño. La interfaz cuenta con imagenes de ejemplos. En caso de querer seleccionar una imagen de su directorio puede descargar de la carpeta imagenes los archivos __image1.png__ y __image2.png__.

```bash
python TP2-OperacionesAritmeticas.py
```
[![suma.png](https://i.postimg.cc/9f7LLhgm/suma.png)](https://postimg.cc/5Hf5tZMT)

# Trabajo Practico N 3

Realizar operaciones sobre el histograma de luminancias aplicando funciones de raiz cuadrada, exponencial o lineal a trozos sobre la imagen. La interfaz cuenta con la seleccion de una imagen para calcular su histograma segun diferentes contadores y tambien la imagen resultante aplicando los filtros disponibles.

```bash
python TP3-OperacionesLuminancia.py
```
[![frecuencia.png](https://i.postimg.cc/65Mb3zGX/frecuencia.png)](https://postimg.cc/fJ0fqcK2)

# Trabajo Practico N 4

Cargar una imagen en tonos de gris, convirtiendo la misma a YIQ y manteniendo solo la banda de luminancia Y. Al resutado aplicar el filtrado por convolucion pasabajos, detectores de bordes y pasabanda.

```bash
python TP4-Convolucion.py
```
[![convolucion.png](https://i.postimg.cc/m2KZ032b/convolucion.png)](https://postimg.cc/56qMzCCG)

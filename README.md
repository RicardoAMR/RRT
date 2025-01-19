# Notebook del algoritmo de un RRT

Este proyecto contiene un notebook en Python que, al ejecutarse, genera un mapa con obstáculos aleatorios, un comienzo y un objetivo. Este problema se resuelve mediante el algoritmo RRT. Además, mide el tiempo que tarda en obtener el camino hasta el objetivo, generando un archivo `.txt` con dicho tiempo registrado.

## Instrucciones de Uso

1. **Pre-requisitos**:
   - Asegúrate de tener instalado [Jupyter Notebook](https://jupyter.org/) o [JupyterLab](https://jupyter.org/install).
   - Tener instalado Python 3.7 o superior.

3. **Pasos dentro del Notebook**:
   - Simplemente ejecuta todas las celdas secuencialmente. 
   - Al finalizar, el notebook generará un archivo llamado `resultados.txt` que contiene el tiempo total de ejecución, además de una ventana con el mapa y el camino encontrado.

4. **Salida**:
   - El archivo `resultados.txt` estará en el mismo directorio donde se encuentra el notebook.
   - El contenido del archivo mostrará el tiempo de ejecución total en segundos.
   - Una ventana mostrando el mapa con el camino obtenido.

## Estructura del Proyecto

- `rrt.ipynb`: Contiene el código que ejecuta las operaciones y mide el tiempo.
- `resultados.txt`: Archivo de salida que se genera automáticamente al ejecutar todas las celdas del notebook.




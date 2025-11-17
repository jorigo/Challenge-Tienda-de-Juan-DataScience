# Challenge-Tienda-de-Juan-DataScience
En este Reto, aplicaremos todos los conocimientos adquiridos para resolver una petición del Señor Juan; quien desea optimizar sus tiendas, y con el analisis de datos le daremos a conocer que debe hacer despues que obtengamos los resultdos

# Proyecto de Análisis de Datos de Tiendas

## 1. Propósito del análisis
Este proyecto tiene como objetivo analizar la información de ventas de cuatro tiendas utilizando Python y la librería **pandas**. El análisis permite extraer información clave como:
- Ingresos totales por tienda.
- Ventas por categoría de productos.
- Calificación promedio asignada por los clientes.
- Productos más y menos vendidos.
- Costo de envío promedio por tienda.
- Visualizaciones que facilitan la interpretación de los datos.

## 2. Estructura del proyecto
```
/proyecto_analisis_tiendas
│
├── tienda_1.csv
├── tienda_2.csv
├── tienda_3.csv
├── tienda_4.csv
│
├── analisis_tiendas.ipynb   # Notebook principal con el análisis
├── README.md                # Documento descriptivo del proyecto
```

## 3. Ejemplos de gráficos e insights
Los gráficos generados incluyen:

- **Ingresos por tienda:** compara visualmente cuál tienda generó mayores ganancias.
- **Distribución de ventas por categoría:** muestra cuáles categorías son más populares en cada tienda.
- **Calificaciones promedio:** revela el nivel de satisfacción general.
- **Top y bottom productos:** identifica qué productos destacan y cuáles deben ser evaluados.
- **Envío promedio:** muestra diferencias de costos entre tiendas, lo cual puede influir en la percepción del cliente.

Ejemplos de insights:
- Algunas tiendas tienen ingresos notablemente más altos debido a la presencia de productos con mayor precio promedio.
- La categoría "Tecnología" suele ser la más vendida en la mayoría de tiendas.
- Las calificaciones muestran una correlación con los productos más vendidos.
- El costo promedio de envío varía significativamente entre tiendas, lo cual puede influir en la decisión del cliente.

## 4. Instrucciones para ejecutar el notebook

### Requisitos previos
- Google Colab o un entorno Python 3.8+
- Librerías necesarias:
  ```python
  import pandas as pd
  import matplotlib.pyplot as plt
  ```

### Pasos
1. Abrir Google Colab.
2. Subir los archivos `tienda_1.csv` a `tienda_4.csv`.
3. Subir el archivo `analisis_tiendas.ipynb`.
4. Ejecutar las celdas del notebook en orden.
5. Ver los resultados impresos y los gráficos generados.

---

Este README sirve como guía para comprender y ejecutar el análisis completo del proyecto.

# Análisis de Rendimiento de Tiendas - AluraStore Latam
Este repositorio contiene el análisis de datos exploratorio (EDA) y el informe de recomendación para el Desafío de Data Science de Alura Latam. El objetivo principal es analizar el rendimiento de cuatro tiendas ficticias (AluraStore) para determinar cuál de ellas debería ser vendida, basando la decisión en un equilibrio entre rentabilidad y satisfacción del cliente.

## Descripción del Proyecto
El análisis se realiza a partir de cuatro conjuntos de datos (uno por tienda) que contienen información sobre ventas, productos, clientes y logística. El notebook de Jupyter (AluraStoreLatam.ipynb) procesa estos datos, genera visualizaciones clave y extrae los insights que fundamentan el Informe Final.

## 📈 Análisis de Factores Clave
El informe final se basa en el análisis comparativo de las cuatro tiendas, considerando los siguientes factores:
* Ingresos Totales: Facturación bruta de cada tienda.
* Ventas por Categoría: Productos más y menos vendidos.
* Calificaciones Promedio: Nivel de satisfacción de los clientes (escala 1-5).
* Costo de Envío Promedio: Eficiencia logística y costo para el cliente.
* Relación Ganancias vs. Costo: Un análisis combinado para ver la eficiencia operativa frente a la experiencia del cliente.
# 📊 Conclusión del Análisis
El análisis concluyó que la Tienda 1, aunque es la líder en ingresos totales (26.1% del total), también es la que presenta el peor rendimiento en métricas de satisfacción: tiene la calificación promedio más baja y el costo de envío más alto.

Por el contrario, las Tiendas 2 y 3 muestran el mejor equilibrio entre ingresos y satisfacción. La Tienda 4 tiene los ingresos más bajos, but goza de una alta satisfacción del cliente y los costos de envío más bajos, lo que sugiere un buen potencial de crecimiento.

**Recomendación Final: Vender la Tienda 1.**

Justificación: Se prioriza la salud de la marca y la sostenibilidad a largo plazo. Vender la Tienda 1 elimina el activo con mayor fricción operativa y peor reputación, al mismo tiempo que genera el mayor capital de venta para reinvertir en las tiendas más saludables y eficientes (2, 3 y 4).

## 🚀 Cómo Ejecutar el Proyecto

Este proyecto está contenido en un Jupyter Notebook y puede ejecutarse fácilmente en Google Colab o de forma local.

### 1. Dependencias y Bibliotecas

El análisis utiliza las siguientes bibliotecas estándar de Data Science en Python:

* pandas (para la manipulación y análisis de datos)
* matplotlib (para la visualización de datos)

Puedes instalar las dependencias necesarias usando pip ->
*pip install pandas matplotlib*

### 2. Fuente de Datos

Los datos son 4 archivos CSV proporcionados por Alura, alojados en GitHub. El notebook carga estos datos directamente desde sus respectivas URLs, por lo que no es necesario descargar los archivos localmente.

### 3. Ejecución

**Opción A: Google Colab**

1. Abre Google Colab.

2. Sube el archivo AluraStoreLatam_DesafioCompleto.ipynb.

3. Ejecuta todas las celdas en orden. Las bibliotecas ya están preinstaladas y los datos se cargarán automáticamente.

**Opción B: Entorno Local (Jupyter)**

1. Clona este repositorio o descarga los archivos.

2. Asegúrate de tener las dependencias instaladas (pandas y matplotlib).

3. Inicia Jupyter Notebook o Jupyter Lab desde tu terminal:
*jupyter notebook*

4. Abre el archivo AluraStoreLatam_DesafioCompleto.ipynb y ejecuta las celdas.

## 👤 Autor
*Jesus Antonio Torres Contreras / MrX7Torres*

## 📜 Agradecimientos
Este proyecto es parte del Desafío de Data Science de Alura Latam. La consigna del problema y los conjuntos de datos fueron proporcionados por Alura.

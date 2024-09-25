# Proyecto de Segmentación de Intermediarios Financieros

Este proyecto se centra en la segmentación de intermediarios financieros utilizando técnicas de *machine learning* no supervisado, como el *clustering* K-Means, con el objetivo de optimizar las condiciones comerciales y mitigar el riesgo de siniestros. La entidad que lidera el proyecto se denominará **"Entidad"** por motivos de confidencialidad.

## Descripción

La **Entidad** trabaja con diversos intermediarios financieros (IF) que otorgan créditos a empresas y trabajadores independientes. Sin embargo, el modelo actual de tarifas basado en el riesgo de los IF penaliza a algunos intermediarios que, a pesar de manejar grandes volúmenes de crédito, son castigados injustamente por la estructura tarifaria, lo que afecta las relaciones comerciales. El objetivo de este proyecto es agrupar a los intermediarios según diversas características, para identificar aquellos con mayor riesgo de siniestralidad y ajustar las políticas tarifarias de manera más justa.

Este proyecto emplea técnicas de *clustering* para descubrir patrones en los datos históricos y ofrece recomendaciones basadas en los resultados obtenidos.

## Tecnologías y herramientas utilizadas

- **Python**: Lenguaje principal para el análisis de datos.
- **Bibliotecas**: 
  - `Pandas` para la manipulación y análisis de datos.
  - `Matplotlib` y `Seaborn` para la creación de visualizaciones.
  - `Scikit-learn` para la implementación de algoritmos de *machine learning* no supervisado, específicamente K-Means y DBSCAN.
  
- **Jupyter Notebooks**: Para la ejecución del código y visualización de los resultados.
- **Gráficos**: Varias visualizaciones generadas para el análisis de distribución y comportamiento de los IFs, incluidas en el repositorio.

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:

```
├── notebooks/
│   ├── Proyecto_final.ipynb      # Notebook principal con el análisis y clustering
├── images/                       # Carpeta que contiene las visualizaciones generadas
│   ├── distribucion_siniestros.png
│   ├── clusters_kmeans.png
│   ├── boxplot_siniestros.png
│   └── ...
├── README.md                     # Este archivo README
```

## Imágenes

Las imágenes contenidas en la carpeta **`/images`** fueron generadas durante el proceso de análisis y representan gráficas clave, como la distribución del promedio de días hasta el siniestro, la relación entre el total desembolsado y los siniestros, y las visualizaciones de los clusters obtenidos mediante K-Means.

## Confidencialidad de los datos

Por motivos de confidencialidad, los datos originales utilizados en este análisis **no están incluidos en este repositorio**. La base de datos contiene información sensible de intermediarios financieros, por lo que no puede ser compartida públicamente. Además, el nombre real de la entidad ha sido sustituido por **"Entidad"** en todo el proyecto para proteger la identidad de la organización.

Si deseas reproducir este análisis con tus propios datos, puedes adaptar el código disponible en el notebook `Proyecto_final.ipynb`.

## Resultados principales

- Se identificaron grupos de intermediarios financieros con características similares utilizando algoritmos de *clustering*.
- El análisis reveló patrones importantes en el comportamiento de los intermediarios con respecto a la siniestralidad y el total desembolsado.
- Se realizaron recomendaciones para ajustar las tarifas de manera más justa, con el objetivo de optimizar la relación comercial y mitigar el riesgo de impago.

## Recomendaciones futuras

Se recomienda que la **Entidad** implemente un sistema dinámico de segmentación de intermediarios financieros, basado en un análisis de datos continuo, para ajustar las tarifas de manera más justa y eficaz. También se sugiere considerar factores externos, como cambios macroeconómicos, en futuros análisis.

## Instalación y uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_proyecto.git
   ```
   
2. Instalar las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutar el *notebook* principal en Jupyter:
   ```bash
   jupyter notebook notebooks/Proyecto_final.ipynb
   ```

## Contacto

Si tienes preguntas sobre este proyecto, no dudes en contactarnos a través de este repositorio.

---

Con este **README**, incluyes toda la información relevante para el proyecto, garantizando que la confidencialidad de los datos y la identidad de la entidad se mantenga protegida. ¡Espero que te sea útil!

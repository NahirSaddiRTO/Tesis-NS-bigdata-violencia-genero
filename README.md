# Tesis de Licenciatura - Sistemas de Información  
## Aplicación de un Proceso de Big Data para Categorizar Factores de Riesgo sobre Violencia contra las Mujeres  
**Autora:** Nahir Saddi  

Este repositorio contiene el código fuente y los datos utilizados en el desarrollo de los capítulos 3 y 4 de la tesis “Aplicación de un Proceso de Big Data para categorizar factores de riesgo sobre Violencia contra las Mujeres”.

El trabajo explora cómo las técnicas de Big Data, análisis exploratorio, limpieza y modelado no supervisado pueden emplearse para identificar patrones, tendencias y factores de riesgo en situaciones de violencia contra las mujeres en Argentina.

---

## 📚 Estructura de la Tesis

1. **Introducción**  
   Presenta el contexto y motivación de la tesis, así como los objetivos generales y específicos.

2. **Marco Teórico**  
   Define conceptos clave como violencia de género y Big Data. Se analiza la interrelación entre ambos y se revisa literatura relevante.

3. **Diseño Metodológico y Análisis Exploratorio**  
   Describe la metodología aplicada, el proceso de obtención y tratamiento de los datos, la limpieza y análisis exploratorio (capítulo 3).

4. **Modelado y Agrupamiento de Datos**  
   Presenta el análisis de clustering y la identificación de patrones de riesgo (capítulo 4).
5. **Conclusiones**  
   Resume los hallazgos, implicaciones y futuras líneas de trabajo.

## 📂 Estructura del Repositorio

capitulo3_analisis_exploratorio_analisis.ipynb
capitulo3_procesamiento_limpieza.ipynb
capitulo4_clustering.ipynb
datos_nuevo/
├── originales/
│ ├── intervenciones_domiciliarias.csv
│ ├── llamados_atendidos.csv
│ ├── linea144_20.csv
│ ├── linea144_21.csv
│ ├── linea144_22.csv
│ └── linea144_23.csv
├── (archivos generados luego de la limpieza)
└── (pueden eliminarse, ya que se regeneran al ejecutar los notebooks)
requerimientos.txt
README.md

## 🧠 Contenido de los Notebooks

### `capitulo3_procesamiento_limpieza.ipynb`
Contiene las etapas de **preprocesamiento y limpieza** de los datos.  
Incluye:
- Integración y normalización de fuentes.  
- Detección y tratamiento de valores faltantes o inconsistentes.  
- Generación de archivos limpios almacenados en `datos_nuevo/`.

### `capitulo3_analisis_exploratorio_analisis.ipynb`
Incluye el **análisis exploratorio de datos (EDA)**:  
- Visualización de medidas y distribución de variables.  
- Identificación de patrones descriptivos y correlaciones.  
- Análisis de frecuencia de casos, tipos de violencia, relación víctima-agresor, entre otros.

### `capitulo4_clustering.ipynb`
Desarrolla el **análisis de agrupamiento (clustering)** para identificar grupos de riesgo.  
Incluye:
- Aplicación de algoritmos no supervisados.  
- Visualización y descripción de los clústeres resultantes.  
- Interpretación de los hallazgos en el contexto del estudio.

---

## 💾 Conjuntos de Datos

Los archivos originales se encuentran en `datos_nuevo/originales`:

- `intervenciones_domiciliarias.csv`: Intervenciones por violencia familiar.  
- `llamados_atendidos.csv`: Llamados atendidos por situaciones de violencia.  
- `linea144_20.csv`: Datos Línea 144 – Año 2020.  
- `linea144_21.csv`: Datos Línea 144 – Año 2021.  
- `linea144_22.csv`: Datos Línea 144 – Año 2022.  
- `linea144_23.csv`: Datos Línea 144 – Año 2023.  

Los archivos generados tras la limpieza se almacenan en `datos_nuevo/` y pueden ser eliminados para regenerarlos al ejecutar el código.

---

## ⚙️ Requerimientos

Las bibliotecas necesarias para ejecutar los notebooks se encuentran listadas en `requerimientos.txt`.  
Para instalarlas, ejecutar:

```bash
pip install -r requerimientos.txt







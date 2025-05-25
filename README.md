# Tesis de Licenciatura - Sistemas de Información  
## Aplicación de un Proceso de Big Data para Categorizar Factores de Riesgo sobre Violencia contra las Mujeres  
**Autora:** Nahir Saddi  

Este repositorio contiene el código fuente correspondiente a los capítulos 3 y 4 de la tesis.  
El trabajo explora cómo las técnicas de Big Data y modelos predictivos pueden ser utilizados para identificar patrones y factores de riesgo en situaciones de violencia contra las mujeres en Argentina.

---

## 📚 Estructura de la Tesis

1. **Introducción**  
   Presenta el contexto y motivación de la tesis, así como los objetivos generales y específicos.

2. **Marco Teórico**  
   Define conceptos clave como violencia de género y Big Data. Se analiza la interrelación entre ambos y se revisa literatura relevante.

3. **Marco de Trabajo Propuesto**  
   Describe el diseño metodológico, el proceso de recolección de datos y el análisis exploratorio (contenido reflejado en el código del capítulo 3).
   El informe interactivo en Power BI, se puede ver siguiendo este link: 
   https://app.powerbi.com/reportEmbed?reportId=4d65e609-a72a-49f1-84a2-92f326ae859a&autoAuth=true&ctid=9c691607-ee0c-4ec3-8e1e-d68db427e72c

4. **Caso de Estudio y Modelo Predictivo**  
   Presenta la aplicación del modelo de clasificación (Random Forest), junto con técnicas de balanceo (SMOTE), y la interpretación de resultados (contenido reflejado en el código del capítulo 4).

5. **Conclusiones**  
   Resume los hallazgos, la importancia de anticipar situaciones de riesgo y las implicancias para políticas públicas.

## 📂 Estructura del Repositorio

- `capitulo3_analisis_exploratorio.ipynb`: Jupyter notebook correspondiente al análisis exploratorio de los datos, con la exploración de patrones y tendencias iniciales.
- `capitulo4_modelo_predictivo.ipynb`: Jupyter notebook con la implementación y análisis de un modelo predictivo para categorizar el riesgo de violencia.
- `datos/`: Carpeta que contiene los conjuntos de datos utilizados en la tesis.
  - `intervenciones_domiciliarias.csv`: Datos de intervenciones domiciliarias por violencia familiar.
  - `llamados_atendidos.csv`: Información sobre llamados atendidos relacionados con violencia.
  - `linea144_20.csv`: Datos de la Línea 144 correspondientes al año 2020.
  - `linea144_21.csv`: Datos de la Línea 144 correspondientes al año 2021.
  - `linea144_22.csv`: Datos de la Línea 144 correspondientes al año 2022.
  - `linea144_23.csv`: Datos de la Línea 144 correspondientes al año 2023.
  - `requerimientos.txt`: Lista de las bibliotecas y dependencias necesarias para ejecutar los notebooks.
- `README.md`: Este archivo que proporciona una visión general del repositorio.

## 📊 Fuentes de Datos

Se utilizaron registros provenientes de distintas bases de datos públicas y gubernamentales de atención a víctimas de violencia:

- Intervenciones domiciliarias (Línea 137)
- Llamados atendidos (Línea 137)
- Registros de la Línea 144 (años 2020 a 2023)

---
## 📈 Resultados

El modelo predictivo alcanzó métricas perfectas (accuracy, precision, recall y F1-score = 1.00) luego de aplicar técnicas de preprocesamiento, balanceo con SMOTE y selección del algoritmo Random Forest.
Esto permitió identificar con alta precisión los casos clasificados como de alto riesgo en base a variables como edad, género, tipo de violencia y relación con el agresor.

## ⚙️ Requisitos 
```bash
pip install -r requerimientos.txt 






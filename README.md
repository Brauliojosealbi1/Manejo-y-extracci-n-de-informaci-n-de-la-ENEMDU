# Análisis de pobreza con la ENEMDU en R - Quito

Este repositorio contiene un script en **R** para cargar, limpiar y analizar los datos de la Encuesta Nacional de Empleo, Desempleo y Subempleo (**ENEMDU**) de diciembre 2024, con enfoque en el cantón **Quito**. Se utilizan los factores de expansión oficiales para producir estimaciones representativas.

## 📌 Autor
**Juan José Almeida**  
Licenciado en Negocios Internacionales | Máster en Relaciones Internacionales y Comunicación  
Especialista en cooperación y análisis de datos

## 📊 Funcionalidades principales

- Limpieza de entorno de trabajo
- Carga automatizada de paquetes
- Lectura de datos de personas ENEMDU (formato CSV)
- Definición de parroquias de Quito
- Aplicación del diseño muestral con `survey`
- Cálculo de:
  - Proporción de desnutrición crónica en menores de 2 años
  - Porcentaje de mujeres en pobreza en Quito
  - Totales de población, mujeres, pobreza y pobreza extrema

## 📦 Paquetes utilizados

```r
pacman::p_load(readr, tidyverse, haven, data.table, questionr, survey, skimr, jtools)

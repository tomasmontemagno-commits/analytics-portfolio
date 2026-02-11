# 🇦🇷 Análisis de Brecha Salarial en Argentina: Actividad y Geografía

## 🎯 Resumen del Proyecto
Este proyecto de Data Analytics explora la distribución y evolución de los salarios en Argentina durante el período **2014-2022**. A través del procesamiento de datos oficiales del Ministerio de Desarrollo Productivo, se visualizan las disparidades económicas regionales (Norte vs. Patagonia) y la creciente brecha entre sectores industriales estratégicos y de servicios.

## 🔍 Principales Hallazgos (Insights)

### 1. Desigualdad Geográfica Marcada
El análisis geoespacial revela una clara segmentación de ingresos en el país:
- **Zona Noroeste (NOA):** Registra sistemáticamente las medias salariales más bajas.
- **Zona Pampeana y Patagonia:** Concentran los ingresos más altos, correlacionados con la ubicación de industrias extractivas y energéticas.

### 2. Sectores Ganadores vs. Perdedores (2014-2022)
Se detectó que la brecha salarial se ha ampliado significativamente en la última década a favor de las industrias "duras":
- **Energía y Minería:** Los sectores de "Suministro de electricidad/gas" y "Explotación de minas" lideran la tabla, con crecimientos nominales del **1145%** y **1171%** respectivamente.
- **Educación y Cultura:** En contraste, sectores como "Enseñanza" (+984%) y "Servicios Artísticos/Culturales" (+884%) crecieron por debajo de los líderes, perdiendo competitividad relativa.

### 3. La Brecha se Acelera
El análisis de series temporales muestra que, a partir de **2014**, las curvas de salario medio se bifurcan agresivamente, consolidando a la industria energética y minera con salarios promedio que (a valores de 2022) superaban los $250.000, distanciándose del resto de la economía.

## 🛠 Stack Tecnológico y Metodología
Este reporte fue generado íntegramente en **R** utilizando el paradigma de programación literaria (RMarkdown).

- **Procesamiento de Datos:** `dplyr` y `tidyr` para la limpieza y estructuración del dataset del Ministerio.
- **Visualización:** `ggplot2` para gráficos de líneas y barras comparativas.
- **Análisis Geoespacial:** Generación de mapas coropléticos (Mapas de calor por provincias/departamentos) para visualizar la distribución territorial del ingreso.
- **Reporte:** Renderizado final en formato HTML/PDF mediante `knitr`.

## 📂 Estructura del Repositorio
- `/data`: Datasets crudos provistos por el Ministerio de Desarrollo Productivo.
- `/scripts`: Código fuente en R con el paso a paso del ETL y la generación de gráficos.
- `/output`: Reporte final en formato PDF (`Analisis del salario en Argentina por actividad.pdf`).

## 🚀 Cómo visualizar el reporte
Puedes descargar el análisis completo en PDF directamente desde este repositorio o visualizar el código fuente en la carpeta `/scripts` para ver la lógica de procesamiento.

---
*Autor: Tomás Montemagno - Marketing Analytics Lead*
*https://www.linkedin.com/in/tom%C3%A1s-montemagno-15104a70/*

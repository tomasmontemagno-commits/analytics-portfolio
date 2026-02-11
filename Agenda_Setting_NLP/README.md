# 📰 Análisis de Agenda Setting en Medios Digitales Argentinos (NLP)

## 🎯 Objetivo del Proyecto
Este proyecto aplica técnicas de **Procesamiento de Lenguaje Natural (NLP)** sobre un corpus de **7.000 noticias** publicadas entre julio y septiembre de 2019. El objetivo es detectar patrones de "Agenda Setting" y comparar las líneas editoriales de los principales medios nacionales (*Clarín, La Nación, Página 12, Crónica, Infobae, Télam, Perfil, MinutoUno*).

## 🧠 Metodología y Algoritmos
Se implementó un pipeline de procesamiento de texto para estructurar datos no estructurados:

1.  **Preprocesamiento:** Limpieza de HTML, tokenización, normalización (lowercase) y remoción de *stopwords* y caracteres especiales.
2.  **Vectorización:** Cálculo de métricas **TF-IDF** (Term Frequency – Inverse Document Frequency) para identificar palabras clave distintivas por medio.
3.  **Modelado de Tópicos (Topic Modeling):** Uso del algoritmo **Latent Dirichlet Allocation (LDA)** para descubrir tópicos ocultos en el corpus y clasificarlos temáticamente (Economía, Policiales, Deportes, Política).

## 📊 Principales Hallazgos (Insights)

### 1. Perfiles Editoriales Definidos
El modelo LDA permitió cuantificar el foco editorial de cada medio:
- **Clarín:** Predominancia significativa de tópicos de **Deportes**, con picos en Política/Economía según la coyuntura.
- **Crónica:** Fuerte sesgo hacia **Policiales** como tópico principal.
- **La Nación / Perfil:** Mayor peso en temáticas de **Familia y Sociedad**.
- **Página 12 / Télam:** Foco distintivo en tópicos de **Sociedad y Política**.

### 2. La "Agenda Compartida" (Efecto PASO 2019)
Se detectó que, independientemente de la línea editorial, los medios convergen en una **agenda común** ante eventos de alto impacto. Durante las elecciones **PASO de agosto 2019**, la jerarquía de tópicos "habitual" (Deportes/Policiales) se rompió, y todos los medios alinearon su cobertura hacia Política y Economía.

## 🛠 Stack Tecnológico
- **Lenguaje:** R
- **Librerías Clave:** `tidyverse` (manipulación de datos), `tidytext` (tokenización), `topicmodels` (LDA), `tm` (text mining).
- **Visualización:** `ggplot2` para graficar la evolución temporal de los tópicos.

## 🚀 Visualizaciones
*<img width="975" height="731" alt="image" src="https://github.com/user-attachments/assets/00db6760-17ee-46f4-ba67-e6105c6c1a68" />
*
> Gráfico: Evolución de la probabilidad de tópicos durante las elecciones PASO 2019.

---
*Autor: Tomás Montemagno - Data Analytics Lead*# Análisis de Agenda Setting en Medios
Análisis de corpus de noticias utilizando R para detectar tópicos principales.

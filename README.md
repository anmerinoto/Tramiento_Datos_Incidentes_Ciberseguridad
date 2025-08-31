# 🛡️ Proyecto de Análisis de Incidentes de Ciberseguridad  

## 📌 Descripción del propósito del dataset  
El presente proyecto utiliza el dataset **Cybersecurity Incidents Dataset** (disponible en [Kaggle](https://www.kaggle.com/datasets/huzpsb/cybersecurity-incidents-dataset)), el cual recopila información relacionada con incidentes de ciberseguridad registrados en diferentes países.  

El propósito de este dataset es servir como base para el análisis de tendencias, patrones y posibles vulnerabilidades en el ámbito de la ciberseguridad. Su estudio permite comprender con mayor detalle los tipos de incidentes más frecuentes, los sectores más afectados y la evolución de estas amenazas.  

---

## 🔧 Limpieza y transformación de los datos  
Para preparar el dataset se realizaron los siguientes pasos:  

1.  
2.   
3.  
4.  

---

## 🔧 Procesamiento de Datos  
Se aplicaron los siguientes pasos de preparación:

Limpieza inicial
  Eliminación de registros duplicados.  
  Verificación de valores nulos (no se encontraron).  
  Transformación  

Conversión de variables categóricas a formato numérico.  
  Normalización de variables.  
  Adaptación

Creación de nuevas features:

---

## 📊 Principales hallazgos del análisis  
- Se identificaron los países con **mayores pérdidas económicas** derivadas de incidentes de ciberseguridad, siendo Estados Unidos, India y China los que presentan una tendencia ascendente más pronunciada en los últimos años. El gráfico de líneas  evidencia cómo en estos países las pérdidas en dólares estadounidenses (USD) han crecido de manera sostenida, reflejando tanto el incremento en la frecuencia de incidentes como en la magnitud del impacto financiero.  
- Algunos **sectores presentan mayor vulnerabilidad** frente a ataques específicos, lo que sugiere la necesidad de medidas preventivas particulares.  
- Se observan **tendencias temporales**, con incrementos notables de ciertos incidentes en periodos concretos.  

---

## 📊 Visualizaciones
Se generaron las siguientes visualizaciones:
##  - Gráfico de líneas  
### Evolución de Pérdidas por País
El siguiente gráfico muestra la **evolución de las pérdidas económicas (USD) asociadas a incidentes de ciberseguridad por país** durante el periodo 2019–2024.  

Se observa que países como **Estados Unidos, India y China** presentan un crecimiento acelerado en el monto de pérdidas, lo que indica un aumento tanto en la **frecuencia** como en la **severidad de los ataques** en estas regiones.  
Este comportamiento refleja la concentración de ciberataques en economías altamente digitalizadas, donde la superficie de exposición es mayor y el impacto financiero de los incidentes es significativo.  

El análisis permite identificar patrones de riesgo y priorizar medidas de ciberseguridad a nivel internacional.  

![Evolución de Pérdidas por País](images/grafico_lineas_pais.png)
  - Histogramas → .
  - Boxplots → .
  - 📌 Heatmap de correlación (Seaborn) → .
    * [Quejas vs Pérdidas (2019–2024) – animación por año](images/interactive_scatter_complaints_losses.png)
    * [Bubble Chart: Año vs Pérdidas (size=Quejas, color=Pais)](images/interactive_bubble_year_losses.png)
  - Gráfico de barras → .

---

## 💡 Insights y conclusiones  
- La **distribución de incidentes por tipo** evidencia que la mayor parte se concentra en un número reducido de categorías, lo cual permite priorizar medidas de mitigación en esos ámbitos.  
- Los datos muestran que la **conciencia en ciberseguridad y las políticas de protección** juegan un papel clave en la reducción de riesgos.  
- Este análisis puede ser un punto de partida para diseñar **modelos predictivos** que anticipen posibles incidentes en función de patrones históricos.  

---

## 💡 Equipo de Trabajo
Integrantes:
* Jenny Alava
* Saskia Guerrero
* Angel Merino

---

## 💡 Repositorio
Este repositorio contiene:
- data/ → dataset original.
- images/ → visualizaciones.
- root → análisis exploratorio, notebook y procesamiento.
- README.md → documentación del proyecto.

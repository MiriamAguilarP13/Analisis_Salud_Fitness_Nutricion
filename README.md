# 🩺 Análisis Integral de Salud, Fitness y Nutrición

## Introducción

Este proyecto presenta un análisis de un dataset que integra datos antropométricos, de actividad física, hábitos alimenticios e indicadores de salud. El objetivo es transformar esta información en insights clínicos y deportivos accionables que puedan guiar decisiones en salud preventiva, nutrición y entrenamiento personalizado.

---

## Justificación y Objetivos

En la actualidad, la salud y el rendimiento deportivo son campos donde la toma de decisiones basada en datos es crucial. Este análisis se justifica por la necesidad de contar con herramientas que permitan:

*   **Evaluar el estado de salud:** Identificar perfiles de riesgo y fortalezas individuales.
*   **Diseñar planes personalizados:** Adaptar recomendaciones nutricionales y rutinas de ejercicio a las necesidades específicas de cada persona.
*   **Optimizar el rendimiento:** Entender cómo diferentes variables impactan los resultados físicos.

Los principales objetivos de este análisis son:

1.  **Explorar y describir** las características generales de la población del dataset.
2.  **Analizar la relación** entre la actividad física (tipo, frecuencia, duración) y los resultados de salud (gasto calórico, composición corporal).
3.  **Investigar la influencia** de los hábitos nutricionales (macronutrientes, tipo de dieta, balance calórico) en la composición corporal y otros indicadores de salud.
4.  **Identificar factores clave** que predicen resultados de salud como el porcentaje de grasa corporal.
5.  **Segmentar la población** para identificar grupos con características de salud similares o de "alto riesgo".

---

## Utilidad y Respuestas Clave

Este análisis proporciona información valiosa para:

- **Profesionales de la salud y nutricionistas:** Para una evaluación más precisa y el diseño de planes dietéticos y de ejercicio personalizados.  
- **Entrenadores personales:** Para optimizar rutinas y comprender cómo la nutrición complementa al entrenamiento.  
- **Investigadores:** Como base para estudios más profundos sobre la interrelación entre salud, nutrición y rendimiento.  
- **Individuos:** Para comprender mejor cómo sus hábitos impactan su salud y rendimiento físico.

---

## Estructura del Análisis (Resumen)

1. **Carga de Datos:** Importación del dataset principal.  
2. **Exploración Inicial (EDA):** Tipos de datos, valores nulos, duplicados y estadísticas descriptivas.  
3. **Análisis Descriptivo:** Indicadores clave de salud y demografía.  
4. **Correlación entre Ejercicio y Salud:** Tipo, frecuencia, duración e intensidad.  
5. **Impacto de la Nutrición:** Macronutrientes, balance calórico y tipo de dieta.  
6. **Modelado Predictivo + Clustering:** Factores críticos, importancia de variables y grupos de riesgo.  

---

## 🧪 Hallazgos Destacados

- El **balance calórico** es la variable más influyente en la composición corporal, con una importancia aproximada del **39%** en el modelo predictivo.
- La **proteína (g/kg)** presenta una correlación negativa fuerte con la grasa corporal (**r = -0.60**), siendo la segunda variable más importante (~23%).
- Las métricas de entrenamiento (frecuencia, duración) mostraron **correlaciones bajas** con IMC y % de grasa.
- La nutrición (balance calórico + proteína) explica aproximadamente **62% del impacto total** en la composición corporal.
- El **4.5%** del dataset fue clasificado como un **grupo de alto riesgo**, caracterizado por un **superávit calórico del 99%** y **33% menos proteína** que el promedio.
- Los tipos de ejercicio con mayor gasto energético fueron: **HIIT (~1650 kcal)**, seguido de fuerza y cardio.
- El clustering permitió identificar perfiles de salud diferenciados y patrones asociados a riesgo metabólico.

---


Este README proporciona un resumen conciso y claro del proyecto, sus hallazgos y su relevancia.

---

## Fuente de Datos 

<https://www.kaggle.com/datasets/jockeroika/life-style-data/versions/6/code>

---

## 👩‍💻 Autora

**Miriam Aguilar – Analista de Datos**  
🔗 LinkedIn: <https://www.linkedin.com/in/miriampineda02/>   
🐱 GitHub: <https://github.com/MiriamAguilarP13>  

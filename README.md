# Predicción de la Recuperación de Oro

Proyecto de machine learning aplicado a la minería industrial. Este trabajo se desarrolló como parte del Módulo 2 del Bootcamp de ciencia de datos, con un enfoque en la predicción de la eficiencia del proceso de extracción de oro a partir de datos operativos reales.

---

## Objetivo

Construir un modelo de regresión multivariable que prediga con precisión dos variables clave del proceso metalúrgico:

- `rougher.output.recovery`: Recuperación de oro en la etapa de flotación rougher.
- `final.output.recovery`: Recuperación de oro después de la purificación secundaria.

El objetivo final es optimizar la recuperación de oro, identificar parámetros del proceso que no aportan valor predictivo y proporcionar una herramienta de análisis para mejorar la rentabilidad de la producción.

---

## Contexto Industrial

El proyecto simula el flujo de una planta de procesamiento de oro que emplea flotación y purificación en múltiples etapas. Los datos provienen de un entorno real proporcionado por **Zyfra**, una compañía tecnológica que desarrolla soluciones para la industria pesada.

Los parámetros del proceso incluyen: dosis de reactivos, volumen de aire, tamaño de partículas, concentraciones de metales (Au, Ag, Pb), y condiciones fisicoquímicas del sistema.

---

## Herramientas y Tecnologías

- **Lenguaje:** Python 3.10
- **Entorno:** JupyterLab
- **Librerías principales:**
  - `pandas`, `numpy` — análisis de datos
  - `matplotlib`, `seaborn` — visualización
  - `scikit-learn` — modelado predictivo
  - `git`, `GitHub` — control de versiones y portafolio

---

## Métrica de Evaluación

Para evaluar el rendimiento del modelo se utilizó el **sMAPE** (Symmetric Mean Absolute Percentage Error), una métrica robusta en contextos donde los errores deben ser evaluados proporcionalmente tanto en predicciones altas como bajas.

---

## Fases del Proyecto

1. **Carga y validación de datos**
2. **Revisión de valores anómalos y características ausentes**
3. **Análisis exploratorio de datos (EDA)**
4. **Preprocesamiento y normalización**
5. **Entrenamiento de modelos de regresión**
6. **Evaluación y comparación de resultados**
7. **Entrega de conclusiones técnicas y recomendaciones industriales**

---

## Hallazgos clave

- Se identificaron variables operativas con escasa correlación con la recuperación final, lo que permitió simplificar el modelo y reducir la complejidad del proceso.
- El modelo entrenado logró un sMAPE competitivo en validación cruzada, lo cual puede servir como base para futuras implementaciones en entornos industriales reales.

---

## Autor

**Diana Marlene Reyes Fraire**  
Científica de Datos | Módulo 2 - Bootcamp Data Science - TripleTen  
GitHub: https://github.com/Marlene-Fraire

---

## Etiquetas

`#machinelearning` `#regresion` `#minería` `#oro` `#industria` `#sMAPE` `#Python` `#Jupyter` `#scikit-learn` `#proyecto-final`

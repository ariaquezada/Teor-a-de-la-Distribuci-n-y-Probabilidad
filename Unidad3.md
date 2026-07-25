# 📗 Unidad 3: Modelos de Regresión y Validación Predictiva

Esta sección almacena las prácticas, laboratorios y el desarrollo del trabajo práctico correspondientes al modelado estadístico, regresión lineal y logística, y la validación de modelos predictivos aplicados al proyecto.

---

### 📂 Registro de Actividades Prácticas (APEs)

Da clic sobre cualquier laboratorio para inspeccionar el cuaderno de código directamente en el visor de GitHub:

* 📓 [Ver APE 11: Pruebas No Paramétricas y Ajuste](./APE11.ipynb)
  * *Descripción:* Evaluación de distribuciones y pruebas de bondad de ajuste en variables no paramétricas.
* 📓 [Ver APE 12: Regresión Lineal Simple](./APE_012_Regresion_ipynb_.ipynb)
  * *Descripción:* Modelado de relación entre variables cuantitativas, ajuste por mínimos cuadrados y evaluación de $R^2$.
* 📓 [Ver APE 14: Regresión Lineal Múltiple](./APE_014_Regresion_Multiple_.ipynb)
  * *Descripción:* Construcción de modelos multivariados y análisis de multicolinealidad en conjuntos de datos.
* 📓 [Ver APE 15: Regresión Logística](./APE_015_Logistica.ipynb)
  * *Descripción:* Clasificación binaria, estimación de *Odds Ratios* y modelado de probabilidades.
* 📓 [Ver APE 16: Validación y Curvas ROC](./APE_016_ValidacionROC.ipynb)
  * *Descripción:* Evaluación del rendimiento de modelos mediante matrices de confusión, sensibilidad, especificidad y curvas ROC/AUC.

---

### 📓 Bitácora de Aprendizaje y Autoevaluación

**1. Aprendizajes Clave en la Unidad de Modelado:**
Durante esta unidad, avancé de la inferencia clásica al desarrollo de modelos predictivos. Comprendí cómo la regresión lineal múltiple y logística permiten proyectar comportamientos basados en variables explicativas del dataset ENEMDU, interpretando correctamente coeficientes, métricas de error y el área bajo la curva (AUC).

**2. Dificultades Algorítmicas Superadas:**
El mayor desafío técnico radicó en la preparación de matrices de características, la codificación de variables categóricas y el manejo de la multicolinealidad. La implementación de la evaluación con curvas ROC mediante `scipy.stats` y `sklearn` requirió una estructuración rigurosa para evitar el sobreajuste (*overfitting*) en las predicciones.

---

### 🎯 Competencias Consolidadas

* **Modelado Predictivo:** Capacidad para formular, entrenar y diagnosticar modelos de regresión lineal y logística en Python.
* **Validación Estadísticas:** Habilidad para clasificar, evaluar métricas de precisión y validar modelos mediante análisis ROC.

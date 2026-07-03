# 📘 Unidad 2: Distribuciones Continuas e Inferencia Estadística

Esta sección almacena las prácticas, laboratorios, la evaluación sumativa y la defensa del trabajo autónomo correspondientes al estudio de distribuciones notables, estimación de parámetros y pruebas de hipótesis aplicadas al proyecto.

---

### 📂 Registro de Actividades Prácticas (APEs)

Da clic sobre cualquier laboratorio para inspeccionar el cuaderno de código directamente en el visor de GitHub:

* 📓 [Ver APE 06: Distribuciones Continuas Notables](./APE006_GrupoB.ipynb)
  * *Descripción:* Modelado y aplicación de funciones de densidad continuas en contextos estadísticos.
* 📓 [Ver APE 07: Distribuciones Muestrales y TLC](./APE_007_TLC.ipynb)
  * *Descripción:* Verificación del Teorema del Límite Central mediante simulación estocástica.
* 📓 [Ver APE 08: Inferencia Estadística - Intervalos de Confianza](./APE_008_Intervalos.ipynb)
  * *Descripción:* Estimación de parámetros e intervalos de confianza utilizando las distribuciones Z y T de Student.
* 📓 [Ver APE 09: Pruebas de Hipótesis Paramétricas](./APE009_GrupoB.ipynb)
  * *Descripción:* Implementación de pruebas de hipótesis paramétricas (Z y T) junto al análisis del Valor-p.
* 📓 [Ver APE 10: Inferencia Estadística Multigrupo](./APE_010_DosMuestras.ipynb)
  * *Descripción:* Análisis de Varianza (ANOVA de 1 factor) y pruebas Post-Hoc de Tukey para comparación múltiple.

---

### 📝 Evaluación Sumativa y Base de Datos

* ⚡ [Ver Evaluación Sumativa II: Examen Práctico](./ExamenII_ArletteQuezada.ipynb)
  * *Descripción:* Resolución práctica de problemas de inferencia y modelos estadísticos aplicados con conjuntos de datos reales.
* 📊 [Ver Dataset Fuente: Datos de Loja](./Dataset_hogares_ambiental_2025.csv)
  * *Descripción:* Matriz de datos original utilizada como insumo para el procesamiento estadístico y las simulaciones en Python.

---

### 🎥 Componente 2: Trabajo Autónomo (Defensa en Video)

* 🎬 [Ver Video de Defensa - Componente 2](https://drive.google.com/file/d/1IuH6-SREl6r1NkJoXJtFIlHAy-vx2Pou/view?usp=drive_link)
  * *Descripción:* Video explicativo (6-8 min) detallando la justificación de pruebas paramétricas mediante tests de normalidad (Shapiro-Wilk), demostración del código en Jupyter y la interpretación del valor-p para la toma de decisiones estadísticas.

---

### 📓 Bitácora de Aprendizaje y Autoevaluación (Componente 3)

**1. Aprendizajes Clave en la Unidad de Inferencia:**
Durante esta unidad, consolidé la transición de la estadística descriptiva hacia la inferencia robusta. El logro principal fue automatizar mediante Python la verificación de supuestos críticos (como el test de normalidad de Shapiro-Wilk) antes de proceder con pruebas paramétricas. Logré comprender a fondo el peso matemático del *p-valor* y cómo este determina con un 95% de confianza el rechazo o no de una hipótesis nula en problemas de comparación múltiple (ANOVA).

**2. Dificultades Algorítmicas Superadas:**
El mayor reto técnico a nivel de código fue estructurar correctamente los dataframes con las muestras locales de Loja y limpiar los datos faltantes o nulos (`NaN`) sin alterar el tamaño crítico de la muestra. Asimismo, la correcta configuración de los grados de libertad en las pruebas T de Student para muestras independientes y la interpretación matricial de las pruebas Post-Hoc de Tukey requirieron un esfuerzo extra de abstracción algorítmica, logrando resolver las inconsistencias mediante el uso estricto de las funciones vectorizadas de `scipy.stats`.

---

### 🎯 Competencias Consolidadas

* **Inferencia y estimación:** Habilidad para validar hipótesis estadísticas y estimar parámetros poblacionales con rigor matemático.
* **Modelado estocástico:** Capacidad para simular procesos y evaluar variaciones grupales mediante análisis ANOVA avanzados.

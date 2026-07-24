# 🔄 Ciclo de vida de un modelo supervisado

## 🎯 Objetivos de aprendizaje

Al finalizar este módulo seré capaz de:

✅ Comprender las etapas del desarrollo de un modelo supervisado.  
✅ Explicar cómo se preparan los datos antes del entrenamiento.  
✅ Diferenciar entrenamiento, validación y prueba.  
✅ Identificar cómo los modelos llegan a aplicaciones reales.  
✅ Reconocer los principales retos del Machine Learning aplicado.

---

# 🧩 Flujo general de un modelo supervisado

```mermaid
flowchart LR
A[📂 Recopilación de datos] --> B[🧹 Preparación de datos]
B --> C[✂️ División Train/Test]
C --> D[🤖 Entrenamiento del modelo]
D --> E[⚙️ Ajuste de hiperparámetros]
E --> F[📊 Evaluación]
F --> G[🚀 Despliegue]
G --> H[🔄 Monitoreo y mejora]
```

---

# 1. 📂 Recopilación y preparación de datos

Los datos son la base de cualquier modelo de Machine Learning.

Antes de entrenar un algoritmo, es necesario obtener información relevante y asegurar su calidad.

## 🧹 Limpieza de datos

La limpieza permite corregir problemas que pueden afectar el aprendizaje del modelo.

Incluye:

| Problema | Solución |
|---|---|
| Valores faltantes | Imputación o eliminación |
| Datos duplicados | Eliminación de registros repetidos |
| Errores de formato | Normalización de datos |
| Valores inconsistentes | Corrección o validación |

---

## 🛠️ Ingeniería de características (*Feature Engineering*)

Consiste en transformar los datos originales en variables más útiles para el modelo.

Ejemplos:

- 📅 Convertir fechas en días de la semana.
- 👤 Crear rangos de edad.
- 📏 Normalizar valores numéricos.

Una buena selección de características puede mejorar significativamente el rendimiento del modelo.

---

# 2. ✂️ División de datos

Antes del entrenamiento, los datos se separan para comprobar si el modelo puede generalizar.

| Conjunto | Propósito | Porcentaje aproximado |
|---|---|---|
| 🟢 Entrenamiento | Aprende patrones de los datos | 70-80% |
| 🔵 Prueba | Evalúa datos desconocidos | 20-30% |

También puede utilizarse **validación cruzada (*Cross Validation*)** para obtener evaluaciones más confiables.

---

# 3. 🤖 Entrenamiento del modelo

Durante esta etapa el algoritmo aprende la relación entre las variables de entrada y la variable objetivo.

Dependiendo del problema:

| Problema | Objetivo | Ejemplo |
|---|---|---|
| 📈 Regresión | Predecir valores numéricos | Precio de una vivienda |
| 🏷️ Clasificación | Predecir categorías | Diagnóstico médico |

El modelo ajusta sus parámetros para minimizar errores y mejorar sus predicciones.

---

# 4. ⚙️ Ajuste de hiperparámetros

Los hiperparámetros controlan el comportamiento del algoritmo durante el aprendizaje.

Algunas técnicas utilizadas:

- 🔎 **Grid Search:** prueba diferentes combinaciones de parámetros.
- 🎲 **Random Search:** busca combinaciones aleatorias.
- 🔁 **Cross Validation:** valida el rendimiento en diferentes particiones.

---

# 5. 📊 Evaluación del modelo

Después del entrenamiento, el modelo debe ser evaluado utilizando métricas específicas.

## 📈 Modelos de regresión

| Métrica | Descripción |
|---|---|
| R² | Mide qué tan bien explica el modelo la variabilidad de los datos |
| MSE | Mide el error promedio entre predicciones y valores reales |

---

## 🏷️ Modelos de clasificación

| Métrica | Descripción |
|---|---|
| Accuracy | Porcentaje de predicciones correctas |
| Precision | Exactitud de las predicciones positivas |
| Recall | Capacidad de encontrar casos positivos |
| F1-score | Equilibrio entre precision y recall |
| Matriz de confusión | Analiza errores entre categorías |

---

# 6. 🚀 Despliegue del modelo

Cuando el modelo obtiene buenos resultados puede integrarse en sistemas reales.

Formas comunes de implementación:

- 🌐 APIs.
- 💻 Aplicaciones web.
- ☁️ Servicios en la nube.
- 🏢 Sistemas empresariales.

Ejemplo:

Un hospital puede integrar un modelo predictivo que analice datos de pacientes y ayude en el diagnóstico.

---

# 🌎 Aplicaciones reales

| Sector | Aplicación |
|---|---|
| 🏥 Salud | Predicción de enfermedades y apoyo al diagnóstico |
| 💰 Finanzas | Detección de fraude y análisis de riesgos |
| 📢 Marketing | Predicción del comportamiento del consumidor |
| 🏭 Manufactura | Mantenimiento predictivo de maquinaria |

---

# ⚠️ Retos del Machine Learning aplicado

## Calidad de datos

La precisión del modelo depende directamente de la calidad de la información utilizada.

---

## Sobreajuste (*Overfitting*)

Ocurre cuando el modelo aprende demasiado los datos de entrenamiento y pierde capacidad de generalización.

---

## Selección de características

Elegir variables relevantes evita información innecesaria y mejora el rendimiento del modelo.

---

# 📝 Conclusión

El desarrollo de un modelo supervisado no consiste únicamente en entrenar un algoritmo.

Es un proceso completo que incluye:

1. 📂 Preparación de datos.
2. 🤖 Entrenamiento.
3. ⚙️ Optimización.
4. 📊 Evaluación.
5. 🚀 Implementación.
6. 🔄 Monitoreo continuo.

Comprender este ciclo permite desarrollar soluciones de Machine Learning capaces de resolver problemas reales.
# Introducción a Machine Learning

## ¿Qué es Machine Learning?

Machine Learning (ML), o Aprendizaje Automático, es una rama de la Inteligencia Artificial (IA) que permite a las computadoras aprender patrones a partir de los datos para realizar predicciones o tomar decisiones sin que cada regla sea programada explícitamente.

En lugar de seguir instrucciones fijas, un modelo de Machine Learning identifica relaciones entre las variables de un conjunto de datos y utiliza ese conocimiento para analizar información nueva.

---

## ¿Por qué es importante?

Actualmente, la cantidad de datos generados es enorme y crece constantemente. Machine Learning permite aprovechar esa información para resolver problemas complejos y automatizar procesos de decisión.

Algunas de sus aplicaciones incluyen:

- Predicción de precios de viviendas.
- Diagnóstico de enfermedades.
- Detección de fraude financiero.
- Sistemas de recomendación.
- Reconocimiento de imágenes y voz.
- Predicción de ventas.

---

## Inteligencia Artificial, Machine Learning y Deep Learning

Estos conceptos están relacionados, pero representan diferentes niveles.

- **Inteligencia Artificial (IA):** disciplina que desarrolla sistemas capaces de realizar tareas que normalmente requieren inteligencia humana.
- **Machine Learning (ML):** subcampo de la IA que permite que los modelos aprendan automáticamente a partir de datos.
- **Deep Learning (DL):** subcampo del Machine Learning que utiliza redes neuronales profundas para resolver problemas de mayor complejidad.

### Relación entre ellos

```text
Inteligencia Artificial
│
└── Machine Learning
      │
      └── Deep Learning
```

---

## Tipos de Machine Learning

Existen tres enfoques principales.

### Aprendizaje Supervisado

Utiliza datos etiquetados para aprender la relación entre las variables de entrada y la salida esperada.

Ejemplos:

- Predicción de ventas.
- Diagnóstico de diabetes.
- Clasificación de correos electrónicos.

### Aprendizaje No Supervisado

Trabaja con datos que no poseen etiquetas y busca descubrir patrones o agrupaciones de forma automática.

Ejemplos:

- Segmentación de clientes.
- Agrupamiento de productos.
- Detección de anomalías.

### Aprendizaje por Refuerzo

Un agente aprende mediante prueba y error interactuando con un entorno, recibiendo recompensas o penalizaciones según sus acciones.

Ejemplos:

- Videojuegos.
- Robótica.
- Vehículos autónomos.

---

## Flujo general de un proyecto de Machine Learning

El desarrollo de un proyecto de Machine Learning suele seguir las siguientes etapas:

1. Recolección de datos.
2. Preparación y limpieza de los datos.
3. Análisis exploratorio.
4. División en entrenamiento y prueba.
5. Selección del algoritmo.
6. Entrenamiento del modelo.
7. Evaluación del modelo.
8. Optimización.
9. Predicción con nuevos datos.
10. Implementación del modelo.

```text
Datos
   │
   ▼
Preparación
   │
   ▼
Entrenamiento
   │
   ▼
Evaluación
   │
   ▼
Predicción
```

---

## Herramientas más utilizadas

Durante este repositorio utilizaré principalmente:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Git y GitHub

---

## Resumen

Machine Learning permite desarrollar modelos capaces de aprender a partir de datos y realizar predicciones o clasificaciones sobre información nueva. Dependiendo del tipo de problema, se pueden emplear técnicas de aprendizaje supervisado, no supervisado o por refuerzo. En los siguientes módulos se estudiarán estos enfoques con mayor detalle mediante explicaciones teóricas e implementaciones prácticas en Python.
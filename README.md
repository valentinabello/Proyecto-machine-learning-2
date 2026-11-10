# README: Proyecto Integrador – Machine Learning II
## Detección temprana del riesgo de deserción universitaria mediante técnicas de Machine Learning

---

## 📋 1. Portada e Información General

* **Institución:** Universidad Externado de Colombia
* **Facultad / Programa:** Economía (Estudiantes de la Universidad Externado de Colombia)
* **Asignatura:** Machine Learning II
* **Año / Periodo:** 2026
* **Integrantes del Equipo:**
  * Valentina Bello Olarte
  * William Gómez Marín

---

## 🎯 2. Descripción y Objetivos del Proyecto

### Descripción general
La deserción universitaria representa un desafío crítico para las instituciones de educación superior debido a sus profundas implicaciones académicas, sociales y económicas. Este proyecto desarrolla un modelo de aprendizaje automático (*Machine Learning*) robusto y auditable para identificar y clasificar de manera temprana el nivel de riesgo de deserción en estudiantes universitarios, basándose en variables de naturaleza académica, personal y contextual. 

Para garantizar la fiabilidad operativa, se implementaron rigurosas estrategias de validación cruzada anidada, controles estrictos contra la fuga de datos (*data leakage*), auditorías sobre datos sintéticos y técnicas de interpretabilidad mediante SHAP (*SHapley Additive exPlanations*).

### Objetivos
* **Objetivo General:** Desarrollar y evaluar modelos de aprendizaje automático orientados a clasificar el nivel de riesgo de deserción universitaria mediante un flujo reproducible de preparación, entrenamiento, validación e interpretación.
* **Objetivos Específicos:**
  1. Examinar y auditar la estructura, procedencia y posibles duplicados del conjunto de datos original.
  2. Generar y validar registros sintéticos complementarios evaluando su consistencia distributiva frente a los datos reales.
  3. Diseñar una estrategia de partición estricta basada en perfiles para mitigar el riesgo de fuga de información.
  4. Comparar el desempeño de múltiples algoritmos de clasificación optimizando métricas orientadas al rescate de casos en riesgo.
  5. Implementar validación cruzada anidada para la selección neutral de hiperparámetros.
  6. Analizar errores de clasificación y aplicar explicabilidad SHAP para identificar los factores determinantes del abandono.

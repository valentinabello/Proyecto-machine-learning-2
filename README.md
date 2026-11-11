# Proyecto Integrador: Detección Temprana del Riesgo de Deserción Universitaria

DESPLIEGUE: https://aula-alerta-academica.streamlit.app/

---

## 1. Información General y Autores

* **Institución:** Universidad Externado de Colombia
* **Facultad / Programa:** Economía
* **Asignatura:** Machine Learning II
* **Periodo Académico:** 2026
* **Equipo de Trabajo:**
  * Valentina Bello Olarte
  * William Gómez Marín

---

## 2. Resumen Ejecutivo y Motivación

La deserción universitaria representa un desafío crítico para las instituciones de educación superior debido a sus profundas implicaciones académicas, sociales y económicas. Este proyecto desarrolla un sistema de aprendizaje automático (*Machine Learning*) robusto, auditable y de alta precisión para identificar de manera temprana el nivel de riesgo de deserción en estudiantes universitarios. 

Para garantizar la fiabilidad operativa y evitar falsas expectativas de rendimiento, el flujo de trabajo implementa:
1. **Auditoría estricta contra la fuga de datos (*data leakage*).**
2. **Generación y validación de datos sintéticos** para balancear el espacio muestral sin comprometer la distribución original.
3. **Estrategias de partición basada en grupos (`StratifiedGroupKFold`)** para evaluar la generalización real en perfiles no vistos.
4. **Validación cruzada anidada** para la selección neutral de hiperparámetros.
5. **Auditoría de interpretabilidad mediante valores SHAP** (*SHapley Additive exPlanations*).

---

## 3. Estructura del Repositorio

El proyecto se encuentra organizado en las siguientes carpetas y archivos principales tal como se visualiza en el repositorio:

```text
 Proyecto-machine-learning
 ┣  Entrega_final/                      # Entregable final del proyecto
 ┣  Entregas/                           # Reportes de seguimiento y entregas realizadas durante el proyecto
 ┣  artículo/                           # Documento del artículo académico guía
 ┣  data/                               # Dataset procesado y consolidado
 ┃    DATASET_MACHINE_LEARNING_II.xlsx # Consolidado final (Real + Sintético)
 ┣  notebook/                           # Notebook de Jupyter con el flujo metodológico
 ┃  ┣  01_Consolidacion_Y_Generacion.ipynb # Auditoría inicial, limpieza y aumento sintético
 ┃  ┣  02_Validacion_Sinteticos.ipynb      # Pruebas de Kolmogorov-Smirnov y correlación
 ┃  ┣  03_Flujo_Sin_Fuga.ipynb             # Modelado predictivo y partición por grupos
 ┃  ┗  04_Modelado_Avanzado_Y_SHAP.ipynb   # Optimización, hiperparámetros y explicabilidad
 ┗  README.md                           # Documentación principal del repositorio

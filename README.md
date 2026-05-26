# Evento Evaluativo 4 — Predicción con Machine Learning

Instituto Tecnológico Metropolitano · Departamento de Sistemas · Ingeniería de Sistemas
Curso: Análisis de Datos · Docente: Daniel Alexis Nieto Mora · Semestre: 2026-1

## Integrantes

| Integrante |
|------------|
| Danny Mateo Hernández Sánchez |
| Stefany Builes Lopera |
| Leidy Daihana Mora Trujillo |
| Alejandra Alvarez Serna |

## Objetivo del proyecto

Aplicar los conocimientos adquiridos en el curso sobre aprendizaje de máquina (Machine Learning) en dos casos prácticos: clasificación de tumores malignos y benignos y agrupamiento de clientes según comportamiento de compra, utilizando datasets reales y justificando las decisiones técnicas.

## Fuente de datos

### Ejercicio 2 — Clasificación de Tumores Malignos y Benignos

| Elemento | Detalle |
|----------|---------|
| *Tipo* | Tabular |
| *Origen* | Breast Cancer Wisconsin (Diagnostic) Dataset |
| *Variable objetivo* | Diagnóstico: `maligno` / `benigno` |
| *Modelos aplicados* | Regresión Logística, SVM, Random Forest |
| *Métricas* | Accuracy, F1-Score, Matriz de Confusión |
| *Reducción de dimensionalidad* | PCA |
| *Notebook* | breast_cancer.ipynb |

### Ejercicio 4 — Agrupamiento de Clientes según Comportamiento de Compra

| Elemento | Detalle |
|----------|---------|
| *Tipo* | Tabular |
| *Origen* | Mall Customers Dataset |
| *Variable objetivo* | Segmentos de mercado (no supervisado) |
| *Modelos aplicados* | K-Means, DBSCAN, Clustering Jerárquico |
| *Métricas* | Silhouette Score, visualización PCA |
| *Notebook* | Agrupamiento_Clientes.ipynb |

---

## Estructura del repositorio

```
evaluacion_4/
├── README.md
├── Agrupamiento_Clientes.ipynb
├── Mall_Customers.xls 
├── breast_cancer.ipynb
└── data.csv
    
```




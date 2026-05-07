# 🏨 Hotel Booking Cancellation Analysis — ETL Pipeline

**Corporate Intelligence Project | UFV Madrid | Master in Corporate Intelligence | 2025–2026**

---

## 📌 Descripción

Este repositorio contiene el pipeline ETL completo para el análisis de cancelaciones hoteleras desarrollado como parte del proyecto de Business Intelligence.

El pipeline transforma el dataset raw *Hotel Booking Demand* en un dataset limpio y enriquecido de **87.144 registros y 44 variables**, listo para su uso en Power BI.

---

## 🚀 Ejecutar en Google Colab

Haz clic en el botón para abrir y ejecutar el notebook directamente en tu navegador, sin instalar nada:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juangalvez7077/Hotel-Bookings-/blob/main/Hotel_Bookings_ETL_code.ipynb)

> **Requisito:** Necesitarás subir el archivo `hotel_bookings.csv` cuando el notebook te lo pida.

---

## 🔄 Estructura del Pipeline

| Step | Descripción |
|------|-------------|
| **Step 1 – Extract** | Carga del dataset original (119.390 registros, 32 columnas) |
| **Step 2 – Quality Analysis** | Detección de nulos, duplicados, outliers y registros inválidos |
| **Step 3 – Data Cleaning** | Eliminación de duplicados, imputación de nulos, corrección de tipos |
| **Step 4 – Feature Engineering** | Creación de 11 nuevas variables: `total_nights`, `estimated_revenue`, `risk_score`, etc. |
| **Step 5 – Validation** | Verificación del dataset final antes de la carga |
| **Step 6 – Load** | Exportación a Excel (`.xlsx`) listo para Power BI |

---

## 📊 Resultados del Pipeline

| Métrica | Valor |
|---------|-------|
| Registros originales | 119.390 |
| Registros tras limpieza | 87.144 |
| Columnas finales | 44 |
| Tasa de cancelación | 27,52% |
| Revenue estimado total | EUR 34.312.805 |
| Revenue perdido (cancelaciones) | EUR 11.427.753 |

---

## 📁 Archivos del repositorio

```
Hotel-Bookings/
│
├── Hotel_Bookings_ETL_code.ipynb   # Notebook ETL completo
└── README.md                        # Este archivo
```

---

## 👥 Autores

Proyecto desarrollado para la asignatura de Corporate Intelligence — Universidad Francisco de Vitoria (UFV Madrid).

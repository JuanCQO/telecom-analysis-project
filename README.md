Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.

El proyecto trabaja con tres datasets: `plans.csv`, `users_latam.csv` y `usage.csv`, que incluyen información de planes, clientes y uso real de servicios de una empresa de telecomunicaciones en LATAM. Los datos contienen valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del sector.

## 📂 Contenido del repositorio

- `notebooks/S7_ConnectaTel_analysis.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers, segmentación y análisis ejecutivo.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11Oi72eME_M0g8_HsBzz1m6z9GokjyC5g)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S7_ConnectaTel_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente los datasets desde `/datasets/`

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Segmentar clientes por nivel de uso y edad
- Generar insights y recomendaciones para el equipo de ConnectaTel

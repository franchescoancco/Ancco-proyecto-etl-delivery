# Ancco-proyecto-etl-delivery
# 🚀 Pipeline ETL & Inteligencia de Mercado — Food Delivery (USA)

Pipeline ETL completo desarrollado como Trabajo Práctico Integrador del módulo de Python
para Análisis de Datos. Simula el rol de Data Engineer & Analista BI para una startup de
Food Delivery que evalúa en qué ciudades de EE. UU. expandirse.

## 🎯 Objetivo de negocio
Responder, con datos, 4 preguntas críticas del directorio: penetración geográfica,
distribución de precios, estrategia de menú por ciudad y correlación precio-calidad.

## 🏗️ Stack
- **Python:** Pandas, NumPy
- **Base de datos:** SQLite + SQLAlchemy
- **Visualización:** Matplotlib, Seaborn

## 📊 Pipeline
1. **EXTRACT** — Lectura y diagnóstico inicial de datasets crudos (~900K registros de menú, 63K restaurantes).
2. **TRANSFORM** — Limpieza de texto, split de direcciones, mapeo de precios, casteo numérico y filtro de optimización de memoria.
3. **LOAD** — Carga del dataset consolidado a una base SQLite local.
4. **BUSINESS INTELLIGENCE** — Consultas SQL + visualizaciones con conclusiones accionables para el negocio.

## 📂 Cómo reproducirlo
Este proyecto usa los datasets `restaurants.csv` y `restaurant-menus.csv` del repositorio del curso:
https://github.com/IanCN-23/dalatam_ed3_TPI_Python

1. Descarga esos datasets y colócalos en una carpeta `DATA/` junto al notebook.
2. Instala las dependencias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sqlalchemy`.
3. Abre `TPI_ETL_Food_Delivery.ipynb` y ejecuta las celdas en orden (Run All).

## 👤 Autor
Franchesco Edwin Ancco Mamani — [LinkedIn](https://www.linkedin.com/in/franchesco-ancco-472142386/)

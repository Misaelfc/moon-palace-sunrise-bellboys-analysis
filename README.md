# 🏨 Optimización Logística: Departamento de Bellboys (Moon Palace Sunrise)

Este proyecto analiza la eficiencia operativa y el cumplimiento de los acuerdos de nivel de servicio (SLA) para un equipo de 35 bellboys encargados de la atención a más de 1,200 habitaciones.

## 🎯 Objetivo
Elevar el cumplimiento del **SLA de Check-in del 34.8% al 85%** en un periodo de tres meses mediante la optimización de flujos de trabajo basados en datos geográficos y temporales.

## 📊 Problema Identificado
Tras analizar la operación, se detectó que el incumplimiento no se debe a la falta de personal, sino a una **latencia geográfica**:
* **Pico de Demanda:** Existe una demanda bimodal con un punto crítico a las 11:00 AM.
* **Cuello de Botella:** Las áreas con mayor tiempo de espera (hasta 42 min) son las Villas 2 y 3 y el edificio Chile, debido a su distancia de la base central.

## 🛠️ Herramientas Utilizadas
* **Python:** Procesamiento y limpieza de datos con `Pandas`.
* **Análisis Estadístico:** Visualización de distribución de demanda con `Seaborn` y `Matplotlib`.
* **SQL:** Gestión y consulta de la base de datos de servicios.
* **Tableau:** Dashboard interactivo para el mapeo de calor de tiempos de respuesta por sección.

## 💡 Propuesta Estratégica
La solución propuesta consiste en la implementación de una **Estación Satélite** en la Sección Sur para:
1. Reducir los tiempos de traslado en áreas críticas.
2. Bajar el tiempo de espera promedio de **42 a 25 minutos**.
3. Maximizar el uso de los recursos existentes sin incrementar la nómina.

## 📁 Estructura del Repositorio
* `analysis.ipynb`: Notebook con el análisis exploratorio y visualizaciones.
* `datasets/`: Datos simulados de la operación de bellboys.
* `reporte_ejecutivo.pdf`: Resumen de hallazgos y estrategia de negocio.

---
**Analista:** Abraham Flores  
**Formación:** Data Analytics por TripleTen
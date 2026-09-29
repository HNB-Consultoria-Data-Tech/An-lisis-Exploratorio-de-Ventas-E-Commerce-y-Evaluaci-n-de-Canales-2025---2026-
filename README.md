# Análisis Exploratorio de Ventas E-Commerce y Evaluación de Canales (2025 - 2026)

## 📋 Descripción del Proyecto
El presente proyecto corresponde a una **demo de servicio** desarrollada para el portafolio de la consultoría **HNB Consultoría Data & Tech**. Consiste en la ejecución de un ciclo completo de **Data Analytics**, **Business Intelligence (BI)** y **Exploratory Data Analysis (EDA)** sobre el registro histórico de transacciones de una empresa de comercio electrónico (**E-Commerce**) a nivel nacional.

El análisis abarca desde la preparación, limpieza e inspección de datos hasta la generación de **data-driven insights** sobre el volumen transaccional, comportamiento de compra y la dinámica entre los distintos canales de distribución.

## 🎯 Objetivo
Evaluar el desempeño histórico de las ventas en el periodo **Enero 2025 – Agosto 2026** para diagnosticar patrones de consumo, identificar la efectividad de los canales de venta y estructurar una base de datos limpia que sirva como insumo estratégico en la toma de decisiones para el plan de trabajo de Q3 y Q4 de 2026.

## 🔴 Problema de Negocio
La dirección general y el área comercial de la empresa enfrentaban los siguientes retos estratégicos:
* **Falta de visibilidad sobre la estacionalidad:** Ausencia de un diagnóstico claro respecto a las fluctuaciones en la demanda mensual y la concentración de **sales volume** a lo largo del año.
* **Incertidumbre en la efectividad de canales:** Necesidad de auditar y comparar el desempeño individual de cada canal de venta (clientes clave/distribuidores) para determinar su aporte al negocio.
* **Calidad de datos deficiente (Raw Data):** Presencia de datos duplicados, inconsistencias en los tipos de variables y formatos no estandarizados que impedían un reporteo automatizado y confiable.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3
* **Manipulación y Procesamiento de Datos:** `pandas`, `numpy`
* **Visualización de Datos:** `matplotlib`, `seaborn`, `plotly.express`
* **Análisis Estadístico y Fechas:** `scipy.stats`, `datetime`
* **Entorno de Desarrollo:** Jupyter Notebook / VS Code
* **Control de Versiones:** Git & GitHub

## 🎓 Habilidades Demostradas
* **Data Cleaning & Wrangling:** Identificación y depuración de duplicados, normalización de campos, casting de tipos de datos y validación de **missing values**.
* **Exploratory Data Analysis (EDA):** Análisis de tendencias temporales, distribuciones y comportamiento de variables cualitativas y cuantitativas.
* **Business Intelligence & Analytics:** Conversión de datos duros en **insights** accionables para la planeación comercial y la evaluación **omnichannel**.
* **Visualización de Datos:** Creación de gráficos claros y descriptivos para la transmisión efectiva de hallazgos a partes interesadas (stakeholders).
* **Pensamiento Crítico y Negocio:** Traducción de métricas operativas (SKUs, registros, clientes) a decisiones estratégicas.

## 🔗 Insights Relacionados
1. **Comportamiento y Estacionalidad Multianual:**
   * **Ciclo 2025:** Concentración histórica de picos transaccionales en los trimestres Q1 y Q4.
   * **Ciclo 2026:** Repunte significativo durante Q2 y Q3, alcanzando un **peak** histórico de ventas en marzo de 2026 con **81 transacciones**.
2. **Evaluación de Canales (Multi-channel Performance):**
   * **Incursión Estratégica (Canal `3093`):** Tras su incorporación en mayo de 2026, este canal experimentó un crecimiento acelerado, posicionándose como uno de los principales generadores de volumen transaccional hacia agosto de 2026.
   * **Estabilidad del Core (Canal `2808`):** Mantuvo el flujo transaccional más constante durante todo el **timeframe**, logrando su mayor nivel de actividad en abril de 2026.
3. **Distribución del Catálogo:**
   * El volumen total de ventas se distribuye en un catálogo activo de **42 SKUs/artículos**, permitiendo detectar la rotación y dispersión de la demanda.

## 📝 Notas Técnicas
* **Dataset Inicial:** 885 registros transaccionales originales.
* **Deduplicación:** Se identificaron y eliminaron **46 registros duplicados**, obteniendo una muestra limpia de **839 observaciones**.
* **Integridad:** Se verificó la ausencia total de valores nulos (`0` missing values).
* **Estandarización:** Se transformaron los encabezados a formato `snake_case` y se realizó el parseo adecuado de fechas (`datetime`) y claves de clientes (`string`).
* **Confidencialidad:** Los nombres de clientes, precios y métricas confidenciales fueron omitidos o anonimizados para cumplir con las políticas de uso para portafolio.

## 👨‍💼 Autor
**HNB Consultoría Data & Tech**
* **Contacto / LinkedIn:** [Jose Alfredo Gonzalez Neri](https://www.linkedin.com/in/jose-alfredo-gonzalez-neri/?isSelfProfile=true)
* **Rol:** Director Comercial & Desarrollo de Negocio
* **Especialidad:** Business Intelligence · Data Analytics · Estrategia Comercial · Tech Consulting

## 📄 Licencia
Este proyecto se encuentra bajo la licencia **MIT License**. Consulta el archivo `LICENSE` para más detalles sobre su uso libre y distribución.
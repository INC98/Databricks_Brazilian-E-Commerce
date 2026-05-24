# Brazilian E-Commerce Data Engineering Project

Proyecto de ingeniería de datos basado en un dataset público de e-commerce brasileño.  
El objetivo es construir un pipeline ETL utilizando Databricks y generar visualizaciones analíticas en Power BI.

---

# Tecnologías utilizadas

- Databricks
- PySpark
- SQL
- Power BI
- Git / GitHub

---

# Arquitectura del proyecto

El pipeline sigue la siguiente arquitectura:

- Bronze Layer → ingesta de datos crudos
- Silver Layer → limpieza y transformación
- Gold Layer → métricas y tablas analíticas

---

# Dataset

Se utilizó el dataset público Brazilian E-Commerce Dataset by Olist.

Incluye información sobre:

- órdenes
- clientes
- pagos
- productos
- vendedores
- reviews
- geolocalización

---

# Procesamiento de datos

Algunas transformaciones realizadas:

- limpieza de nulos y duplicados
- normalización de columnas
- joins entre entidades
- generación de métricas de ventas
- agregaciones analíticas
- modelado para visualización

---

# Dashboard Power BI

El dashboard incluye:

- KPIs generales
- métricas de vendedores
- métricas de clientes
- tiempos de entrega

---

# Cómo ejecutar

1. Importar datasets en Databricks
2. Ejecutar notebooks ETL
3. Generar tablas finales
4. Abrir archivo Power BI

---

# Autor

Ignacio Castronuovo

- LinkedIn: https://www.linkedin.com/in/ignacio-castronuovo-25a4b61a1/
- GitHub: https://github.com/INC98

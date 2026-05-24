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
  <img width="1006" height="566" alt="image" src="https://github.com/user-attachments/assets/d8e8ee74-7e3a-4ab4-b0ff-2a3d5988e520" />
- métricas de vendedores
  <img width="1009" height="566" alt="image" src="https://github.com/user-attachments/assets/49376cf7-3c4a-4aaa-9a07-30996ffe60d6" />
- métricas de clientes
  <img width="1012" height="566" alt="image" src="https://github.com/user-attachments/assets/9ac1600e-5efa-45f7-b2fb-e1bcae6c7fc9" />
- tiempos de entrega
  <img width="1009" height="566" alt="image" src="https://github.com/user-attachments/assets/8aa47521-4ecc-454e-8161-212059fcef12" />

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

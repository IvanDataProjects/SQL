# Análisis Avanzado de Datos en AdventureWorks con SQL 🔍

## 📌 Descripción del Proyecto

Este proyecto contiene una serie de consultas avanzadas en SQL basadas en la base de datos **AdventureWorks**. El objetivo es realizar análisis sobre diferentes aspectos del negocio, como ventas, empleados, territorios y productos.

El trabajo está dividido en varias fases:

1. **Exploración de datos**: Análisis de las tablas y relaciones relevantes.
2. **Desarrollo de consultas avanzadas**: Realización de consultas SQL para obtener insights clave.

## 🎯 Objetivo

El objetivo principal de este proyecto es:

- Desarrollar consultas SQL para obtener información valiosa y realizar análisis de ventas, empleados y productos.
- Evaluar el rendimiento y la eficiencia de las consultas utilizando las herramientas SQL adecuadas.

## 🧹 Parte 1: Limpieza y exploración de datos

Antes de ejecutar las consultas, es necesario entender la estructura de la base de datos y preparar los datos para el análisis. Esto incluye:

- **Análisis de tablas**: Explorar las tablas de la base de datos para identificar las relaciones entre ellas.
- **Revisión de datos nulos**: Verificar si hay valores nulos en las columnas clave.
- **Selección de columnas relevantes**: Identificar las columnas necesarias para cada consulta.

Una vez entendida la estructura de los datos, se procede a escribir las consultas SQL.

## 📊 Parte 2: Consultas y análisis

Se desarrollan varias consultas avanzadas para extraer información clave de la base de datos:

#### 1. **Ranking de ventas generales**
   - Generación de un ranking de ventas en función del monto (`TotalDue`).

#### 2. **Ranking de ventas por territorio**
   - Creación de un ranking de ventas por cada territorio con los detalles de cada venta.

#### 3. **Contribución de ventas por vendedor**
   - Cálculo de la contribución de cada vendedor a las ventas totales del año.

#### 4. **Fluctuación del tipo de cambio (USD a EUR)**
   - Cálculo de la fluctuación máxima diaria del tipo de cambio entre Dólar y Euro.

#### 5. **Ventas más altas de los dos mejores vendedores**
   - Identificación de las 5 ventas más altas de los vendedores con mayores ventas.

#### 6. **Pedido máximo por producto con alto precio**
   - Análisis de los pedidos de productos con precio superior a 3000 y la identificación del día con más pedidos.

#### 7. **Los dos compradores con mayores compras por territorio**
   - Identificación de los dos compradores que realizaron mayores compras por territorio.

#### 8. **Ventas por categoría y territorio**
   - Generación de una tabla que muestre la cantidad de unidades vendidas por cada categoría y territorio utilizando `PIVOT`.

## 📁 Archivos incluidos

- **consultas.sql**: Archivo que contiene todas las consultas SQL desarrolladas.
- **README.md**: Descripción detallada del proyecto y las consultas.

## 🛠️ Tecnologías utilizadas

- **SQL** (Microsoft SQL Server)
- **AdventureWorks**: Base de datos de ejemplo utilizada para este análisis.

## 🚀 Autor

Iván García Raso  
GitHub - [IvanDataProjects](https://github.com/IvanDataProjects)  
LinkedIn - [Iván García Raso](https://www.linkedin.com/in/ivan-garcia-raso)

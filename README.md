# Sales Performance Dashboard

## 1. Descripción del proyecto

Proyecto de análisis de ventas desarrollado en Power BI para estudiar el rendimiento comercial, identificar tendencias y facilitar la toma de decisiones basadas en datos.

## 2. Herramientas utilizadas

- **Power BI Desktop:** creación del dashboard interactivo y visualización de datos.
- **Power Query:** limpieza, transformación y preparación de los datos.
- **DAX:** creación de medidas e indicadores clave de rendimiento (KPI).
- **CSV:** archivos de datos utilizados como fuente.
- **GitHub:** documentación y publicación del proyecto.

## 3. Datos utilizados

El análisis se basa en datos comerciales que incluyen las siguientes tablas:

- **Pedidos:** identificadores, fechas de pedido y envío, costes de transporte y datos relacionados con la entrega.
- **Detalles de pedidos:** productos, cantidades, precios unitarios y descuentos aplicados.
- **Productos:** nombres, precios, categorías y disponibilidad de los productos.
- **Categorías:** nombres y descripciones de las categorías.
- **Clientes:** empresas, ciudades y países.
- **Empleados:** información sobre los empleados responsables de los pedidos.
- **Transportistas:** empresas encargadas de los envíos.
- **Calendario:** fechas y atributos temporales utilizados para analizar la evolución de las ventas.

## 4. Página 1 — Sales Performance Dashboard

![Sales Performance Dashboard](images/dashboard-overview.png)

Esta página ofrece una visión general del rendimiento de las ventas.

### Indicadores clave (KPI)

- **Total Revenue:** ingresos totales después de aplicar los descuentos.
- **Total Orders:** número de pedidos únicos.
- **Average Order Value:** valor medio por pedido.
- **Units Sold:** cantidad total de unidades vendidas.

### Visualizaciones

- **Revenue Trend Over Time:** evolución mensual de los ingresos.
- **Orders Trend Over Time:** evolución mensual del número de pedidos.
- **Revenue by Category:** comparación de los ingresos entre categorías de productos.
- **Top 10 Products by Revenue:** identificación de los diez productos con mayores ingresos.
- **Filtros interactivos:** permiten analizar los datos por fecha, categoría, país y transportista.

### Objetivo de la página

Proporcionar una visión rápida del rendimiento comercial, identificar las categorías y los productos más relevantes y observar la evolución de los principales indicadores.

**Captura de pantalla:**

*Aquí añadiremos la imagen de la primera página del dashboard.*

## 5. Página 2 — Sales Analysis

![Sales Analysis](images/sales-analysis.png)

Esta página profundiza en el análisis geográfico y en los resultados por cliente y mercado.

### Visualizaciones

- **Sales by Country:** mapa para explorar la distribución geográfica de las ventas.
- **Revenue by Country:** comparación de los ingresos generados en cada país.
- **Matriz de ventas por cliente y producto:** permite consultar unidades vendidas, número de pedidos e ingresos, con posibilidad de ampliar el detalle mediante una jerarquía.
- **Filtros interactivos:** facilitan el análisis de los resultados según los criterios seleccionados.

### Objetivo de la página

Comparar el rendimiento de los distintos mercados, identificar los países con mayor contribución a los ingresos y analizar en detalle el comportamiento de los clientes y productos.

**Captura de pantalla:**

*Aquí añadiremos la imagen de la segunda página del dashboard.*

## 6. Modelado y análisis de datos

Se ha creado un modelo de datos relacional para conectar los pedidos con sus detalles y con las dimensiones de productos, categorías, clientes, empleados, transportistas y calendario.

Se han utilizado medidas DAX para calcular los indicadores principales y permitir que las visualizaciones respondan a los filtros interactivos.

## 7. Objetivos de aprendizaje

- Preparación y transformación de datos.
- Modelado de datos en Power BI.
- Creación de medidas DAX.
- Diseño de dashboards interactivos.
- Análisis de ventas por tiempo, producto, cliente y país.
- Comunicación de resultados mediante visualizaciones.

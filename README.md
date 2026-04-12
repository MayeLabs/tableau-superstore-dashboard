# tableau-superstore-dashboard
Interactive Tableau dashboard analyzing sales and profit  from the Sample Superstore dataset, covering context  filters, date parameters and multi-sheet visualizations.

## Description / Descripción

EN

Practice projects build with tableu Desktop using the sample superstore dataset. Include interactive filters, context filters, dat range sliders, parameter controls, ande multi-sheet dashboards analyzing sales and profit across regions, categories and customer segments.

ES

Proyecto de práctica desarrollado con Tableau Desktop 
usando el dataset Sample Superstore. Incluye filtros 
interactivos, filtros de contexto, sliders de rango 
de fechas, controles de parámetros y dashboards 
multi-hoja para analizar ventas y beneficios por 
región, categoría y segmento.

## Session 1 - Sales Dashboard

EN / ES

- Sales disaggregated by region and category / Ventas desagregadas por región y categoría
- Profit by region with target line / Beneficio por región con línea de target / 
- Sales by subcategories highlighting Binders / Ventas por subcategorías resaltando Binders 
- Average monthly sales - Seasonality analysis/ Promedio de ventas por meses - Análisis de estacionalidad 
- Profit by category and region / Beneficio por categoría y región
- Profitability by category and subcategory /Rentabilidad por categoría y subcategoría
- Sales percentage by category and segment / Porcentaje de ventas por categoría y segmento
-  Sales evolution with trend / Evolución de ventas con tendencia
-  Annual Sales and Cost Comparison / Comparativa de Ventas y Costo anual
- Totals and subtotals table / Tabla de totales y subtotales

### Exercise 1 / Ejercicio 1
---

EN
- Build a customer sales dashboard

As a user, I want to be able to choose one or all customers when visualizing the dashboard, and observe the charts and insights of the selected customer.

The dashboard must include:
* Filters: Customers and Years
* Insights: #Total Sales and #Profit Percentage
* Charts:
    - Sales Evolution - The year filter must not affect this chart
    - Sales disaggregated by category and subcategories
    - Profit by segment
* Table: Top 5 best-selling products for the selected 
customer or all customers


ES
- Realizar un dashboard de ventas por cliente

Yo como usuario, quiero que al visualizar el dashboard, pueda elegir uno o todos los clientes y observar las gráficas e insights del cliente seleccionado.

El dashboard debe tener:
* Filtros: Clientes y Años
* Insigts: #Total de ventas y  #Rentabilidad en porcentaje
* Gráficos:
    - Evolución de ventas - El frilto de año no debe afectar dicho gráfico
    - Ventas desagregadas por categoría y subcategorías
    - Beneficios por segmentos
* Tabla: Top 5 productos más vendidos al cliente 
seleccionado o de todos los clientes

### Exercise 1 - Resolution / Resolución
* Dashboard: Ventas por cliente
* File: `SuperStore_ventasXcliente.twb`

![Customer Sales Dashboard](img/Dashboard_ventasXclientes.png)



## Session 2 - Sales Dashboard / Dashboard de Ventas

### Part I / Parte I

EN / ES

* Sales, discount and profit by category and subcategory / Ventas, descuento y beneficio por categoría y subcategoría
* Grand totals and subtotals / Totales generales y subtotales
* Sales by region and category / Ventas por región y categoría
* Sales by state map / Mapa de ventas por estados
* Sales by state + Tooltip (chart + table) / Ventas por estados + Descripción emergente (gráfico + tabla)
* Sales disaggregated by ship mode / Ventas desagregadas por ship mode
* Dashboard: Sales - Mosaic / Dashboard: Ventas - Mosaico
* Dashboard: Sales - Floating / Dashboard: Ventas - Flotante
* Stories in Tableau / Historias en Tableau

![Dashboard Mosaic](img/SuperStore_MapasTablas/DashboardMosaic.png)
![Dashboard Floating](img/SuperStore_MapasTablas/DashboardFloating.png)


### Part II / Parte II

#### Dashboard design / El diseño del dashboard 
EN

1. What is the objective ?
2. Who is it aimed at? Depending on the answer it will have more or less detail.
3. What are the best char to choose based on the objective ?
4. Priorize simplification, hierarchy and aligment.

Remember that dashboards are as much about the data as 
they are about the charts, so take into account:
- Comparability or context.
- Temporality.
- Filters.

For excellent results, pay attention to composition, 
typography and colors.

ES

1. ¿Cuál es el objetivo?
2. ¿Para quién está dirigido? Según la respuesta tendrá más o menos detalles
3. ¿Cuáles son los mejores gráficos a elegir según el objetivo?
4. Dar prioridad a la simplicidad, jerarquización y alineación.

Recordar que el o los dashboards tienen tanto que ver con los datos 
como con los gráficos, para ello tomar en cuenta:
- La comparabilidad o contextualidad.
- La temporalidad.
- Los filtros.

Para excelentes resultados, fijarse en la composición, tipografía y colores.
# 🍕 Pizza Sales Analysis | Excel + Power BI

Análisis de datos comerciales de una pizzería utilizando **Excel, Power Query y Power BI**, con el objetivo de transformar datos transaccionales en información útil para comprender el comportamiento de las ventas, los clientes y el desempeño del portafolio de productos.

El proyecto sigue un flujo de trabajo de análisis de datos que incluye **limpieza y transformación de datos en Excel**, análisis exploratorio y construcción de dashboards interactivos en Power BI.

---

## 🎯 Objetivo del proyecto

Transformar datos transaccionales de ventas en **insights accionables para la toma de decisiones**, identificando patrones temporales, comportamiento de compra, desempeño de productos y oportunidades comerciales.

El análisis se enfoca principalmente en:

- 📈 Evolución de las ventas.
- 📅 Patrones temporales y estacionalidad.
- 🍕 Desempeño de productos y categorías.
- 📦 Preferencias de tamaño.
- 🕐 Comportamiento según horario.
- 💰 Ticket promedio y variabilidad de las órdenes.
- 📊 Relación entre volumen vendido e ingresos.

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| **Excel** | Exploración y preparación inicial de los datos |
| **Power Query** | Limpieza y transformación |
| **Power BI** | Modelado y visualización |
| **DAX** | Creación de métricas y KPIs |

---

## 💎 Principales métricas

| KPI | Resultado |
|---|---:|
| 💵 Ticket promedio | **16.82** |
| 📊 Desviación estándar por transacción | **4.44** |
| 🍕 Promedio de pizzas por orden | **≈ 1 unidad** |

> Las métricas presentadas corresponden al período analizado en el dataset.

---

## 🔎 Preguntas de negocio

### 📈 Ventas y tendencias

- ¿Cómo evolucionan las ventas a lo largo del año?
- ¿Qué meses y días presentan mayor o menor desempeño?
- ¿Existen patrones estacionales relevantes?

### 🍕 Productos y categorías

- ¿Qué productos presentan mayor y menor demanda?
- ¿Qué categorías y tamaños tienen mayor participación?
- ¿Qué productos generan alto volumen pero menor monetización?

### 🕐 Comportamiento de compra

- ¿En qué períodos del día se concentra la mayor cantidad de órdenes?
- ¿Cuál es la cantidad promedio de pizzas por transacción?
- ¿Existen oportunidades de upselling o promociones?

### 💰 Volumen e ingresos

- ¿Existe relación entre cantidad vendida e ingresos?
- ¿Los productos más vendidos son también los que generan mayores ingresos?
- ¿Qué productos presentan diferencias relevantes entre volumen y monetización?

---

## 💡 Principales insights

- 📅 **El día 15 concentra el mayor volumen de ventas**, mostrando un patrón de consumo relevante dentro del mes.
- 📉 **Febrero presenta una caída importante**, seguida de una recuperación entre marzo y julio.
- 📈 **Las ventas se desaceleran entre agosto y octubre**, con recuperación hacia el cierre del año, especialmente en diciembre.
- 🍕 **The Big Meat Pizza es el producto de mayor volumen**, mientras que **The Italian Capocollo Pizza presenta la menor demanda**.
- 📏 **Los tamaños grandes, especialmente L, concentran gran parte de las ventas**, mostrando una clara preferencia por presentaciones de mayor tamaño.
- 💰 **Mayor volumen no implica necesariamente mayor monetización**: algunos productos venden muchas unidades pero generan menos ingresos por su menor precio unitario.
- 🕐 **La tarde concentra la mayor actividad de compra**, mientras que la mañana presenta el menor volumen de órdenes.
- 💵 **El ticket promedio es de 16.82**, con una desviación estándar de 4.44, mostrando una variabilidad moderada entre transacciones.
- 📦 **El promedio cercano a una pizza por orden** evidencia un patrón de compra de baja cantidad y presenta una oportunidad para estrategias de **upselling y combos**.
- 📊 El análisis evidencia **estacionalidad tanto mensual como intramensual**, información útil para planificar promociones, inventario y personal.

---

## 📊 Dashboard

El proyecto cuenta con **dos dashboards complementarios**:

### 📈 Dashboard — Sales & Operations

Enfocado en el rendimiento general del negocio:

- Ventas.
- Órdenes.
- Unidades vendidas.
- Evolución temporal.
- Categorías.
- Tamaños.
- Comportamiento de las ventas.

![Dashboard de ventas](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/1.png)

### 🍕 Dashboard — Product & Customer Behavior

Enfocado en el comportamiento de compra y desempeño de productos:

- Ticket promedio.
- Precio unitario.
- Volumen por producto.
- Ingresos por producto.
- Relación entre cantidad e ingresos.
- Distribución de órdenes por período del día.

![Dashboard de productos](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/2.png)

---

## 🧩 Modelado de datos

El proyecto utiliza un modelo de datos en Power BI para estructurar la información y facilitar el análisis mediante medidas y relaciones.

![Modelo de datos](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/model.png)

---

## 📌 Conclusión

El análisis muestra que el comportamiento de la pizzería presenta **patrones temporales, preferencias claras de producto y oportunidades de optimización comercial**.

Entre los principales hallazgos destacan la concentración de ventas a mitad de mes, la preferencia por tamaños grandes, la mayor actividad durante la tarde y la diferencia entre **volumen de ventas e ingresos generados**.

Estos resultados pueden utilizarse como punto de partida para desarrollar estrategias de **promociones, upselling, planificación de inventario y optimización del portafolio de productos**.

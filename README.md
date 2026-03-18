# Analisis de datos de Pizzería | Excel + PowerBI 

## Introducción

Este proyecto consiste en el análisis del dataset “Pizza Sales”, obtenido de Kaggle, con el objetivo de explorar el comportamiento comercial y operativo de una pizzería mediante el uso de Excel y Power BI.

El flujo de trabajo comenzó con la carga, limpieza y transformación de los datos en Excel, donde se preparó el dataset para su análisis, asegurando consistencia en campos clave como fechas, cantidades, precios, categorías, tamaños de producto y horarios de compra. Posteriormente, los datos fueron importados a Power BI, donde se desarrollaron dashboards interactivos enfocados en el análisis de métricas clave de negocio.

##

A través de este proyecto se construyeron dos dashboards complementarios:

Un dashboard orientado al rendimiento comercial y operativo, centrado en ventas totales, cantidad vendida, órdenes, comportamiento temporal, categorías y tamaños.

Un dashboard orientado al comportamiento de compra y análisis por producto, centrado en ticket promedio, precios unitarios, volumen por producto, dispersión entre cantidad e ingresos, y distribución de órdenes por período del día.

Este proyecto representa un caso práctico de análisis exploratorio de datos (EDA) y Business Intelligence (BI), aplicando un flujo realista de preparación, análisis y visualización de datos con herramientas ampliamente utilizadas en entornos empresariales.

## Objetivo del proyecto

El objetivo principal de este proyecto es transformar datos transaccionales en información accionable para la toma de decisiones, permitiendo identificar patrones de ventas, comportamiento de compra y desempeño de productos dentro del negocio.

## Preguntas que responde este proyecto

Este proyecto ayuda a responder preguntas clave de negocio como:

¿Cuáles son los meses con mejor y peor desempeño en ventas?

¿Existen patrones estacionales en las ventas?

¿Qué días del mes concentran más compras?

¿Qué productos son los más y menos vendidos?

¿Qué tamaños de pizza prefieren más los clientes?

¿Cómo se comportan las ventas según el período del día?

¿Qué relación existe entre la cantidad vendida y los ingresos?

¿El precio unitario parece influir en la demanda?

¿Cuál es el ticket promedio por transacción?

¿Qué tan variable es el valor de las órdenes?

¿Qué productos generan alto volumen pero menor monetización?

¿Dónde existen oportunidades de upselling o promociones?

## Objetivos específicos:

- Analizar la evolución de las ventas a lo largo del tiempo.

- Identificar los meses y días con mejor y peor desempeño.

- Detectar los productos con mayor y menor demanda.

- Evaluar el impacto del tamaño y la categoría del producto en las ventas.

- Analizar la relación entre volumen vendido e ingresos generados.

- Comprender los patrones de compra según el momento del día.

- Estimar el ticket promedio y la dispersión del valor de las transacciones.

- Detectar oportunidades comerciales para promociones, upselling y optimización del portafolio.

## Insights clave del análisis

1. Concentración de ventas a mitad de mes

Se observa que el día 15 concentra el mayor volumen de ventas dentro del mes, lo que sugiere un posible patrón de consumo asociado a la mitad de mes. Una hipótesis razonable es que este comportamiento pueda estar relacionado con fechas de pago o mayor liquidez del cliente, aunque sería necesario validarlo con información adicional.

2. Debilidad en febrero y recuperación entre marzo y julio

Se observa una caída relevante en febrero, seguida de una recuperación y un período de desempeño estable y favorable entre marzo y julio, lo que indica una etapa de mayor rendimiento comercial dentro del año analizado.

3. Desaceleración entre agosto y octubre, con recuperación al cierre

Entre agosto y octubre se observa una desaceleración en ventas, concentrando algunos de los niveles más bajos del período analizado. Posteriormente, se aprecia una recuperación hacia el cierre del año, especialmente en diciembre.

4. Producto más vendido y producto de menor demanda

The Big Meat Pizza fue el producto con mayor volumen de ventas, mientras que The Italian Capocollo Pizza presentó el menor nivel de demanda dentro del grupo analizado. Esto sugiere oportunidades para revisar estrategias de posicionamiento, visibilidad o promociones del producto de menor rotación.

5. Preferencia por tamaños grandes

En la mayoría de las categorías, los tamaños grandes (especialmente L) concentran el mayor volumen de ventas, lo que sugiere una preferencia del cliente por presentaciones de mayor tamaño frente a opciones pequeñas o extra grandes.

6. Relación positiva entre cantidad vendida e ingresos

Existe una relación positiva entre la cantidad vendida y los ingresos generados: a mayor volumen, mayores ventas totales. Sin embargo, The Big Meat Pizza destaca como una excepción relevante, ya que presenta un volumen muy alto de ventas pero una generación de ingresos relativamente menor frente a otros productos con menor cantidad, lo que puede estar asociado a un precio unitario más bajo.

7. Mayor actividad de compra en la tarde

El mayor volumen de órdenes se concentra en la tarde, mientras que la mañana representa el menor nivel de actividad. Esto sugiere una oportunidad para diseñar estrategias de activación en horario matutino, como combos, promociones tempranas o productos adaptados a ese segmento horario.

8. Posible influencia del precio en la demanda

Se observa que varias de las pizzas con mayor volumen de ventas también se encuentran entre las de menor precio unitario, lo que sugiere que el precio podría influir en la demanda. Sin embargo, sería recomendable profundizar este análisis con una comparación más estructurada entre precio, volumen e ingresos por producto.

9. Patrón de compra de baja cantidad por orden

La cantidad promedio de pizzas compradas por transacción es cercana a 1 unidad, lo que sugiere un patrón de compra predominantemente individual o de baja cantidad por orden. Esto abre oportunidades para estrategias de upselling, combos o promociones por volumen.

10. Ticket promedio y variabilidad de las transacciones

El ticket promedio se sitúa en aproximadamente 16.82, con una desviación estándar cercana a 4.44, lo que indica una dispersión moderada en el valor de las transacciones. En términos prácticos, la mayoría de las órdenes tienden a mantenerse relativamente cerca del ticket promedio, aunque existen variaciones relevantes entre compras.

11. El negocio presenta estacionalidad intramensual y estacionalidad mensual

El comportamiento de ventas no es completamente uniforme: se observan patrones tanto dentro del mes (pico en torno al día 15) como a nivel anual (meses fuertes y meses débiles), lo que sugiere que el negocio presenta una estacionalidad de doble nivel que puede ser útil para planificar inventario, personal y campañas promocionales.

13. El dashboard permite diferenciar entre volumen y rentabilidad

Uno de los hallazgos más importantes del análisis es que vender más unidades no siempre implica generar proporcionalmente más ingresos. Esto es valioso porque introduce una distinción clave entre popularidad del producto y aporte económico real, algo muy importante en análisis de negocio.

## Dashboard

![1.png](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/1.png)

![2.png](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/2.png)

## Modelado de datos

![model.png](https://github.com/aacekm-7/PizzaSales-Excel-PowerBI-SQL/blob/2279f2d96b65f2c12011f6a14df55f767a3f8c4d/model.png)

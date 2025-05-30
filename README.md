
# Análisis Estratégico de Ventas de Adidas en EE.UU.

## 📄 Descripción del Proyecto

En este proyecto, analizo datos de ventas de Adidas en EE.UU. para identificar patrones clave que optimicen la estrategia comercial. Los datos cubren ventas por región, retailer, producto y método de venta.

**Objetivo:** Identificar oportunidades para mejorar márgenes, redistribuir recursos y potenciar métodos de venta efectivos.

Para analizar y extraer recomendaciones, he desarrollado cuatro dashboards que permiten examinar la información de manera segmentada, según los siguientes enfoques:

📊 Desempeño de Ventas y Rentabilidad.

🏪 Eficiencia de Retailers.

🌎 Análisis Geográfico.

🛍️ Efectividad del Método de Venta.

📍 Queda a disposición de quien desee consultar el archivo de Power BI adjunto (Proyecto Adidas US Sales.pbix) para explorar el proyecto en mayor profundidad. De este modo, cualquier interesado puede analizar en detalle los datos, visualizaciones y conclusiones desarrolladas a lo largo del análisis.

## 🔍 Fuente de la Base de Datos

Los datos empleados en este proyecto provienen del conjunto [Adidas US Sales ](https://www.kaggle.com/datasets/sagarmorework/adidas-us-sales/data), disponible en la plataforma Kaggle. Aunque se trata de una base de datos ficticia, ha sido diseñada para simular de manera realista los datos transaccionales típicos de un entorno minorista. Si deseas explorar el conjunto de datos en mayor profundidad, puedes hacerlo accediendo al enlace anterior.

Es importante tener en cuenta que, al tratarse de datos simulados, muchas de las conclusiones y recomendaciones derivadas del análisis podrían diferir de la realidad. Esto puede deberse a factores como la limitada variedad de productos, minoristas, estados o ciudades representados en el dataset, entre otros motivos.

## 👨‍🎓 Habilidades Demostradas

| Herramientas para Power BI                | Habilidades necesarias para crear dashboards en Power BI        |
|-------------------------------------------|-----------------------------------------------------------------|
| Power BI Desktop                          | Conexión e integración de fuentes de datos                      |
|                                           | Modelado de datos y establecimiento de relaciones               |
| Power Query                               | Transformación y limpieza de datos                              |
| DAX (Data Analysis Expressions)           | Creación de medidas, KPIs y cálculos personalizados             |
| Visualizaciones integradas (gráficos, tablas, mapas, etc.) | Selección y personalización de visualizaciones adecuadas         |
| Segmentaciones y filtros                  | Diseño de dashboards interactivos                               |
| Temas y plantillas                        | Aplicación de principios de diseño visual y consistencia         |
| Paneles y bookmarks                       | Organización y navegación eficiente en el dashboard              |


## 🧵 Empezamos con el análisis

### 📊 Dashboard 1. Desempeño de Ventas y Rentabilidad:

#### Ventas por Región:
- La Región Oeste encabeza las ventas con el 26,9% del total (23 millones de dólares en 2021), destacando California como el estado con mayores ventas dentro de la región (7 millones de dólares). En contraste, el Sureste registra ventas por 13 millones dólares, equivalentes al 16% del total, siendo Kentucky el estado con menor contribución en la región (1 millón  dólares, 9%).
- En cuanto a las ganancias brutas, el Oeste también lidera con el 23,7% del total (5 millones de dólares), y California aporta el 29% dentro de la región. El Sureste alcanza 3 millones de dólares en ganancias brutas, el 15,3% del total, con Kentucky como el estado de menor aporte (393.590 dólares, 11%).
- **Recomendación:** Incrementar inversión en California y replicar estrategias de precios en regiones con bajo margen.

#### Productos con Mayor/Menor Margen:
- El calzado de calle para hombre tiene el margen más alto (26,8%), mientras que el calzado deportivo de mujer tiene el más bajo (11,6%).
- **Recomendación:** Promocionar paquetes que combinen productos de alto y bajo margen para equilibrar rentabilidad.

#### Tendencia Temporal: 
- Las ventas en 2021 alcanzaron la cifra de 86,8 millones de dólares, un ascenso en las ventas del 260% respecto al año anterior. Por otro lado, las ganancias brutas ascendieron a 24,2 millones.
- **Recomendación:** Capitalizar el crecimiento explosivo reforzando la inversión en canales digitales (publicidad segmentada y logística para demanda estacional) y optimizar el margen bruto (actualmente ~28%) mediante estrategias de pricing dinámico.

#### 🔴 Extra. Ejemplo de análisis del "Waterfall Chart" del dashboard 1:

![2021 - Crecimiento Mensual](1imagen.PNG)

**Tendencia general:** Extremadamente volátil, con variaciones desde **+579%** (enero) hasta **-17%** (febrero).

**Patrones destacados:**
  - **Crecimiento explosivo en enero (+579%):** Posible efecto rebote post-cierre fiscal 2020 o lanzamiento de colección limitada.
  - **Caídas consecutivas:**
    - Febrero (-17%): Corrección tras crecimiento insostenible de enero. 
    - Marzo (-16%): Posible agotamiento de inventario inicial.
    - Septiembre (-14%) y octubre (-16%): Posible efecto de crisis logística global.
    
**Hallazgos clave:**  
1. **Ciclo anómalo:**  
   - El crecimiento de enero distorsiona la base comparativa, haciendo caídas posteriores más pronunciadas.
2. **Riesgo operativo:**
   - Las caídas en marzo y septiembre-octubre sugieren problemas de planificación de inventario o demanda sobrestimada.  

**Recomendación:**
- **Análisis de enero:** Investigar si el pico se debió a:
  - Ventas acumuladas de diciembre 2020 reportadas en enero o al éxito de producto específico.  
- **Ajuste de metas:**  
  - Usar promedios móviles (ej: últimos 3 meses) para evitar distorsiones por posisibles outliers como enero. 

---

### 🏪 Dashboard 2. Eficiencia de Retailers:

#### Retailers Top:
- Sports Direct tiene el mayor volumen (22 millones de dóalares) y yel mejor margen (30%).
- **Recomendación:** Negociar mejores condiciones con retailers de alto margen.

#### Retailer con el margen más bajo:
- Walmart mantiene un margen saludable (23%), pero su volumen de ventas (106.427 unidades) es bajo comparado con líderes como Sports Direct (498.941 unidades)
- **Recomendación:** Potenciar la relación con Walmart para escalar ventas sin comprometer el margen.

#### 🔴 Extra. Ejemplo de análisis del "heatmap" del dashboard 2:

![2021 – Relación Ventas vs. Margen de Ganancia por Retailer](2imagen.PNG)

El heatmap muestra la relación entre ventas totales y margen de ganancia para cinco retailers principales en 2021 (Amazon, Foot Locker, Kohl’s, Sports Direct, Walmart y West Gear), normalizados en una escala de 0 a 1. Se observan diferencias notables en la eficiencia operativa y la rentabilidad entre los distintos actores.

**Patrones destacados:**
- **Sports Direct:** Lidera tanto en margen de ganancia (1.00) como en ventas totales (1.00), posicionándose como el retailer más eficiente del grupo. Esto indica una operación equilibrada donde se maximiza tanto la rentabilidad como el volumen de ventas.

- **Walmart:** Presenta los valores más bajos en ambas métricas (0.00), lo que sugiere un desempeño deficiente en 2021, posiblemente afectado por factores externos o una estrategia de bajo margen para mantener precios competitivos.

- **Foot Locker:** Destaca por su alto nivel de ventas (0.86), pero su margen de ganancia es moderado (0.56). Esto puede indicar una estrategia de volumen alto con márgenes ajustados, típica de grandes cadenas especializadas.

- **Amazon:** Muestra un margen de ganancia relativamente alto (0.74) pero ventas bajas (0.20), lo que podría reflejar un enfoque en segmentos premium o una optimización de rentabilidad sobre volumen en ciertas líneas de negocio.

- **West Gear y Kohl’s:** Ambos presentan valores intermedios en ambas métricas, lo que sugiere una posición equilibrada pero sin destacar en eficiencia extrema ni en debilidad.

**Hallazgos clave:**

- **Desalineación entre ventas y margen:** No existe una correlación directa entre alto volumen de ventas y alto margen de ganancia en todos los casos.

**Recomendación:**

- **Benchmarking de Sports Direct:** Analizar en detalle las prácticas de Sports Direct para identificar factores clave que permitan replicar su eficiencia en otras cadenas.
- **Revisión de estrategia en Walmart:** Investigar causas de bajo desempeño y considerar ajustes en la estrategia de precios, surtido o eficiencia operativa.
- **Monitoreo continuo:** Implementar sistemas de alerta temprana para detectar desviaciones significativas en ventas o márgenes y reaccionar proactivamente.
---

### 🌎 Dashboard 3. Análisis Geográfico:

#### Ciudades Clave:
- Orlando, Los Ángeles y San Francisco concentran el 15% de las ventas. Charlotte destaca en ventas online (8,2% del total local).
- **Recomendación:** Asignar más presupuesto de marketing digital en ciudades con alta penetración online.

#### Método por Ubicación:
- Los outlets son populares en áreas suburbanas (ej: Orlando, zonas residenciales), mientras que las tiendas físicas tradicionales dominan en centros urbanos (ej: Manhattan, distritos comerciales).
- **Recomendación:** Aprovechar esta segmentación geográfica para optimizar la estrategia omnicanal.

#### 🔴 Extra. Ejemplo de análisis del scatter chart del dashboard 3:

![2021 – Relación Ventas vs. Ganancia Operativa por Región](3imagen.PNG)

El scatter chart muestra la relación entre ventas totales y ganancias operativas en distintas regiones durante 2021. Cada punto representa un Estado, permitiendo visualizar cómo se distribuyen los resultados en términos de eficiencia operativa y volumen de ventas.

**Patrones destacados:**
- **Tendencia positiva:** Existe una correlación clara y positiva entre ventas y ganancias operativas: a mayor nivel de ventas, generalmente se observa mayor ganancia operativa. La mayoría de los puntos se agrupan en el rango de $0M a $4M en ventas y $0M a $1M en ganancias operativas.

- **Estado sobresaliente:** California, el punto situado en la esquina superior derecha indica un desempeño excepcional tanto en volumen como en eficiencia.

- **Agrupación principal:** La mayoría de las regiones se concentran en niveles intermedios, sin grandes outliers negativos, lo que sugiere una gestión relativamente homogénea en la mayoría de los mercados.

**Hallazgos clave:**
- **Consistencia operativa:** La alineación de los puntos en una diagonal ascendente indica que, en general, las regiones mantienen una relación proporcional entre ventas y ganancias operativas.

- **Desempeño destacado:** La región con el mayor volumen de ventas y ganancias operativas puede servir como referencia para identificar prácticas exitosas que puedan replicarse en otras áreas.

- **Ausencia de rezagados extremos:** No se observan regiones con ventas altas y ganancias operativas bajas, lo que sugiere que no hay mercados con problemas severos de rentabilidad a pesar de vender mucho.

**Recomendación:**
- **Benchmarking estatal:** Analizar en profundidad la región con mejor desempeño para extraer aprendizajes y mejores prácticas aplicables a otras regiones.

- **Optimización continua:** Mantener el monitoreo de la relación ventas/ganancia operativa para detectar desviaciones y actuar rápidamente si alguna región se aleja de la tendencia positiva.

---

### 🛍️ Dashboard 4. Efectividad del Método de Venta:

#### Margen por Unidad:
- Venta física lidera en margen por unidad (17,7$), pero el online vende 1,7 veces más unidades.
- **Recomendación:** Usar datos de clientes online para impulsar ventas cruzadas.

#### Impacto en Volumen:  
- Los outlets tienen baja rotación pero alto margen en productos exclusivos.
- **Recomendación:** Optimizar la estrategia de outlets para maximizar su potencial.

#### 🔴 Extra. Ejemplo de análisis de la tabla de métodos de venta – Dashboard 4.
**2021 – Relación Unidades Vendidas, Ventas Totales y Margen de Ganancia por Canal de Venta**

**Patrones destacados:**

| Canal      | Unidades Vendidas | Ventas Totales     | Margen de Ganancia (%) | Ganancia por Unidad ($) | Variación Margen (%)   | Observaciones                                                                 |
|------------|------------------|--------------------|-----------------------|------------------------|-----------------------|------------------------------------------------------------------------------|
| Online     | 759.332          | $35.819.499        | 23,1                  | $10,9                  | +392,53               | Mayor volumen de ventas, menor margen y ganancia por unidad, gran mejora anual|
| Outlet     | 602.296          | $27.774.577        | 26,9                  | $12,4                  | -6,39                 | Volumen y ventas intermedios, caída de margen, posible presión competitiva    |
| In-store   | 478.455          | $23.198.450        | 36,5                  | $17,7                  | +8,55                 | Menor volumen, mayor margen y ganancia por unidad, crecimiento saludable      |

**Hallazgos clave:**

- **Desalineación entre volumen y rentabilidad:** El canal online lidera en ventas y crecimiento de margen, pero sigue siendo el menos rentable por unidad. In-store, aunque vende menos, es el más rentable.

- **Riesgo en outlet:** La caída del margen en outlet requiere análisis, ya que puede afectar la sostenibilidad del canal si la tendencia continúa.

**Recomendación:**

- **Profundizar en la mejora online:** Analizar qué factores impulsaron la mejora del margen online para replicarlos y consolidar el canal como motor de crecimiento rentable.

- **Revisión estratégica en outlet:** Investigar causas de la caída del margen (costos, precios, competencia) y definir acciones correctivas.

- **Potenciar la experiencia in-store:** Aprovechar la alta rentabilidad del canal físico para ofrecer experiencias diferenciadas y productos premium que mantengan el margen elevado.

---

## 💡 Conclusiones y Acciones Propuestas

### 🔑 Hallazgos Clave:
1. **California y el retailer "Sports Direct" son joyas ocultas** por su alto margen.
2. **El canal online necesita optimizar costos** para mejorar su rentabilidad.
3. **Productos con bajo margen** podrían empaquetarse con artículos premium.

### 🚀 Acciones Recomendadas:
- **Lanzar una campaña regional** en California con productos de alto margen.
- **Capacitar a vendedores físicos** en técnicas de upselling.
- **Rediseñar la estrategia de outlets** para atraer tráfico con eventos locales.

### 📌 Nota:

En varias de las conclusiones y recomendaciones, cuando aparecen datos exagerados o muy sesgados, se busca deliberadamente ofrecer una explicación plausible y realista. Sin embargo, soy conscientes de que, en muchos casos, estas irregularidades se deben principalmente a la naturaleza ficticia del conjunto de datos. Este ejercicio permite mantener la coherencia del análisis, aunque es importante reconocer que algunas anomalías reflejan limitaciones inherentes al dataset simulado y no necesariamente situaciones reales del mercado.

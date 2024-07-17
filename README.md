# Proyecto Individual de Data Analyst
## Descripción del Proyecto
Las telecomunicaciones juegan un papel vital en la sociedad moderna, facilitando la comunicación y el intercambio de información a través de medios electrónicos como la telefonía, la televisión, la radio y el internet.
Este proyecto se centra en el análisis del sector de las telecomunicaciones en Argentina, con un énfasis particular en el acceso a internet y otros servicios de comunicación.

La tarea principal es realizar un análisis exploratorio de datos (EDA) y desarrollar un dashboard interactivo para identificar patrones, oportunidades de crecimiento y áreas de mejora para una empresa prestadora 
de servicios de telecomunicaciones.

## Contenido del Repositorio

- dataset: Carpeta con los arhivos obtenidos a partir de el ETL para proceder al analisis de datos con power BI
- Desarrollo.ipynb: notebook donde se realizo la ETL y el analisis exploratorio de datos
- Diccionario de datos PIDA.docx: diccionario de los archivos entregados para realizar el enalisis de datos

## Estructura del Proyecto
Análisis Exploratorio de Datos (EDA)
En el notebook Desarrollo.ipynb se realiza un análisis exhaustivo de los datos, documentando cada paso con claridad. Los aspectos cubiertos incluyen:

Detección de valores faltantes: Identificación y tratamiento de valores nulos.
Valores atípicos/extremos: Análisis de outliers y su impacto en los datos.
Registros duplicados: Identificación y eliminación de registros duplicados.
Visualización de datos: Gráficos y visualizaciones iniciales para entender mejor los datos.

Dashboard Interactivo
El dashboard interactivo se encuentra en el archivo DA_telecomunicaciones.pbix y permite explorar los datos de manera detallada con filtros interactivos. Los aspectos clave del dashboard incluyen:

Filtros interactivos: Permiten explorar los datos según diferentes criterios (e.g., provincia  y año).
Claridad en la presentación de datos: Diseño intuitivo que facilita la interpretación de la información.
Visualizaciones coherentes: Uso adecuado de gráficos según el tipo de variable a visualizar.
KPIs
En el script Desarrollo.ipynb se calcula el KPI propuesto y dos KPIs adicionales que consideramos relevantes para la temática. Los KPIs propuestos son:

Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia:

Fórmula: KPI = ((Nuevo acceso - Acceso actual) / Acceso actual) * 100
Este KPI mide el aumento en el acceso a Internet por cada 100 hogares en cada provincia.
KPI 2: Rendimiento esperado al año

Fórmula: ((acceso total proximo año/trimestre - acceso total año/trimestre actual) / acceso total año/trimestre actual) * 100
Descripción: [Tiene como objetivo medir el rendmiento de acceso de gente al acceso internet el cual puede indicar como van mejorando los ingresos a partir de un mayor acceso y/o observando si es que se está 
disminuyendo el acceso por principalmente cambios de tecnologías, cambios de rangos de internet, etc.]

KPI 3: [Rendimiento de los ingresos]

Fórmula: [((Ingresos del proximo año - Ingreso actual) / Ingreso actual) * 100]
Descripción: [Tiene como objetivo ver el rendimiento en las ganancias ya sea por el aumento de personas que contratan internet independiente de la tecnologia y/o rango de internet contratado
con este es posible llevar a cabo un analisis más exhaustivo en los años que se haya generado disminuciones en los rendimientos y poder analizar en profundidad las posibles causas que estén generando
la disminuciones en los rendimientos como también poder tomar decisiones informadas a partir de este.]

## Reporte de Análisis

A partir de lo obtenido en el dashboard de power Bi fue posible observar que la mayoria de la concentranción de accesos a internet son principalmente en las ciudades de Buenos aires, Capital Federal, Córdoba y santa Fe,
Quedando una serie de provincias practicamente "Aisladas" para el acceso de internet, lo cual puede deberse a las lejanias que presentan estas a la capital. lo cual también se genera en otros países como chile donde las
regiones del sur de esta presentan dificultas por facilitar la señal a las comunidades más lejanas a la población generando que distintas entes busquen facilitar el acceso a internet mediante señales satelitales. Una buena
manera de poder incrementar los accesos a internet y en consecuencia un aumento de ingresos seria el descentralizar la implementación de internet, ya que estamos en una época donde el internet está siendo utilizado practicamente
para todo, por otro lado, se debe investigar el por qué los rendimientos de provincias del norte y sur de argentina presentaban buenos rendimientos en el año 2014 para luego ir disminuyendo drásticamente, sabiendo esto es posible
tomar otro enfoque para poder retomar ese rendimiento y la metodología que se estaba implementado para que las personas de estos sectores obtuvieran acceso a internet.

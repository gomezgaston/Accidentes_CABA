<p align='center'>
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>

# **Siniestros viales**</h1>
<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 500>
<p>


## Introducción
Este proyecto final individual se enfoca en la posición de **"Data Analyst"** en la institución en la que actualmente estoy estudiando.

Para este proyecto, se nos presentó el siguiente contexto:

>## **Descripción del problema**
>------
>Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.
>
>En el contexto de una ciudad como Buenos Aires, los siniestros viales pueden ser una preocupación importante debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.
>
>Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Estas tasas se calculan, generalmente, como el número de muertes por cada cierto número de habitantes o por cada cierta cantidad de vehículos registrados. Reducir estas tasas es un objetivo clave para mejorar la seguridad vial y proteger la vida de las personas en la ciudad.
>
>Es importante destacar que la prevención de siniestros viales involucra medidas como la educación vial, el cumplimiento de las normas de tráfico, la infraestructura segura de carreteras y calles, así como la promoción de vehículos más seguros. El seguimiento de las estadísticas y la implementación de políticas efectivas son esenciales para abordar este problema de manera adecuada.
>
>## **Contexto**
>-----
>En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país.
>Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.
>
>Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.
>
>### **Rol a desarrollar**
>
>El `Observatorio de Movilidad y Seguridad Vial` (OMSV), centro de estudios que se encuentra bajo la órbita de la ***Secretaría de Transporte*** del Gobierno de la Ciudad Autónoma de Buenos Aires, nos solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.
>Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato *xlsx* y contiene dos hojas llamadas: **hechos** y **víctimas**. Asimismo, observarán que incluye otras dos hojas adicionales de diccionarios de datos, que les podrá servir de guía para un mayor entendimiento de la data compartida.
>
## **Objetivos y alcances**: 

El presente proyecto tiene como objetivo la realización de un MVP (Producto Mínimo Viable) siguiendo las pautas de evaluación proporcionadas. La ejecución del mismo se llevará a cabo en un plazo de 5 días, durante los cuales se buscará aprovechar al máximo las directrices entregadas, sin perder de vista el espíritu que representa un MVP.

## Herramientas Utilizadas
-----

### Para la realizacion de este proyecto se utilizaron las siguientes herramientas:

+ **Visual Studio Code**: 
   Se utilizo como editor de codigo y generador de virtual enviroments. 

+ **Python**:
   Lenguaje de programacion utilizado en el proyecto.

+ **Jupyter Notebooks**:
   Entorno utilizado para la organizacion, del proyecyo.

+ **Matplotlib**:
   Para la realizacion de graficos dentro del entorno de trabajo Jupyter.

+ **GitHub**:
   Para realizar control de versiones y disponibilizar mi repositorio a Render.

+ **PowerBi**:
    Para la realizacion de la presentacion y dashboard interactivo

+ **Power Query y DAX**:
    Para hacer las transformaciones necesarias dentro del entorno de PowerBi

## Introducción
En la realización del siguiente proyecto, se emplearon diversas técnicas y herramientas para llevar a cabo las distintas etapas del proceso.

A continuación, se describen las principales herramientas utilizadas:

### 1. Transformación de Datos con Pandas
En la fase inicial, se utilizó la librería **Pandas** para llevar a cabo la transformación de datos. Este trabajo se documentó en el archivo `EDA.ipynb`, donde se realizó un breve análisis exploratorio de nuestro conjunto de datos con el objetivo de obtener una comprensión preliminar del mismo y una orientacion tecnica. Además, se llevaron a cabo pequeñas transformaciones e imputaciones de datos para facilitar las etapas posteriores del proceso.

### 2. Análisis Exploratorio de Datos (EDA)
Durante la etapa de análisis exploratorio de datos, también conocida como **EDA** (Exploratory Data Analysis), se hicieron uso de las siguientes librerías:
- **Pandas**: Para manipulación y análisis de datos.
- **Matplotlib**: Para la creación de visualizaciones gráficas.
- **Seaborn**: Para la mejora de la visualización de datos y la generación de gráficos estadísticos.


### 3. Presentación con Microsoft Power BI

INSERTAR DASH 0

Para la presentación final del proyecto, se llevará a cabo una exposición oral de los procesos y conclusiones obtenidas. Esta presentación se respaldará con un **dashboard interactivo** creado utilizando **Microsoft Power BI**. 

Este panel de control contiene dos tableros interactivos: uno con datos generales y otro en el cual se representarán los indicadores clave de rendimiento (KPIs).

INSERTAR DASH 1
##### Dashboard de proposito general

En resumen, las herramientas utilizadas abarcaron desde la transformación inicial de los datos con Pandas, pasando por el análisis exploratorio con Pandas, Matplotlib y Seaborn, hasta la presentación final con Microsoft Power BI.

--- 

## *Informe de Análisis de Accidentes de Tráfico en la Ciudad de Buenos Aires (CABA)*

Este informe tiene como objetivo analizar los datos de accidentes de tráfico en la Ciudad de Buenos Aires (CABA) para identificar tendencias y patrones significativos que puedan contribuir a mejorar la seguridad vial en la ciudad.

### Resumen de Hallazgos

En este análisis exploratorio de datos, hemos realizado las siguientes observaciones clave:

### Ubicación de Accidentes

- La mayoría de los accidentes fatales ocurren en avenidas y en intersecciones, lo que sugiere la necesidad de enfocar los esfuerzos de seguridad en estos puntos críticos.

INSERTAR data 1


### Accidentes por Año y Mes

- Se observa una disminución en los accidentes fatales en 2020, posiblemente relacionada con las medidas de distanciamiento social debido a la pandemia. Esto resalta la influencia de eventos externos en los datos.


### Categorización de Víctimas y Acusados

- Las víctimas más comunes son motociclistas y peatones, mientras que las principales categorías de acusados incluyen autos particulares, transporte de pasajeros y transporte de carga. Estos hallazgos pueden guiar las políticas de tráfico y seguridad vial.

INSERTAR data 2

### Género de las Víctimas

- La mayoría de las víctimas son de género masculino. Aunque este dato es relevante, se necesita una investigación adicional para comprender completamente su significado y posibles implicaciones.

### Comunas

- Se identifican diferencias significativas en las tasas de fatalidades entre las comunas de CABA. Algunas comunas son más propensas a accidentes que otras, lo que puede guiar la focalización de esfuerzos de seguridad vial.



##  KPIs
----

A raíz de estas conclusiones que hemos obtenido y con el objetivo de reducir la gravedad de los accidentes de tránsito, se proponen los siguientes indicadores clave de desempeño (KPIs):

### 1. Reducción de la Tasa de Homicidios en Siniestros Viales
- **Objetivo**: Reducir en un 10% la tasa de homicidios en siniestros viales en los últimos seis meses, en la Ciudad Autónoma de Buenos Aires (CABA), en comparación con la tasa del semestre anterior.
  
- **Definición de la Tasa de Homicidios en Siniestros Viales**: La tasa de homicidios en siniestros viales se calcula como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.

### 2. Reducción de la Cantidad de Accidentes Mortales de Motociclistas
- **Objetivo**: Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en la Ciudad Autónoma de Buenos Aires (CABA), respecto al año anterior.
  
- **Definición de la Cantidad de Accidentes Mortales de Motociclistas en Siniestros Viales**: La cantidad de accidentes mortales de motociclistas se refiere al número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un período de tiempo determinado. 

### 3. Cantidad de Accidentes Mortales de Peatones en Siniestros Viales
- **Propósito**: Reducir un 5% la cantidad de accidentes mortales de peatones en siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) en el último año.
  
- **Definición**: La cantidad de accidentes mortales de peatones se refiere al número absoluto de accidentes fatales en los que estuvieron involucradas víctimas transeúntes en un período de tiempo de un año.

### 4. Cantidad de Accidentes Mortales en Intersecciones
- **Propósito**: Reducir en un 10% la cantidad de accidentes mortales que ocurren en intersecciones de calles en la Ciudad Autónoma de Buenos Aires (CABA) en el último año.
  
- **Definición**: La cantidad de accidentes mortales en intersecciones se refiere al número absoluto de accidentes fatales que ocurren en puntos de cruce entre dos o más calles, independientemente de los tipos de vehículos involucrados, durante un período de tiempo de un año.

Estos KPIs se diseñaron con el objetivo de medir y mejorar la seguridad vial en la Ciudad Autónoma de Buenos Aires, proporcionando métricas clave para evaluar el desempeño y la efectividad de las medidas de prevención y seguridad implementadas.

INSERTAR DASHBOARD 2
##### dashboard KPI



### Datos
**Obligatorio:**
- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): Se utilizará el dataset denominado `Homicidios`



# Nombre del Proyecto

## Contexto
En los últimos años, el mercado de las criptomonedas ha experimentado un crecimiento exponencial y una creciente adopción a nivel mundial. La aparición del Bitcoin en 2009 marcó el inicio de una revolución financiera que ha llevado a la creación de miles de criptomonedas diferentes con diversas funcionalidades y tecnologías subyacentes.

Con el aumento del interés en el mercado de criptomonedas, cada vez más inversores, empresas y entusiastas buscan comprender mejor el comportamiento y la evolución de estos activos digitales. Sin embargo, la naturaleza altamente volátil y compleja de las criptomonedas presenta desafíos significativos para aquellos que desean tomar decisiones informadas sobre inversiones o simplemente para comprender mejor cómo funcionan estos mercados emergentes.

El análisis y la exploración de datos desempeñan un papel crucial en la obtención de información valiosa dentro del vasto conjunto de datos disponibles sobre criptomonedas. En este contexto, es clave el uso de una valiosa fuente de datos actualizados que proporcionen información sobre una amplia variedad de criptomonedas, incluidos precios, volúmenes de negociación, capitalización de mercado, información histórica y más.

## Proceso ETL

### Extracción

Los datos se extraen de diversas fuentes confiables y populares en el ámbito de las criptomonedas, como CoinGecko, CoinMarketCap, y otras APIs relacionadas. Estas plataformas ofrecen acceso a una amplia variedad de datos que abarcan desde precios en tiempo real hasta históricos de transacciones y métricas específicas de cada criptomoneda.

### Transformación

Una vez extraídos, los datos pasan por un proceso de limpieza y transformación. Esto implica:

- Normalizar las diferentes estructuras de datos provenientes de múltiples fuentes.
- Identificar y gestionar posibles valores faltantes o inconsistentes.
- Crear características derivadas que puedan ser relevantes para el análisis, como indicadores técnicos o métricas específicas relacionadas con la volatilidad.
- Agrupar y segmentar los datos para facilitar su posterior análisis y visualización.

### Carga

Tras la transformación, los datos se cargan en una base de datos optimizada para consultas analíticas. Desde allí, se alimentan al dashboard y a las diversas herramientas de análisis para proporcionar insights valiosos y facilitar la comprensión del mercado de criptomonedas.

## Análisis Exploratorio de Datos (EDA)

El EDA, en el marco de este proyecto, se ha enfocado principalmente en comprender el comportamiento y la evolución de las criptomonedas en el mercado emergente. Tras el proceso ETL, donde recopilamos, transformamos y cargamos datos relevantes de las criptomonedas, el EDA se sumerge en los siguientes aspectos:

### Descriptivo

- **Estadísticas básicas:** Calculamos métricas fundamentales de las criptomonedas más relevantes, tales como su precio actual, volúmenes de operaciones diarias, y capitalización de mercado, proporcionando una vista panorámica del estado actual del mercado.

- **Distribuciones:** Analizamos cómo se distribuyen las capitalizaciones de mercado y los volúmenes de trading entre las principales criptomonedas, identificando cuáles dominan el mercado y cuáles presentan potencial de crecimiento.

### Relacional

- **Correlaciones:** Examinamos cómo se relacionan las fluctuaciones de precio entre las criptomonedas más importantes, lo que puede indicar posibles relaciones o tendencias compartidas en el mercado. 

- **Comparativas:** Estudiamos el desempeño de ciertas criptomonedas frente a otras, especialmente durante eventos clave que afectan al mercado global.

### Temporal

- **Evolución histórica:** Observamos el comportamiento pasado de las criptomonedas, identificando patrones de crecimiento, caídas y recuperaciones, y cómo estos se comparan entre sí.

- **Eventos significativos:** Enlazamos movimientos destacados en las criptomonedas con eventos globales que podrían haber influido en ellos, como decisiones de grandes empresas tecnológicas, anuncios de regulaciones gubernamentales, entre otros.

### Visual

- **Gráficos interactivos:** Utilizamos representaciones visuales para mostrar la evolución del precio, capitalización de mercado, y volúmenes de operaciones, facilitando la interpretación y comparación entre distintas criptomonedas.

Este enfoque detallado nos permite, no solo entender el estado actual del mercado de criptomonedas, sino también identificar oportunidades, riesgos, y prepararnos mejor para las tendencias futuras.

## Dashboard y Storytelling

El dashboard diseñado busca proporcionar una visión holística e intuitiva sobre el comportamiento de las principales criptomonedas en el mercado. A través de una serie de gráficos y métricas, se espera que los usuarios puedan obtener insights valiosos sobre las tendencias, la volatilidad y la salud general del mercado de criptomonedas.

### Historia Principal

La evolución de las criptomonedas ha sido vertiginosa desde su creación, y su volatilidad es notoria. A través de este dashboard, se desea contar la historia de cómo las principales criptomonedas han cambiado en valor y cómo su interacción y correlación pueden influir en las decisiones de inversión. 

#### Evolución a lo largo del tiempo

Uno de los aspectos clave que se destacará es la evolución del valor de las criptomonedas a lo largo del tiempo. Se presentarán gráficos que muestren las subidas y bajadas, y cómo ciertos eventos en el mundo pueden haber influido en estas tendencias.

#### Relación entre Criptomonedas

A través de un correlograma, los usuarios podrán visualizar cómo diferentes criptomonedas se relacionan entre sí. ¿Existe una criptomoneda que, cuando sube, otra tiende a bajar? ¿O tal vez todas tienden a moverse juntas? Estas son las preguntas que buscamos responder.

#### Volatilidad y Riesgo

La volatilidad es una característica inherente de las criptomonedas. Con gráficos como las Bandas de Bollinger y métricas de volatilidad, el dashboard permitirá a los usuarios evaluar el riesgo y la estabilidad de cada moneda.

#### Más allá del Precio: Otras métricas clave

El dashboard también mostrará métricas adicionales extraídas de CoinGecko, como volumen de transacciones, capitalización de mercado y datos históricos, proporcionando una visión más completa del mercado.

### Objetivo del Dashboard

Nuestro objetivo principal es empoderar a los usuarios con información, permitiéndoles tomar decisiones informadas, ya sea para invertir, para investigar o simplemente para saciar su curiosidad sobre el fascinante mundo de las criptomonedas.



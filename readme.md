
# Análisis y Visualización del Informe de la Felicidad Mundial de las Naciones Unidas en 2023

![Dashboard](https://github.com/jose-luis666/w8-final_project/blob/main/img/dashboard_imagen.png)


# Temática


En este proyecto vamos a observar y analizar los datos acerca de los niveles de felicidad de los países del mundo según las Naciones Unidas en 2023. 

Estos datos han sido recogidos por la consultora Gallup, que a través de encuestas, ha consultado a entre mil y tres mil habitantes de 137 países, preguntas como la siguiente:

Imagina una escalera: en la parte superior se encuentra la representación de la vida ideal para ti, mientras que en la parte inferior se encuentra la representación de la peor vida posible. ¿En qué escalón de esa escalera te encuentras?

Este planteamiento, basado en la escala de Cantril, consiste en obtener una serie de respuestas sinceras acerca del nivel de satisfacción con la vida de las personas , en el que que la mejor vida posible para ellos sería un 10 y la peor vida posible un 0. A continuación de esa pregunta, también se les pide que valoren su propia vida actual en esa escala de 0 a 10.

Esta, entre otras preguntas, es lo que la consultora Gallup, encargada de realizar las encuestas y recopilar los datos, incluye en su cuestionario, que luego pasará a manos de las Naciones Unidas, para que junto con sus investigaciones, información y cálculos acerca de cada uno de los países encuestados, confeccionen unas puntuaciones en relación a la felicidad de cada país, y posteriormente un ránking.


Para la confección de esta "puntuación de la felicidad", la escalera de Cantril se relaciona con los siguientes seis factores:


- PIB per cápita

- Esperanza de vida saludable

- Apoyo social

- Libertad de elección en la vida

- Generosidad

- Percepción de la corrupción



En este repositorio observaremos y analizaremos los datos del informe de 2023 en detalle, y acudiremos a los datos de años anteriores para tener una perspectiva más clara sobre los cambios que han ido ocurriendo.


# Tareas realizadas


A continuación se detallan las principales tareas realizadas en el notebook:


## Limpieza de datos con Pandas

Se llevó a cabo una exhaustiva limpieza de los datos utilizando la biblioteca Pandas. Esto incluyó la identificación y manejo de valores nulos, eliminación de duplicados, homogeneización de los datos y ajuste de tipos de datos adecuados. Se aplicaron técnicas como el rellenado de valores faltantes, eliminación de filas con datos incompletos y eliminación de duplicados para garantizar la calidad de los datos utilizados en el análisis.



## Observación y análisis de los datos
Se realizaron diversos análisis estadísticos de los datos, calculando parámetros como medias, varianzas, dispersiones y distribuciones. Estos análisis permitieron obtener una comprensión profunda de las características y tendencias de los datos relacionados con la felicidad de los países en 2023 y en los años anteriores, explorarando sus diferencias y las relaciones entre sus variables clave.



## Creación de gráficos
Se emplearon bibliotecas gráficas como Matplotlib y Seaborn para crear visualizaciones efectivas de los parámetros analizados. Se generaron gráficos de barras, gráficos de dispersión y otros tipos de gráficos relevantes para representar la información de manera clara y comprensible. Estas visualizaciones ayudaron a identificar patrones, tendencias y anomalías en los datos.



## Uso de la librería Geopy
Se utilizó la librería Geopy para enriquecer el conjunto de datos con información geoespacial. Esto permitió obtener datos como las coordenadas geográficas de los países, lo cual resultó útil para crear un mapa en el que marcamos los países más felices de Europa.



## Incorporación de información externa
Se agregó información externa adicional al dataframe original para enriquecer el análisis. Esto incluyó la incorporación de datos sobre la presencia de mujeres en los gabinetes de gobierno de los países y la diferenciación entre países con regímenes autoritarios y democráticos. Estos datos complementarios permitieron realizar un análisis más completo y profundo de los factores relacionados con la felicidad de los países.



## Machine Learning y predicciones
Se aplicaron técnicas de aprendizaje automático (machine learning) para predecir posibles niveles de felicidad en el año 2024. A través de los métodos de regresión lineal y random forest se exploraron dos escenarios diferentes: uno relacionado con un posible nuevo brote de COVID-19 en el año 2024 y otro relacionado con la disminución del apoyo social. Se utilizaron algoritmos de regresión para entrenar modelos predictivos y se evaluaron sus resultados.



# Estructura del Proyecto

El proyecto consta de los siguientes archivos principales:

- Codigo fuente, con el cuaderno de Jupyter principal que contiene el análisis y de los datos

- Enlace a dashboard interactivo de Tableau: [Link al Dashboard de Tableau](https://prod-uk-a.online.tableau.com/#/site/nadiepatin/views/presentacion_felicidad_tableau/Historia1?:iid=1)

- Predicciones de machine learning: Covid 2024 y Apoyo social

- Histórico de datos del informe de la felicidad desde el 2015 hasta 2023

- Documentación acerca de los informes de la felicidad de las Naciones Unidas

- Carpeta de gráficos extraídos del análisis



# Contribuciones

Las contribuciones a este proyecto son bienvenidas. Si desea mejorar o agregar nuevas características, puede enviar una solicitud de extracción y se revisará para su inclusión en el repositorio.

Si encuentra errores o problemas, puede abrir un problema en el repositorio y se tratará de solucionar lo antes posible.


# Referencias

United Nations Sustainable Development Goals: https://www.un.org/sustainabledevelopment/

World Happiness Report 2022: https://worldhappiness.report/

Gallup World Poll: https://www.gallup.com/analytics/351329/gallup-world-poll.aspx

World Health Organization (WHO): https://www.who.int/

World Bank Open Data: https://data.worldbank.org/

United Nations Development Programme (UNDP): https://www.undp.org/

OECD Better Life Index: http://www.oecdbetterlifeindex.org/

World Values Survey: https://www.worldvaluessurvey.org/

Eurostat: https://ec.europa.eu/eurostat

International Monetary Fund (IMF): https://www.imf.org/


# Agradecimientos

Agradecimientos especiales a:

- Yonatan Rodriguez: Por su valiosa entrega a la hora de enseñar.
- Oriana Ampuero: Por su dedicación y colaboración durante el curso.
- Carlos Mato: Por su orientación y asesoramiento a la hora de plantear del proyecto.

Además, se agradece a las fuentes bibliográficas mencionadas anteriormente por su aporte invaluable, sus valiosos informes, datos y recursos han sido fundamentales para llevar a cabo este análisis.

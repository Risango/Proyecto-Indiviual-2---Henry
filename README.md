# Análisis de Siniestros Viales en CABA

Este proyecto se centra en el análisis de los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) durante el período 2016-2021. Utilizando técnicas avanzadas de análisis de datos y visualización, este trabajo intenta ofrecer insights que ayuden a mitigar las tasas de incidentes y mejorar la seguridad vial.

## Estructura del Repositorio

**/notebooks**
- `eda.ipynb`: Notebook con el análisis exploratorio de datos, incluyendo limpieza de datos, identificación de valores faltantes y outliers, y visualizaciones preliminares.
- `etl.ipynb`: Script que detalla el proceso de transformación y carga de datos, preparándolos para un análisis más detallado y visualización en Power BI.

**/data**
- `report_victimas_ydata.html`: Reporte generado con YData, ofreciendo un perfil detallado de las víctimas de siniestros viales.
- `PBI.pbix`: Dashboard de Power BI que permite una interacción detallada con los datos visualizados.
- `PBI.xlsx`: Datos empleados en el dashboard de Power BI, incluyendo detalles sobre los siniestros viales.

**/docs**
- `KPI_Documentation.pdf`: Documentación sobre los indicadores clave de rendimiento (KPIs) utilizados en el proyecto.

## Conclusión del Análisis Exploratorio de Datos (EDA)

- La mayoría de las víctimas de siniestros viales tienen entre 20 y 40 años.
- Los días cercanos a las quincenas registran el mayor número de accidentes, posiblemente debido a un aumento en la actividad económica y el tráfico.
- Los meses de inicio y cierre de año muestran un aumento en los accidentes, potencialmente por las festividades y un incremento en conductores bajo influencia de alcohol.
- Existe una mayor variabilidad en la edad de las víctimas femeninas en los incidentes reportados.
- Las comunas ubicadas a mayores alturas registran más incidentes, sugiriendo una correlación entre la altitud de la comuna y la frecuencia de siniestros.
- Los principales campos con valores faltantes son 'Altura Cruce', que podría necesitar atención especial para mejorar la calidad de los datos.

## Tecnologías Utilizadas

- **Python**: Utilizado para scripts de ETL y análisis exploratorio de datos.
- **Power BI**: Empleado para la creación de dashboards interactivos y visualización de datos.
- **Pandas** y **NumPy**: Herramientas de Python para la manipulación y análisis de datos.
- **Matplotlib** y **Seaborn**: Librerías de Python para la visualización de datos.

## Autores

- **Ricardo Santana**

## Notas Adicionales

Este proyecto aborda un tema crítico de seguridad vial mediante un análisis profundo de los datos y la visualización interactiva, proporcionando insights clave para la toma de decisiones y estrategias de prevención de accidentes.

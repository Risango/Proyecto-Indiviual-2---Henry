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

## Análisis del Dashboard de Power BI

### Conclusiones del Dashboard

1. **KPI de Muertes en Moto**:
   - Se observa una disminución general en el número de muertes en moto desde 2016 hasta 2020, con un aumento en 2021.
   - Los años con mayores disminuciones porcentuales fueron 2019 (-18.03%) y 2020 (-36.00%), indicando una mejora en la seguridad o cambios en la movilidad.

2. **Tasa de Homicidios**:
   - La tasa de homicidios muestra una tendencia a la baja, especialmente notable a partir de 2018.
   - Los valores objetivo y los resultados reales sugieren que las medidas implementadas han tenido un efecto positivo en la reducción de homicidios en siniestros viales.

3. **Distribución de Accidentes por Comuna y Tipo de Calle**:
   - Las comunas 1, 4 y 9 registran un mayor número de accidentes.
   - Las avenidas son las vías con mayor número de accidentes, seguidas por las calles generales y la autopista Gral. Paz.

4. **Accidentes por Horario y Sexo**:
   - La mayoría de los accidentes ocurren durante la mañana, seguidos de la tardenoche.
   - Los hombres representan la mayor proporción de víctimas de siniestros viales, con un 76% comparado con el 23.15% de mujeres.

5. **Accidentes Participantes**:
   - Los motociclistas y peatones son los grupos más afectados en los siniestros viales.
   - La participación de distintos tipos de vehículos y usuarios en los accidentes destaca la necesidad de medidas de seguridad específicas para cada grupo.

## Tecnologías Utilizadas

- **Python**: Utilizado para scripts de ETL y análisis exploratorio de datos.
- **Power BI**: Empleado para la creación de dashboards interactivos y visualización de datos.
- **Pandas** y **NumPy**: Herramientas de Python para la manipulación y análisis de datos.
- **Matplotlib** y **Seaborn**: Librerías de Python para la visualización de datos.

## Autores

- **Ricardo Santana**

## Notas Adicionales

Este proyecto aborda un tema crítico de seguridad vial mediante un análisis profundo de los datos y la visualización interactiva, proporcionando insights clave para la toma de decisiones y estrategias de prevención de accidentes.


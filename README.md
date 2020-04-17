# Práctica: Módulo Exploración y Visualización de datos - Tableau - Bootcamp KeepCoding - BIG DATA & MACHINE LEARNING

# Exploración y Visualización de datos - Tableau

En esta práctica se utiliza una de las herramientas de visualización más atratactivas e intuitivas que existen, **Tableau**. Esta herramienta permite el procesamiento de datos en memoria para refrescos rápidos en visualizaciones al explorar datos. Conjuntos de datos más grandes sí requieren llamdas directas a la fuente.

Tableau tiene soporte totalmente integrado para los lenguajes R y Python y puede desplegarse en la nube gestionada por Tableau o en plataformas terceras, incluyendo Amazon Web Services y Microsoft Azure.

Conceptos tratados en este módulo con Tableau:

- Conexión a datos
- Intérprete de datos
- Dimensiones, métricas y KPIs
- Creación de vistas
- Ordenación de datos
- Filtros
- Jerarquías, grupos y conjuntos
- Fechas
- Mapeo geográfico de datos. Personalización de mapas
- Creación de parámetros
- Generación de modelos. Regresiones, pronósticos, clústeres
- Generación de campos calculados
- Cálculos de tablas rápidos
- Diseño de dashboards
- Combinación de tablas de bases de datos diferentes
- Visualización de relaciones entre valores numéricos. Gráficos de dispersión
- Visualizacón valores específicos. Mapas de calor
- Visualización de un desglose de un todo. Gráficos Pie Chart, Nube de palabras, Gráfico de burbuja, Gráfio de árbol, Gráfico de anillo
- Visualización de distribuciones. Histograma, Box plot

Para esta práctica se utilizan los datos del fichero **airbnb-listing Madrid.csv**. Este fichero está comprimido en la carpeta data de este proyecto


# Enunciado de la práctica

A partir de los datos de Airbnb, obten los KPIs que puedan ser de relevancia y contesta a través de un dashboard a una pregunta relevante que hagas sobre los datos.

a. Se valorará el diseño final del dashboard.

b. El uso de buenas prácticas.

c. El cálculo de KPIs adecuados y el uso de campos calculados avanzados.

d. El uso de vistas interactivas.

# Desarrollo

En la práctica se han elaborado dos Dashboards por los que se puede navegar e interactuar.

### Dashboard 1: Evolución de número de viviendas de alquilé en Madrid por año, tipo de vivienda y nivel  de satisfacción de los usuarios
![Dashboard1](https://raw.githubusercontent.com/mcpade/Practica_Tableau/master/graficos/Dashboard1.png)

En el margen derecho arriba tenemos los posibles filtros que afectan a los gráficos del Dashboard. Podemos filtrar por tipo de habitación, año y también podemos cambiar el número de barrios que queremos observar (están ordenados por números de viviendas).

#### "Evolución de nº de viviendas" 

En este gráfico se representa como ha ido evolucionando el número de viviendas de Airbnb en Madrid a lo largo de los años. La gráfica de arriba representa el total acumulado de viviendas y la de abajo el total acumulado pero por Tipo de Habitaciones (Entire home/pat, Private room, Shared room)
Si se va pasando el puntero por encima del gráfico nos aparecerán el número concreto de viviendas en cada año.

#### Evolución número viviendas por barrio y año

En este caso se representan la evolución del acumulado del número de viviendas en los 10 barrios con más viviendas de Madrid en los sucesivos años. Es posible cambiar el número de barrios representados con el filtro "Top de registros".
En la parte de arriba de la gráfica, junto a los años nos aparece un símbolo **+** ó **-** que nos permite ver el acumulado por trimestre del año, por meses e incluso por semanas. 


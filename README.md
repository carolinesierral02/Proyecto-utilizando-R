# Proyecto-utilizando-R

## Proyecto utilizando  "Student-Performance-dataset"

El objetivo de este proyecto fue realizar la limpieza de datos, transformación y un análisis exploratorio de datos (EDA) sobre un conjunto de datos de rendimiento estudiantil. El conjunto de datos contiene información sobre diversos factores como el tiempo de estudio, el apoyo parental, las ausencias y el GPA. A través de este análisis, se busca obtener información sobre las relaciones entre las variables y hacer recomendaciones para mejorar el rendimiento académico.

## Descripción

El análisis se lleva a cabo utilizando R y varias librerías para la manipulación de datos, limpieza, visualización y análisis. El flujo de trabajo incluye la carga y limpieza del conjunto de datos y la visualización de los resultados para explorar las relaciones entre las variables.

## Tecnologías Utilizadas

- **R**: Lenguaje principal para el análisis de datos.
- **dplyr**: Para la manipulación de datos.
- **Hmisc** y **psych**: Para análisis estadísticos y estadísticas descriptivas.
- **dlookr**: Para la generación de reportes automáticos de EDA.
- **arrow**: Para el manejo de datos en diferentes formatos.

## Uso

1. **Carga de Datos**: El conjunto de datos de rendimiento estudiantil se carga desde un archivo CSV llamado `student_performance.csv`. El archivo debe estar ubicado en el directorio correcto para que el código funcione correctamente.

2. **Limpieza y Transformación de Datos**:
   - El dataset proporiconado viene bastante limpio por lo que no hizo falta ninguna manipulación de datos.

3. **Análisis Exploratorio de Datos (EDA)**: Se utiliza el paquete **dlookr** para generar un reporte automático de EDA, correlaciones, visualizaciones para explorar las relaciones entre las variables del conjunto de datos, etc.

## Hallazgos y Observaciones Clave

Durante el análisis, se realizaron las siguientes observaciones clave:
- **Impacto de las Ausencias en el Rendimiento Académico**: Se encontró una fuerte correlación positiva entre **Ausencias** y **GradeClass**, lo que sugiere que los estudiantes con más ausencias tienden a obtener calificaciones más bajas.
- **Tiempo de Estudio y GPA**: La relación entre **StudyTimeWeekly** y **GradeClass** es débilmente negativa, lo que indica que la cantidad de tiempo de estudio no influye directamente en el rendimiento académico en este conjunto de datos.
- **Apoyo Parental**: La correlación débil negativa entre **ParentalSupport** y **GradeClass** sugiere que el apoyo parental puede tener un impacto limitado en las calificaciones de los estudiantes en este caso.

Estos hallazgos pueden utilizarse para guiar futuras mejoras en el sistema educativo e informar estrategias de apoyo académico. El análisis detallado se encuentra en el Notebook de R adjunto.

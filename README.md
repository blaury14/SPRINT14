# SPRINT14 - PROYECTO FINAL

# Análisis de Comportamiento de Usuarios en la Aplicación Móvil "Trash to Treasure"

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los usuarios de la aplicación móvil "Trash to Treasure". La aplicación permite a los usuarios publicar anuncios para vender objetos que ya no necesitan. A través de un análisis exhaustivo de los datos de eventos registrados en la aplicación, buscamos identificar patrones de uso y segmentar a los usuarios en grupos significativos para mejorar la experiencia del usuario y optimizar las estrategias de marketing y retención.

## Estructura del Proyecto

El proyecto se divide en varias etapas clave, cada una de las cuales fue cuidadosamente diseñada para asegurar un análisis completo y detallado:

1. **Preprocesamiento de Datos**
   - **Carga y visualización de datos:** Se realizó una primera inspección visual de los datos para identificar rápidamente cualquier anomalía o patrón inicial.
   - **Limpieza de datos:** Eliminamos valores nulos y duplicados, y convertimos los tipos de datos para asegurar la integridad y consistencia de los datos.
   - **Unión de datasets:** Combinamos los diferentes conjuntos de datos en uno solo para facilitar el análisis posterior.

2. **Análisis Exploratorio de Datos (EDA)**
   - **Descripción estadística de los datos:** Proporciona una base sólida para entender la distribución y las características de los datos.
   - **Visualización inicial:** Creación de gráficos para visualizar la distribución de eventos por tipo, el número de eventos por día y la distribución de usuarios por fuente de descarga. Estas visualizaciones ayudan a identificar tendencias y patrones significativos.

3. **Segmentación de Usuarios**
   - **Clustering:** Utilizamos algoritmos de clustering como K-Means para agrupar a los usuarios según sus interacciones con la aplicación. Este enfoque permite identificar grupos de usuarios con comportamientos similares.
   - **Análisis de grupos:** Calculamos métricas clave para cada grupo y verificamos la coherencia y significancia de los clusters mediante visualizaciones y validación cruzada.

4. **Prueba de Hipótesis**
   - **Hipótesis sobre conversión:** Formulamos y probamos hipótesis sobre la diferencia en la conversión entre usuarios que descargaron la aplicación desde diferentes fuentes (Bing vs Google). 
   - **Pruebas adicionales:** Definimos y probamos hipótesis adicionales basadas en los insights obtenidos del análisis exploratorio.

5. **Dashboards**
   - **Visualización interactiva:** Creamos dashboards interactivos en Tableau para visualizar métricas clave de manera dinámica y facilitar la toma de decisiones basada en datos.

## Motivación y Justificación

La metodología adoptada para este proyecto está basada en las mejores prácticas de análisis de datos y ciencia de datos. Cada etapa del proyecto fue diseñada para asegurar que los datos fueran procesados de manera efectiva y que los resultados obtenidos fueran significativos y accionables:

- **Preprocesamiento de Datos:** La limpieza y unión de datos aseguran que el análisis se realice sobre un conjunto de datos coherente y libre de errores.
- **Análisis Exploratorio de Datos:** Proporciona una comprensión profunda de los datos, permitiendo identificar patrones y tendencias que informan las etapas posteriores del análisis.
- **Segmentación de Usuarios:** El uso de algoritmos de clustering permite identificar grupos de usuarios con comportamientos similares, lo cual es crucial para personalizar la experiencia del usuario y optimizar las estrategias de marketing.
- **Prueba de Hipótesis:** Las pruebas estadísticas validan los insights obtenidos del análisis exploratorio, asegurando que las diferencias observadas entre grupos sean estadísticamente significativas.
- **Dashboards:** Las visualizaciones interactivas facilitan la comprensión de los resultados y permiten a los stakeholders tomar decisiones informadas basadas en datos.

## Resultados y Recomendaciones

Los resultados del análisis revelaron varios insights clave sobre el comportamiento de los usuarios. Basado en estos insights, se formularon las siguientes recomendaciones:

1. Mejorar la interacción con sugerencias (tips).
2. Optimizar la experiencia de visualización de fotos.
3. Aumentar la conversión de contactos.
4. Personalizar estrategias de marketing según la fuente de descarga.
5. Utilizar los clusters para personalizar las interacciones.
6. Incorporar análisis por cohortes en la toma de decisiones.
7. Aplicar segmentación RFM para campañas de retención.
8. Monitorear continuamente y ajustar dinámicamente.

## Contribución

¡Las contribuciones son bienvenidas! Por favor, abre un issue o envía un pull request para sugerencias y mejoras.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para cualquier consulta, por favor contacta a [blaury14@gmail.com](mailto:blaury14@gmail.com).


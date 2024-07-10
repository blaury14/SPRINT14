# SPRINT14

# PROYECTO FINAL - Análisis de Comportamiento de Usuarios en la Aplicación Móvil "Trash to Treasure"

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los usuarios de la aplicación móvil "Trash to Treasure". La aplicación permite a los usuarios publicar anuncios para vender objetos que ya no necesitan. A través de un análisis exhaustivo de los datos de eventos registrados en la aplicación, buscamos identificar patrones de uso y segmentar a los usuarios en grupos significativos para mejorar la experiencia del usuario y optimizar las estrategias de marketing y retención.

## Estructura del Proyecto

El proyecto se divide en varias etapas clave:

1. **Preprocesamiento de Datos**
   - Carga y visualización de datos.
   - Limpieza de datos: eliminación de valores nulos y duplicados, y conversión de tipos de datos.
   - Unión de datasets en un solo conjunto de datos coherente.

2. **Análisis Exploratorio de Datos (EDA)**
   - Descripción estadística de los datos.
   - Visualización inicial: distribución de eventos por tipo, número de eventos por día, y distribución de usuarios por fuente de descarga.

3. **Segmentación de Usuarios**
   - Agrupación de usuarios según eventos completados utilizando algoritmos de clustering.
   - Análisis de grupos: cálculo de métricas clave y verificación de la coherencia y significancia de los clusters.

4. **Prueba de Hipótesis**
   - Hipótesis 1: Diferencia en conversión entre fuentes (Bing vs Google).
   - Hipótesis 2: Definición y prueba de otra hipótesis basada en el análisis previo.

5. **Dashboards**
   - Creación de dashboards interactivos en Tableau para visualizar métricas clave.

## Requisitos

- Python 3.6+
- Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy
- Tableau para la creación de dashboards

## Uso

1. **Preprocesamiento de Datos:**
   Ejecuta el script `preprocessing.py` para cargar, limpiar y unir los datasets.
   ```bash
   python preprocessing.py
   ```

2. **Análisis Exploratorio de Datos (EDA):**
   Ejecuta el script `eda.py` para realizar el análisis exploratorio y visualizar los datos.
   ```bash
   python eda.py
   ```

3. **Segmentación de Usuarios:**
   Ejecuta el script `segmentation.py` para agrupar a los usuarios y analizar los clusters.
   ```bash
   python segmentation.py
   ```

4. **Prueba de Hipótesis:**
   Ejecuta el script `hypothesis_testing.py` para realizar las pruebas de hipótesis.
   ```bash
   python hypothesis_testing.py
   ```

5. **Dashboards:**
   Importa los datos procesados a Tableau para crear los dashboards interactivos según las instrucciones en `dashboard_instructions.md`.

## Resultados

Los resultados del análisis y las visualizaciones están disponibles en la carpeta `results/`. Incluyen gráficos, tablas y resúmenes de las pruebas de hipótesis.

## Recomendaciones

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

Para cualquier consulta, por favor contacta a [BLAURY14@GMAIL.com](mailto:BLAURY14@GMAIL.com).

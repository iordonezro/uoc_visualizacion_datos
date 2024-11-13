---
marp: false
theme: default
class: lead
paginate: true
header: 'Visualización de Datos - UOC'
footer: 'PEC 2: XXXX - Igor Ordóñez Rodríguez '
---

# PEC 2 - Visualización de Datos  
### Máster en Ciencia de Datos - UOC

---

# Contenido

1. Presentación
2. Acceso a las Visualizaciones
3. Definición General de las Técnicas de Visualización
   - Gráficos de Barras Apiladas (Stacked Bar Graphs)
   - Mapas de Flujo (Flow Maps)
   - Gráficos en Espiral (Spiral Plots)
4. Tipos de Datos y Limitaciones de las Técnicas
5. Representaciones con Conjuntos de Datos Abiertos
   - Gráfico de Barras Apiladas
   - Mapa de Flujo
   - Gráfico en Espiral
6. Comentario de las Representaciones

---


# Presentación

Hola, mi nombre es **Igor Ordóñez Rodríguez**.  
Presento la buena práctica de la **PEC 2** de la asignatura de **Visualización de Datos** del **Máster en Ciencia de Datos** de la **UOC**.  

- Análisis de **tres técnicas** de visualización:
  - **Gráficos de Barras Apiladas (Stacked Bar Graphs)**
  - **Mapas de Flujo (Flow Maps)**
  - **Gráficos en Espiral (Spiral Plots)**  

---

# Acceso a las Visualizaciones (Pendiente)
- Las visualizaciones estarán accesibles a través de enlaces públicos una vez completado el desarrollo del proyecto.

---

# Definición general de las técnicas

## Gráficos de barras apiladas (Stacked Bar Graphs)
- **Origen**: Representación de datos categóricos y cuantitativos.
- **Descripción**: Muestra subcategorías apiladas dentro de una categoría principal.
- **Aplicaciones**: Comparaciones de ventas, ingresos, etc.
- **Pros**: Comparación relativa de subcategorías.
- **Contras**: Difícil de leer con muchas subcategorías.

---

# Ejemplo Visual: Gráfico de Barras Apiladas
<iframe src="http://localhost:8000/stacked_bar.html" width="800" height="600"></iframe>
 
---

# Definición general de las técnicas

## Mapas de flujo (Flow Maps)
- **Origen**: Visualización de movimientos de datos o entidades.
- **Descripción**: Conexiones geoespaciales con volúmenes de flujo.
- **Aplicaciones**: Migración, comercio, tráfico.
- **Pros**: Representa patrones de flujo claros.
- **Contras**: Puede ser complejo con demasiados datos.

---

# Ejemplo Visual: Mapa de Flujo

<iframe src="http://localhost:8000/flow_map.html" width="800" height="600"></iframe>

---

# Definición general de las técnicas

## Gráficos en espiral (Spiral Plots)
- **Origen**: Visualización de datos cíclicos o temporales.
- **Descripción**: Resalta patrones periódicos.
- **Aplicaciones**: Datos estacionales, tendencias temporales.
- **Pros**: Muestra patrones repetitivos de manera clara.
- **Contras**: Difícil de leer con muchos datos.

---

# Ejemplo Visual: Gráfico en Espiral

<iframe src="http://localhost:8000/spiral_plot.html" width="800" height="600"></iframe>

---

# Tipos de Datos y Limitaciones

## Gráficos de barras apiladas (Stacked Bar Graphs)
- **Datos**: Categóricos y cuantitativos.
- **Estructura**: Subcategorías apiladas dentro de una barra.
- **Limitaciones**: Comparación limitada si hay muchas subcategorías.

---

# Tipos de Datos y Limitaciones

## Mapas de flujo (Flow Maps)
- **Datos**: Geoespaciales, origen-destino y volumen.
- **Estructura**: Punto de origen, destino y cantidad de flujo.
- **Limitaciones**: Complejidad visual con muchas conexiones.

---

# Tipos de Datos y Limitaciones

## Gráficos en espiral (Spiral Plots)
- **Datos**: Cíclicos o temporales.
- **Estructura**: Series temporales distribuidas en una espiral.
- **Limitaciones**: Dificultad de lectura con demasiados puntos de datos.

---

# Conclusión y Comentarios

- **Gráficos de Barras Apiladas**: Comparación de subcategorías dentro de una categoría total.
- **Mapas de Flujo**: Representación de movimientos y conexiones.
- **Gráficos en Espiral**: Identificación de patrones cíclicos.

---

# Representaciones con conjuntos de datos abiertos 

## Gráfico de barras apiladas
- **Título del Gráfico**: Distribución de la Población por Territorio Histórico y Grupo de Edad en la C.A. de Euskadi
- **Fuente**: [Opendata Euskadi](https://opendata.euskadi.eus/catalogo/-/poblacion-de-la-c-a-de-euskadi-por-ambitos-territoriales-segun-grandes-grupos-de-edad-y-sexo/)
- **Herramienta utilizada**: Flourish
- **Objetivo**: Representar de manera visual la proporción de población por grupos de edad y género en cada territorio histórico de la C.A. de Euskadi para facilitar el análisis demográfico.
- **Resumen**:
  - La visualización muestra la distribución de la población por grupos de edad (0-19 años, 20-64 años y mayores de 65 años) y por género en cada uno de los territorios históricos de Euskadi: Araba/Álava, Bizkaia y Gipuzkoa.
  - Se destaca la predominancia de la población en edad laboral (20-64 años) y las diferencias demográficas entre territorios.
  - La segmentación por género permite visualizar las diferencias específicas dentro de cada grupo.
- **Por qué es el Gráfico Idóneo**:
  - Los gráficos de barras apiladas permiten comparar proporciones dentro de una categoría principal (territorios históricos).
  - Facilita el análisis visual rápido de la distribución total y relativa de cada grupo de edad y género.
  - Proporciona una visión clara de las tendencias demográficas y posibles necesidades de política pública.

---

## Mapa de Flujo
- **Título del Gráfico**: Rutas de vuelos origen aeropuerto San Francisco - resto del mundo 2020
- **Fuente**: [FlySFO - Air Traffic Statistics 2020](https://www.flysfo.com/media/facts-statistics/air-traffic-statistics/2020)
- **Herramienta utilizada**: Tableau
- **Objetivo**: Visualizar las rutas de vuelos desde el aeropuerto de San Francisco (SFO) hacia distintos destinos internacionales, mostrando las conexiones y distancias.
- **Resumen**:
  - La visualización muestra las rutas de vuelos que parten desde el aeropuerto de San Francisco hacia distintos aeropuertos alrededor del mundo.
  - Cada conexión representa una ruta de vuelo, con líneas que indican la dirección y el destino final del vuelo.
  - Además, la distancia entre San Francisco y el destino correspondiente se visualiza a través de la longitud de las conexiones, permitiendo un análisis geoespacial de las rutas.
- **Por qué es el Gráfico Idóneo**:
  - Los mapas de flujo son ideales para representar visualmente movimientos o conexiones entre diferentes puntos geográficos, proporcionando una representación clara de las rutas de vuelo.
  - La visualización ayuda a identificar los patrones de conectividad aérea y su alcance global, así como a observar posibles tendencias en las rutas internacionales.

---

## Gráfico en Espiral
- **Título del Gráfico**: Indicadores de Sostenibilidad: Variación interanual en la cifra de empleo (%) C.A. de Euskadi
- **Fuente**: [OpenData Euskadi - Indicadores Municipales de Sostenibilidad](https://opendata.euskadi.eus/catalogo/-/indicadores-municipales-de-sostenibilidad-variacion-interanual-en-la-cifra-de-empleo/)
- **Herramienta utilizada**: Python (Matplotlib y Pandas)
- **Objetivo**: Visualizar la evolución temporal de la variación del empleo en los territorios de la Comunidad Autónoma de Euskadi (Araba/Álava, Bizkaia y Gipuzkoa) de forma cíclica, destacando tendencias de crecimiento, crisis y recuperación.
- **Resumen**:
  - Este gráfico muestra las fluctuaciones en la variación interanual del empleo a lo largo del tiempo, desde 2003 hasta 2023, con enfoque en tres territorios: Araba/Álava, Bizkaia y Gipuzkoa.
  - La visualización permite identificar claramente períodos de crisis económica, como la crisis financiera de 2008 y el impacto de la pandemia de COVID-19 en 2020, seguidos por fases de recuperación.
  - Resalta diferencias entre los territorios en términos de impacto y recuperación, mostrando cómo Bizkaia tiende a ser más volátil en comparación con Gipuzkoa y Araba/Álava.
- **Por qué es el Gráfico Idóneo**:
  - Los gráficos en espiral son ideales para representar datos cíclicos o temporales, proporcionando una visualización clara de patrones repetitivos o evolutivos a lo largo del tiempo.
  - Permite observar cambios y tendencias en un formato visualmente atractivo y fácil de interpretar, haciendo evidente cómo eventos globales afectan de manera diferenciada a los territorios.

---

## Conclusión Final

- **Diversidad de Técnicas**: Las visualizaciones presentadas han demostrado una poderosa combinación de enfoques, cubriendo datos categóricos, geoespaciales y temporales. Esta diversidad nos ha permitido explorar las complejidades de cada conjunto de datos desde múltiples perspectivas.

- **Valor Añadido**: Cada técnica ha sido cuidadosamente seleccionada para resaltar patrones y tendencias únicas. Los gráficos de barras apiladas ofrecen una comprensión precisa de proporciones y categorías; los mapas de flujo ilustran conexiones globales de manera intuitiva, y los gráficos en espiral muestran la evolución y patrones cíclicos en un formato atractivo y claro.

- **Impacto**: Estas visualizaciones no solo mejoran la interpretación de datos, sino que también proporcionan una base sólida para la toma de decisiones informadas. Al combinar diferentes enfoques, logramos un análisis integral y accesible que desvela insights clave y arroja luz sobre realidades complejas de forma efectiva y visualmente impactante.

---


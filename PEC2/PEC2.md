---
marp: true
theme: default
class: lead
paginate: true
header: 'Visualización de Datos - UOC'
footer: 'PEC 2: Visualización de datos- Igor Ordóñez Rodríguez '
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

# Acceso a las visualizaciones 
- Las visualizaciones estarán accesibles a través de enlaces públicos una vez completado el desarrollo del proyecto.

https://github.com/iordonezro/uoc_visualizacion_datos/tree/main/PEC2

---

# Definición general de las técnicas

## Gráficos de barras apiladas (Stacked Bar Graphs)
- **Origen**: Representación de datos categóricos y cuantitativos.
- **Descripción**: Muestra subcategorías apiladas dentro de una categoría principal.
- **Aplicaciones**: Comparaciones de ventas, ingresos, etc.
- **Pros**: Comparación relativa de subcategorías.
- **Contras**: Difícil de leer con muchas subcategorías.

---

# Ejemplo Visual: gráfico barras apiladas (Stacked Bar Graphs)
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

# Ejemplo Visual: Mapas de flujo (Flow Maps)

<iframe src="http://localhost:8000/flow_map.html" width="800" height="600"></iframe>

---

# Definición general de las técnicas

## Gráfico en espiral (Spiral Plots)
- **Origen**: Visualización de datos cíclicos o temporales.
- **Descripción**: Resalta patrones periódicos.
- **Aplicaciones**: Datos estacionales, tendencias temporales.
- **Pros**: Muestra patrones repetitivos de manera clara.
- **Contras**: Difícil de leer con muchos datos.

---

# Ejemplo Visual: gráfico en espiral (Spiral Plots)

<iframe src="http://localhost:8000/spiral_plot.html" width="800" height="600"></iframe>


---

# Tipos de datos y ñlimitaciones

## Gráficos de barras apiladas (Stacked Bar Graphs)
- **Datos**: Categóricos y cuantitativos.
- **Estructura**: Subcategorías apiladas dentro de una barra.
- **Limitaciones**: Comparación limitada si hay muchas subcategorías.

---

# Tipos de datos y limitaciones

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

# Conclusión y comentarios

- **Gráficos de barras apiladas**: Comparación de subcategorías dentro de una categoría total.
- **Mapas de flujo**: Representación de movimientos y conexiones.
- **Gráficos en espiral**: Identificación de patrones cíclicos.

---

# Representaciones con conjuntos de datos abiertos 

## Gráfico de barras apiladas
- **Título del gráfico**: Distribución de la Población por Territorio Histórico y Grupo de Edad en la C.A. de Euskadi
- **Fuente**: [Opendata Euskadi](https://opendata.euskadi.eus/catalogo/-/poblacion-de-la-c-a-de-euskadi-por-ambitos-territoriales-segun-grandes-grupos-de-edad-y-sexo/)
- **Herramienta utilizada**: Flourish
- **Objetivo**: Representar de manera visual la proporción de población por grupos de edad y género en cada territorio histórico de la C.A. de Euskadi para facilitar el análisis demográfico.

---

## Mapa de Flujo
- **Título del gráfico**: Rutas de vuelos origen aeropuerto San Francisco - resto del mundo 2020
- **Fuente**: [FlySFO - Air Traffic Statistics 2020](https://www.flysfo.com/media/facts-statistics/air-traffic-statistics/2020)
- **Herramienta utilizada**: Tableau
- **Objetivo**: Visualizar las rutas de vuelos desde el aeropuerto de San Francisco (SFO) hacia distintos destinos internacionales, mostrando las conexiones y distancias.
---

## Gráfico en espiral
- **Título del gráfico**: Indicadores de Sostenibilidad: Variación interanual en la cifra de empleo (%) C.A. de Euskadi
- **Fuente**: [OpenData Euskadi - Indicadores Municipales de Sostenibilidad](https://opendata.euskadi.eus/catalogo/-/indicadores-municipales-de-sostenibilidad-variacion-interanual-en-la-cifra-de-empleo/)
- **Herramienta utilizada**: Python (Matplotlib y Pandas)
- **Objetivo**: Visualizar la evolución temporal de la variación del empleo en los territorios de la Comunidad Autónoma de Euskadi (Araba/Álava, Bizkaia y Gipuzkoa) de forma cíclica, destacando tendencias de crecimiento, crisis y recuperación.
---

## Conclusión final

- **Diversidad de técnicas**: Las visualizaciones presentadas han demostrado una poderosa combinación de enfoques, cubriendo datos categóricos, geoespaciales y temporales. 

- **Valor añadido**: Cada técnica ha sido cuidadosamente seleccionada para resaltar patrones y tendencias únicas.

- **Impacto**: Estas visualizaciones no solo mejoran la interpretación de datos, sino que también proporcionan una base sólida para la toma de decisiones informadas.

---



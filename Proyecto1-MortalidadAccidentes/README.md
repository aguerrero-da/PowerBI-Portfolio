# Proyecto 1 – Mortalidad por Accidentes de Tránsito en Bogotá

**Herramienta:** Power BI  
**Fuente de datos:** https://datosabiertos.bogota.gov.co/dataset/mortalidad-por-accidentes-de-transito

## 🎯 Objetivo del Proyecto
Analizar la mortalidad por accidentes de tránsito en Bogotá para identificar:
- Tendencias temporales
- Localidades más afectadas
- Grupos poblacionales vulnerables
- Tipos de accidente más frecuentes
- Momentos críticos del día y la semana

## 📊 Indicadores (KPIs)
- Total de muertes por año
- Variación porcentual año contra año (YoY)
- Muertes por localidad
- Distribución por tipo de accidente
- Distribución por edad y sexo
- Día y hora con mayor mortalidad

## 🗺️ Visualizaciones sugeridas
- Línea de tiempo (evolución anual)
- Mapa de calor por localidad
- Barras por tipo de accidente
- Barras por grupo etario
- Heatmap: Día de la semana vs Hora
- Tarjetas con KPIs principales

## 🔧 Transformaciones (Power Query)
- Limpieza de valores nulos
- Formato de fechas
- Creación de tabla calendario
- Estandarización de texto en columnas categóricas
- Eliminación de columnas irrelevantes

## 🧮 DAX (posible)
- Total Muertes = COUNTROWS()
- Muertes Año Actual
- Variación YoY
- Medidas para segmentación por edad y sexo

## 📝 Insights esperados
- Identificación de puntos críticos en la ciudad
- Horarios de mayor riesgo
- Impacto de edad y género
- Recomendaciones de política pública basadas en datos

## 📁 Estructura del Proyecto

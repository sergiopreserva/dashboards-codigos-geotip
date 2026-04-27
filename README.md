# dashboards-codigos-geotip
Scripts Arcade para consultar, filtrar y visualizar eventos sísmicos recientes en ArcGIS Dashboards.
# dashboards-codigos-geotip

Este repositorio contiene scripts desarrollados en **Arcade** para su uso en **ArcGIS Dashboards**, orientados a la consulta, filtrado, análisis y visualización de eventos sísmicos recientes.

Los códigos permiten consumir capas alojadas en **ArcGIS Online**, aplicar filtros por magnitud y temporalidad, realizar cruces espaciales con capas de referencia como países, y generar salidas personalizadas para indicadores, listas, tablas y gráficos dentro de un dashboard.

## Objetivo del repositorio

Organizar y documentar los códigos utilizados en ArcGIS Dashboards para facilitar su reutilización, mantenimiento y consulta por parte de otros usuarios o miembros del equipo.

## Funcionalidades principales

- Consulta de capas mediante `FeatureSetByPortalItem`.
- Carga de capas de sismos y países desde ArcGIS Online.
- Filtro de eventos sísmicos por magnitud.
- Filtro de sismos recientes según su tiempo de ocurrencia.
- Relación espacial entre eventos sísmicos y países.
- Generación de `FeatureSets` personalizados.
- Preparación de datos para indicadores, listas, tablas y gráficos.
- Personalización de elementos mediante expresiones Arcade.

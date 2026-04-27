# dashboards-codigos-geotip

Repositorio de scripts Arcade utilizados en ArcGIS Dashboards para consultar, filtrar y visualizar eventos sísmicos recientes.

## Descripción

Este repositorio contiene expresiones desarrolladas en Arcade para apoyar la construcción de un geotip o dashboard de eventos sísmicos. Los códigos permiten consumir capas desde ArcGIS Online, filtrar sismos por magnitud y tiempo, realizar cruces espaciales con capas de países y generar salidas personalizadas para elementos de ArcGIS Dashboards.

## Estructura del repositorio

```text
dashboards-codigos-geotip/
│
├── expresiones-columna-derecha/
│   └── Códigos utilizados para mostrar registros clasificados por tiempo
│
├── expresiones-columna-izquierda/
│   └── Códigos utilizados para mostrar registros, clasificados por magnitud
│
├── expresion_interseccion_espacial.arcade
│   └── Expresión para relacionar espacialmente los sismos con la capa de países.
│
└── README.md

# Ventas HomeRetail — Informe Power BI (2019–2021)

> Análisis de ventas de una empresa de artículos para el hogar con operaciones en **Uruguay, Argentina, Chile, España y Portugal**.  
> Este repositorio contiene el informe de Power BI desarrollado como trabajo obligatorio del curso Power BI potenciado por IA en el Instituto CPE

## 🎯 Objetivo
Construir un **informe en Power BI Desktop** que responda a preguntas de negocio sobre desempeño comercial, utilizando archivos Excel por país y datos complementarios de productos y sucursales.

## 📁 Fuentes de datos
- Carpeta **Ventas** (agosto/2019 a agosto/2021): `AR.xlsx`, `CH.xlsx`, `ES.xlsx`, `PT.xlsx`, `UY.xlsx`
- `Sucursales.xlsx`
- `Productos.txt`

> **Nota:** Los archivos se ubican en `data/`. Si no se distribuyen por licencia del curso, se deja la estructura y las instrucciones para conectarlos localmente.

## 🧩 Alcance del análisis
- Consolidación de ventas multi-país (append y normalización).
- Enriquecimiento con **Sucursales** y **Productos**.
- Métricas base: **Ingresos**, **Unidades**, **Tickets**, **Ticket Promedio**, **Top Productos/Países**, **Tendencia temporal**.
- Visualizaciones por **país**, **sucursal** y **categoría**.

## 🔧 Transformaciones (Power Query)
- **Combine** de archivos Excel por país (patrón de carpeta).
- Estandarización de tipos de datos y formatos de fecha.
- Limpieza de columnas y normalización de nombres.
- Merge/Join con **Sucursales** y **Productos**.
- Creación de tabla **Calendario** (para análisis temporal).

## 📊 Páginas del informe
1. **Resumen**: KPIs principales y evolución general.
2. **Ventas por País**: comparación y ranking.
3. **Productos**: top productos, ticket promedio, mix.
4. **Sucursales**: desempeño y contribución.
5. **Tendencias**: estacionalidad y evolución mensual.



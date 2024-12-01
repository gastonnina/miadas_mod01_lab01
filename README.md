<!-- omit in toc -->
# Laboratorio 1: Extracción y Análisis de Datos de Portales Inmobiliarios y API del Banco Mundial (Scrapy) con lenguage "R"

Este proyecto realiza la extracción de datos desde portales web inmobiliarios y consulta información económica mediante la API del Banco Mundial, utilizando el lenguaje R. El objetivo es generar una base de datos consolidada con información de venta de casas en Bolivia y calcular indicadores económicos relevantes.

<!-- omit in toc -->
## Tabla de Contenidos

- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Estructura de Archivos](#estructura-de-archivos)
- [Ejecución](#ejecución)
- [Resultados](#resultados)


## Requisitos

- **R** (≥ 4.0.0): [Descargar R](https://cran.r-project.org/)
- **RStudio** (opcional, pero recomendado): [Descargar RStudio](https://posit.co/download/rstudio-desktop/)

- **Librerías de R:** `httr`, `rvest`, `dplyr`, `jsonlite`, `wbstats`

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/gastonnina/miadas_mod01_lab01.git
   cd proyecto-miadas_mod01_lab01
   ```

2. Instalar librerías en R:

   ```r
   install.packages(c("httr", "rvest", "dplyr", "jsonlite", "wbstats"))
   ```

## Estructura de Archivos

```

├── README.md               # Archivo con instrucciones del proyecto
├── nina_lab1.Rmd           # Archivo principal con el código en R Markdown
├── _data/                  # Carpeta donde se guardarán los resultados
│   └── nina_lab1_casas.RData  # Archivo RData con la base de datos consolidada
```

## Ejecución

1. Abre `nina_lab1.Rmd` en RStudio.
2. Ejecuta las siguientes secciones del archivo en orden correlativo:

## Resultados

El archivo de datos consolidado se guardará en:
`_data/nina_lab1_casas.RData`.

Este archivo contendrá información de al menos 10 registros por cada fuente y departamento (La Paz y Santa Cruz).

Los resultados de las otras consultas se pueden ver en: https://gastonnina.github.io/miadas_mod01_lab01/
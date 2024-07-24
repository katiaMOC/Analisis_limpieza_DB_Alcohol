## Proyecto de Limpieza de Datos - Encuesta de Alcohol y Productos Farmacéuticos Descripción

Este repositorio contiene el código y los recursos necesarios para la limpieza de datos de la base de datos "alcohol". Los datos fueron obtenidos de la encuesta "CUESTIONARIO ZOOM/TELÉFONO - CATEGORÍA ALCOHOL Y OTROS PRODUCTOS FARMACÉUTICOS" realizada por la empresa Arellano. La encuesta tenía como objetivo estudiar el consumo de alcohol y productos farmacéuticos en los hogares.

Estructura de la Base de Datos
La base de datos contiene las siguientes columnas:

* caso
* FILTRO_A
* FILTRO_B
* FILTRO_C
* FILTRO_C2
* NSE
* NSE2
* P1
* P2
* LIMAS
...
* P34_4
* P34_5
* P34_6
* P34_7
* P34_8
* P34_NR
* p159v1
* vpond
* VPOND1
* VPOND2

# Contenido del Repositorio

* data/: Carpeta que contiene la base de datos original y la base de datos limpia.
* data_cleaning.ipynb: Jupyter notebook con el proceso de limpieza de datos.
* README.md: Este archivo.

# Proceso de Limpieza de Datos
El proceso de limpieza de datos se realizó con los siguientes pasos:
 
* `'Carga de Datos: '`Se cargaron los datos desde el archivo original.
* `Revisión y Exploración de Datos:` Se revisaron las características de los datos y se exploraron los valores   únicos de cada columna.
* `'Tratamiento de Valores Nulos:'` Se identificaron y manejaron los valores nulos en las columnas relevantes.
*`' Normalización de Datos: '`Se normalizaron los valores de las columnas según la necesidad del análisis.
* `'Conversión de Tipos de Datos'`: Se convirtieron los tipos de datos de las columnas para asegurar la consistencia.
* `'Eliminación de Duplicados:'` Se eliminaron registros duplicados para asegurar la integridad de los datos.
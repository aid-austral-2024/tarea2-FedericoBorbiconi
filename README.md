# Tarea 1: lectura y ordenamiento de datos
Este repositorio contiene todo lo referido a la segunda tarea de Análisis Inteligente de Datos.

## Distribución de carpetas
En la ruta padre de este repositorio se encuentra:

-   El enunciado en el archivo *'enunciado.md'*
-   El archivo del proyecto *'tarea2-FedericoBorbiconi.Rproj'*
-   El archivo con todo el análisis realizado que genera el reporte *'index.qmd'*
-   El reporte *'index.html'*
-   Este *README.md*

En la carpeta **'codigo'** se encuentra:

-   Archivo vacío para demostrar la organización del proyecto si no estuviera el requisito de dejar en el directorio principal el archivo .qmd


En la carpeta **'datos_crudos'** se encuentran todos los datos obtenidos de la página web del Banco Mundial para realizar el análisis

En la carpeta **'datos_limpios'** se encuentra:

-   Un archivo con los datos limpios y georreferenciados *'G20_agro.csv'*
-   Un archivo con los datos limpios de Área selvática a lo largo del tiempo *'Area_selvatica.csv'*

En la carpeta **'imagenes'** se encuentra el archivo *'area_selvatica.gif'* que se genera a partir del reporte.


## Ejecución
Para lograr replicar el informe *'index.html'* se debe:

-   Descargar/Clonar este repositorio

-   Una vez situado en la carpeta, abrir el proyecto *'tarea2-FedericoBorbiconi.Rproj'*

-   Abrir el archivo *index.qmd* y ejecutarlo completamente asegurandose de la instalación de todas las librerias.


## Paquetes Utilizados
Los paquetes utilizados en la ejecucion del son:

-   **readxl:** para lectura de archivos de Excel.
-   **tidyverse:** para manipular, limpiar y ordenar los data sets, generar gráficos y utilizar demás librerías incluidad en el que facilitan el análisis.
-   **leaflet:** para la creación de mapas interactivos.
-   **spData:** para utilizar el data set *'world'*.
-   **tmaptools:** para personalizar las escalas de brewer.
-   **htmltools:** para poder enriquecer el texto que se agrega a los gráficos.
-   **gganimate:** para poder generar gráficos animados.
-   **kableExtra:** para mejorar la visualización de las tablas en el reporte.
-   **scales:** para modificar las escalas de los gráficos.
-   **plotly:** para convertir gráficos de ggplot2 a gráficos interactivos
  
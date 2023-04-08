# Análisis de comportamiento de reproducción en Spotify

Este repositorio contiene un proyecto de aplicación de ciencia de datos utilizando Python para analizar el comportamiento de reproducción en Spotify. El propósito general de este proyecto es analizar el comportamiento personal de los usuarios de Spotify en la reproducción de música y conocer de manera detallada sus preferencias y hábitos de uso de la plataforma.

## Descripción del proyecto

Este proyecto tiene como objetivo principal analizar una base de datos de canciones reproducidas en Spotify para responder preguntas sobre cómo los usuarios utilizan la plataforma y cuáles son sus preferencias de reproducción de música. Para llevar a cabo este análisis, se utilizarán técnicas de limpieza y preprocesamiento de datos, así como análisis exploratorio de datos.

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:

- `Data`: Contiene la información a utilizar y el archivo `.csv` exportado después de la limpieza de datos.
- `Notebooks`: Contiene los notebooks organizados según el proceso que se estará realizando, los cuales son:
    - `1_Carga_y_limpieza.ipynb`: Notebook donde se cargan y limpian los datos.
    - `2_Análisis_Exploratorio.ipynb`: Notebook donde se realiza el análisis exploratorio de los datos.

## Instrucciones de uso

Para ejecutar los scripts y notebooks de este repositorio, se requiere tener instaladas las librerías listadas en el archivo `requirements.txt`. Para instalarlas, por favor ejecute el siguiente comando dentro de su entorno:

```{bash}
pip install -r requirements.txt
```
Una vez que se hayan instalado las librerías, puede abrir los notebooks de la carpeta `Notebooks` y ejecutarlos paso a paso.

También puede explorar los datos limpios en formato `.csv` en la carpeta `Data`.

## Nota sobre privacidad
Se debe tener en cuenta que algunos archivos `.json` contienen información privada, por lo que serán ignorados y solo se mostrará su carga. Además, su contenido se mostrará después de realizar un drop de las columnas mencionadas.

## Contribuir
Este proyecto está en constante evolución y se aprecia cualquier contribución para mejorarlo. Si tienes sugerencias o quieres reportar un problema, puedes hacerlo a través de la sección de Issues en este repositorio.

## Requisitos
Este proyecto fue desarrollado con la versión 3.11.3 de Python.
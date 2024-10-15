**Repositorio de Código para Entrenar Modelos de IA con TIGIEs de México para Comercio Exterior**
===========================================================

**Descripción del Repositorio**

Este repositorio almacena recursos y scripts para entrenar modelos de Inteligencia Artificial (IA) con la Tarifa Integral de Exportación (TIGIE) de México. La TIGIE es un sistema de clasificación de mercancías utilizada en el comercio exterior de México.

**Archivos en el Repositorio**
-----------------------------

### `tigiepip_plano.json`

* **Descripción:** Es un archivo JSON que contiene la estructura de la TIGIE de México, con un nivel de desagregación de 5 dígitos.
* **Contenido:** Cada elemento del JSON describe un código de la TIGIE, con sus respectivos nombres y descripciones.
* **Uso:** Se utiliza como base para entrenar modelos de clasificación de mercancías con la TIGIE.


### `actualizacionTIGIE-SCIAN.csv`

* **Descripción:** Es un archivo CSV que contiene la tabla de correlación entre la TIGIE y el Sistema de Clasificación Industrial de la Economía (SCIAN) de México.
* **Contenido:** Cada fila del archivo describe una correlación entre un código de la TIGIE y un código del SCIAN.
* **Uso:** Se utiliza para entrenar modelos de clasificación de mercancías con la TIGIE y el SCIAN.

### `criteriosActualizacionTIGIE-SCIAN.txt`

* **Descripción:** Es un archivo de texto que contiene los criterios para actualizar la tabla de correlación entre la TIGIE y el SCIAN.
* **Contenido:** El archivo describe los criterios para actualizar la tabla de correlación y cómo se deben utilizar para entrenar modelos de IA.
* **Uso:** Se utiliza como base para entrenar modelos de clasificación de mercancías con la TIGIE y el SCIAN.

**Notas**

* Los archivos en este repositorio se encuentran en formato JSON, CSV y HTML.
* Los archivos se pueden utilizar para entrenar modelos de IA con la TIGIE de México.
* Los criterios para actualizar la tabla de correlación entre la TIGIE y el SCIAN se encuentran en el archivo `criteriosActualizacionTIGIE-SCIAN.txt`.

# Alquilar-en-CABA
Este repositorio contiene todos los documentos con los cuales esta herramienta fue desarrollada. Incluye la documentación técnica, scripts utilizados para el procesamiento de datos y guias de uso, (por si alguien quiere contribuir con el proyecto).

<div align="center"><img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/gh-banner-readme.png"></div>

## Descripción

Capital federal es la ciudad **más poblada** del país y mudarse a este destino puede ser todo un desafio. 
El usuario promedio tarda alrededor de **45 dias en tomar una decision final**. Tiempo en el cual muchos avisos pueden finalizar, lo que puede alargar aun mas el proceso.

Con esta herramienta, podés **comparar** diferentes barrios y **tomar una decisión informada**, basada en [**datos reales**]((https://data.buenosaires.gob.ar/dataset/)) sobre transporte, seguridad, servicios y puntos de interés.

## Funcionalidades

### Capas de mapa

Las capas tematicas permiten visualizar **datos contextuales** de sumo interes, que no siempre estan disponibles, lo que agiliza tomar una decision y conseguir el **alquiler adecuado en el momento indicado**.

<div align="center"><img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Infografias/infografia-capas-de-mapa.png" height=640></div>

En esta primera versión, las [**capas tematicas**](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki#) disponibles son:
  - **Urbanismo:**
    - Comunas y barrios.
    - Villas y asentamientos informales.
  - **Movilidad:**
    - Estaciones de SUBTE.
    - Estaciones de Ferrocarril.
  - **Estadisticas de Delito:**
    - Robo total.
    - Robo automotor.
    - Hurto total.
    - Hurto automotor.

<br> 

### Planilla de seguimiento

Por si sola, sirve para centralizar tu relevamiento y, a medida que tu lista crece, poder filtrarlo de manera personalizada. 
Si se la utiliza en tandem, esta planilla te permite **exportar la lista de alquileres como una capa de mapa**.

<div align="center"><img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Infografias/infografia-planilla-mapa-2.png"></div>

Esto no solo agiliza mucho el proceso de seguimiento, sino que genera una **descripcion con datos clave**, que aparece como una ventana flotante al hacer click en cualquier marcador:

<div align="center"><img " width="480px" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Cliparts/clip-mensaje-flotante.png"></div>

<br>

#### Seguimiento automatico

Adicionalmente, podés elegir **automatizar el seguimiento** de las publicaciones de alquileres, permitiendo que los datos **se actualicen en tiempo real**, permitiendo que te enfoques en tareas mas importantes.
En la siguiente imagen podés ver como funciona; simplemente copias y pegas el enlace y la planilla se encarga de cargar el resto de los datos.
<br>

<div align="center"><img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Cliparts/gif-carga-automatica.gif"></div>

<br>

Sin embargo, esta funcionalidad esta desactivada por defecto, porque utiliza tecnicas de "webscrapping" (**extrae datos directamente de sitios web**). No todas las paginas permiten esta practica, por lo que [debe utilizarse responsablemente](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Planilla-de-carga#modulo-de-extraccion-de-datos).
Si de todas formas te interesa usarlo, podés seguir la [guía de uso para conectar el modulo](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Activar-el-seguimiento-automatico).

<br>

## Desarrollado con

- [Google My Maps](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/My-Maps-%E2%80%90-Implementacion)
- [Google Sheets](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Sheets-%E2%80%90-Implementacion)
- [Python](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Python-Script-%E2%80%90-Conversi%C3%B3n-CSV%E2%80%90KML)

<br>

## Conseguí tu propia copia!

### Prerrequisitos

Nada más que tener una cuenta de Google.

### Enlaces

- [**Mapa interactivo**](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Obtener-una-copia-de-Alquilar-en-CABA))
- [**Planilla de carga**](https://docs.google.com/spreadsheets/d/1n8KmH8Q9s2Fp96RFHQW84AAExconjnvSWJ40BhUe-6I/copy)
- [**Modulo Extracción de datos**](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Guia-de-instalacion-%E2%80%90-Seguimiento-automatico)

<br> 

## Como colaborar

Y si queres colaborar, tambien podes! De hecho, la idea es que este producto crezca gracias a la comunidad.
Si queres armar una capa de mapa basada con los set de datos de [BA DATA](https://data.buenosaires.gob.ar/), pero no sabes como hacerlo, te dejo la guia con la tecnica que use yo.

### Prerrequisitos

Tener una cuenta de Google.

<br> 

## Back matter

### Aviso legal

El modulo de extraccion de datos debe ser usado solo en aquellos sitios que permitan este tipo de acciones: 
Es responsabilidad del usuario final obedecer todas las leyes locales, estatales y federales aplicables.
Porque nadie lee estas cosas, esta separado por defecto. El usuario debe conectar el modulo de manera manual y aceptar la responsabilidad de uso para activarlo.
De esta manera, los desarrolladores no asumen ninguna responsabilidad y no son responsables de ningún mal uso o daño causado por esta herramienta.


### Reconocimientos

* Gracias a la Ciudad Autonoma de Buenos Aires por liberar al publico su extensa base de datos.
* Gracias a [Roel Van de Paar](https://www.linkedin.com/in/roelvandepaar/?originalSubdomain=au) por subir un [video con 5 soluciones](https://youtu.be/qthItOmOmQw?t=58) para convertir documentos csv a kml.
* Gracias a [Jimmy](https://gis.stackexchange.com/users/214905/jimmy) por [preguntar](https://gis.stackexchange.com/questions/444963/how-to-convert-wkt-polygons-to-kml-file-using-python) y a [Shawn](https://gis.stackexchange.com/users/96775/shawn) por responder con un script para realizar la conversión.

### Sitios de interes

- [Buenos Aires Data](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
- [Mapa interactivo de CABA](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- [Mapa del delito](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
- [Jhon (Script)](https://github.com/me-and-company/readme-template)
- [Google Devs - KML](https://github.com/me-and-company/readme-template)

### To-do

- [x] Publicar el avance del proyecto
- [x] Crear la pagina de Facebook
- [x] Armar la presentación en Behance
    - [x] Esquematizar presentacion
    - [x] Armar infografias
    - [ ] Armar paginas de la presentacion
    - [ ] Publicar en Behance
- [x] Armar el repositorio de github
    - [x] Armar el documento README.md
        - [x] Completar la seccion "Descripcion"
        - [x] Completar la seccion "Consegui tu copia!"
        - [ ] Completar la seccion "Como colaborar"
    - [x] Armar la wiki del proyecto
        - [x] Agregar documentacion tecnica
        - [x] Subir el script de python
        - [x] Armar la pagina guia de uso "Procesamiento de datos"
        - [x] Armar tutorial para conseguir una copia
        - [ ] Armar guia para "Agregar capas de mapa"
        - [ ] Armar guia para "Armar capas de mapa"
        - [ ] Armar guia para "Procesar set de datos de BA DATA"
        - [x] Armar guia para "Convertir tablas de datos a capas de mapa - Python" [Testeado → Deprecado]
        - [x] Armar guia para "Configurar Entorno Virtual"
        - [x] Armar guia para "Convertir tablas de datos a capas de mapa - QGIS" [Testeado → Deprecado]
        - [x] Desarrollar Conversor WKT a KML No-code
        - [x] Armar guía para "Convertir tablas de datos a capas de mapa - Freebie" [Testeado]
        - [ ] Armar guia para "Convertir tablas de datos a capas de mapa - Python"
        - [ ] Armar glosario "Coloquio tecnico"
        - [ ] Armar glosario "Librerias utilizadas"
        - [ ] Armar la pagina guia de uso "Normas de colaboracion"
    - [x] Agregar carpeta con set de datos.
    - [x] Agregar carpeta con recursos para la wiki
- [ ] Publicar en Linkedin

### Licencia

Este proyecto tiene una [licencia MIT](LICENSE.md).

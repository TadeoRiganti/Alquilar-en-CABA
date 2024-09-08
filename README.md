# Alquilar-en-CABA
Este repositorio contiene todos los documentos con los cuales esta herramienta fue desarrollada. Incluye la documentación técnica, scripts utilizados para el procesamiento de datos y guias de uso, (por si alguien quiere contribuir con el proyecto).

<img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/gh-banner-readme.png">

## Descripción

Capital federal es una ciudad **enorme** y mudarse a este destino puede ser todo un desafio. 
Con esta herramienta, podés **comparar** diferentes barrios y **tomar una decisión informada**, basada en [**datos reales**]((https://data.buenosaires.gob.ar/dataset/)) sobre transporte, seguridad, servicios y puntos de interés.

### Funcionalidades

#### Capas de mapa:

Es como el [mapa interactivo de la ciudad](https://mapa.buenosaires.gob.ar/), pero con la posibilidad de elegir ver lo que te importa **al mismo tiempo**.
<img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Infografias/infografia-capas-de-mapa.png">

En esta primera versión, las capas de mapa **disponibles** son:
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

  
#### Planilla de carga

Esta planilla **transforma tu lista** de alquileres relevados a una capa de mapa con todas las ubicaciones.
A diferencia de la carga manual, se genera automaticamente una **descripcion con datos clave**, que aparece como una ventana flotante al hacer click en cualquier marcador.

<img align="center" src="https://github.com/TadeoRiganti/Alquilar-en-CABA/blob/main/kit-de-prensa/Infografias/Infografia-planilla-mapa.png">

En esta primera versión, se muestran los siguientes datos:
- **Datos clave:**
    - Precio total
    - Superficie cubierta
    - Precio /m2
- **Descripción breve**
- **Enlace a la publicación**



#### Seguimiento automatico

Opcionalmente, podés elegir **automatizar el seguimiento** de las publicaciones de alquileres, **actualizando los datos en tiempo real** para que siempre tengas la información correcta.

Como utiliza funciones de **extracción de datos web**, por defecto **esta funcionalidad esta desconectada** de la planilla. 
En la wiki, esta la (guía de uso para conectar el modulo)[#] que tambien goza de la misma licencia.
Si queres saber porque esta desarrollado asi, te invito a leer el [articulo de la wiki](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Planilla-de-carga#modulo-de-extraccion-de-datos) donde se **explica la cuestión** a fondo. 

### Desarrollado con

- [Google My Maps](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/My-Maps-%E2%80%90-Implementacion)
- [Google Sheets](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Sheets-%E2%80%90-Implementacion)
- [Python](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Python-Script-%E2%80%90-Conversi%C3%B3n-CSV%E2%80%90KML)

## Como empezar

### Prerrequisitos

Completar!  Dependencies not explicitly covered in the installation process; e.g., OS restrictions.

### Instalacion

Completar! Ideally, write a script whose usage is described here.

### Configuracion

Completar! Manual, context-specific tasks not covered in the installation process.

### Uso

Completar! Agregar GIFS!

### Preguntas frecuentes

Completar!

## Back matter

### Aviso legal

El modulo de extraccion de datos debe ser usado solo en aquellos sitios que permitan este tipo de acciones: 
Es responsabilidad del usuario final obedecer todas las leyes locales, estatales y federales aplicables.
Porque nadie lee estas cosas, esta separado por defecto. El usuario debe conectar el modulo de manera manual y aceptar la responsabilidad de uso para activarlo.
De esta manera, los desarrolladores no asumen ninguna responsabilidad y no son responsables de ningún mal uso o daño causado por esta herramienta.


### Reconocimientos

Gracias a la Ciudad Autonoma de Buenos Aires por liberar al publico su extensa base de datos. 

### Sitios de interes

- [Buenos Aires Data](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
- [Mapa interactivo de CABA](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- [Mapa del delito](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
- [Jhon (Script)](https://github.com/me-and-company/readme-template)
- [Google Devs - KML](https://github.com/me-and-company/readme-template)

### To-do

- [x] Publicar el avance del proyecto
- [x] Crear la pagina de Facebook
- [ ] Armar la presentación en Behance
- [x] Armar el repositorio de github
- [x] Armar el documento README.md
- [ ] Completar la seccion "Descripcion"
- [ ] Completar la seccion "Como empezar"
- [x] Armar la wiki del proyecto
- [x] Agregar documentacion tecnica
- [x] Subir el script de python
- [ ] Armar la pagina guia de uso "Procesamiento de datos"
- [ ] Armar la pagina guia de uso "Normas de colaboracion"
- [ ] Publicar en Behance
- [ ] Publicar en Linkedin

### Licencia

Este proyecto tiene una [licencia MIT](LICENSE.md).

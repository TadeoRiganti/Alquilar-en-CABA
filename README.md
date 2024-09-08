# Alquilar-en-CABA
Este repositorio contiene todos los documentos con los cuales esta herramienta fue desarrollada. Incluye la documentación técnica, scripts utilizados para el procesamiento de datos y guias de uso, (por si alguien quiere contribuir con el proyecto).

<div align="center">
  <kbd>
    <img src="https://raw.githubusercontent.com/TadeoRiganti/Alquilar-en-CABA/main/kit-de-prensa/gh-banner-readme.png" />
  </kbd>
</div>

## Descripción

La Ciudad Autonona de Buenos Aires es grande. Tanto asi que se divide en 15 comunas (que es algo asi como los partidos de las provincias) y posee alrededor de 48 barrios oficiales.
Esta herramienta esta pensada como una referencia mas (a las recomendaciones de conocidos, a los blogs, a las publicaciones en foros), con la diferencia que permite visualizar datos que sean de nuestro interes y que puedan ayudar a evaluar donde conviene alquilar en CABA:

Desde cuestiones basicas como la movilidad (estaciones de SUBTE cercanas, ferrocarril, paradas de colectivo, de taxis), cuestiones complejas como la inseguridad en cada zona, pero además tambien permite saber si cerca del lugar hay espacios culturales, bares, una bicicleteria hasta incluso una lavanderia. 

Y es que todo esto esta disponible en la [base de datos](https://data.buenosaires.gob.ar/dataset/) que la ciudad pone a dispocision del publico.
Esta herramienta toma varios de esos set de datos y los pone a dispocision de las personas "de a pie" en un mapa interactivo personalizable.

En esta etapa inicial no es mas que una humilde prueba de concepto, que mezcla el [mapa interactivo de la ciudad](https://mapa.buenosaires.gob.ar/comollego/?lat=-34.620000&lng=-58.440000&zl=12&modo=transporte) con el [mapa del delito](https://mapa.seguridadciudad.gob.ar/) para ayudar con este problema.
Pero conforme avancen las pruebas de usabilidad y entrevistas, probablemente evolucione de manera diferente. 

### Funcionalidades

- Mapa interactivo.
- Visualizacion de datos relacionados a CABA:
  - Urbanismo:
    - Comunas y barrios.
    - Villas y asentamientos informales.
  - Movilidad:
    - Estaciones de SUBTE.
    - Estaciones de Ferrocarril.
  - Estadisticas de Delito:
    - Robo total.
    - Robo automotor.
    - Hurto total.
    - Hurto automotor.
- [Planilla de carga](https://github.com/TadeoRiganti/Alquilar-en-CABA/wiki/Planilla-de-carga):
    - Exportar marcadores
    - Relevamiento de alquileres
        - Opcional; Carga de datos automatica

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

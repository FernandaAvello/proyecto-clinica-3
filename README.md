# Proyecto Clínica

## Descripción
Este proyecto para una página web para una clínica ficticia.

## Características
- Vista Principal (Incluye sección de bienvenida, servicios, testimonios, pie de página)
- Presentación de Equipo Médico , listado.
- Página de Contacto (incluye formulario de contacto, mapa de la clínica)

## Requisitos
- Navegador Web.

## Ejecución
1. Clona el repositorio:
  ```bash
  git clone https://github.com/FernandaAvello/proyecto-clinica3.git
  ```
2. Navega al directorio del proyecto:
3. Doble click en archivo `index.html`

## Estructura de Carpetas 7-1 con SASS
El proyecto utiliza la estructura de carpetas 7-1 para modularizar los estilos con SASS. Esta estructura divide los estilos en 7 carpetas principales y un archivo principal:

abstracts/: Contiene variables, mixins y funciones.
base/: Contiene los estilos base y reset.
components/: Contiene los estilos de los componentes.
layout/: Contiene los estilos de la disposición de la página.
pages/: Contiene los estilos específicos de cada página.
themes/: Contiene los estilos de los temas.
vendors/: Contiene los estilos de terceros o librerías.

## Metodología BEM
Se ha aplicado la metodología BEM (Block, Element, Modifier) para mantener un código CSS limpio y mantenible. Esta metodología ayuda a crear componentes reutilizables y a evitar conflictos de nombres en los estilos. Esta metodología se encuentran implementada a lo largo de los distintos archivos html.

## Integración de Bootstrap y Modificaciones con SASS
Bootstrap se ha integrado en el proyecto para aprovechar sus componentes y utilidades. Se han realizado modificaciones a las variables de Bootstrap utilizando SASS para personalizar los estilos según las necesidades del proyecto. Por ejemplo, se ha sobrescrito la variable de color success de Bootstrap, eso puede ser revisado en 'src/styles/sass/vendors/_bootstrap'


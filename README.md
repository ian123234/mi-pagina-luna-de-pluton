# Neumorfismo <!-- omit in toc -->

> Tema de Jekyll diseñado con neumorfismo para sitios web personales, portfolios y currículos.

* Destacado en [JAMstack Themes](https://jamstackthemes.dev/theme/jekyll-neumorphism/)
* Destacado en [Jekyll Themes](https://jekyll-themes.com/neumorphism/)
* Destacado en [jekyllthemes](http://jekyllthemes.org/themes/neumorphism/)

[![Open Issues](https://badgen.net/github/open-issues/longpdo/neumorphism)](https://github.com/longpdo/neumorphism/issues)
[![License](https://badgen.net/github/license/longpdo/neumorphism)](LICENSE)
<a href="https://jekyll-themes.com">
    <img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

[Ver Demo](https://longpdo.github.io/neumorphism/) · [Reportar Error](https://github.com/longpdo/neumorphism/issues) · [Solicitar Característica](https://github.com/longpdo/neumorphism/issues)

<!-- TABLA DE CONTENIDOS -->
## Tabla de Contenidos <!-- omit in toc -->

* [Acerca del Proyecto](#acerca-del-proyecto)
  * [Construido Con](#construido-con)
  * [Características](#características)
* [Guía de Inicio](#guía-de-inicio)
  * [Requisitos Previos](#requisitos-previos)
  * [Instalación](#instalación)
* [Uso](#uso)
  * [Personalizar y Configurar](#personalizar-y-configurar)
    * [_config.yml](#_configyml)
    * [Plugin de Metadatos de Github](#plugin-de-metadatos-de-github)
    * [_data/*.yml](#_datayml)
    * [Particles.js](#particlesjs)
* [Contribuciones](#contribuciones)
* [Licencia](#licencia)
* [Agradecimientos](#agradecimientos)

<!-- ACERCA DEL PROYECTO -->

## Acerca del Proyecto

[![Captura de Pantalla del Proyecto][product-screenshot]](https://longpdo.github.io/neumorphism/)

Este es un sitio web personal construido con `Jekyll` y alojado en `Github Pages`, basado en la nueva tendencia de diseño de `Neumorfismo` y desarrollado con un enfoque móvil primero. Esto puede ser utilizado por desarrolladores que desean mostrar su currículum y portafolio. Si deseas usarlo para tu propio sitio web, forkea este repositorio y luego consulta [personalizar y configurar](#personalizar-y-configurar).

### Construido Con

* [Jekyll](https://jekyllrb.com/)

### Características

* Diseño Responsive Móvil Primero
* Animación de precarga animada
* Página de aterrizaje con fondo animado usando [particles.js](https://vincentgarreau.com/particles.js/), un Carrusel de Escritura y iconos sociales animados
* Diseño de Neumorfismo Oscuro en el contenido principal
* [Animaciones al Desplazarse](https://michalsnik.github.io/aos/)
* Nube de palabras *Habilidades* filtrable
* [API de Github](https://developer.github.com/v3/) que llena automáticamente la sección de *Proyectos de Código Abierto*
* Flujo de trabajo de desarrollo con Gulp usando [BrowserSync](https://browsersync.io/), [Autoprefixer](https://autoprefixer.github.io/) y minificación de `JS` y `SCSS`.
* [Google Analytics](https://analytics.google.com/)

<!-- GUÍA DE INICIO -->

## Guía de Inicio

Para obtener una copia local y hacerla funcionar, sigue estos simples pasos.

`Los comandos e instrucciones que proporciono son para MacOS - consulta los comandos específicos para tu sistema operativo por tu cuenta.`

### Requisitos Previos

* [NodeJS](https://nodejs.org/en/)

```sh
brew install node

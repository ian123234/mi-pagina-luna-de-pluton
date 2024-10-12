# Documentación para _config.yml

## Configuración General del Sitio

* `title`: Esto se mostrará como el nombre del sitio web en la pestaña de tu navegador.
* `description`: Este será el contenido de la etiqueta meta HTML. Esto se puede ignorar.
* `baseurl`: La subruta de tu sitio
  * establece esto en **""**, si renombraste el repositorio a `<user>.github.io`

## Página de Inicio

* `username`: Esto se mostrará en la página de inicio como tu nombre.

* `typing_text`: Este será el texto que se escribirá antes de *desplázate hacia abajo para más*.
  * establece esto como tu título profesional, por ejemplo, **Desarrollador Fullstack**
* `email`: Tu dirección de correo electrónico para el botón de email.
* Botones de enlaces sociales:
  * Para cada botón social que desees mostrar, establece tu nombre de usuario o ID de usuario
  * Los nombres de usuario o IDs generalmente se pueden obtener de tus enlaces de perfil
  * Si no utilizas uno de los siguientes sitios web, entonces déjalo vacío
  * por ejemplo, dado que no blogeo en dev.to ni tengo Twitter, mis configuraciones son así:
    * `github_username`: **longpdo**
    * `codepen_username`: **longpdo**
    * `dev_username`:
    * `linkedin_username`: **longpdo**
    * `twitter_username`:

## Sección Acerca de Mí

* `show_aboutme_card`:
  * establecer esto en **true**, mostrará la sección Acerca de Mí
  * establecer esto en **false**, omitirá la sección Acerca de Mí
* `about_me_title`: Esto se mostrará como el título en la sección Acerca de Mí
* `about_me_description`: Esto se mostrará debajo del título.
  * Puedes añadir y estilizar enlaces de sitios web con esta plantilla HTML dentro de cada **section_description**, por ejemplo, revisa la actual `about_me_description`:

  ```html
  <a class="highlight-link" href="https://github.com/longpdo/neumorphism" target="_blank" rel="noreferrer"> Github </a>

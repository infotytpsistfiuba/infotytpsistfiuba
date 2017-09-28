# infotytpsistfiuba.github.io
Información sobre tesis y trabajo profesional para carreras de sistemas en la fiuba

## Como contribuir a la página

### Crear un issue
Simplemente se va a la solapa "Issues" de la web con el repositorio, y se crea uno.

### Fork & Pull

#### Proceso
Para aquel que no conozca demasiado de es el workflow, aqui un tutorial:
https://gist.github.com/Chaser324/ce0505fbed06b947d962
(Basicamente creas un fork de el repo en tu cuenta de github, lo editas, y despues nos haces un pull request via la pagina web)

#### Info técnica
Se utilizan las siguientes librerias de javascript, con la siguiente documentacin

Bootstrap: Para simplificar notablemente el diseño y css
https://getbootstrap.com/docs/4.0/getting-started/introduction/

jQuery: Necesaria para bootstrap, simplifica varias interacciones con html
https://api.jquery.com/
https://learn.jquery.com/using-jquery-core/

Popper: Necesaria para bootstrap, maneja cosas de tooltips, popovers, etc
https://popper.js.org/popper-documentation.html

Holder: Para crear imagenes de placeholder
https://github.com/imsky/holder

#### Y si no se nada de html?
Es muy sencillo, es markup basada en tags con jerarquía (documentados ampliamente online), y cualquiera de ellos puede tener adicionalmente class="algo" para aplicarle estilos de css.
Usaremos mayormente las clases de css definidas por bootstrap.
La pagina usa poco y nada de javascript, mayormente solo llamará funciones de jQuery para que el html no sea un asco.
            
#### Por que estan incluidas las librerias en vez de usar CDN?
Es simplemente para tener la comodidad cuando uno testea en maquina local de no necesitar conexión a internet.

#### Por que las librerias son las .min.js?
Estan minificadas para no gastar ancho de banda innecesario, si bien github nos hostea gratis, uno ahorra.
Cualquiera que quiera las versiones no minificadas para codear mejor, puede conseguirlas facilmente.

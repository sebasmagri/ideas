﻿# Ideas

Welcome to our repository of conceptualization, design, requirements and specifications. Since we're all Venezuelans, we'll be writing this in Spanish. 🇻🇪

## Nuestro Repositorio de Ideas

Bienvenidos a nuestra central de creatividad. Aquí documentaremos todo tipo de ocurrencias y conjeturas. Usaremos prácticas estándares de desarrollo para contribuir sobre las ideas propuestas hasta darle forma a algo viable. Debido a la forma autorreferencial de este repositorio, es necesario desglozar nuestras intenciones en los siguientes puntos: 

- [La **motivación** detrás de este repositorio.](#motivacion)
- [La **estructura** de los archivos en este repositorio.](#estructura)
- [Una explicación breve de las **herramientas de planificación** que usaremos.](#herramientas-de-planificacion)
- [**Cómo contribuir** a este repositorio.](#como-contribuir)
- [**Referencias** externas usadas para definir este repositorio.](#referencias)
- [Código de conducta.](#codigo-de-conducta)
- [Licencia del contenido.](#licencia)

## Motivación

**BerserkTech** es una comunidad de participantes limitados, compuesta de personas capacitadas en conocimientos técnicos y relacionados, con la simple finalidad de lograr cohesión entre la presencia en internet y las ideas de los miembros. Buscamos, con un mínimo de esfuerzo durante nuestro tiempo libre, contribuir con actividades que nos parezcan entretenidas o interesantes, y que por sí mismas sirvan de publicidad para todos y cada uno de nosotros.

Este repositorio surge como respuesta a la necesidad de documentar y establecer orden en la colaboración sobre las ideas que tengamos. **Contribuir en este repositorio no es requerido**. Miembros de esta comunidad pueden hacer contribuciones directamente a los repositorios existentes, o crear nuevos repositorios a voluntad.

Participar en este repositorio es sugerido para para aclarar las ideas que queremos llevar a cabo dentro de la comunidad. Otros medios de comunicación suelen ser impermanentes y no garantizan el entendimiento mutuo a la hora de proponer cambios, o bien de estar al tanto de que los desacuerdos han sido resueltos. Aquí podemos aportar ideas durante la elaboración de una propuesta, y refinar la propuesta a través del tiempo.

**Cualquier persona viendo esto está invitada a participar en cualquiera de las discusiones aquí presentes**, sin embargo, **no garantizamos atender a todas las sugerencias**, nuestra prioridad son los miembros del equipo.

En este mismo repositorio también se definirá el alcance de nuestra comunidad, **BerserkTech**.

## Estructura

Aquí separaremos las ideas propuestas en directorios a los que llamaremos "categorías", cuyos nombres permitirán la fácil identificación del tipo de contenido. Dentro de cada una de estas carpetas deberá haber por lo menos una carpeta por cada propuesta. A continuación algunos ejemplos de categorías:

- `/investigacion`: Un directorio que contendrá notas sobre estudios. En él podemos documentar nuestro proceso de investigación para lograr otros proyectos, o simplemente como forma de documentar estudios que queramos compartir con otros miembros del equipo (y la
  comunidad extendida).
- `/proyectos`: Aquí almacenaremos especificaciones y requerimientos de proyectos que queramos elaborar. Estos proyectos incluyen aquellos que dependan y que no dependan directamente de código, como por ejemplo: charlas, podcasts y hangouts (pero no se limiten por eso).
- `/filosofia`: Aquí podemos documentar argumentos filosóficos. La utilidad detrás de estos será poder debatir y quizás lograr coincidir en nuestras ideas. Ejercitar nuestras creencias y puntos de vistas nos parece crucial para mantener la cohesión en el equipo y proyectar nuestra misión, visión y valores como individuos (y consecuentemente como equipo). Sin embargo, aquí no definiremos el alcance de nuestra comunidad, para eso estará la siguiente categoría:
- `/meta`: Aquí profundizaremos en las fundaciones de **BerserkTech**, incluyendo nuestro _Manifesto_, nuestro _Código de Conducta_ como comunidad, nuestro proceso de selección de participantes y otros temas.

Cada carpeta de un proyecto, deberá cumplir con la siguiente estructura:

```
/[categoría]/[nombre-del-proyecto]
README.md
CHANGELOG.md
AUTHORS
code/
docs/
[otras carpetas y/o archivos]
```

Explicación:

- `/[categoría]/[nombre-del-proyecto]` Cada proyecto deberá estar dentro de alguna de las carpetas de categorías. Si la categoría no existe, se debe crear. Trataremos de minimizar la totalidad de las categorías para evitar redundancia. La carpeta de cada idea deberá ser llamada en base al nombre del proyecto, donde cada palabra deberá estar unida a la siguiente usando el símbolo `-`.
- `README.md` Cada proyecto deberá tener un archivo README escrito en Markdown que por lo menos describa al proyecto y además explique su justificación y su estructura.
- `CHANGELOG.md` Este archivo documentará cambios hechos a lo largo del tiempo a cada idea. Cada Pull Request deberá incluir al menos un cambio en el archivo CHANGELOG.md correspondiente a la idea que se elabora. En cada uno de estos archivos, seguiremos las especificaciones definidas en https://semver.org/. El primer Pull Request que se haga deberá incluir este archivo con una sola entrada:
```
# 0.0.0
* Idea [categoría]/[nombre-del-proyecto] creada.
```
- `AUTHORS` Este archivo contendrá el nombre completo y el correo de las personas que se responsabilizarán por este proyecto. A estas personas les pertenecerá el contenido del proyecto, y dependerá de estas personas el alcance y la licencia del mismo. La licencia de los contenidos en este repositorio está regida por el archivo LICENSE, pero **cada proyecto tendrá su propia licencia y otras restricciones en el repositorio donde se conlleve su desarrollo**. Recordemos que este repositorio es solo para llegar a acuerdos. Para más información, ver la sección de [Licencia](#licencia).
- `code/` En el caso de que un proyecto incluya código fuente, este código deberá ir en esta carpeta. **Estos proyectos no están pensados para contener repositorios completos**, el código que exista aquí deberá ser código de referencia, que pueda ser usado como punto de partida o ideas para cuando se elabore el proyecto final.
- `docs/` En el caso de que un proyecto contenga archivos de texto con formato, estos deberán estar escritos en Markdown o en Latex, y deberán estar en el sub-directorio `docs/`.
- `[otras carpetas y/o archivos]` Las carpetas antes mencionadas puede que no se adapten plenamente a todas las propuestas de proyectos que se puedan presentar. Siéntanse libre de crear más carpetas en donde agrupar contenido. Traten de ser concisos para minimizar la totalidad de estas carpetas.

## Herramientas de Planificación

En este repositorio, utilizaremos herramientas disponibles en GitHub para hacer referencia a las contribuciones que hagamos y manejarlas a través del tiempo. Usaremos principalmente:

- Tags.
- Issues.
- Pull Requests.
- Otras herramientas de GitHub.

De la siguiente forma:

### Tags

Por cada categoría, crearemos un _tag_ con el nombre de la categoría (y nada más). Por cada proyecto, crearemos un _tag_ con el nombre de la categoría más el nombre del proyecto, como `[categoría]/proyecto`. De esta forma podemos separar distintas inquietudes sobre un mismo proyecto en varios issues, no solo al momento de crear un proyecto, sino en el futuro, cuando vayamos a hacer revisiones al mismo.

Está permitido crear otros _tags_ para poder identificar o especificar la naturaleza de cualquier Issue y Pull Request que no esté estrictamente relacionado a un proyecto específico, o bien que facilite la categorización de proyectos o propuestas de proyectos fuera de lo descrito en este archivo.

**Sobre el idioma:** Estará permitido crear _tags_ tanto en Inglés como en Español.

### Issues

Cada Issue deberá ser resuelto eventualmente por un Pull Request. Antes de hacer algún Pull Request, crearemos un issue sobre el mismo, donde estaremos abiertos a los comentarios generales sobre la idea que tenemos. La idea es mantener el Pull Request limpio de conversaciones, cosa de poder hacer inspecciones del código sin tener que esquivar comentarios irrelevantes o indirectos al contenido presente.

Por cada PR (Pull Request), se deberá hacer referencia a al menos un _issue_ existente. De esta forma, GitHub enlazará los contenidos y podremos mantener una historia lineal del progreso de cada proyecto.

Será perfectamente válido incluir números de issues tanto en cualquier título como en cualquier descripción, comentario o contenido (con la forma del numeral `#` seguido del número del issue).

**QUEDA A DISCRECIÓN DE LOS AUTORES DE CADA PROYECTO LA INCLUSIÓN DE SOLICITUDES, AÑADIR AUTORES O LA RESOLUCIÓN DE CONFLICTOS.** Sin embargo, **TODOS LOS AUTORES DEBERÁN ADHERIRSE AL CÓDIGO DE CONDUCTA PRESENTE EN ESTE REPOSITORIO**.

También queda a la libertad individual de cada participante (interno o externo) la posibilidad de crear una copia idéntica de cada proyecto en caso de que no se llegue un acuerdo determinado en el proyecto original, lo cual es válido siempre y cuando estos cambios sean sobre el contenido publicado en este repositorio. Reiteramos, la ubicación y las condiciones de otros repositorios que surjan como producto de lo publicado en este NO sostendrá las limitaciones o garantías existentes en este repositorio. La única excepción a esta regla son los proyectos en la categoría **meta**. Copias a estos proyectos deberán hacerse en otros repositorios, para evitar conflictos fundamentales aquí.

**Sobre el idioma:** Estará permitido crear issues donde tanto el título como la descripción y los comentarios estén en Inglés y en Español.

### Pull Requests

Los Pull Request deberán contener los archivos de estructura de una nueva propuesta, o cambios a los archivos de alguna de las propuestas ya existentes. En caso de ser un Pull Request de un proyecto nuevo, se deberá seguir la estructura definida en la sección [Estructura](#estructura). Cada Pull Request deberá ser aprobado por la totalidad de los autores definidos en el archivo `AUTHORS` asociado al proyecto. Cualquier otra persona está bienvenida a comentar en los Pull Requests abiertos, sin embargo, quedará a discreción de los autores aceptar o descalificar la sugerencia.

El nombre de la rama (branch name) de cada pull request deberá estar asociado a la categoría y al proyecto respectivo, de la siguiente forma:
- El primer Pull Request de cada proyecto deberá estar dentro del branch: `[categoría]/[proyecto]`.
- Subsiguientes Pull Requests deberán seguir el formato: `[categoría]/[proyecto]/[número de issue]`.

**Sobre el idioma:** Estará permitido crear Pull Requests donde tanto el título como la descripción y los comentarios estén en Inglés y en Español. Sin embargo, los archivos dentro del pull request deberán estar primariamente en Español, a menos de que se traten de traducciones de contenido ya disponible en español, o se trate de comentarios dentro de código (los cuales se prefieren en Inglés, pero se acepta cualquier idioma que sea entendido por las personas que aparezcan en `AUTHORS`).

### Otras Herramientas de GitHub

En este repositorio buscaremos usar otras herramientas disponibles para proyectos específicos. Ya sean Milestones o Proyectos (o herramientas futuras dentro de esta plataforma), deberá delimitarse claramente como asociada a un proyecto específico.

## Cómo Contribuir

Se puede contribuir tanto mediante la web oficial de GitHub como mediante del terminal, haciendo una copia del repositorio y subiendo cambios (en caso de tener acceso).

Las conversaciones se mantendrán en los _issues_ asociados a cada proyecto, y las sugerencias al contenido propuesto irá como parte de los Pull Requests relacionados a cada proyecto. En caso de sugerir un cambio que esté relacionado a un _issue_ existente, se deberá hacer referencia al issue usando el formato `#[número del issue]`, el cual también es válido para hacer referencia a otros pull requests (los issues y los pull requests comparten el mismo incrementador numérico). En caso de sugerir un cambio que esté relacionado un una línea identificable del contenido propuesto, de preferencia se deberá hacer como comentario directo en la línea de código correspondiente.

Además, toda contribución deberá estar adherida al Código de Conducta presente en este proyecto, sin embargo, cualquier proyecto elaborado por fuera de este repositorio producto de contenido aquí presente, no está necesariamente atado a los lineamientos definidos aquí.

## Código de conducta

Todos los autores y participantes de este repositorio deberán adherirse al código de conducta presente en `/CODE_OF_CONDUCT.md` sin excepciones. Sin embargo, cualquier proyecto elaborado por fuera de este repositorio producto de contenido aquí presente, no está necesariamente atado a los lineamientos definidos aquí.

## Licencia

La licencia de los contenidos en este repositorio está regida por el archivo LICENSE.md, pero cada proyecto tendrá su propia licencia y otras restricciones en el repositorio donde se conlleve su desarrollo. Recordemos que este repositorio es solo para llegar a acuerdos. Por consiguiente **TODO LO PUBLICADO EN ESTE REPOSITORIO ESTÁ ATADO A LA LICENCIA DISPONIBLE EN EL ARCHIVO "LICENSE.md" EN LA RAÍZ DEL REPOSITORIO**, la cual es:

[Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

## Referencias

Los siguientes enlaces sirvieron de inspiración para este proyecto:

- https://github.com/ethereum/research
- https://github.com/ethereum/eth2.0-pm
- https://github.com/ethereum/eth2.0-specs/tree/dev/specs
- https://github.com/nodejs/node
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ4MTQ2MTY4OSw3ODgxOTM3MTksLTEyMT
k2MzcyNTgsLTE3ODcwNDM5NjUsMTUwNzk3NDU3NV19
-->

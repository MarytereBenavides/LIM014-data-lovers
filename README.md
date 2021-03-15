
**Proyecto: Data Lovers - Rick and Morty**

### Data lovers:
![Banner](https://i.guim.co.uk/img/media/b563ac5db4b4a4e1197c586bbca3edebca9173cd/0_12_3307_1985/master/3307.jpg?width=1020&quality=85&auto=format&fit=max&s=9dbc7c10980d174e67725b5cacf3c3a2)
## RICK AND MORTY
Rick y Morty es una serie de televisión estadounidense de animación para adultos. La serie tiene gran acogida a nivel mundial, de todo este fandom hay un grupo que desea poder interactuar y ver la información de los personajes y de la serie en general.

#### Investigación con seguidores de Rick and Morty
Hicimos una rápida investigación sobre la información que podrían necesitar nuestros usuarios y encontramos que los datos de mayor interés para ellos son:

Información relevante sobre los personajes, como nombre, género, especie, lugar de origen, imagen y episodios donde aparece.

Adicionalmente a esta información, para nuestros usuarios es importante poder ver la lista de personajes que aparecen en la serie, la cantidad de episodios, los diferentes lugares de origen, para tener mayor información de la serie.

#### Problema del usuario
El usuario quiere encontrar información de un personaje pero no tiene una herramienta que le permita hacerlo desde una web.

#### Definición del producto
Aplicación web de búsqueda de personajes de "Rick and Morty" por: nombre, estado de vida, género, especie, lugar de origen,  y episodios en los que aparece. Además tiene una sección de estadísticas sobre datos de los personajes, una sección con información sobre la serie y un enlace para poder ver los caítulos de la serie.

#### Proceso de diseño
El diseño de la página web se centra en mostrar los personajes, ordenados y en páginas para una búsqueda rápida y fácil.
Como filtro principal está el filtro por nombre para el que elegimos usar una caja de texto porque permite ingresar rápidamente la búsqueda con el teclado.
Además agregamos un elemento select para elegir un orden alfabético, que puede ser de A-Z y de Z-A.
El filtro avanzado está conformado por una sección con etiquetas select y opciones de cada filtro por: status, species, gender, origin, episodes. Se organizó de esta forma por la facilidad de uso y rapidez de búsqueda de la información que quiere encontrar, en la parte inferior se agregó un botón para limpiar todos los filtros con etiqueta select para poder hacer una nueva búsqueda desde cero. 
La barra de navegación tiene 4 botones:
- "Home" es un botón que nos lleva a la página inicial con todos los personajes. 
- "Statistics" es un botón que nos lleva a una pantalla donde están los calculos agregados con datos de interés sobre características de los personajes de "R&M".
- "About" es un botón que nos lleva a una url con [información sobre "R&M"](https://rickandmorty.fandom.com/wiki/Rick_and_Morty_(TV_series))
- "Watch Online" es un botón que nos lleva a una url de los [capitulos de "R&M"](https://www.adultswim.com/streams/rick-and-morty) de la página de adultswim de manera gratuita.

#### Cómo resuelve los problemas del usuario
La aplicacion web tiene:
- Tarjetas de los personajes con información relevante como nombre, género, especie.
- Un filtro para buscar por nombre a los personajes de la serie. 
- Un filtro para especifcar el género, especie, lugar de origen y episodios donde aparece.
- Orden alfabético para encontrar más fácilmente a los personajes.
- Paginación.
- Información sobre la serie.
- Estadisticas sobre los personajes.

#### Historias de usuario
**1. Yo como usuario
	Quiero ver a los personajes de Rick and Morty para obtener información de cada uno.
	Para poder conocer más sobre cada uno de los personajes.**

   ***Criterios de aceptación ***
1.	El usuario puede visualizar a todos los personajes en la web en tarjetas con el nombre, especie y estado de vida.
2.	El usuario puede ingresar desde el navegador web Google Chrome.
3.	El usuario puede visualizar 20 personajes como máximo en cada página.
4.	El usuario puede seleccionar a qué página se dirigirá.

***Definición de terminado ***
1.	El código cumple con la guía de estilos acordada.
2.	El código está en el repositorio.
3.	El código tiene, y pasa, los test necesarios.
4.	El código ha sido hecho en pair-programming.
5.	La historia ha sido testeada con al menos 5 usuarios y se implementaron las mejoras.
6.	El código hace que se muestren 20 personajes por página.

**2. Yo como Usuario
Quiero tener opciones de filtrado
Para encontrar información sobre los personajes de forma rápida. **

***Criterios de aceptación.***

1. El usuario puede filtrar personajes por el nombre.
2. El usuario puede ordenar los personajes alfabéticamente.
3. El usuario puede filtrar personajes por: estado de vida, especie, género, origen, episodio.
4. El usuario puede ver la información completa del personaje haciendo click en la tarjeta del personaje.

***Definición de terminado***
1. El código cumple con la guía de estilos acordada.
2. El código está en el repositorio.
3. El código tiene, y pasa, los test necesarios.
4. El código ha sido hecho en pair-programming.
5. El código de filtrado funciona uniendo los filtros.
6. El código tiene orden alfabético.
7. El código muestra un mensaje de “Sorry, not found” cuando no encuentra coincidencias con la búsqueda.
8. El código permite buscar por el nombre de los personajes con minúsculas o mayúsculas.

**3. Yo como Usuario
Quiero poder acceder/visualizar la página en celulares, tablet y computadora.
Para poder usar la página en celuares, tablets y computadoras.**

***Criterios de aceptación***
1. El usuario puede ver las tarjetas adaptadas a la pantalla que está usando.
2. El usuario puede ver las imágenes y texto adaptados a la pantalla.
3. El usuario puede ver el modal dentro de la pantalla, sin importar el dispositivo que use.

***Definición de terminado* **
1. El código cumple con la guía de estilos.
2. El código está en el repositorio.
3. El código de estilo (css) cumple con adaptar la página web a los distintos dispositivos en los que se use (celulares, tablet y computadora).
4. La historia ha sido testeada con al menos 5 usuarios y se implementaron las mejoras.

**4. Yo como Usuario
Quiero que la página se vea ordenada y armoniosa en colores, contraste, alineación y jerarquía.
Para que sea más atractivo de usar.**

***Criterios de aceptación***
1. El usuario puede ver la página ordenada por secciones.
2. El usuario recibe una página con los colores característicos de la serie.
3. El usuario puede visualizar claramente las palabras dentro de la página web.
4. El usuario puede navegar por la página de forma intuitiva.
5. El usuario visualiza primero el título de la página y la barra de búsqueda al ingresas a la página.

***Definición de terminado ***
1. El código cumple con la guía de estilos acordada.
2. El código está en el repositorio.
3. El código tiene implementado las etiquetas del HTML5.
4. El código html ayuda a ordenar la página por jerarquía/importancia.


#### Diseño de interfaz de usuario
El diseño de la página se hizo basado en los colores y temas de la serie "Rick and Morty" y en los intereses de un grupo del fandom que busca acceder facilmente a información sobre los personajes y datos de interés sobre ellos.
Consta de tarjetas con el nombre, imagen y datos (estado de vida, especie, género) para mostrar a los personajes en la pantalla principal y que puedan interactuar facilmente con ellos.
Para la busqueda de personajes específicos, cuenta con un buscador por nombre en la parte superior, también tiene la opción de ordenar alfabéticamente con un selector de opciones de "A-Z" o "Z-A".
Cuenta con un filtro avanzado para las busquedas más específicas con las opciones de filtrado: Estado de vida, Especies, Género, Origen, Episodios en los que aparece.
Para poder ver la información completa sobre un personaje, usamos una ventana emergente o modal en forma de tarjeta de identificación donde muestra: Imágen del personaje, nombre, estado de vida, especie, tipo, género, origen, localización y los episodios en los que aparece. 
En la barra de navegación se puede acceder a tres opciones: About, donde hay información resumida sobre la serie, Statistics con datos agrupados y graficos estadísticos con datos relevantes sobre los personajes y Watch Online que lleva a un enlace para poder ver capitulos de la serie de manera gratuita.

##### Prototipo de baja fidelidad
Sketch de la solución
**Desktop**
![Banner](https://i.imgur.com/jRH9IZW.jpg)
**Modal**
![Banner](https://i.imgur.com/Onyg1o8.jpg)
**Movile**
![Banner](https://i.imgur.com/O1tULo2.jpg)
**Mejoras en la propuesta final:**
- Implementación de la pantalla de inicio.
![Banner](https://i.imgur.com/rnD33eR.jpg)
- Implementación del apartado de estadísticas.
![Banner](https://imgur.com/iystcVF.jpg)
##### Prototipo de alta fidelidad
Diseño de la Interfaz de Usuario:
[Figma: Desktop](https://www.figma.com/file/1Lwf3mKnS7NLDSKOVpWkvF/Rick-y-morty-pc?node-id=0%3A1)
[Figma: Movile](https://www.figma.com/file/wqaeab4MosleGeD2Hk5H9x/Rick-y-morty-mobile?node-id=55%3A168)

##### Testeos de usabilidad
[Link a Zeplin](https://scene.zeplin.io/project/603db83201cfd737ae87e53b)
Se realizaron tests de usabilidad con distintos usuarios, mediante el feedback con compañeras del bootcamp y en base a los resultados iteramos los diseños.

*Problemas de usabilidad detectados a través de los tests:*
- Tamaño de la letra.
- Agregar una pantalla de inicio.
- Efecto mouse hover en las tarjetas.
- Botón clean filter.
=======
# Data Lovers

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación mínimos del proyecto](#5-criterios-de-aceptación-mínimos-del-proyecto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Consideraciones técnicas](#7-consideraciones-técnicas)
* [8. Pistas, tips y lecturas complementarias](#8-pistas-tips-y-lecturas-complementarias)
* [9. Checklist](#9-checklist)

***

## 1. Preámbulo

Según [Forbes](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read),
el 90% de la data que existe hoy ha sido creada durante los últimos dos años.
Cada día generamos 2.5 millones de terabytes de datos, una cifra sin
precedentes.

No obstante, los datos por sí mismos son de poca utilidad. Para que esas
grandes cantidades de datos se conviertan en **información** fácil de leer para
los usuarios, necesitamos entender y procesar estos datos. Una manera simple de
hacerlo es creando _interfaces_ y _visualizaciones_.

En la siguiente imagen, podrás ver cómo con la data que que se ve en la parte
izquierda se puede construir una interfaz amigable y entendible por el usuario
al lado derecho.

![json-interfaz](https://lh4.googleusercontent.com/Tn-RPXS26pVvOTdUzRT1KVaJ-_QbFs9SpcGLxSPE43fgbHaXtFgMUInuDt7kV41DkT1j8Tt29V0LxQW7SMtC6digOIhfTXSBKdwI08wUwhD3RAqlwy0hjfmhZ2BFe91mtmCSEqysfgk)

## 2. Resumen del proyecto

En este proyecto **construirás una _página web_ para visualizar un
_conjunto (set) de datos_** que se adecúe a lo que descubras que tu usuario
necesita.

Como entregable final tendrás una página web que permita **visualizar la data,
filtrarla, ordenarla y hacer algún cálculo agregado**. Con cálculo agregado
nos referimos a distintos cálculos que puedes hacer con la data para mostrar
información aún más relevante para los usuarios (promedio, el valor máximo
o mínimo, etc).

Esta vez te proponemos una serie de datos de diferentes _temáticas_ para que
explores y decidas con qué temática te interesa trabajar. Hemos elegido
específicamente estos sets de datos porque creemos que se adecúan bien a esta
etapa de tu aprendizaje.

Una vez que definas tu área de interés, buscar entender quién es tu usuario
y qué necesita saber o ver exactamente; luego podrás construir la interfaz que
le ayude a interactuar y entender mejor esos datos.

Estos son datos que te proponemos:

* [Pokémon](src/data/pokemon/pokemon.json):
  En este set encontrarás una lista con los 251 Pokémon de la región de Kanto
  y Johto, junto con sus respectivas estadísticas usadas en el juego
  [Pokémon GO](http://pokemongolive.com).
  - [Investigación con jugadores de Pokémon Go](src/data/pokemon/README.md)

* [League of Legends - Challenger leaderboard](src/data/lol/lol.json):
  Este set de datos muestra la lista de campeones en una liga del
  juego League of Legends (LoL).
  - [Investigación con jugadores de LoL](src/data/lol/README.md)

* [Rick and Morty](src/data/rickandmorty/rickandmorty.json).
  Este set nos proporciona la lista de los personajes de la serie Rick and
  Morty. [API Rick and Morty](https://rickandmortyapi.com).
  - [Investigación con seguidores de Rick and Morty](src/data/rickandmorty/README.md)

* [Juegos Olímpicos de Río de Janeiro](src/data/athletes/athletes.json).
  Este set nos proporciona la lista de los atletas que ganaron medallas en las
  olímpiadas de Río de Janeiro.
  - [Investigación con interesados en juegos olímpicos de Río de Janeiro](/src/data/athletes/README.md)

## 3. Objetivos de aprendizaje

El objetivo principal de este proyecto es que aprendas a diseñar y construir una
interfaz web donde se pueda visualizar y manipular data, entendiendo lo que el
usuario necesita.

### HTML y CSS

* [ ] [Uso de HTML semántico.](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
* [ ] [Uso de selectores de CSS.](https://css-tricks.com/almanac/selectors/)
* [ ] Construir tu aplicación respetando el diseño realizado (maquetación).
* [ ] [Uso de flexbox en CSS.](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### DOM y Web APIs

* [ ] [Uso de selectores del DOM](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Localizando_elementos_DOM_usando_selectores).
* [ ] [Manejo de eventos del DOM.](https://www.w3schools.com/js/js_events.asp)
* [ ] [Manipulación dinámica del DOM.](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n)
(appendChild |createElement | createTextNode| innerHTML | textContent | etc.)

### JavaScript

* [ ] Uso de condicionales (if-else | switch | operador ternario)
* [ ] [Uso de bucles (for | for..in | for..of | while)](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Bucles_e_iteraci%C3%B3n)
* [ ] [Uso de funciones (parámetros | argumentos | valor de retorno)](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Funciones)
* [ ] [Manipular arrays (filter | map | sort | reduce)](https://code.tutsplus.com/es/tutorials/how-to-use-map-filter-reduce-in-javascript--cms-26209)
* [ ] [Manipular objects (key | value)](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Object)
* [ ] [Uso ES modules](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/M%C3%B3dulos) ([`import`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
| [`export`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export))
* [ ] [Diferenciar entre expression y statements.](https://openclassrooms.com/en/courses/4309531-descubre-las-funciones-en-javascript/5108986-diferencia-entre-expresion-y-sentencia)
* [ ] [Diferenciar entre tipos de datos atómicos y estructurados.](https://developer.mozilla.org/es/docs/Web/JavaScript/Data_structures)

### Testing

* [ ] [Testeo unitario.](https://jestjs.io/docs/es-ES/getting-started)

### Estructura del código y guía de estilo

* [ ] [Organizar y dividir el código en módulos (Modularización)](https://medium.com/@sebastianpaduano/modularizaci%C3%B3n-en-javascript-538bd6c75fa)
* [ ] Uso de identificadores descriptivos ([Nomenclatura](http://snowdream.github.io/javascript-style-guide/javascript-style-guide/es/naming-conventions.html) | [Semántica](https://geekytheory.com/semantica-coder))
* [ ] Uso de linter (ESLINT)

### Git y GitHub

* [ ] [Uso de comandos de git (add | commit | pull | status | push)](https://github.com/jlord/git-it-electron)
* [ ] Manejo de repositorios de GitHub (clone | fork | gh-pages)
* [ ] Colaboración en Github (branches | pull requests | |[tags](https://git-scm.com/book/en/v2/Git-Basics-Tagging))

### UX

* [ ] Diseñar la aplicación pensando y entendiendo al usuario.
* [ ] Crear prototipos para obtener feedback e iterar.
* [ ] Aplicar los principios de diseño visual (contraste, alineación, jerarquía)
* [ ] Planear y ejecutar tests de usabilidad.

## 4. Consideraciones generales

* Este proyecto se debe resolver en duplas.
* El proyecto será entregado subiendo tu código a GitHub (commit/push) y la
  interfaz será desplegada usando [GitHub Pages](https://pages.github.com/).
* Tiempo para completarlo: Toma como referencia 4 semanas.

## 5. Criterios de aceptación mínimos del proyecto

Los criterios para considerar que has completado este proyecto son:

### Definición del producto

Documenta brevemente tu trabajo en el archivo `README.md` de tu repositorio,
contándonos cómo fue tu proceso de diseño y cómo crees que el producto resuelve
el problema (o problemas) que tiene tu usuario.

### Historias de usuario

Una vez que entiendas las necesidades de tus usuarios, escribe las [Historias
de Usuario](https://es.wikipedia.org/wiki/Historias_de_usuario) que representen
todo lo que el usuario necesita hacer/ver. Las **Historias de Usuario** deben
ser el resultado de tu proceso de investigación o _research_ de tus usuarios.

Asegúrate de incluir la definición de terminado (_definition of done_) y los
Criterios de Aceptación para cada una.

En la medida de lo posible, termina una historia de usuario antes de pasar
a la siguiente (Cumple con Definición de Terminado + Criterios de Aceptación).

### Diseño de la Interfaz de Usuario

#### Prototipo de baja fidelidad

Durante tu trabajo deberás haber hecho e iterado bocetos (_sketches_) de tu
solución usando papel y lápiz. Te recomendamos tomar fotos de todas las
iteraciones que hagas, que las subas a tu repositorio y las menciones en tu
`README.md`.

#### Testeos de usabilidad

Durante el reto deberás hacer _tests_ de usabilidad con distintos usuarios, y
en base a los resultados, deberás iterar tus diseños. Cuéntanos
qué problemas de usabilidad detectaste a través de los _tests_ y cómo los
mejoraste en tu propuesta final.

### Implementación de la Interfaz de Usuario (HTML/CSS/JS)

Luego de diseñar tu interfaz de usuario deberás trabajar en su implementación.
**No** es necesario que construyas la interfaz exactamente como la diseñaste.
Tu tiempo de hacking es escaso, así que deberás priorizar

Como mínimo, tu implementación debe:

1. Mostrar la data en una interfaz: puede ser un card, una tabla, una lista,
   etc.
2. Permitir al usuario interactuar para obtener la infomación que necesita.
3. Ser _responsive_, es decir, debe visualizarse sin problemas desde distintos
   tamaños de pantallas: móviles, tablets y desktops.
4. Que la interfaz siga los fundamentos de _visual design_.

### Pruebas unitarias

El _boilerplate_ de este proyecto no incluye Pruebas Unitarias (_tests_), así es
que  tendrás que escribirlas tú para las funciones encargadas de  _procesar_,
_filtrar_ y _ordenar_ la data, así como _calcular_ estadísticas.

Tus _pruebas unitarias_ deben dar una cobertura del 70% de _statements_
(_sentencias_), _functions_ (_funciones_), _lines_ (_líneas_), y _branches_
(_ramas_) del archivo `src/data.js` que contenga tus funciones y está detallado
en la sección de [Consideraciones técnicas](#srcdatajs).

## 6. Hacker edition

Las secciones llamadas _Hacker Edition_ son **opcionales**. Si **terminaste**
con todo lo anterior y te queda tiempo, intenta completarlas. Así podrás
profundizar y/o ejercitar más sobre los objetivos de aprendizaje del proyecto.

Features/características extra sugeridas:

* En lugar de consumir la data estática brindada en este repositorio, puedes
  consumir la data de forma dinámica, cargando un archivo JSON por medio de
  `fetch`. La carpeta `src/data` contiene una versión `.js` y una `.json` de
  de cada set datos.
* Agregarle a tu interfaz de usuario implementada visualizaciones gráficas. Para
  ello te recomendamos explorar librerías de gráficas como
  [Chart.js](https://www.chartjs.org/)
  o [Google Charts](https://developers.google.com/chart/).
* 100% Coverage

## 7. Consideraciones técnicas

La lógica del proyecto debe estar implementada completamente en JavaScript
(ES6), HTML y CSS. En este proyecto NO está permitido usar librerías o
frameworks, solo [vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e),
con la excepción de librerías para hacer gráficas (charts); ver
[_Parte opcional_](#6-hacker-edition) más arriba.

No se debe utilizar la _pseudo-variable_ `this`.

El _boilerplate_ contiene una estructura de archivos como punto de partida así
como toda la configuración de dependencias:

```text
.
├── EXTRA.md
├── README.md
├── package.json
├── src
|  ├── data (según con qué data trabajes)
|  |  ├── lol
|  |  |  ├── lol.js
|  |  |  ├── lol.json
|  |  |  └── README.md
|  |  ├── pokemon
|  |  |  ├── pokemon.js
|  |  |  ├── pokemon.json
|  |  |  └── README.md
|  |  └── rickandmorty
|  |     ├── rickandmorty.js
|  |     └── rickandmorty.json
|  |     └── README.md
|  |  └── athletes
|  |     ├── athletes.js
|  |     └── athletes.json
|  |     └── README.md
|  ├── data.js
|  ├── index.html
|  ├── main.js
|  └── style.css
└── test
   └── data.spec.js

directory: 6 file: 17
```

### `src/index.html`

Como en el proyecto anterior, existe un archivo `index.html`. Como ya sabes,
acá va la página que se mostrará al usuario. También nos sirve para indicar
qué scripts se usarán y unir todo lo que hemos hecho.

### `src/main.js`

Recomendamos usar `src/main.js` para todo tu código que tenga que ver con
mostrar los datos en la pantalla. Con esto nos referimos básicamente a la
interacción con el DOM. Operaciones como creación de nodos, registro de
manejadores de eventos (_event listeners_ o _event handlers_), ....

Esta no es la única forma de dividir tu código, puedes usar más archivos y
carpetas, siempre y cuando la estructura sea clara para tus compañeras.

En este archivo encontrarás una serie de _imports_ _comentados_. Para _cargar_
las diferentes fuentes de datos tendrás que _descomentar_ la línea
correspondiente.

Por ejemplo, si "descomentamos" la siguiente línea:

```js
// import data from './data/pokemon/pokemon.js';
```

La línea quedaría así:

```js
import data from './data/pokemon/pokemon.js';
```

Y ahora tendríamos la variable `data` disponible en el script `src/main.js`.

### `src/data.js`

El corazón de este proyecto es la manipulación de datos a través de arreglos
y objetos.

Te recomendamos que este archivo contenga toda la funcionalidad que corresponda
a obtener, procesar y manipular datos (tus funciones). Por ejemplo:

* `filterData(data, condition)`: esta función `filter` o filtrar recibiría la
  data, y nos retornaría aquellos datos que sí cumplan con la condición.

* `sortData(data, sortBy, sortOrder)`: esta función `sort` u ordenar
  recibe tres parámetros.
  El primer parámetro, `data`, nos entrega los datos.
  El segundo parámetro, `sortBy`, nos dice con respecto a cuál de los campos de
  la data se quiere ordenar.
  El tercer parámetro, `sortOrder`, indica si se quiere ordenar de manera
  ascendente o descendente.

* `computeStats(data)`: la función `compute` o calcular, nos permitirá hacer
  cálculos estadísticos básicos para ser mostrados de acuerdo a la data
  proporcionada.

Estos nombres de funciones y de parámetros son solamente referenciales, lo que
decidas depende de tu propia implementación.

Estas funciones deben ser [_puras_](https://medium.com/laboratoria-developers/introducci%C3%B3n-a-la-programaci%C3%B3n-funcional-en-javascript-parte-2-funciones-puras-b99e08c2895d)
e independientes del DOM. Estas funciones serán después usadas desde el archivo
`src/main.js`, al cargar la página, y cada vez que el usuario interactúe (click,
filtrado, ordenado, ...).

### `src/data`

En esta carpeta están los datos de las diferentes fuentes. Encontrarás una
carpeta por cada fuente, y dentro de cada carpeta dos archivos: uno con la
extensión `.js` y otro `.json`. Ambos archivos contienen la misma data; la
diferencia es que el `.js` lo usaremos a través de una etiqueta `<script>`,
mientras que el `.json` está ahí para opcionalmente cargar la data de forma
asíncrona con [`fetch()`](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
(ver sección de [_Parte Opcional_](#6-hacker-edition)).

### `test/data.spec.js`

Tendrás también que completar las pruebas unitarias de las funciones
implementadas en el archivo `data.js`.

## 8. Pistas, tips y lecturas complementarias

### Primeros pasos

Antes de empezar a escribir código, debes definir qué deberá hacer el producto
en base al conocimiento que puedas obtener de tu usuario. Estas preguntas te
pueden ayudar:

* ¿Quiénes son los principales usuarios de producto?
* ¿Cuáles son los objetivos de estos usuarios en relación con el producto?
* ¿Cuáles son los datos más relevantes que quieren ver en la interfaz y por qué?
* ¿Cuándo utilizan o utilizarían el producto?
* Toda tu investigación previa debe tener como resultado todas las Historias
  de Usuario de tu proyecto.
* No hagas los prototipos de alta fidelidad de todas tus Historias. Comienza
  solamente por los que se necesiten para tu Sprint 1 (semana 1 de trabajo). Más
  pistas en la guía de organización para el proyecto.

Cuando ya estés lista para codear, te sugerimos empezar de esta manera:

1. Una de las integrantes del equipo debe realizar un :fork_and_knife:
   [fork](https://help.github.com/articles/fork-a-repo/) del repo de tu cohort,
   tus _coaches_ te compartirán un _link_ a un repo y te darán acceso de lectura
   en ese repo. La otra integrante del equipo deber hacer un fork **del
   repositorio de su compañera** y
   [configurar](https://gist.github.com/BCasal/026e4c7f5c71418485c1) un `remote`
   hacia el mismo.
2. :arrow_down: [Clona](https://help.github.com/articles/cloning-a-repository/)
   tu *fork* a tu computadora (copia local).
3. 📦 Instala las dependencias del proyecto con el comando `npm install`. Esto
   asume que has instalado [Node.js](https://nodejs.org/) (que incluye [npm](https://docs.npmjs.com/)).
4. Si todo ha ido bien, deberías poder ejecutar las :traffic_light:
   pruebas unitarias (unit tests) con el comando `npm test`.
5. Para ver la interfaz de tu programa en el navegador, usa el comando
  `npm start` para arrancar el servidor web y dirígete a
  `http://localhost:5000` en tu navegador.
6. A codear se ha dicho! :rocket:

### Contenido de referencia

#### Diseño de experiencia de usuario (User Experience Design)

* Investigación con usuarios / entrevistas
* Principios de diseño visual

#### Desarrollo Front-end

* Unidad de testing en curso de JavaScript en LMS.
* Unidad de arreglos en curso de JavaScript en LMS.
* Unidad de objetos en curso de JavaScript en LMS.
* Unidad de funciones en curso de JavaScript en LMS.
* Unidad de DOM en curso de Browser JavaScript en LMS.
* [Array en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array)
* [Array.sort en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/sort)
* [Array.map en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/map)
* [Array.filter en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/filter)
* [Array.reduce en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/reduce)
* [Array.forEach en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/forEach)
* [Object.keys en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Object/keys)
* [Object.entries en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Object/entries)
* [Fetch API en MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
* [json.org](https://json.org/json-es.html)
* [expressions-vs-statements](https://2ality.com/2012/09/expressions-vs-statements.html)
* [expresión vs sentencia](https://openclassrooms.com/en/courses/4309531-descubre-las-funciones-en-javascript/5108986-diferencia-entre-expresion-y-sentencia)
* [datos atómicos vs datos estructurados](https://www.todojs.com/tipos-datos-javascript-es6/)
* [Modulos: Export](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/export)
* [Modulos: Import](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/import)

#### Herramientas

* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)
* [Node.js](https://nodejs.org/)
* [Jest](https://jestjs.io/)

#### Organización del Trabajo

* [Historias de Usuario](https://www.youtube.com/watch?v=ky6wFiF5vMk&t=344s).
  Ojo que Cris no diferencia _Definición de terminado_ de _Criterios de
  Aceptación_ y nosotros sí lo haremos. Más detalles en la guía.
* [Cómo dividir H.U.](https://www.youtube.com/watch?v=Ueq786iZ30I&t=341s)
* [Guía para Data Lovers](https://docs.google.com/presentation/d/e/2PACX-1vQhx9D36NjpH-Daea-ITPUDUzNL8ZiNAprq_7b5PSUrfutk45tEtaOLz2lmd8f54_5jX1hypDM8f8SM/pub?start=false&loop=false&delayms=60000)

## 9. Checklist

* [ ] Usa VanillaJS.
* [ ] No hace uso de `this`.
* [ ] Pasa linter (`npm run pretest`)
* [ ] Pasa tests (`npm test`)
* [ ] Pruebas unitarias cubren un mínimo del 70% de statements, functions y
  lines y branches.
* [ ] Incluye _Definición del producto_ clara e informativa en `README.md`.
* [ ] Incluye historias de usuario en `README.md`.
* [ ] Incluye _sketch_ de la solución (prototipo de baja fidelidad) en
  `README.md`.
* [ ] Incluye _Diseño de la Interfaz de Usuario_ (prototipo de alta fidelidad)
  en `README.md`.
* [ ] Incluye link a Zeplin en `README.md`.
* [ ] Incluye el listado de problemas que detectaste a través de tests de
  usabilidad en el `README.md`.
* [ ] UI: Muestra lista y/o tabla con datos y/o indicadores.
* [ ] UI: Permite ordenar data por uno o más campos (asc y desc).
* [ ] UI: Permite filtrar data en base a una condición.
* [ ] UI: Es _responsive_.


# Introducción a HTML 🚀💻

HTML es un **lenguaje de marcado de hipertexto**, un lenguaje muy sencillo que se compone de elementos en el cual se le puede dar al mismo texto un significado como podriamos poner viñetas, titulos, parrafos, incluso tablas entre otras.

---

Para esta parte aprenderas a colocar etiquetas basicas de un html y para que sirve cada una de estas, empecemos:

La etiqueta **< html >< / html >**, funciona para indicar donde empieza la web y donde termina la lectura de cada elemento que tiene esta estructuta. ✅

La etiqueta **< head >** nos indica el encabezado de una web en donde se alojan elementos **informativos** de la web como por ejemplo el titulo. ✅

La etiqueta **< title >** nos indica el nombre o titulo de la web en un ejemplo seria Facebook o Youtube. ✅

La etiqueta **< body >** no menos o mas importante ya que esta es donde pondremos toda la estructura de nuestra web como apartados, imagenes, recursos, etc. ✅

La etiqueta **< footer >** nos indica el pie de pagina donde se obtendran datos generales de la misma o incluir imagenes, enlaces de interes, textos o incluso blogs. ✅

---

# Titulos

En html tenemos una variedad de titulos los cuales nos ayudan a indicar al usuario que son diferentes secciones.

Ejemplo:

<h1>esto es un titulo h1: "< h1 >< /h1 >" indica el texto mas importante de la web</h1>

<h2>esto es un titulo h2: "< h2 >< /h2 >" indica y nos ayuda a dividir subsecciones</h2>

<h3>esto es un titulo h3: "< h3 >< /h3 >" al igual que el h2 el h3 nos ayuda a dividir subsecciones</h3>

<h4>esto es un titulo h4: "< h4 >< /h4 >" nos indica información adicional con más detalles al igual que el h5 y h6</h4>

<h5>Información con mas detalle: h5</h5>

<h6>Información con mas detalle: h6</h6>

---

# Párrafos 📄

Para representar un párrafo de texto podemos utilizar la etiqueta < p > la cual tambien podemos utilizar para separar bloques de texto en una página.

<p>Esto seria un parrafo con la etiqueta < p >< /p ></p>

al igual que este otro:

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati numquam, incidunt nisi sunt velit nobis amet voluptate, recusandae reprehenderit laboriosam tenetur eveniet assumenda! Autem nisi quibusdam enim. Dignissimos, minus voluptates.</p>

---

# Enlaces 🔗

Para colocar un enlace dentro de nuestro sitio podremos colocar la etiqueta que se declara como < a > pero solo con esta etiquta basta con ponerla y agregarle la url de cualquier otro sitio si no que debemos de implementar dentro de este elemento un atributo como:

> [!NOTE]
> < a href: "URL">Click aqui < /a >

Lo anterior seria un ejemplo del como se podria una url pero que es href solo sirve para poner una url de lagun sitio, href funciona no solamente redirigirnos a un sitio externom tambien para colocar la ruta de una imagen local o de nuestro proyecto, a otra carpeta o incluso a otra parte de nuestro proyecto como "home", "portafolio", etc href es un atributo que nos ayuda a especificar la direccion del recurso a la cual se va a enviar o enlazar.

---

# Imagenes 🖼️

Para colocar una imagen en nuestro sitio la etiqueta < img > nos permite realizarlo para su uso debemos agregar un atributo en este caso seria un src o source el cual nos ayuda a localizar la ruta exacta de la imagen ya sea igual por **url** o **ruta local dentro de nuestro proyecto** un ejemplo seria:
< img src="/html/multimedia/etiqueta-html-img/html.webp" alt="Logo de HTML5" />

<img src="https://purina.com.pe/sites/default/files/2022-10/Que_debes_saber_antes_de_adoptar_un_gatito.jpg" />

---

# Div 🎲

Esta etiqueta nos sirve para hacer divisiones logicas dentro de nuestro contenido web, podemos utilizarlas para centrar bloques de contenido, crear efectos de columna y crear diferentes áreas de color en otras cosas mas. el div se coloca de esta manera:

> [!NOTE]
> < div > **Aqui iria el contenido** < /div >

Dependiendo el contenido podemos asignarle diferentes efectos.

---

# Input 📄

Esta etiqueta nos sirve para colocar campos interactivos para formularios basados en la web con el fin de definir de recibir datos del usuario como:

- nombre
- edad
- Numero Tel

entre otros mas la forma indicada de colocar un input es de la siguiente manera

> [!NOTE]
> < input > dentro del mismo podemos colocar otros atributos especificado para que se requiere, si es obligatorio e incluso ponerle un texto de ejemplo.

esto es un input: <input type = "text" placeholder="Tu nombre colocalo aqui">

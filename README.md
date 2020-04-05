 # Classroom in B4

## *by: José Agustín Rios*

Este es un proyecto escolar con el fin de crear una página para uso interno en el que se pueda compartir material didáctico
Recursos propuestos a utilizar:

**Aspectos interactivos de la página y aspectos visuales:**

HTML CSS y Javascript

**Servidor:**

MongoDB (Base de datos)_**1**_ y Node.js**1**  
  

  

**Documentación recomendada:**

Empezando en la web:[https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web)

Aprender HTML: [https://developer.mozilla.org/es/docs/Learn/HTML](https://developer.mozilla.org/es/docs/Learn/HTML)

Aprender CSS: [https://developer.mozilla.org/es/docs/Learn/CSS](https://developer.mozilla.org/es/docs/Learn/CSS)

MongoDB: [https://www.mongodb.com/es](https://www.mongodb.com/es)**1**

NodeJs: [https://nodejs.dev/](https://nodejs.dev/)**1**

Javascript: https://developer.mozilla.org/es/docs/Glossary/JavaScript

  

  

**Recursos útiles para maquetación de la página web (CSS)**

Bootstrap: https://getbootstrap.com/

Sass: [https://sass-lang.com/](https://sass-lang.com/)

  

**Ideas:**

1. Caja de comentarios.

2. Login.

3. Tarjetas faciles de crear para agregar más cursos.

4. Establecer una forma sencilla de crear nuevos apartados y clases

  

  

1) **Caja de comentarios**: Una caja de comentarios que se muestre al final de cada clase,

es necesario que esta caja permita crear los comentarios(1.a), enviarlos, identificarte(1.b) y que el educador pueda eliminar los comentarios que son irrelevantes o inapropiados y que además el educador pueda contestar las dudas directamente desde el comentario.

  

**Características en profundidad:**

1.a)  Posibilidad de escribir comentarios:

Los problemas que presenta esto es el envío de el texto al servidor para que los comentarios sean persistentes, para esto propongo usar la función de formularios de HTML.

Enlaces útiles:

https://developer.mozilla.org/es/docs/Learn/HTML/Forms

[https://developer.mozilla.org/en-US/docs/Learn/Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

  

1.b) Identificarte:

Existen que ahora se me ocurran tres posibles soluciones:

1. Crear un **login** global y permitir que los usuarios que usen ese mismo login para subir contenido en otras clases

clases y a su vez permitir a los educadores trackear a sus estudiantes por la Plataforma.

2. Agregar al formulario la posibilidad de poner el nombre y apellido del alumno y ya esta.

3. Agregar sistemas de comentarios externos cómo por ejemplo comentarios de facebook o el sistema disqus.

Pros/Cons:

1. Es muy útil, se puede usar para muchas otras cosas dentro de la plataforma/ Cuesta mucho de programar "BIEN"

2. Es rápido y práctico de programar / Nada te impide poner cualquier cosa en el formulario como usuario.

3. Rápido y práctico, a diferencia de la solución anterior es más difícil de falsear / Aburrido, sigue siendo necesario el login.

  

3) Eliminar los comentarios:

Se puede implementar esta funcionalidad de forma sencilla agregando algún boton con alguna programación en Javascript (Bootsrap tiene una funcionalidad implementada).

Los problemas que se presentan son que solamente deberián de poder los comentarios son el autor y el educador.

Por lo que la necesidad del **login** resulta aún mas importante.

  

2) Login: es necesario implementar una forma de identificar a los alumnos y los profesores a través de la plataforma.

Por loque estuve investigando esto se puede integrar mediante una librería de Node.js llamada Passport.js

Adjunto su página principal:

[http://www.passportjs.org/](http://www.passportjs.org/)

_[1](#sdfootnote1anc)*Por ahora se ignorara completamente esto ya que responde cuestiones más técnicas_
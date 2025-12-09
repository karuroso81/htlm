#  REPOSITORIO DE PRÁCTICAS DEL MÓDULO DE DISEÑO DE INTERFACES WEB (DIW)

A continuación se recogen todas las prácticas realizadas durante el módulo, organizadas por tareas y siguiendo el formato del ejemplo proporcionado.

---

#  TAREA 1 – HTML  
##  [ENLACE A LA TAREA](practicas/Tarea1HTML)

###  DESCRIPCIÓN  
Ejercicio práctico que consiste en **crear una web sencilla** utilizando etiquetas básicas de HTML: imágenes, listas, tablas y enlaces.

###  CÓDIGO EJEMPLO  

```html
<h1>Mi primera página HTML</h1>
<p>Este es un ejemplo básico de texto y estructura en HTML.</p>
<img src="img/ejemplo.png" width="200">
```

---

#  TAREA 2 – HTML  
## 🔗 [ENLACE A LA TAREA](practicas/Tarea2HTML)

###  DESCRIPCIÓN  
Actividad donde se trabajan las etiquetas de maquetación, la estructura de secciones y el concepto de jerarquía de contenido.

###  CÓDIGO EJEMPLO  

```html
<header>
  <h2>Encabezado principal</h2>
</header>

<nav>
  <ul>
    <li>Inicio</li>
    <li>Contacto</li>
  </ul>
</nav>
```

---

#  TAREA 3 – HTML  
##  [ENLACE A LA TAREA](practicas/Tarea3HTML)

###  DESCRIPCIÓN  
Práctica centrada en el uso de **formularios HTML**, inputs, selects y validaciones básicas.

###  CÓDIGO EJEMPLO  

```html
<form>
  <label>Nombre:</label>
  <input type="text" required>
  <button>Enviar</button>
</form>
```

---

#  TAREA 4 – HTML  
##  [ENLACE A LA TAREA](practicas/Tarea4HTML)

###  DESCRIPCIÓN  
Tarea enfocada en el uso de **tablas HTML**, estilado básico y estructura compleja de filas y columnas.

###  CÓDIGO EJEMPLO  

```html
<table>
  <tr><th>Producto</th><th>Precio</th></tr>
  <tr><td>Artículo 1</td><td>10€</td></tr>
</table>
```

---

#  TAREA 5 – HTML  
##  [ENLACE A LA TAREA](practicas/Tarea5HTML)

###  DESCRIPCIÓN  
Desarrollo de una maqueta HTML más avanzada con secciones repetitivas, listas de elementos y estructura semántica.

###  CÓDIGO EJEMPLO  

```html
<section class="productos">
  <article>
    <h3>Producto 1</h3>
    <p>Descripción...</p>
  </article>
</section>
```

---

#  TAREA 6 – HTML  
##  [ENLACE A LA TAREA](practicas/Tarea6HTML)

###  DESCRIPCIÓN  
Trabajo final de HTML antes de pasar a CSS, combinando todo lo aprendido: formularios, tablas, imágenes y estructura general.

###  CÓDIGO EJEMPLO  

```html
<footer>
  <p>© 2024 Mi Web</p>
</footer>
```

---

#  TAREA SASS 1  
##  [ENLACE A LA TAREA](practicas/Sass tarea1)

###  DESCRIPCIÓN  
Introducción a **SASS** utilizando variables, anidamiento y compilación de archivos `.scss` a `.css`.

###  CÓDIGO EJEMPLO  

```scss
$color: #3498db;

h1 {
  color: $color;
}
```

---

#  TAREA SASS 2  
##  [ENLACE A LA TAREA](practicas/Sass tarea2)

###  DESCRIPCIÓN  
Uso de mixins, extend y arquitectura básica de estilos SASS.

###  CÓDIGO EJEMPLO  

```scss
@mixin centrado {
  display: flex;
  justify-content: center;
}

header {
  @include centrado;
}
```

---

#  TAREA SASS 2.3 (Proyecto completo)  
##  [ENLACE A LA TAREA](practicas/Sass tarea 2.3)

###  DESCRIPCIÓN  
Maquetación completa de una web profesional utilizando **SASS**, **tipografías personalizadas**, **flexbox**, **grid**, imágenes y estructura modular.

Incluye:

- `index.html`  
- `style.scss`  
- `style.css`  
- `assets/img/`  
- `assets/fonts/`  

###  CÓDIGO EJEMPLO  

```html
<header class="hero">
  <div class="top-bar">
    <span class="language-switcher">ES | EN | DE</span>
  </div>
</header>
```

```scss
.hero {
  background-image: url("assets/img/header-background.jpg");
  background-size: cover;
}
```

---

#  AUTOR  
Carlos — Prácticas del módulo DIW.


---

## 📑 Conceptos importantes utilizados

- **class**: Se utiliza para asignar estilos a elementos específicos mediante CSS.

- **id**: Permite identificar de forma única un elemento en el documento HTML y puede ser referenciado en CSS con `#` o como ancla en enlaces.

- **role**: Atributo relacionado con **ARIA (Accessible Rich Internet Applications)**. Define el rol de un elemento para que los lectores de pantalla puedan interpretar correctamente la estructura y función de la página.

- **li a**: Combinación de etiquetas que se utiliza para crear listas con enlaces, comúnmente usadas en menús de navegación.

- **hero**: Sección destacada que capta la atención del usuario al ingresar al sitio. Generalmente contiene un título llamativo, imagen o botón.

- **:root**: Selector que apunta al elemento raíz del documento (`<html>`) y permite definir variables CSS que pueden reutilizarse en todo el proyecto.

- **--color-primary**: Ejemplo de una variable CSS que almacena un valor de color para aplicarlo de forma consistente en diferentes elementos.

- **var(--color-primary)**: Sintaxis para llamar e implementar una variable CSS previamente definida.

- **breakpoints**: Puntos de interrupción que permiten aplicar estilos CSS específicos según el tamaño de la pantalla, mejorando la visualización en dispositivos de distintos tamaños.

- **main**: Elemento semántico que debe aparecer una sola vez en cada documento HTML y representa el contenido principal de la página.

- **meta name="viewport"**: Controla cómo se adapta la visualización del sitio en dispositivos móviles.  
  👉 Ejemplo correcto:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="viewport" content="Presentacion de un Desarrollador Frontend">: lo que aparce en la descripccion del proyecto cuando se publica en la web y lo que se relaciona con la busqueda

**settings**
  "editor.fontSize": 14,
    "editor.tabSize": 2,
    "editor.insertSpaces": true,
    "editor.wordWrap": "on",
    "editor.linkedEditing": true,
    "editor.formatOnSave": true,
    "editor.minimap.enabled": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
    "liveServer.settings.port": 3000,
    "liveServer.settings.root": "/",
    "liveServer.settings.CustomBrowser": "chrome",
    "liveServer.settings.host": "localhost",
    "liveServer.settings.useWebExt": false
    estas son las extenciones que voy a utilizar en el visual


@media (min-width: 768px) {
  .container {
    padding: 0 var(--space-lg);
  }
} estas lineas correspondonde aun media query que nos permite q cuando el elemnto .container cumpla la ondicion entre parentesis min-width: 768px cambie a padding: 0 var(--space-lg)



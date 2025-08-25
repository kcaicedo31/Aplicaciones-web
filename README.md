# Aplicaciones-web
Taller de practica aplicaciones web

---

## 1. ¿Qué es HTML y cuál es su función en la web?
HTML (HyperText Markup Language) es el lenguaje estándar para estructurar el contenido de una página web. Su función principal es organizar textos, imágenes, videos y enlaces para que los navegadores puedan mostrarlos de manera correcta.

---

## 2. ¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?
Una etiqueta HTML es un elemento que se utiliza para definir la estructura y el contenido en una página web.  
**Etiquetas comunes:**
- `<html>` → Define el inicio del documento.
- `<head>` → Contiene metadatos.
- `<body>` → Contiene el contenido visible.
- `<h1>` a `<h6>` → Títulos.
- `<p>` → Párrafos.
- `<a>` → Enlaces.
- `<img>` → Imágenes.
- `<div>` → Contenedor genérico.

---

## 3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?
Un atributo es información adicional que modifica el comportamiento de una etiqueta.  
**Atributos comunes:**
- `id` → Identificador único.
- `class` → Define una clase para aplicar estilos.
- `src` → Fuente de una imagen o script.
- `href` → Enlace de un hipervínculo.
- `alt` → Texto alternativo para imágenes.

---

## 4. ¿Qué es CSS y cómo se utiliza para el diseño web?
CSS (Cascading Style Sheets) es el lenguaje que define la apariencia de los elementos HTML. Permite dar colores, fuentes, tamaños, márgenes, alineación, animaciones y diseño responsivo a una página web.


---

## 5. ¿Qué es una propiedad en CSS y menciona las propiedades más comunes?
Una propiedad en CSS define un aspecto visual de un elemento.
**Ejemplos:**
- color (color de texto).
- background-color (color de fondo).
- font-size (tamaño de fuente).
- margin y padding (espacios externos e internos).
- border (bordes de elementos).

---

## 6. ¿Qué es un selector en CSS y cuáles tipos existen?
Un selector en CSS es el patrón que se usa para seleccionar los elementos HTML a los que se les aplicarán los estilos. Es el "quién" del estilo. Existen varios tipos de selectores, como:
* **Selector de tipo/elemento:** Selecciona elementos por su nombre de etiqueta (ej. `p`, `h1`).
* **Selector de clase:** Selecciona elementos por su atributo `class` (ej. `.mi-clase`).
* **Selector de ID:** Selecciona un elemento único por su atributo `id` (ej. `#mi-id`).
* **Selector de atributos:** Selecciona elementos que tienen un atributo específico.

---

## 7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?
JavaScript es un lenguaje de programación que se ejecuta en el navegador.

#### Permite añadir dinamismo e interactividad, como:
- Validar formularios.
- Crear animaciones.
- Modificar elementos en tiempo real.
- Manejar eventos (clics, teclas, etc.).

---

## 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?
Los tipos de datos primitivos son la base del lenguaje. JavaScript tiene siete tipos primitivos:
- string → cadenas de texto.
- number → números (enteros y decimales).
- boolean → verdadero o falso.
- null → valor nulo.
- undefined → variable sin definir.
- symbol → valores únicos.
- bigint → números enteros muy grandes.

--- 

## 9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript?
Las estructuras de control de flujo determinan el orden de ejecución del código.
- if / else → ejecutan bloques de código dependiendo de una condición.
- switch → elige entre varios casos posibles.
- Bucles:
   - for → repite un bloque de código un número definido de veces.
   - while → repite mientras la condición sea verdadera.
   - do…while → ejecuta al menos una vez y luego evalúa la condición.

   ---

## 10. ¿Por qué es importante usar nombres significativos para variables y métodos?
Porque facilita la lectura, mantenimiento y comprensión del código. Nombres claros evitan errores, ayudan a otros desarrolladores y hacen que el proyecto sea más profesional.

---

## 11. ¿Qué es una variable de entorno y por qué son importantes para JavaScript o la programación en general?

Son valores externos al código que se usan para configurar el entorno de ejecución (ejemplo: claves API, puertos, rutas de base de datos).
**Son importantes porque:**
- Mejoran la seguridad (no se exponen contraseñas en el código).
- Permiten portabilidad entre distintos entornos (desarrollo, pruebas, producción).

---

**12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?**

Las herramientas de desarrollo de Chrome (Chrome DevTools) son un conjunto de herramientas integradas en el navegador para inspeccionar y depurar páginas web. Se accede a ellas con `Ctrl` + `Shift` + `I` (Windows/Linux) o `Cmd` + `Opt` + `I` (macOS), o haciendo clic derecho en la página y seleccionando "Inspeccionar".

---

**13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?**

El panel "Elements" permite inspeccionar y modificar el DOM (HTML) y los estilos (CSS) de una página en tiempo real. Puedes editar el texto, los atributos o las reglas CSS para ver el efecto de inmediato.

---

**14. ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?**

El panel "Console" es un entorno de línea de comandos de JavaScript útil para depurar código (ver errores y registros con `console.log()`), realizar pruebas rápidas y monitorear mensajes del navegador.

---

## 15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?

Muestra todas las solicitudes que hace la página al servidor (archivos, imágenes, APIs, scripts).
**Es importante porque:**
- Permite analizar tiempos de carga.
- Detecta errores de conexión.
- Optimiza el rendimiento de la web.

---

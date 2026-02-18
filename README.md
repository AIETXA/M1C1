# 📐 M1C1 Asignación de CSS Grid

## 📋 Descripción

Durante la primera sección del Módulo 1, habrás repasado la muy útil herramienta **CSS Grid**. CSS Grid es una herramienta que los desarrolladores pueden usar para controlar el diseño y el comportamiento de sus elementos HTML. Tu primer contacto con CSS Grid fue durante el curso de Fundamentos de Programación. 

Ahora que repasaste y aprendiste más sobre CSS Grid en esta primera sección de Full Stack, **¡es hora de practicar!** 

Vas a usar HTML y CSS para completar esta asignación. Se espera que crees y edites archivos usando un editor de texto y que uses una hoja de estilos externa. Por favor completá la siguiente asignación y contáctate a través de la App de Soporte para que un mentor revise tu trabajo. 

> ⚠️ **Importante**: Esta asignación debe completarse para aprobar esta sección del curso.

---

## 🎯 Conceptos Incluidos

- HTML, CSS, CSS Grid
- Clases HTML, IDs HTML
- Etiquetas HTML: Div, Img y Párrafo
- Color de Fondo en CSS, Color de Texto en CSS
- Filas, Columnas y Unidades Fraccionarias en CSS Grid
- Hojas de Estilo Externas y Estilos en Línea en CSS
- Google Fonts y Font Awesome

---

## 📝 Ejercicios

### Grid 1

Creá una etiqueta `div` con la clase **"gridOne"**. Creá dos etiquetas de párrafo que digan respectivamente "Hello World" y "My Fantastic Content". Este grid debe tener dos columnas de igual tamaño. Usá estilos en línea para poner el texto del segundo párrafo en color azul.

**Requisitos:**
- ✅ Div con clase `gridOne`
- ✅ Dos párrafos con el texto especificado
- ✅ Dos columnas de igual tamaño (`1fr 1fr`)
- ✅ Segundo párrafo en azul con estilo en línea

---

### Grid 2

Creá otra etiqueta `div` en el mismo archivo HTML. Aseguráte de que ninguno de los grids esté anidado dentro de otro. Dale a este div la clase **"gridTwo"**. Creá tres divs dentro de gridTwo, lo que significa que serán divs hijo en relación a gridTwo. Asigná a cada uno una clase única. Agregá una etiqueta de párrafo a cada uno de los divs con el texto que quieras. Cada div hijo debe tener su propio color de fondo diferente. Probá usando rojo, azul y amarillo. Este grid debe tener tres columnas. La tercera columna debe ser el doble de grande que las primeras dos. Los colores de fondo te ayudarán a identificar si los tamaños creados por `grid-template-columns` son correctos.

**Requisitos:**
- ✅ Div con clase `gridTwo`
- ✅ Tres divs hijos con clases únicas
- ✅ Cada hijo con un párrafo de texto
- ✅ Tres colores de fondo diferentes (rojo, azul, amarillo)
- ✅ Tres columnas: `1fr 1fr 2fr`

---

### Grid 3

Creá otra etiqueta `div` en el mismo archivo HTML. Dale a este div la clase **"gridThree"**. Creá dos divs hijo dentro de gridThree y dale a ambos una clase única. El primer div hijo debe contener una etiqueta de párrafo y el segundo debe contener una imagen de tu elección. Este grid debe tener dos filas. La segunda fila debe ser tres veces más grande que la primera. Usá colores de fondo nuevamente para que los tamaños sean más claros. Dale a gridThree un ancho de **500 píxeles** y una altura de **300 píxeles**.

**Requisitos:**
- ✅ Div con clase `gridThree`
- ✅ Dos divs hijos con clases únicas
- ✅ Primer hijo: párrafo / Segundo hijo: imagen
- ✅ Dos filas: `1fr 3fr`
- ✅ Ancho: 500px / Alto: 300px
- ✅ Imagen: 500px × 225px con `object-fit: cover`

> 💡 **Nota**: Aseguráte de darle a la imagen un ancho de 500 píxeles y una altura de 225 píxeles. También debés asegurarte de que `object-fit` sea igual a `cover` para que la imagen no se distorsione ni sea demasiado grande para la fila.

---

### Grid 4

Creá otra etiqueta `div` en el mismo archivo HTML. Dale a este div la clase **"gridFour"**. Creá dos divs hijo y dale al primero un nombre de clase único y al segundo un ID. El primer div debe contener una etiqueta de párrafo. El segundo debe contener dos etiquetas de párrafo. GridFour debe tener dos filas de igual tamaño. Ahora vamos a trabajar con un **grid anidado**. Seleccioná el segundo div hijo por su ID. Usá CSS Grid para crear otro grid en ese div. Deben haber dos columnas de igual tamaño. Dale a gridFour un ancho de **500 píxeles** y un color de fondo verde.

**Requisitos:**
- ✅ Div con clase `gridFour`
- ✅ Primer hijo: clase única con 1 párrafo
- ✅ Segundo hijo: ID único con 2 párrafos
- ✅ Dos filas de igual tamaño: `1fr 1fr`
- ✅ Grid anidado en el segundo hijo: `1fr 1fr`
- ✅ Ancho: 500px / Fondo: verde

---

### Grid 5

Creá otro grid siguiendo las mismas instrucciones que en Grid 4, con la excepción del segundo div hijo. Dale a este div la clase **"gridFive"**. El segundo div hijo debe tener dos imágenes en lugar de dos etiquetas de párrafo. La primera imagen debe ser el doble de ancha que la segunda. También debés redimensionar estas imágenes para que entren: probá darle a cada una **200 píxeles** de alto y de ancho. Aseguráte de usar `object-fit: cover;` nuevamente.

**Requisitos:**
- ✅ Div con clase `gridFive`
- ✅ Primer hijo: clase única con 1 párrafo
- ✅ Segundo hijo: ID único con 2 imágenes
- ✅ Dos filas de igual tamaño: `1fr 1fr`
- ✅ Grid anidado en el segundo hijo: `2fr 1fr`
- ✅ Imágenes: 200px × 200px con `object-fit: cover`

---

### Grid 6

Creá otra etiqueta `div` en el mismo archivo HTML. Dale a este div la clase **"gridSix"**. Debe haber dos elementos dentro de gridSix. El primero debe ser un ícono de **Font Awesome** de tu elección. El segundo elemento debe ser una etiqueta de párrafo. Elegí una fuente de **Google Fonts** y applicála a la etiqueta de párrafo. GridSix debe tener dos `grid-template-columns`. La segunda columna, con el párrafo, debe ser tres veces más grande que la primera columna con el ícono. Dale a gridSix un ancho de **500px** y hace que el color de fondo sea gris claro.

**Requisitos:**
- ✅ Div con clase `gridSix`
- ✅ Primer elemento: ícono de Font Awesome
- ✅ Segundo elemento: párrafo con Google Font
- ✅ Dos columnas: `1fr 3fr`
- ✅ Ancho: 500px / Fondo: gris claro

---

## 🖼️ Imágenes de Ejemplo

Las imágenes utilizadas provienen de [Unsplash](https://unsplash.com) y son de uso libre:

- **Hielo**: [https://unsplash.com/photos/hSPVuakrJqs](https://unsplash.com/photos/hSPVuakrJqs)
- **Linterna**: [https://unsplash.com/photos/qC117ahi-mE](https://unsplash.com/photos/qC117ahi-mE)
- **Calle**: [https://unsplash.com/photos/_TuI8tZHlk4](https://unsplash.com/photos/_TuI8tZHlk4)

---

## 📚 Recursos Útiles

- [CSS Grid Guide - MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout)
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Unsplash](https://unsplash.com/)

---

## 💬 Soporte

Si tenés alguna pregunta o necesitás ayuda, ¡avisá a través de la App de Soporte para que podamos ayudarte!

---

**¡Buena suerte! 🚀**
# Notas sobre HTML

---

## Conceptos básicos

- Los titulos van del `h1` al `h6`
- Los parrafos se declaran con la etiqueta `<p>`
- Las etiquetas se cierran con la sintaxis `</p>`
---

## Atributos

- **Atributo:** Es un valor colocado dentro de la etiqueta de apertura de un elemento HTML.
- La sintaxis basica de un atributo es: `<element atribute="value"> </element>` donde el nombre del atributo es seguido por un signo `=` y un valor entre comillas.

### Tipos de atributos

- `href`: Se utiliza para especificar la URL de un enlace.
- `target`: Se utiliza para especificar el destino de un enlace.
- `src`: Se utiliza para especificar la URL de una imagen.
- `alt`: Se utiliza para especificar el texto alternativo de una imagen.
- `checked`: Algunos atributos son poco unicos con su sintaxis, como el `checked` que no necesita un valor, solo necesita estar presente para que el elemento este seleccionado.
- `input` y `type`: El `input` es la etiqueta y `type` es el atributo que se utiliza para especificar el tipo de input.
- `disabled`: Este atributo se utiliza para especificar que un elemento no esta disponible para su uso, es decir, que no se puede utilizar.
- `readonly`: Este atributo se utiliza para especificar que un elemento no se puede editar, es decir, que no se puede modificar.
- `required`: Este atributo se utiliza para especificar que un elemento es requerido, es decir, que no se puede enviar el formulario sin completar ese elemento.

---

## Ejemplo

1. `href` y `target`
```html
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
```

El `a` es la etiqueta, `href` y `target` son atributos y `Visit freeCodeCamp` es el contenido del enlace. Sin la etiqueta `a` no se podria crear el enlace, sin el atributo `href` no se podria especificar la URL del enlace y sin el atributo `target` no se podria especificar el destino del enlace, que al usar `_blank` indica que ese hipervinculo se abriria en una nueva pestaña.

2. `src` y `alt`

```html
<img src="url de la imagen" alt="texto alternativo">
```

El `img` es la etiqueta, `src` y `alt` son atributos y `url de la imagen` y `texto alternativo` son los valores de los atributos. Sin la etiqueta `img` no se podria crear la imagen, sin el atributo `src` no se podria especificar la URL de la imagen y sin el atributo `alt` no se podria especificar el texto alternativo de la imagen.

3. `checked`

```html
<input type="checkbox" checked />
```

El `input` es la etiqueta, `type` y `checked` son atributos y `checkbox` y `true` son los valores de los atributos. Sin la etiqueta `input` no se podria crear el input, sin el atributo `type` no se podria especificar el tipo de input y sin el atributo `checked` no se podria especificar si el input esta seleccionado. El atributo `checked` no necesita un valor, solo necesita estar presente para que el elemento este seleccionado, es decir, que si nosotros eliminaramos el `checked` al final, pues la casilla ya no estaria seleccionada. Tal que:

```html
<input type="checkbox" />
```
4. `disabled` y `readonly`

```html
<input type="text" disabled>
```
Al estar presente el `disable` entonces no es posible escribir en el `input`, pero si eliminamos el `diable` entonces ya podriamos editar sin ningun inconveniente:

```html
<input type="text">
```
Mientras que si agregamos entonces `readonly` al inputm estariamos diciendo que es un campo NECESARIO para poder continuar:

```html
<input type="text" required>
```

---
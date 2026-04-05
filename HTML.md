# Notas sobre HTML

---

## Conceptos básicos

- Los titulos van del `h1` al `h6`
- Los parrafos se declaran con la etiqueta `<p>`
- Las etiquetas se cierran con la sintaxis `</p>`
- Al insertar una foto se realiza el siguiente paso: `<img src="enlace de la foto" alt="texto alternativo">`

---

## Atributos

- **Atributo:** Es un valor colocado dentro de la etiqueta de apertura de un elemento HTML.
- La sintaxis basica de un atributo es: `<element atribute="value"> </element>` donde el nombre del atributo es seguido por un signo `=` y un valor entre comillas.

### Tipos de atributos

- `href`: Se utiliza para especificar la URL de un enlace.
- `target`: Se utiliza para especificar el destino de un enlace.

---

## Ejemplo

```html
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
```

El `a` es la etiqueta, `href` y `target` son atributos y `Visit freeCodeCamp` es el contenido del enlace. Sin la etiqueta `a` no se podria crear el enlace, sin el atributo `href` no se podria especificar la URL del enlace y sin el atributo `target` no se podria especificar el destino del enlace, que al usar `_blank` indica que ese hipervinculo se abriria en una nueva pestaña.

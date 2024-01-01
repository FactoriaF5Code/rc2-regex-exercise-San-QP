[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/aRQGnba4)

# Expresiones Regulares (regex)

## Investiga:

- qué son las expresiones regulares?
- Qué problema resuelven? Por qué es importante conocerlas?

## Ejercicio 1:

Escribe las expresiones regulares correctas para validar:

- un email: [\w._%+-]+@[\w.-]+\.[a-zA-Z]{2,4}
- un número de teléfono (español):
  - teléfono fijo: (\+34)?[9][0-9]{8}
  - teléfono móvil: (\+34)?[6][0-9]{8}
- un DNI: [0-9]{8}-?[a-zA-Z]

## Ejercicio 2:

Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. El formulario debe incluir: nombre, apellidos, dni, número de teléfono, email, dni y dirección.

Nota: puedes hacerlo añadiendo un archivo `index.html` en este repositorio.

## Referencias

- [Expresiones Regulares en Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
- [Online Regex Editor](https://regex101.com/)

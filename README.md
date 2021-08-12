# form-validación-regex
**Formulario con expreciones regulares regex, bootcamp femtech**

Ejercicio A:

 Escribe las expresiones regulares correctas para validar:

    1. un email: pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$"
    2. un número de teléfono (español): pattern="(\+34|0034|34)?[ -]*(6|7)[ -]*([0-9][ -]*){8}"
    3. un DNI: pattern="(([X-Z]{1})([-]?)(\d{7})([-]?)([A-Z]{1}))|((\d{8})([-]?)([A-Z]{1}))"

Ejercicio B:

 Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. 
  El formulario debe incluir:

  1. Nombre 
  2. Apellidos
  3. DNI
  4. Número de teléfono
  5. Email 
  6. Dirección

Cree un proyecto nuevo y en este dos carpertas, una llamada index.html que es donde 
estara el formulario y otro archivo llamado style.css que sera para darle estilo a nuestro formulario. 
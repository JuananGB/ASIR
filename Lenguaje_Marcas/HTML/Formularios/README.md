```bash
// Etiquetas de formulario en HTML
   <form>...</form>: Define un formulario HTML para la entrada de usuario.
   <input>: Define un campo de entrada donde el usuario puede ingresar datos.
   <textarea>: Define un área de texto multilínea para la entrada de usuario.
   <datalist> Ejemplo de formulario con botones de opciones y casillas de verificación

        // Atributos comunes de <form>
        action: Especifica la URL a la que se enviarán los datos del formulario.
        method: Define el método HTTP para enviar los datos (GET o POST).
        enctype: Especifica cómo se codifican los datos del formulario al enviarlos.
        target: Define dónde se abrirá el documento enviado (por ejemplo, en una nueva pestaña).
        
        // Atributos comunes de <input>
        list : El atributo "list" de un <input> vincula ese campo con un <datalist> (mediante su id),
        type: Define el tipo de campo de entrada (text, password, radio, file,submit,reset).
        name: Especifica el nombre del campo de entrada, utilizado para identificar los datos enviados.
        value: Define el valor predeterminado del campo de entrada.
        placeholder: Proporciona un texto de sugerencia dentro del campo de entrada.
        required: Indica que el campo de entrada es obligatorio.
        maxlength: Especifica el número máximo de caracteres permitidos en el campo de entrada.
        size: Define el ancho visible del campo de entrada en caracteres.

        // Atributos comunes de <textarea>
        name: Especifica el nombre del área de texto, utilizado para identificar los datos enviados.
        rows: Define el número de filas visibles en el área de texto.
        cols: Define el número de columnas visibles en el área de texto.
        placeholder: Proporciona un texto de sugerencia dentro del área de texto.
        required: Indica que el área de texto es obligatoria.

        // Atributos comunes de <datalist>
        - Atributos comunes del elemento <datalist>:
                - id: necesario para enlazarlo con un <input> mediante el atributo list.
                - class, style, title, hidden y otros atributos globales (data-*, tabindex, etc.).
                - atributos ARIA (role, aria-*, para accesibilidad).

        - Contenido (hijos <option>):
                - value: valor sugerido que se inserta en el <input>.
                - label: etiqueta alternativa/descriptiva para la opción.
                - disabled: marca la opción como no seleccionable.
```
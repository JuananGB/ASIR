``` bàsh
    <a> </a> // Etiqueta de un enlace
// ATRIBUTOS
    // Enlaces absolutos y relativos
        - href: Define la URL del enlace.
        - target: Define dónde se abrirá el enlace. Valores comunes:
            _self: Abre el enlace en la misma pestaña (predeterminado).
            _blank: Abre el enlace en una nueva pestaña.
            _parent: Abre el enlace en el marco padre.
            _top: Abre el enlace en la ventana completa.
        - title: Proporciona información adicional sobre el enlace (aparece como tooltip)

*** Ejemplo de enlaces relativos:
    - Enlace a un archivo en la misma carpeta:
        <a href="pagina_relativa.html">Abrir pagina_relativa.html</a>

    - Enlace a un archivo en una subcarpeta:
        <a href="carpeta/pagina.html">Abrir carpeta/pagina.html</a>

    - Enlace a un archivo en la carpeta superior:
        <a href="../padre.html">Abrir ../padre.html</a>

    - Enlace a una ancla dentro del mismo documento:
        <a href="#seccion1">Ir a la sección 1</a>

    - Enlace desde la raíz del servidor:
        <a href="/proyecto/index.html">Abrir /proyecto/index.html</a>

```
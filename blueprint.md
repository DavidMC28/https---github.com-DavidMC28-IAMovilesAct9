
# Blueprint: App de Comida

## Visión General

Una aplicación Flutter para explorar y pedir comida, basada en un boceto proporcionado por el usuario. La aplicación contará con un diseño moderno, un esquema de colores personalizable y una interfaz de usuario limpia para una experiencia de usuario atractiva.

## Estilo y Diseño

- **Diseño Moderno:** Un diseño limpio y visualmente equilibrado con un amplio espacio en blanco.
- **Tipografía:** Utiliza `google_fonts` para la tipografía (`Oswald` para los títulos, `Roboto` para el cuerpo del texto).
- **Tema:**
  - Implementa temas claro y oscuro utilizando el paquete `provider`.
  - El esquema de colores se genera a partir de un único color semilla (`Colors.deepPurple`) para una paleta armoniosa (Material 3).
- **Iconografía:** Iconos de Material Design para la navegación y las acciones.

## Características Implementadas

- **Pantalla de Inicio:**
  - AppBar con el título de la aplicación ("Comida") y un icono de hamburguesa.
  - Botones para cambiar entre los modos de tema (claro/oscuro/sistema).
  - Barra de búsqueda para encontrar platos de comida.
  - Lista horizontal de categorías de comida (por ejemplo, Bebidas, Frituras, Botanas).
  - Lista vertical de platos de comida populares, cada uno con una imagen, nombre y descripción.

## Plan Actual

1.  **Configurar la Estructura de la App:** Inicializar la aplicación con `MaterialApp`, `provider` para la gestión del tema y `google_fonts` para la tipografía personalizada.
2.  **Construir la Interfaz de Usuario de la Pantalla de Inicio:**
    - Crear el AppBar personalizado.
    - Añadir una barra de búsqueda estilizada.
    - Implementar la lista de categorías de desplazamiento horizontal.
    - Implementar la lista de platos de comida de desplazamiento vertical utilizando datos de marcador de posición.
3.  **Refinar el Diseño:** Asegurar que el diseño sea responsivo y estéticamente agradable en diferentes tamaños de pantalla.

# eBazar - Produktu Ataria

Este proyecto es una página web simple para simular una tienda en línea llamada "eBazar". El objetivo es mostrar una interfaz básica con productos, filtros, opciones de ordenación, barra de búsqueda, y un carrito de compras. Está hecha en HTML, CSS y JavaScript para generar productos dinámicamente.

## Características

- **Encabezado y navegación:** Un encabezado con el nombre de la tienda y un menú de navegación con enlaces básicos.
- **Barra de búsqueda:** Permite al usuario buscar productos.
- **Filtros de productos:** Cuatro botones para filtrar por categoría (Electrónica, Ropa, Hogar, Deportes).
- **Ordenación:** Permite ordenar los productos por precio (ascendente o descendente) o nombre (A-Z, Z-A).
- **Generación dinámica de productos:** Los productos se generan dinámicamente con JavaScript. Cada producto tiene una imagen, nombre, breve descripción y precio.
- **Carrito de compras:** Un botón para agregar productos al carrito.
- **Responsividad:** Se adapta a dispositivos móviles y de escritorio.
- **Diseño visual atractivo:** Se utiliza una combinación de colores modernos y un diseño limpio para mejorar la experiencia del usuario.

## Estructura del Proyecto

/eBazar 
│
├── index.html # Archivo principal con la estructura HTML 
├── README.md # Este archivo 

## Instalación

Este proyecto no requiere ninguna configuración o servidor especial. Solo necesitas un navegador web para verlo.

### Pasos:

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en tu navegador web.
3. ¡Disfruta de la experiencia de compra simulada!

## Personalización

Puedes personalizar este proyecto de varias formas:

- **Productos:** Los productos se generan a partir de un array de imágenes y nombres en el archivo `script.js`. Puedes modificar el array de `productNames` y `imageLinks` para agregar o cambiar los productos y sus imágenes.
  
- **Estilos:** El archivo `styles.css` te permite personalizar la apariencia de la página. Puedes cambiar colores, tamaños, márgenes, y más.

- **Ordenación:** La funcionalidad de ordenación se encuentra en un menú desplegable en la sección de filtros. Puedes modificar los criterios de ordenación según tus necesidades.

- **Funcionalidades adicionales:** Si deseas agregar más características como un sistema de autenticación de usuarios, base de datos para productos, o funcionalidades de carrito de compras, puedes ampliar el código en los archivos correspondientes.

## Tecnologías Utilizadas

- **HTML5:** Estructura básica de la página.
- **CSS3:** Estilos y diseño visual de la página, con soporte para medios responsivos.
- **JavaScript:** Generación dinámica de productos y control de la interacción del usuario con filtros y ordenación.
  
## Capturas de Pantalla

*Añade aquí algunas capturas de pantalla que muestren cómo se ve la página en diferentes dispositivos (por ejemplo, en móvil y escritorio).*

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de realizar un fork del repositorio y hacer un pull request con tus mejoras.

Para empezar:

1. Haz un fork de este repositorio.
2. Crea una rama con tu cambio: `git checkout -b mi-cambio`.
3. Haz commit de tus cambios: `git commit -am 'Agregué una nueva característica'`.
4. Haz push a la rama: `git push origin mi-cambio`.
5. Abre un pull request.

## Licencia

Este proyecto es de código abierto y se distribuye bajo la Licencia MIT. Puedes hacer lo que quieras con él, pero no olvides dar el crédito 
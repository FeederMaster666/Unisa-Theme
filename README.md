Shopify Theme – Prueba Técnica

En este repositorio se realiza el desarrollo de un tema en Shopify basado en el theme Horizon, creado como parte de una prueba técnica.
El objetivo principal es replicar el diseño y funcionalidad de la web de referencia Unisa Europa, incluyendo:
-Home Page

-Listado de productos (PLP)

-Detalle de producto (PDP)

--OBJETIVOS DEL PROYECTO--

1-Copiar fielmente el diseño visual (colores, tipografías, tamaños, iconografía).

2-Reproducir interacciones clave: menús, sliders, acordeones y comportamiento responsive.

3-Implementar buenas prácticas de desarrollo con Liquid, CSS y Shopify CLI.

4-Mantener el código versionado con Git para trabajo colaborativo.

--TECNOLOGIAS UTILIZADAS--

Shopify CLI – para el desarrollo local y despliegue en el entorno.

Shopify Liquid – plantillas y lógica de renderizado.

Theme Horizon – base del desarrollo.

HTML5 & CSS3 – maquetación y personalización.

Git – control de versiones.

VS Code – entorno de desarrollo.

--PUESTA EN MARCHA--

1. Clonar el repositorio
git clone https://github.com/usuario/proyecto-shopify-unisa.git
cd proyecto-shopify-unisa

2. Instalacion de Shopify CLI

3. Autenticación en Shopify
shopify login --store nombre-de-la-tienda.myshopify.com

4. Iniciar servidor de desarrollo
shopify theme dev

/*Esto abre una URL temporal donde ver los cambios en tiempo real.*/

5. Subir cambios al entorno
shopify theme push

--ESTRUCTURA DEL PROYECTO--

/sections        → Secciones reutilizables (hero, acordeón, carruseles…)
/snippets        → Fragmentos de código (botones, iconos, menús…)
/templates       → Plantillas para páginas (product, collection, etc.)
/assets          → Archivos CSS, JS e imágenes
/config          → Configuración del tema y presets

--FUNCIONALIDADES DESTACADAS--

-Header:

Menú hamburguesa visible en desktop y móvil.

Opción de destacar un ítem de menú en rojo.

Barra de anuncios editable.

-Home Page:

Carrusel de colecciones con información superpuesta.

Secciones editables desde el CMS (mínima dependencia del código).

-PLP (Product Listing Page):

Filtros y ordenación personalizados.

Breadcrumbs (ejemplo: Inicio > Zapatos de mujer).

Botón de “Agregar al carrito” visible en la tarjeta del producto.

-PDP (Product Detail Page):

Galería principal + miniaturas.

Acordeón para información adicional (sin bordes).

Dropdown de tallas estilo botón.

--PERSONALIZACION VIA CMS

Siempre que es posible, los cambios se realizan desde el Theme Editor de Shopify para evitar tocar directamente el código.
Ejemplos:

-Colores de botones → Configuración de esquema de color.

-Barra de anuncios → Configuración de la sección Announcement Bar.

-Acordeones → Opción de activar/desactivar dividers.

--TAREAS PENDIENTES/MEJORAS FUTURAS--

Terminar carrusel con overlay de información en el Home.

Ajustar estilos de botones en PLP (filtros, ordenar).

Diferenciar PDP según tipo de producto (zapatos/bolsos).

Añadir app para feed de Instagram en el footer.

Optimización responsive avanzada.

--AUTOR--

Nombre: Miguel Alvarez Rodriguez(desarrollador front-end multiplataforma)

Rol: Desarrollo del tema en Shopify + personalización vía CMS y CLI

Contacto: mialvarezro@gmail.com.com
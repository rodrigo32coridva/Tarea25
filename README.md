# Tarea6 - SiteOtaku 🌸

Proyecto web desarrollado como parte de una tarea académica.  
Se trata de una plataforma temática tipo **Otaku/Anime**, creada con **HTML, CSS y Bootstrap 5**, que incluye:

- Página principal con cards de anime mejoradas con etiquetas de género, rating con estrellas, botón de favoritos, contador de vistas y animación al pasar el mouse.
- Reproductores de trailers embebidos en cada card usando iframes de YouTube.
- Menú por géneros (con corrección para desplegar completamente el menú en el navbar).
- Página de login con estilos personalizados y fondo temático.
- Página de registro con estilos personalizados y fondo temático.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3 (con estilos personalizados para animaciones, badges, ratings y favoritos)
- [Bootstrap 5.3](https://getbootstrap.com/)
- Imágenes de fondo y contenido de estilo anime
- Iframes de YouTube para trailers

---

## 📁 Estructura del proyecto

```plaintext
Tarea25/
├── index.html             # Página principal (SiteOtaku) con cards de anime mejoradas
├── css/                   # Carpeta para estilos
│   └── style.css          # Estilos personalizados (tema otaku, animaciones, badges, ratings)
├── Img/                   # Carpeta de imágenes
│   ├── fondo3.jpg         # Fondo para index
│   ├── fondologin.jpg     # Fondo para login y registro
│   └── ...                # Otros assets (personajes, logos, etc.)
├── icon/                  # Carpeta para iconos y favicons
│   ├── favicon-16x16.png  # Ícono favicon tamaño 16x16
│   ├── favicon-32x32.png  # Ícono favicon tamaño 32x32
│   └── ...                # Otros archivos de iconos
├── html/                  # Subcarpeta para páginas secundarias
│   ├── login.html         # Página de inicio de sesión con diseño personalizado
│   └── register.html      # Página de registro con diseño personalizado
└── README.md              # Información del proyecto (actualizado con detalles de modificaciones)
```

## ✨ Cambios y mejoras realizadas

- Se añadieron etiquetas de género en cada card para una mejor clasificación visual.
- Implementación de un botón "Agregar a favoritos" con un ícono ❤️ que cambia de color al pasar el mouse.
- Valoración visual con estrellas (rating) agregada en cada card.
- Animación suave al hacer hover sobre las cards para mejorar la experiencia de usuario.
- Contador estático de vistas en cada card para indicar popularidad.
- Corrección en el navbar para que el menú desplegable de géneros se muestre completo y sin cortarse.
- Optimización del tamaño del logo en el navbar para mejor alineación y visibilidad.
- Estilos personalizados para páginas de login y registro, manteniendo el tema otaku con fondos específicos y colores adecuados.
- Añadida carpeta icon con favicons en diferentes tamaños para mejor soporte en navegadores y dispositivos.

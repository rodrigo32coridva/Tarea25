# Tarea6 - SiteOtaku 🌸

Proyecto web desarrollado como parte de una tarea académica.  
Se trata de una plataforma temática tipo **Otaku/Anime**, creada con **HTML, CSS y Bootstrap 5**, que incluye:

- Página principal con carrusel de anime (imágenes + videos)
- Cards con información de animes
- Reproductores de trailers embebidos
- Menú por géneros
- Página de login
- Página de registro

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- [Bootstrap 5.3](https://getbootstrap.com/)
- JavaScript (ligero, para interacción del carrusel)
- Imágenes y trailers estilo anime
- Videos locales en formato `.mp4`
- Estilos visuales personalizados con `backdrop-filter` y sombras

---

## 🆕 Novedades del carrusel

Se ha implementado un carrusel multimedia en la página principal con las siguientes características:

- ✅ Slide 1: Imagen de presentación con bienvenida a **SiteOtaku**
- ✅ Slide 2: Video de *Solo Leveling* con descripción
- ✅ Slide 3: Video de *Los diarios de la boticaria*
- ✅ Slide 4: Video de *The 100 Girlfriends Who Really, Really, Really, Really, REALLY Love You*

Además, se añadieron captions con fondo sombreado, subtítulos estilizados y centrado total con `position-absolute`, `top-50`, `start-50`, y `translate-middle`.

---

## 📁 Estructura del proyecto

```plaintext
Tarea25/
├── index.html             # Página principal (SiteOtaku)
├── css/
│   └── style.css          # Estilos personalizados (tema otaku + carrusel)
├── Img/
│   ├── fondo3.jpg         # Fondo para index
│   ├── fondologin.jpg     # Fondo para login y registro
│   └── ruleta1.jpg        # Imagen de carrusel
├── videos/
│   ├── Solo Leveling Temporada 2 ｜ TRÁILER OFICIAL.mp4
│   ├── The Apothecary Diaries ｜ OFFICIAL TRAILER.mp4
│   └── The 100 Girlfriends... ｜ TRÁILER OFICIAL.mp4
├── html/
│   ├── login.html         # Página de inicio de sesión
│   └── register.html      # Página de registro
└── README.md              # Información del proyecto

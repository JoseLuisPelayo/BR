# Breaking Bad Fan Page

Este repositorio contiene el código fuente de una página web corporativa diseñada como parte de la actividad individual de la asignatura **Lenguaje de Marcas y Sistemas de Gestión** en la UNIR. La web está dedicada a los fans de *Breaking Bad* y presenta información, curiosidades y herramientas interactivas relacionadas con la serie.

---

## 📋 **Requisitos del Proyecto**

### Requerimiento 1: Página Principal
- **Archivo principal**: `index.html`
- Contenido:
  - Logotipo de la serie (`logo.png`) con un tamaño de 200x200 píxeles.
  - Texto destacado de la serie: 
    *"I did it for me. I liked it. I was good at it. And, I was really... I was alive."*
  - Imagen (`poster.jpg`) con:
    - Tamaño: 700x300 píxeles.
    - Borde: 10px `outset`, color marrón.
    - Esquinas redondeadas: 22px.
  - Fondo de pantalla con la imagen `fondo.jpg`.
- Navegación interactiva:
  - Zona "Breaking" → Redirige a `formulario.html`.
  - Zona "Bad" → Redirige a `tabla.html`.

### Requerimiento 2: Tipografía y Favicon
- Tipografía personalizada para la página principal (`Breaking Bad`).
- El resto de las páginas usa `Helvetica`.
- Favicon configurado en todas las pestañas del navegador.

### Requerimiento 3: Formulario
- Archivo: `formulario.html`
- Contenido:
  - Formulario con:
    - Datos personales: Nombre, Apellidos, Dirección Postal, DNI y Correo Electrónico (obligatorios).
    - Selección de sexo: Botones de opción.
    - Fecha de nacimiento: Selector de calendario.
    - Lista desplegable de personajes de la serie.
    - Caja de comentarios.
    - Botones: Enviar, Borrar y Adjuntar archivo.
  - Envío de datos simulados al correo `raul.rodriguez@jajaja.com`.

### Requerimiento 4: Tabla Periódica Breaking Bad
- Archivo: `tabla.html`
- Contenido:
  - Tabla interactiva con información basada en la estética de la tabla periódica.

### Requerimiento 5: Publicación en Hosting
- Página publicada en GitHub Pages o un hosting gratuito equivalente.
- Dirección web incluida en la entrega.

---

## 🚀 **Ejecución del Proyecto**
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/breaking-bad-fan-page.git


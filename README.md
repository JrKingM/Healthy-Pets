# Healthy Pets - Clínica Veterinaria

Sitio web institucional y de contacto para una clínica veterinaria, desarrollado con HTML semántico, CSS personalizado y Bootstrap 5. El proyecto está orientado a mostrar servicios, reforzar la identidad de marca y facilitar la solicitud de citas mediante WhatsApp.

## Estructura del proyecto

- [index.html](index.html): estructura principal del sitio con secciones de inicio, sobre nosotros, servicios, beneficios, testimonios, contacto y pie de página.
- [css/style.css](css/style.css): estilos personalizados para tipografía, colores, layout responsivo, efectos hover y componentes visuales del sitio.
- [css/bootstrap.min.css](css/bootstrap.min.css): hoja de estilos de Bootstrap 5 para utilidades y componentes base.
- [js/bootstrap.bundle.min.js](js/bootstrap.bundle.min.js): script de Bootstrap 5 para componentes interactivos como el menú colapsable y el carrusel.
- [img/](img/): recursos visuales utilizados en el diseño del sitio.

## Funcionalidades principales

- Diseño responsive adaptado a pantallas móviles y de escritorio.
- Sección de servicios con 4 tarjetas visuales y efecto hover suave.
- Menú de navegación con enlaces internos y desplazamiento suave.
- Botón de emergencia 24/7 con llamada directa mediante tel:.
- Formulario de contacto con selección de servicio para agendar citas.
- Envío directo a WhatsApp con el motivo de consulta y la explicación del cliente.
- Imágenes optimizadas con atributos width, height, loading y alt descriptivos.

## Requisitos revisados y confirmados

- ✅ Se incluyen 4 tarjetas de servicios con la clase article class="tarjeta".
- ✅ El contenedor de servicios usa clases de Bootstrap para flex-wrap y gap.
- ✅ El menú de navegación utiliza enlaces tipo ancla con desplazamiento suave.
- ✅ El botón del menú móvil usa los atributos data-bs-toggle="collapse" y data-bs-target="#navbarMenu".
- ✅ El botón de emergencia 24/7 utiliza un enlace tel:.
- ✅ El contenedor principal está centrado con max-width: 1500px y margin: auto.
- ✅ El sitio implementa scroll-behavior: smooth.
- ✅ Existe un formulario de contacto que envía la información por WhatsApp mediante JavaScript.
- ✅ Bootstrap 5 está cargado correctamente desde js/bootstrap.bundle.min.js.
- ✅ Las imágenes del catálogo incluyen width, height, loading y alt adecuados.

## Cómo ejecutar el sitio localmente

Puedes visualizar el proyecto de dos formas:

1. Abrir directamente el archivo [index.html](index.html) en el navegador.
2. O servir la carpeta desde un servidor local, por ejemplo:

```bash
python -m http.server 8000
```

Luego abrir en el navegador:

```text
http://localhost:8000/
```

## Notas de Bootstrap 5 y responsividad

- Bootstrap 5 se utiliza para la navegación, el carrusel y los estilos base del formulario.
- La distribución de las tarjetas de servicios cambia según el tamaño de pantalla para mejorar la experiencia en dispositivos móviles y desktop.
- Los efectos visuales, como el hover de las tarjetas, fueron diseñados para aportar fluidez y una sensación más moderna.
- El formulario está pensado para facilitar la agendación de citas sin pasos adicionales para el usuario.

## Autor

Desarrollado por Josue Reyes.

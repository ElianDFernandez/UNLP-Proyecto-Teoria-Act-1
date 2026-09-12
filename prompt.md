Actuá como desarrollador/a web especializado/a en HTML y CSS. Necesito que generes una versión completa y funcional de un sitio web estático, sin JavaScript ni ningún otro lenguaje de programación, para una institución ficticia llamada “Instituto Lingüístico UNLP”, que publica cursos de idiomas.

## Objetivo del sitio

El sitio debe permitir consultar un catálogo de cursos y descargar el programa en PDF de cada uno. Debe estar pensado para estudiantes y visitantes de la institución, con una interfaz clara, accesible, moderna y responsive.

## Requisitos obligatorios

1. Usá únicamente HTML y CSS. No incluyas JavaScript, frameworks ni librerías externas.
2. Todas las reglas de estilo deben estar en un archivo separado llamado `estilosIA.css`.
3. Incluí una barra de navegación visible y responsive con enlaces a:
	- Contacto.
	- Quién mantiene el sitio.
	- Inicio o catálogo.
4. El catálogo debe estar organizado por categorías (por ejemplo, "Inglés" y "Francés").
5. La selección de la categoría debe funcionar de manera completamente estática, sin scripts. Podés resolverla mediante radio buttons y el selector CSS `:checked`, o mediante páginas HTML separadas. La categoría seleccionada debe mostrar únicamente, o destacar claramente, los cursos correspondientes.
6. Mostrá al menos tres cursos de inglés y tres cursos de francés. Usá estos cursos:
	- Inglés: Inglés inicial, Inglés intermedio e Inglés avanzado.
	- Francés: Francés inicial, Francés intermedio y Francés avanzado.
7. Cada curso debe presentarse en una tarjeta claramente delimitada, con borde exterior, relleno interior, título, una breve descripción o nivel y un enlace para descargar su programa en PDF.
8. Los enlaces a los programas deben apuntar a archivos ubicados en un directorio llamado `programas`, con estos nombres:
	- `programas/ingles-inicial.pdf`
	- `programas/ingles-intermedio.pdf`
	- `programas/ingles-avanzado.pdf`
	- `programas/frances-inicial.pdf`
	- `programas/frances-intermedio.pdf`
	- `programas/frances-avanzado.pdf`
9. Incluí una sección de contacto con un formulario HTML simple y accesible. El formulario puede contener nombre, correo electrónico, motivo de consulta y mensaje. Como el sitio es estático, no hace falta implementar el envío real, pero indicá claramente que es un formulario de demostración.
10. Incluí una sección “Quién mantiene el sitio” con información ficticia de la persona o equipo responsable.
11. El diseño debe ser responsive y funcionar correctamente en celulares, tablets y computadoras mediante CSS media queries.
12. Aplicá buenas prácticas de accesibilidad: estructura semántica (`header`, `nav`, `main`, `section`, `article`, `footer`), textos alternativos cuando corresponda, etiquetas asociadas a los campos del formulario, buen contraste de colores, foco visible y enlaces descriptivos.
13. No uses estilos en línea. No uses contenido de relleno como `Lorem ipsum`.
14. Agregá metadatos básicos en cada página, incluyendo `charset`, `viewport` y un título descriptivo.

## Archivos que debés entregar

Generá el contenido completo de una estructura de proyecto lista para copiar, incluyendo como mínimo:

- `index.html`
- `estilosIA.css`
- El directorio `programas/` con seis archivos PDF de referencia

Si considerás más conveniente separar las secciones en distintas páginas HTML para mantener la navegación y la selección estática, podés agregar `contacto.html` y `mantenimiento.html`, manteniendo siempre el CSS en `estilosIA.css`.


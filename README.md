# Informe del proyecto "Introducción a Git"

## Descripción general

Este repositorio contiene una página web de presentación creada para la asignatura **Ingeniería de Software I**. El objetivo fue desarrollar una landing page con estilos modernos, documentar el flujo de trabajo con Git y publicar el proyecto en un repositorio remoto en GitHub.

## Objetivos del proyecto

- Desarrollar una página web funcional con HTML y CSS.
- Aplicar un diseño moderno y visualmente atractivo.
- Usar Git para el control de versiones del proyecto.
- Realizar commits progresivos y demostrar el uso de `git reset`.
- Conectar el repositorio local a GitHub y subir los cambios.

## Estructura del repositorio

| Archivo | Descripción |
| --- | --- |
| `Index.html` | Página principal con contenido del proyecto, datos del curso y enlace al repositorio. |
| `style.css` | Estilos visuales: paleta oscura, botones, tarjetas, efectos de fondo y responsive. |
| `README.md` | Informe completo del proyecto y del proceso realizado. |

## Mejoras realizadas en la página web

- Se actualizó el título y la descripción para reflejar el tema de Git y GitHub.
- Se incluyó el nombre del curso: **Ingeniería de Software I · Guía de Laboratorio I**.
- Se agregó un botón destacado que dirige al repositorio remoto.
- Se reforzó la presentación del autor con tarjeta e información académica.
- Se creó una sección de resumen del proyecto con tarjetas de características.
- Se mejoró el estilo general para un aspecto más profesional y moderno.

## Detalles técnicos

### Cambios en `Index.html`

- Cambio del título principal a un encabezado más claro y acorde con el proyecto.
- Inclusión de un CTA con enlace al repositorio de GitHub.
- Adición de una sección `Resumen del proyecto` que explica las características principales.
- Organización del contenido en secciones legibles y jerarquizadas.

### Cambios en `style.css`

- Paleta de colores oscura con acentos celestes y púrpuras.
- Fondos degradados y efectos de vidrio (glassmorphism).
- Botón principal con animación de elevación y efecto hover.
- Tarjetas del resumen con sombreado suave y hover suave.
- Mejora de la tipografía y el espaciado para mayor legibilidad.
- Ajustes responsive para pantalla de tablets y móviles.

## Flujo de trabajo con Git

### Commits realizados

1. `e182b84` — Commit: página web con estilos CSS
2. `fd61424` — Commit: modificación adicional en la página
3. `e75d718` — Commit final: modificación después del reset

### Comandos usados

```bash
git add .
git commit -m "Commit: página web con estilos CSS"
git add Index.html
git commit -m "Commit: modificación adicional en la página"
git reset --hard e182b84
git add Index.html
git commit -m "Commit final: modificación después del reset"
```

### Conexión con GitHub

El repositorio local fue conectado al remoto de GitHub y la rama `master` se subió correctamente:

```bash
git remote add origin https://github.com/RonaldoTcnJnc/IntroduccionGIT.git
git push -u origin master
```

## Resultados obtenidos

- Página funcional con estilo moderno y título claro.
- Implementación de buen uso de Git en el flujo del proyecto.
- Repositorio vinculado a GitHub y cambios empujados correctamente.
- `README.md` mejorado para documentar el proyecto y el proceso de desarrollo.

## Conclusión

Este proyecto demuestra la combinación de diseño web y control de versiones con Git. La página ahora tiene un aspecto profesional, el repositorio está correctamente sincronizado con GitHub y el proceso de commits quedó documentado de forma clara.

## Siguientes pasos recomendados

- Revisar el sitio en un navegador y ajustar el contenido según el estilo académico deseado.
- Añadir más secciones sobre comandos usados o pasos del laboratorio.
- Mantener commits claros y frecuentes al continuar con el proyecto.

# Portafolio Personal - TPO 1

Este proyecto es un portafolio personal desarrollado para la materia Desarrollo Web Frontend. El objetivo es mostrar información personal, proyectos y contacto, aplicando buenas prácticas de HTML5, CSS3 y diseño responsivo.

Repositorio Github: https://github.com/matias-estanqueiro/portfolio-personal

URL del proyecto:   https://mae-dev.vercel.app/

## Checklist

### Estructura del Proyecto:
- [x] Archivo "index.html" ubicado en la raíz.  
	> El archivo principal del sitio, contiene toda la estructura HTML, comentarios explicativos y las distintas secciones del portafolio.
- [x] Carpeta "css" que contenga el archivo "styles.css".  
	> En la carpeta `css/` se encuentra `styles.css`, donde se definen variables, resets, layout, grillas, animaciones y media queries. El archivo está documentado con comentarios por sección.
- [x] (Opcional) Carpeta "img" para recursos gráficos (en este caso, la carpeta es "images").  
	> Los recursos gráficos (imágenes de avatar, proyectos, fondo) están en la carpeta `images/`, referenciados desde el HTML y el CSS.
- [x] Archivo "README.md" creado, que incluya una breve descripción del TP y este checklist.  
	> Este archivo documenta el proyecto, su estructura y el cumplimiento de los requerimientos.

### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.  
	> El código fuente está disponible en GitHub: https://github.com/matias-estanqueiro/portfolio-personal
- [x] Proyecto subido al repositorio.  
	> Todos los archivos y carpetas del proyecto están versionados y subidos al repositorio.
- [x] Proyecto publicado utilizando Vercel.  
	> El sitio está desplegado en Vercel: https://mae-dev.vercel.app/
- [x] En el "README.md" se indica la URL de Vercel.  
	> Ambas URLs (GitHub y Vercel) están indicadas al inicio de este archivo.

### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección "head" del HTML.  
	> En el `<head>` de `index.html` se incluyen los enlaces a Google Fonts para "Space Grotesk" y "Manrope".
- [x] La tipografía importada se aplica en el sitio.  
	> En `styles.css` se definen las variables `--font-heading` y `--font-body` para aplicar las fuentes en títulos y cuerpo, respectivamente.
- [x] Redacta brevemente tu decisión: ¿Por qué elegiste esa fuente?
	> Elegí "Space Grotesk" para títulos y "Manrope" para el cuerpo porque ambas ofrecen una estética moderna y legible, alineada con el diseño cyberpunk del portafolio.

### HTML:
- [x] El documento inicia con la declaración DOCTYPE y usa el atributo lang="es".  
	> En la primera línea de `index.html` se encuentra `<!DOCTYPE html>` y el atributo `lang="es"` en la etiqueta `<html>`.
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.  
	> En el `<head>` están las metaetiquetas `<meta charset="UTF-8">` y `<meta name="viewport" ...>`.
- [x] Se ha definido un título descriptivo.  
	> El título "MAE.dev // System Archive" se define en la etiqueta `<title>`.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.  
	> En el `<head>` se incluyen los enlaces a Google Fonts y el archivo `css/styles.css`.
- [x] Barra de navegación ("nav") presente y contiene al menos 3 enlaces.  
	> Hay dos barras de navegación: una para desktop (`.desktop-nav`) y otra para mobile (`.mobile-bottom-nav`), ambas con enlaces a las secciones principales.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.  
	> El HTML contiene múltiples comentarios explicando la estructura, secciones y puntos requeridos.

### CSS:
- [x] Existe el archivo "styles.css" con estilos personalizados.  
	> El archivo `css/styles.css` contiene estilos organizados por secciones, con comentarios y enfoque Mobile First.
- [x] Se utilizan selectores basados en clases e identificadores.  
	> Se emplean selectores de clase (por ejemplo, `.content-section`, `.project-card`) e identificadores para estructurar y personalizar los estilos.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.  
	> Las fuentes se aplican mediante variables CSS y selectores globales en el archivo de estilos.

#### Layout y Organización:
- [x] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.  
	> Las grillas de habilidades, proyectos y extras usan Flexbox y CSS Grid, definidos en las clases `.skills-grid`, `.projects-carousel` y `.about-grid` en `styles.css`.
- [x] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?
	> Flexbox y Grid permiten organizar el contenido de manera flexible y responsiva, facilitando la adaptación a diferentes tamaños de pantalla y mejorando la experiencia de usuario.

#### Estilización de Componentes:
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.  
	> Los estilos de botones (`.btn-submit`), enlaces, formularios y tarjetas están definidos y documentados en `styles.css`.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (%, rem, vh).  
	> Las imágenes y contenedores usan unidades relativas para asegurar la adaptabilidad, como se observa en `.profile-img`, `.card-img` y grillas.
- [x] Se ha implementado al menos una animación o transición (por ejemplo, efecto hover en tarjetas o botones).  
	> Se implementan transiciones y animaciones en `.pulse-dot`, `.project-card:hover`, `.btn-submit:hover` y otros, para mejorar la experiencia visual.
- [x] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era adecuada para tu proyecto?
	> Se implementaron transiciones en botones y tarjetas para resaltar la interacción del usuario, haciendo la experiencia más dinámica y atractiva. La animación `pulse` en el estado del sistema refuerza la estética tecnológica.

### Consideraciones Adicionales:
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.  
	> El enfoque Mobile First y los media queries en `styles.css` aseguran la correcta visualización en móviles y desktop.
- [x] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos alt en las imágenes).  
	> Todas las imágenes incluyen el atributo `alt` y se cuida el contraste de colores y la navegación por teclado.
- [x] Se añadieron comentarios adicionales donde se describen decisiones de diseño o la lógica de implementación.  
	> Tanto en el HTML como en el CSS se incluyen comentarios explicativos sobre la lógica, estructura y decisiones de diseño.

---

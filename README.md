# 🎨 Juego de Pintar

Un juego de pintar para niños (y no tan niños). Elige un animal, selecciona una herramienta y dale tu toque de color.

## ✨ Características

- **3 dibujos para colorear**: 🐱 gato, 🐠 pez y 🐸 rana.
- **Menú desplegable de herramientas**:
  - 🖌️ **Pincel fino** — para detalles.
  - 🧹 **Brocha gruesa** — para pintar rápido grandes zonas a mano alzada.
  - 💨 **Aerógrafo** — efecto spray difuso.
  - 🪄 **Rellenar región** — haz clic en una zona del dibujo y se pinta entera, sin salirse de las líneas (relleno por inundación con detección de contornos).
  - 🧽 **Borrador**.
- **Paleta de colores** con 16 colores + selector de color personalizado.
- **Tamaño ajustable** del trazo con un deslizador.
- **Deshacer**, **limpiar lienzo** y **guardar tu dibujo como PNG**.
- Funciona en escritorio y táctil (móvil/tablet).

## 🚀 Cómo jugar

1. Abre `index.html` en cualquier navegador (doble clic, o visita la web publicada).
2. Elige el animal en el desplegable **Animal**.
3. Elige la herramienta en el desplegable **Herramienta** y un color de la paleta.
4. ¡Pinta! Con la herramienta *Rellenar región*, un clic dentro de cualquier zona (una oreja, una aleta, el vientre…) la rellena completa.
5. Pulsa **Guardar PNG** para descargar tu obra de arte.

> Sin dependencias externas: funciona incluso sin conexión a internet (solo necesitas el archivo).

## 🌐 Jugar online

El juego está publicado con GitHub Pages en:

**https://ajpuceda.github.io/JuegoPintar/**

## 🛠️ Tecnología

- JavaScript puro (vanilla) en un único archivo HTML — sin frameworks, sin CDN, sin instalación ni compilación.
- Canvas 2D en dos capas: capa de pintura + capa de líneas del dibujo (así los contornos nunca se borran).
- Algoritmo de *flood fill* con máscara de contornos para el relleno por regiones.

¡Feliz pintura! 🖍️

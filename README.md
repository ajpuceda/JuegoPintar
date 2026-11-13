# 🎨 Juego de Pintar

Un juego de pintar para niños (y no tan niños). Elige entre **50 dibujos**, selecciona una herramienta y dale tu toque de color.

## ✨ Características

- **50 dibujos para colorear**, organizados en 4 categorías:
  - 🐾 **Animales (22)**: gato, perro, conejo, caballo, vaca, cerdo, oso, león, elefante, jirafa, rana, tortuga, pez, delfín, mariposa, abeja, mariquita, caracol, pulpo, cangrejo, búho y pingüino.
  - 🚗 **Vehículos (12)**: coche, camión, autobús, moto, bicicleta, velero, barco pesquero, avión, helicóptero, cohete, tren de vapor y globo aerostático.
  - 🌿 **Naturaleza (9)**: flor, girasol, árbol, seta, sol, luna, arcoíris, hoja y copo de nieve.
  - 🏰 **Objetos y lugares (7)**: casa, castillo, robot, balón de fútbol, cometa, manzana y reloj despertador.
- **Interfaz compacta que cabe en una sola pantalla**: el lienzo se ajusta automáticamente al espacio disponible, sin hacer scroll.
- **Botones de herramienta grandes** (pincel, brocha, spray, rellenar, borrador): un solo clic, fáciles de acertar también en pantallas táctiles.
- Herramientas:
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
2. Elige el dibujo en el desplegable **Dibujo**.
3. Elige la herramienta con un botón grande y un color de la paleta.
4. ¡Pinta! Con la herramienta *Rellenar*, un clic dentro de cualquier zona (una oreja, una aleta, el vientre…) la rellena completa.
5. Pulsa **Guardar PNG** para descargar tu obra de arte.

> Sin dependencias externas: funciona incluso sin conexión a internet (solo necesitas los archivos).

## 🌐 Jugar online

El juego está publicado con GitHub Pages en:

**https://ajpuceda.github.io/JuegoPintar/**

## 🛠️ Tecnología

- JavaScript puro (vanilla) en dos archivos — sin frameworks, sin CDN, sin instalación ni compilación.
- Dibujos vectoriales definidos en `dibujos.js` (elipses, curvas Bézier y trazados), renderizados con Canvas 2D.
- Canvas en dos capas: capa de pintura + capa de líneas del dibujo (así los contornos nunca se borran).
- Algoritmo de *flood fill* con máscara de contornos para el relleno por regiones.
- Escalado automático del lienzo con JavaScript puro (sin librerías).

¡Feliz pintura! 🖍️

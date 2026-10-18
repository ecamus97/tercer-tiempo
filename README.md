# Tercer Tiempo · versión web de prueba

Juego de mesa sobre dirigir un club de fútbol amateur de barrio, en versión web para probar reglas, balance y bugs antes de imprimir.

Es una sola página (`index.html`) con CSS y JS inline, sin build. Se abre en el navegador o se publica con GitHub Pages.

## Qué incluye

- Liga completa: 8 clubes, 7 Fechas, Pretemporada, Clásicos en la Fecha 4 y tabla con todos los desempates.
- Las 48 cartas de Plantilla Base, 30 Libres, 12 Eventos, 16 Excusas, 18 Auspiciadores, 16 Dramas, 6 Promesas al Barrio y 5 cartas de Clásico, con sus efectos implementados.
- Multijugador en un mismo dispositivo (de 1 a 6 humanos), con pantalla de privacidad para pasar el teléfono.
- Bots que gestionan clubes como un humano, para probar con pocos jugadores.
- Partido ocasión por ocasión con los dados visibles, quién hizo cada gol y el desglose de cómo se calcularon Ataque y Defensa.
- Deshacer la última decisión (Ctrl+Z o menú), registro completo de la liga y semilla para repetir una liga exacta.
- Laboratorio de balance: simula cientos de ligas con bots y permite mover los números clave.
- Se guarda solo en el navegador (`localStorage`).

## Cambios respecto del documento de diseño

El motor y varias cartas se corrigieron porque tenían bugs de lógica. La lista completa, con el porqué de cada cambio, está dentro de la app en **☰ → Reglas y ajustes**. Cada carta modificada muestra la marca «✎ regla ajustada» y el texto original al pasar el mouse.

## Publicar con GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `(root)`. Queda en `https://ecamus97.github.io/tercer-tiempo/`.

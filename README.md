# AetherWilds — Frontier (mejorado)

AetherWilds es una demo jugable web de aventura 32-bit con identidad y contenido originales.

Inspirado en la libertad de exploración y sandbox de juegos como **PokeWilds**, esta versión refuerza el mundo vivo, las habilidades de campo de las criaturas y la construcción persistente.

## Incluye
- Exploración libre con mapa procedural y biomas.
- Criaturas originales (240 en el catálogo) con estadísticas, tipos, afinidad, género y rasgos.
- Encuentros salvajes y captura mediante cápsulas de vínculo.
- Combate por turnos.
- Progresión de nivel y evoluciones originales.
- Criadero y sistema de cría de demostración.
- Recursos, refugio, curación e inventario en cuadrícula.
- Ciclo día/noche con tinte visual.
- Guardado local.
- Ajustes de música, efectos, volumen y pantalla completa.
- Controles PC (WASD/flechas/E/M) y controles táctiles.
- PWA instalable y funcionamiento offline tras la primera carga.
- Audio generado en tiempo real con WebAudio.

## Mejoras inspiradas en PokeWilds
- **Criatura líder te sigue** en el overworld (posición según la última dirección de movimiento).
- **Habilidades de campo (Field Moves)** según el tipo de la criatura líder:
  - Verdant / Bloom / Mire → **Corte** (tala árboles y hierba → madera)
  - Terra → **Romper** (destroza rocas → piedra)
  - Ember / Solar → **Fogata** (coloca campamento)
  - Tide → **Surcar** (interacción con agua / pesca)
  - Gale → **Ráfaga** (despeja terreno)
  - Volt / Frost / Aether / Umbral → habilidades de recolección y detección
- Construcciones visibles en el mapa (muros, camas, fogatas, cofres…).
- Recolección más significativa: usa la habilidad de tu criatura en lugar de solo “recoger”.
- Hint en pantalla inferior: muestra la habilidad activa de tu líder.
- Día avanza correctamente al pasar de medianoche.

## Controles
- **WASD / Flechas**: moverse
- **E**: interactuar / usar habilidad de campo de la criatura líder
- **M**: menú
- Táctil: pad direccional + botones

## Publicar en GitHub Pages
1. Sube todos los archivos del ZIP a un repositorio.
2. En Settings > Pages selecciona la rama principal y la carpeta raíz.
3. Abre la URL HTTPS de GitHub Pages.
4. En móvil aparecerá la opción del navegador para instalar la PWA.

## Nota
Esta versión es una base jugable y ampliable. Todo el arte, nombres y criaturas incluidos aquí son originales y se generan/dibujan mediante código. No está afiliado a Nintendo, Game Freak ni The Pokémon Company.

## Expansión Frontier
- Inventario en cuadrícula y cofres persistentes.
- Fabricación y construcción.
- Aetherdex con las 240 criaturas.
- Evoluciones originales y árbol de habilidades.
- Regiones y frontera generada indefinidamente por coordenadas.
- NPC y misiones.
- Mazmorras, pisos y jefes.
- Agricultura y pesca.
- Combate ampliado con habilidades y curación.

## Versión Full HTML
El juego principal está autocontenido en `index.html`: motor, estilos y catálogo de criaturas están integrados en un único archivo HTML. El manifest, Service Worker e iconos permanecen separados porque son necesarios para la instalación PWA.

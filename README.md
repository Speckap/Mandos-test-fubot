# Clásico de Mandos

Juego de fútbol 3D para dos jugadores en la misma PC, con dos mandos (o teclado), inspirado en los controles de EA FC. Funciona directamente en el navegador, sin instalar nada.

## Cómo jugar

1. Descarga `clasico-de-mandos.html`.
2. Ábrelo en **Chrome** o **Edge** (el narrador con acento ecuatoriano solo está disponible en Edge).
3. Conecta los dos mandos y pulsa cualquier botón en cada uno para que el juego los detecte.
4. Pulsa **A** o **Start** para empezar.

Necesita internet la primera vez para cargar Three.js desde un CDN.

## Qué incluye

- Estadio 3D con público, iluminación nocturna, césped con patrones de corte y efectos (bloom, viñeta).
- Partidos de 4v4, 5v5, 7v7 y 11v11, con la cancha ajustada al tamaño de cada modo.
- 20 selecciones con colores reales y valoraciones OVR / ATQ / MED / DEF que afectan el juego (nombres de jugadores inventados).
- Reglas completas: faltas, tarjetas, fuera de juego, penales, córners, saques de banda y de meta, ley de la ventaja, tiempo añadido, prórroga, tanda de penales, 5 cambios con cansancio.
- Árbitro y jueces de línea con IA.
- Arqueros que leen el disparo, se lanzan, atajan o despejan; y que puedes controlar cuando tienen el balón.
- Narrador en español y sonido de estadio sintetizado con control de volumen.

## Controles (mando)

**Con balón**

| Botón | Acción |
|---|---|
| A ✕ | Pase raso (mantén para más fuerza) |
| B ○ | Pase alto / centro |
| Y △ | Pase en profundidad · LB + Y bombeado |
| X □ | Disparo (mantén) · RB + X colocado · LB + X vaselina · LB + RB + X raso |
| X y luego A | Amague |
| RS | Regate |
| LT | Proteger el balón |
| RB | Conducción cerrada |
| RT | Sprint |

**Sin balón**

| Botón | Acción |
|---|---|
| LB | Cambiar de jugador · RS elegir a quién |
| B ○ | Entrada |
| X □ | Barrida |
| A (mantener) | Presionar · RB presión de compañero |
| LT | Jockey |
| Y △ (mantener) | Salida del arquero |

**Start** pausa · **Back** cambia la cámara.

## Controles (teclado)

- **Jugador 1:** WASD mover · F=A · H=B · G=X · T=Y · Q=LB · E=RB · R=LT · Shift=RT · V=regate · Esc pausa · C cámara
- **Jugador 2:** flechas mover · K=A · Ñ o ;=B · L=X · O=Y · U=LB · P=RB · I=LT

## Archivos

| Archivo | Qué es |
|---|---|
| `clasico-de-mandos.html` | El juego completo (el modelo del jugador va incluido dentro) |
| `futbolista.blend` | Modelo del futbolista en Blender, con esqueleto y animaciones |
| `futbolista.glb` | El mismo modelo exportado a glTF |

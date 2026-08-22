# Zombie Siege — Diseño del Nivel 2

## Objetivo

El Nivel 2 sube la presión sin usar jefe. El jugador empieza con el bate mejorado y debe administrar la escopeta recortada, el posicionamiento y la distracción del Gato Gordo. El jefe queda reservado para el Nivel 3.

## Flujo

1. **El Callejón (35%)**: horda rápida de zombis básicos. El gato aparece y enseña la distracción con `Q`.
2. **La Intersección (25%)**: dos zombis antidisturbios protegen el pasaje. Hay barriles explosivos y aparece la escopeta al alcanzar el 40% del nivel.
3. **El Bulevar Bloqueado (40%)**: pasillo con autos quemados, barricadas y una horda mixta. Hay que reservar los 8 cartuchos y usar el gato para abrir ventanas de ataque.

## Gato Gordo

Es invulnerable y no tiene vida. `Q` lo envía hacia un objetivo seguro y genera un efecto de cascabel durante 4 segundos. Puede distraer hasta 4 zombis básicos o 1 antidisturbios. El enfriamiento es de 20 segundos.

## Combate y progresión

- El bate del Nivel 2 hace más daño y empuje.
- La escopeta recortada tiene 8 cartuchos, alcance corto y daño masivo en cono.
- Las armas se desbloquean al completar niveles; no se entregan todas al comenzar.
- `1`, `2` y `3` cambian entre armas desbloqueadas y la munición se muestra en el HUD.
- Completar el Nivel 2 sin perder vidas desbloquea el Chaleco Táctico Liviano para el Nivel 3 (absorbe 2 golpes).

## Tipos de zombi

- Básico (60%): más rápido y agresivo que en el Nivel 1.
- Antidisturbios (40%): casco y chaleco. El bate frontal hace poco daño; el ataque por detrás, la escopeta y el gato lo exponen.

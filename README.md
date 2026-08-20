# Cartita para Vick 💗

## Cómo subirlo

Este proyecto son **dos cosas** y tienen que viajar juntas:

```
index.html
img/
  fondo.jpg
  mascara-agua.png
  stitch-portada.png
  stitch-festejo.png
  stitch-playa.png
  huella.png
```

Si separás el `index.html` de la carpeta `img/`, no se ve nada.

### Opción rápida (sin repo)
Arrastrá la carpeta entera a https://app.netlify.com/drop y te da un link al instante.

### GitHub Pages
Ojo: Pages **no funciona con repos privados en el plan gratuito**. Y aunque el repo
sea privado, el sitio publicado queda público igual — la privacidad viene de que
nadie conozca la URL.

## Qué editar

Todo lo editable está en `index.html`, en el bloque marcado
`EDITÁ SOLO ESTE BLOQUE`, cerca del comienzo del `<script>`:

- `NOMBRE_ELLA`, `FIRMA`, `CIERRE`
- `TEXTOS` — los 4 párrafos de la carta
- `ITEMS` — posición de cada objeto tocable (`cx`, `cy` en píxeles del escenario de 480x860)

Para cambiar una imagen, reemplazá el archivo dentro de `img/` con el mismo nombre.
No hace falta tocar el código.

## Probarlo en la compu

No alcanza con abrir el archivo haciendo doble clic. Desde la carpeta:

    python3 -m http.server 8000

y entrá a http://localhost:8000

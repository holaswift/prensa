<p align="center">
  <img src="logo-3d-y-glifos/hola-swift-3d-logo-completo.png" alt="hola Swift!" width="480">
</p>

<p align="center"><b>Kit de prensa de hola Swift, la comunidad de Swift en español.</b><br>
<a href="https://holaswift.com/prensa/">holaswift.com/prensa</a> · prensa@holaswift.com</p>

---

¿Vais a escribir sobre hola Swift? Aquí tenéis todo lo necesario: la nota de prensa, los logos, las imágenes, los vídeos y
las fotos del equipo. Podéis usarlo libremente para hablar de hola Swift.

**[Descargar todo (ZIP)](https://github.com/holaswift/prensa/releases/download/descargas/holaswift-prensa.zip)**

## En pocas palabras

hola Swift es la comunidad de Swift en español: un sitio para quienes crean con Swift y las plataformas de Apple y quieren
aprender, compartir y conocerse en su idioma. Organiza quedadas online cada mes en Discord, con charlas cortas en directo,
y prepara un encuentro en persona. La fundan Jon Ander Orcera y Alejandro Mohamad.

## Qué hay

- **[Nota de prensa](nota-de-prensa)**: el anuncio oficial en PDF, y el texto en Markdown, listo para copiar.
- **[Logotipo](logotipo)**: el logo horizontal y apilado, en color, negro y blanco. SVG y PNG transparente.
- **[Icono y avatar](icono-y-avatar)**: la "h" sola y el avatar redondo para perfiles y apps.
- **[Logo 3D y glifos](logo-3d-y-glifos)**: el "hola" en tubo 3D y las pegatinas de la comunidad, en PNG transparente.
- **[Vídeos](videos)**: la animación del logo en 16:9, 1:1, 4:5 y 9:16, con un fotograma en JPG.
- **[Equipo](equipo)**: fotos y [bios](equipo/bios.md) de los founders y los embajadores.

Cada carpeta tiene también su propio ZIP en la [página de descargas](https://github.com/holaswift/prensa/releases/tag/descargas).

## Cómo escribir el nombre

Se escribe **hola Swift**: dos palabras, "hola" en minúscula y "Swift" con mayúscula, también al empezar una frase.
No: holaSwift, Hola Swift, HolaSwift, hola swift, HOLA SWIFT. En redes somos **@hola_swift**, porque no admiten mayúsculas, y en Bluesky, **@holaswift.com**.

## Cómo usar el logo

- Sin cambiar los colores del "hola" ni deformarlo.
- Con aire alrededor: como mínimo, la altura de la "o".
- Sin sombras, contornos ni brillos.
- Sobre fotos o fondos de color, mejor la versión blanca o la negra.
- Si un SVG se ve raro en algún visor, usad el PNG.

## Contacto

Para entrevistas, datos o cualquier duda: **prensa@holaswift.com**.

hola Swift es una comunidad independiente, sin relación oficial con Apple Inc. Swift y Apple son marcas de Apple Inc.

<details>
<summary>Para quien mantiene este repositorio</summary>

- Los ZIP de la página de descargas (uno por carpeta y `holaswift-prensa.zip` con todo) los genera la Action
  `.github/workflows/descargas.yml` en cada cambio de `main`, en la release `descargas`. La página holaswift.com/prensa enlaza ahí.
  Si cambiáis el nombre de una carpeta, revisad la Action y `index.html`.
- **La página https://holaswift.com/prensa/ es `index.html`**, publicada con GitHub Pages desde `main` (raíz). Con Pages,
  también se puede abrir cualquier archivo directamente, como `holaswift.com/prensa/logotipo/hola-swift-logo-horizontal-color.svg`.
  Las fuentes, los glifos y el favicon los pide a la web principal (`/assets/…`). El email de prensa y las tarjetas de
  descarga están al final, en el bloque «EDITABLE».
- La nota se hace con la skill `holaswift-documentos-web` del repositorio privado `marca`. Su HTML lleva las fuentes y las
  imágenes incrustadas: antes de publicarlo, se sacan a `nota-de-prensa/recursos/`.
- Los logos de `logo-3d-y-glifos/` están en Display P3, como los de la web.

</details>

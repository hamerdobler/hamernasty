# Inventario de imágenes del sitio

Todas las imágenes actuales son **placeholders generados por Google Stitch** (URLs de `lh3.googleusercontent.com`) y deben reemplazarse por fotos reales del local. Este inventario lista cada ubicación en [index.html](index.html) con el nombre de archivo sugerido para la versión definitiva en `assets/img/`.

> **Nota:** Stitch reutilizó la misma foto placeholder en varias ubicaciones (p. ej. la foto del deck al atardecer aparece 6 veces). Acá cada ubicación tiene su propio nombre de archivo sugerido, porque en la versión final cada una debería ser una foto distinta.

## Identidad

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 1 | Logo circular de Malloy's (sol, ola, "Bar de Costa — San Isidro, Argentina") | Barra de navegación, hero y footer (misma imagen en los 3 lugares) | `assets/img/logo.png` |

## Hero (portada)

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 2 | Foto de fondo a pantalla completa: deck de madera sobre el río al atardecer, con palmeras y reposeras (luz dorada) | Hero — fondo | `assets/img/hero-deck-atardecer.jpg` |

## La Experiencia (`#experiencia`)

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 3 | Mesas al aire libre con vista al río (hoy usa la misma foto del hero, con filtro sepia) | "Un bar de playa en San Isidro" — imagen lateral | `assets/img/experiencia-mesas-rio.jpg` |

## La Carta (`#carta`) — tarjetas de categorías

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 4 | Plato a las brasas (ojo de bife / costillar) | Tarjeta "A las brasas" | `assets/img/carta-brasas.jpg` |
| 5 | Rolls de sushi y tiraditos | Tarjeta "Sushi & tiraditos" | `assets/img/carta-sushi.jpg` |
| 6 | Plato de pastas caseras | Tarjeta "Pastas" | `assets/img/carta-pastas.jpg` |
| 7 | Tragos / coctelería de autor | Tarjeta "Coctelería de autor" | `assets/img/carta-cocteleria.jpg` |

## Galería (`#galeria`) — mosaico "Un lugar para quedarse"

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 8 | Deck de madera al atardecer (panorámica 16:9, hoy repite la foto del hero) | Galería — pieza grande superior | `assets/img/galeria-deck-atardecer.jpg` |
| 9 | Palmeras (vertical 3:4, hoy repite la foto del hero) | Galería — pieza vertical | `assets/img/galeria-palmeras.jpg` |
| 10 | Plato a las brasas (cuadrada, hoy repite la foto de la tarjeta #4) | Galería — cuadrada 1 | `assets/img/galeria-brasas.jpg` |
| 11 | Sushi rolls (cuadrada, hoy repite la foto de la tarjeta #5) | Galería — cuadrada 2 | `assets/img/galeria-sushi.jpg` |
| 12 | Tragos de autor (cuadrada, hoy repite la foto de la tarjeta #7) | Galería — cuadrada 3 | `assets/img/galeria-tragos.jpg` |
| 13 | Interior con mural tropical (panorámica 21:9, hoy repite la foto del hero) | Galería — pieza ancha inferior | `assets/img/galeria-interior-mural.jpg` |

## Opiniones (`#opiniones`)

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 14 | Logo de Google (aparece en las 3 tarjetas de reseñas, hoy con 3 URLs distintas) | Reseñas de Martina, Facundo y Valentina | `assets/img/google-logo.svg` (un solo archivo para las 3) |

## CTA final

| # | Qué muestra | Sección | Archivo sugerido |
|---|-------------|---------|------------------|
| 15 | Foto de fondo del bloque "Reservar por WhatsApp" (hoy repite la foto del hero) | Banda con CTA antes del footer | `assets/img/cta-rio-atardecer.jpg` |

## Resumen

- **15 ubicaciones** de imagen en el sitio, pero solo **8 archivos placeholder únicos** (Stitch repitió fotos).
- Fotos reales necesarias: **13 fotos del local/platos + logo + logo de Google** (el logo de Google conviene bajarlo como SVG oficial).
- La sección de ubicación (`#ubicacion`) no usa imagen: el "mapa" es un placeholder hecho con HTML/CSS. Considerar reemplazarlo por un embed de Google Maps.
- `screen.png` (en la raíz del repo) es una captura del diseño exportada por Stitch, no forma parte del sitio.

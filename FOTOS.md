# Inventario de imágenes del sitio

Las fotos reales del local ya están integradas en `assets/img/` (origen: carpeta `D:\malloys fotos`). Este inventario documenta qué hay en cada ubicación de [index.html](index.html) y qué falta.

## Archivos en `assets/img/`

| Archivo | Contenido | Origen |
|---------|-----------|--------|
| `logo.jpg` | Logo de Malloy's: "Bar de Costa 19✕82 · Cocina & Grill · Martínez Partido de San Isidro" (texto negro sobre fondo blanco) | `logomalloys.jpg` |
| `hero-deck-atardecer.jpg` | Atardecer sobre el río con árboles y orilla de arena (optimizada: 1920px, 431 KB) | `atardecer malloys.jpg` |
| `experiencia-bar.jpg` | Interior del bar: neón "Malloy's", estantes de botellas, lámparas colgantes y plantas | `bar malloys.png` (convertida a JPEG) |
| `carta-brasas.jpg` | Matambre a la pizza con tomates cherry en plato negro | `carne malloys.png` (convertida a JPEG) |
| `carta-sushi.jpg` | Bento box con rolls y niguiris | `sushi malloys.jpg` |
| `carta-pastas.jpg` | Sorrentinos con salsa cremosa y copa de vino, sobre mantel de Malloy's | `pastas malloys.png` (convertida a JPEG) |
| `carta-cocteleria.jpg` | Dos tragos en copas de cobre con el río al atardecer de fondo (vertical) | `tragos malloys.jpg` |
| `google-logo.svg` | Logo "G" de Google para las reseñas | creado a mano (SVG único para las 3 reseñas) |

## Asignación por ubicación

| # | Sección / ubicación | Imagen usada | Estado |
|---|---------------------|--------------|--------|
| 1 | Nav, hero y footer — logo (en contenedor circular blanco) | `logo.jpg` | ✅ Definitiva |
| 2 | Hero — fondo | `hero-deck-atardecer.jpg` | ✅ Definitiva |
| 3 | Experiencia — imagen lateral | `experiencia-bar.jpg` | ✅ Definitiva |
| 4 | Carta — "A las brasas" | `carta-brasas.jpg` | ✅ Definitiva |
| 5 | Carta — "Sushi & tiraditos" | `carta-sushi.jpg` | ✅ Definitiva |
| 6 | Carta — "Pastas" | `carta-pastas.jpg` | ✅ Definitiva |
| 7 | Carta — "Coctelería de autor" | `carta-cocteleria.jpg` | ✅ Definitiva |
| 8 | Galería — pieza grande 16:9 | `hero-deck-atardecer.jpg` (reutilizada) | ⏳ Espera foto propia (ideal: deck de madera al atardecer) |
| 9 | Galería — pieza vertical 3:4 | `carta-cocteleria.jpg` (reutilizada) | ⏳ Espera foto propia (ideal: palmeras / exterior) |
| 10 | Galería — cuadrada 1 | `carta-brasas.jpg` (reutilizada) | ⏳ Espera foto propia (otro plato a las brasas) |
| 11 | Galería — cuadrada 2 | `carta-sushi.jpg` (reutilizada) | ⏳ Espera foto propia (otra pieza de sushi) |
| 12 | Galería — cuadrada 3 | `carta-pastas.jpg` (reutilizada) | ⏳ Espera foto propia (otro plato o tragos) |
| 13 | Galería — pieza ancha 21:9 | `experiencia-bar.jpg` (reutilizada, asignación pedida) | ⏳ Ideal: foto panorámica del interior |
| 14 | Opiniones — logo de Google (×3) | `google-logo.svg` | ✅ Definitiva |
| 15 | CTA final — fondo "Reservar por WhatsApp" | `hero-deck-atardecer.jpg` (reutilización aprobada) | ⏳ Puede recibir foto propia más adelante |

En la galería ninguna imagen aparece dos veces: atardecer, tragos, brasas, sushi, pastas y bar — las 6 fotos, una vez cada una.

## Pendientes

- **6 fotos nuevas** para que la galería y el CTA no reutilicen imágenes (ubicaciones #8, 9, 10, 11, 12, 15; #13 ya tiene la foto del bar asignada a pedido).
- El **"mapa"** de la sección ubicación (`#ubicacion`) sigue siendo un placeholder hecho en HTML/CSS — considerar reemplazarlo por un embed de Google Maps.
- `screen.png` (raíz del repo) es la captura del diseño de Stitch, no forma parte del sitio.

## Notas técnicas

- Optimización aplicada: fotos > 500 KB se redimensionaron a máx. 1920px y/o recomprimieron como JPEG calidad ~75–82. Los PNG fotográficos se convirtieron a JPEG.
- El logo tiene fondo blanco, por eso en el HTML se muestra dentro de un contenedor circular blanco (`bg-white` + `rounded-full` + padding), replicando el diseño original.
- La convención de nombres refleja la ubicación *principal* de cada foto; las reutilizaciones referencian el mismo archivo (no hay copias duplicadas).

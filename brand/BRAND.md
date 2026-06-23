# Pharos — Manual de marca

> *Pharos*: el Faro de Alejandría, primer instrumento científico-arquitectónico. Un faro proyecta
> luz cálida en la noche para orientar. Esta marca hace lo mismo con software científico y educativo:
> **infraestructura sin barreras de entrada.**

Autor: **José Labarca Baeza** (JLB) · Lic. en Física, USM Valparaíso · `github.com/kegouro`

---

## 1. Concepto

Un **faro de noche sobre el mar de Valparaíso**. La luz es **cálida** (ámbar), no fría — un faro real
emite luz de sodio, no neón. El haz del faro aparece **segmentado en elementos diferenciales** (`dx`):
la misma idea que sostiene *Parcella* (integración). El faro **proyecta**; cada proyecto es **un haz de
su propio color**. Esa es la metáfora que une todo el ecosistema.

## 2. Paleta

Cálida, de noche, sobre negro. La luz es el acento; el fondo nunca compite.

| Rol | Nombre | Hex |
| :-- | :-- | :-- |
| Fondo | Noche (negro cálido) | `#0a0908` |
| Superficie | Carbón | `#15110d` |
| Línea / borde | Brasa apagada | `#2a2118` |
| Texto | Tinta cálida | `#efe7d8` |
| Texto tenue | Sepia | `#9a8a76` |
| **Acento primario** | **Haz / Faro (ámbar)** | **`#f5a72c`** |
| Acento secundario | Brasa (ember) | `#ff7a3c` |
| Brillo / glow | Oro | `#ffd690` |

**Colores-haz de los proyectos** (cada proyecto conserva el suyo; son las luces que el faro proyecta):
parcella `#7c5cff` · curvana `#4ade80` · flux `#f43f5e` · beamlab-web `#2dd4bf` ·
spmkit `#fb923c` · virtualspm `#a78bfa` · lablog `#38bdf8` · BeamLab Studio `#f5a72c`.

## 3. Tipografía

| Rol | Tipografía | Uso |
| :-- | :-- | :-- |
| Display | **Fraunces** (500, opsz alto) | Wordmark "PHAROS", títulos. Gravitas monumental (Alejandría). Con restraint. |
| Texto | **Inter** (400/500) | Cuerpo, descripciones. Coincide con las apps (Parcella, Curvana). |
| Utilidad / datos | **IBM Plex Mono** (400/500) | Etiquetas, nombres de repo, stacks, la firma. El registro "física computacional". |

Detalle de firma del wordmark: la **O** de PHAR**O**S va en *itálica ámbar* — el ojo del faro.

## 4. El logotipo (la marca)

El **haz segmentado**: un triángulo angosto (el haz) apilado en franjas con pequeños huecos (los `dx`),
de oro brillante en la punta a ámbar en la base, con la **punta luminosa** y una línea de **horizonte**
cálida tenue. Es geométrico puro — **siempre SVG hecho a mano**, nunca generado por IA (se mantiene
nítido a 16 px y vectorial en git).

- `assets/pharos.svg` — marca a color (64×64).
- `assets/pharos-mono.svg` — versión monocromática (para sellos, una sola tinta).
- `assets/favicon.svg` — favicon con caja redondeada (legible a 16 px).

## 5. La firma tipográfica

En el pie de cada repo y de la web. No necesita imágenes; se ve igual en cualquier pantalla:

```
┌─
│ Pharos Project
│ José Labarca Baeza
└─ USM · Valparaíso · Chile
```

El `┌─ … └─` evoca el haz descendente del faro / un eje de coordenadas.

## 6. Banner y tarjeta social

- `assets/banner.png` (1280×320) — banner horizontal **"by JLB"** para la cabecera del perfil o READMEs.
- `assets/og.png` (1200×630) — tarjeta Open Graph para compartir enlaces (WhatsApp, X, Discord).

Regla de banners: fondo negro cálido, marca + wordmark, `by JLB` en brasa, una regla ámbar→brasa al
pie. **Nada de capturas ni íconos.** El minimalismo grita "física computacional".

## 7. Marca de agua

En exportaciones (PNG/GIF de las apps): texto `pharos/<app>` en `monospace`, **opacidad 15 %**, blanco
sobre fondo oscuro o negro sobre claro. La herramienta nunca estorba la visualización científica.

## 8. Voz

Directa, precisa, sin relleno. Verbos activos, minúsculas en los nombres de repo. Se nombra lo que el
usuario controla, no cómo está construido por dentro. El lema, siempre:
**"infraestructura científica y educativa sin barreras de entrada."**

## 9. Licencia

Todo el ecosistema es **MIT**. El `LICENSE` se mantiene **estándar** (para que GitHub detecte "MIT");
el sello Pharos vive en el README y en la firma, no en el encabezado legal.

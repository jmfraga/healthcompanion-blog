# Health Companion · Blog

Blog público de **Health Companion** — companion app de bienestar personal.

- **Sitio en vivo:** [blog.healthcompanion.app](https://blog.healthcompanion.app)
- **App:** [app.healthcompanion.app](https://app.healthcompanion.app)
- **Marca:** wellness, no dispositivo médico. NO diagnostica, NO receta.

## Estructura

```
.
├── index.html              # landing del blog con grid de artículos
├── posts/                  # un .html por post
├── assets/
│   ├── logos/              # branding (mixta color, símbolo SVG)
│   └── og/                 # imágenes de share por post
└── CNAME                   # blog.healthcompanion.app
```

## Branding

| Token | Hex | Uso |
|---|---|---|
| Ink | `#0c2a2a` | texto + trazo principal |
| Aqua | `#2dd4bf` | acentos, anillos, hovers |
| Cream | `#f4ede1` | fondo cálido oficial |

Tipografías: **Fraunces** (display, italic optical) + **Geist** (sans).

## Deploy

GitHub Pages publica desde `master`. CNAME en `blog.healthcompanion.app`.

## Edición

Los posts se generan vía [Marketing Studio](https://marketing.simacademy.lat) o se editan a mano. Marketing Studio commitea aquí directo bajo `posts/YYYY-MM-DD-<slug>.html` con CSS inline + meta OG.

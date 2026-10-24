# Web de Grogu - Star Wars

Web de práctica de HTML y CSS dedicada a Grogu (Baby Yoda) y a las enseñanzas que deja a cada generación.

## Secciones

- **Inicio** (`index.html`): artículo principal sobre Grogu.
- **Presentación** (`whatwedo.html`): explica de qué trata la web y cómo está hecha.
- **Quiénes somos** (`about.html`): breve descripción del espacio.
- **Contacto** (`contact.html`): formulario de contacto.

## Aspecto visual

Colores (definidos como variables en `css/main.css`):

| Variable | Color | Uso |
| --- | --- | --- |
| `--color-fondo` | `#080B12` | Fondo de cabecera y pie |
| `--color-superficie` | `#151C29` | Fondo del contenido |
| `--color-texto` | `#E8EDF5` | Texto |
| `--color-acento` | `#FFE81F` | Amarillo Star Wars para destacar |
| `--color-grogu` | `#8FAF75` | Verde para los títulos |

Estructura de cada página: cabecera (título, imagen y menú), contenido central y pie de página.

## Organización del código

```
dia-7/
├── index.html
├── whatwedo.html
├── about.html
├── contact.html
├── css/
│   └── main.css
├── js/
│   └── main.js
└── images/
    └── grogu.jpg
```

## Técnicas utilizadas

- **Flexbox**: menú horizontal, formulario en columna y pie de página siempre abajo.
- **Responsive**: etiqueta `meta viewport` y `max-width` para que el contenido se adapte a pantallas pequeñas.

## Reutilización de estilos

- Todas las páginas usan la misma hoja de estilos `css/main.css`.
- Los colores son variables en `:root`, así un cambio se aplica a toda la web.
- La cabecera, el menú y el pie de página son iguales en todas las páginas.

## Repositorio

https://github.com/bedoyacloud/DW-Octubre-2026

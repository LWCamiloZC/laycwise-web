<p align="center">
  <img src="img/logo-horizontal-color.svg" alt="LAYC WISE" width="320">
</p>

<p align="center">
  Sitio web oficial de <strong>LAYC WISE S.A.S.</strong><br>
  <a href="https://laycwise.com">laycwise.com</a>
</p>

---

## Sobre el sitio

Página de presentación de LAYC WISE, empresa de tecnología con sede en Medellín, Colombia. Muestra los servicios de la empresa (desarrollo de software, diseño web, nube, bases de datos, análisis de datos y consultoría), proyectos realizados y datos de contacto.

Es un sitio estático: HTML y CSS, sin dependencias ni proceso de compilación.

## Estructura

```
.
├── index.html        # Página principal
├── 404.html          # Página para enlaces que no existen
├── css/
│   └── styles.css    # Estilos y colores de la marca
├── img/              # Logos, favicons y logos de clientes
└── CNAME             # Dominio personalizado (no borrar)
```

## Colores de la marca

| Color | Hex | Uso |
|---|---|---|
| Azul oscuro | `#0B2545` | Textos principales y fondos oscuros |
| Turquesa | `#12B5CE` | Acentos, botones y enlaces |
| Azul medio | `#1E4976` | Textos secundarios |

Tipografía: [Manrope](https://fonts.google.com/specimen/Manrope) (Google Fonts).

## Ver el sitio localmente

Basta con abrir `index.html` en el navegador. Para probarlo como en producción:

```bash
python3 -m http.server 8080
```

y abrir <http://localhost:8080>.

## Publicación

El sitio se publica con **GitHub Pages** desde la rama `main` (carpeta raíz). Cada cambio que llega a `main` se publica automáticamente en [laycwise.com](https://laycwise.com) en uno o dos minutos.

- El DNS del dominio se administra en GoDaddy (registros `A` hacia GitHub Pages y `CNAME` de `www`).
- El correo `@laycwise.com` usa Google Workspace; sus registros DNS (MX, SPF, DKIM) no deben modificarse al cambiar el hosting.

---

© 2026 LAYC WISE S.A.S. Todos los derechos reservados.

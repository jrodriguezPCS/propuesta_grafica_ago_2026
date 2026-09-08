# PCS For All — Propuesta gráfica

**Redes y campañas · Agosto 2026**  
Javier Esteban Rodríguez Medina

Visor web de la propuesta gráfica para **PCS For All** (mayorista TI en partes y accesorios). La pieza es una lámina vertical de **1920 × 9720 px** que se escala al 100 % del ancho del dispositivo y crece en altura de forma proporcional.

[![Ver propuesta](https://img.shields.io/badge/Ver_propuesta-GitHub_Pages-0767B1?style=for-the-badge)](https://jrodriguezpcs.github.io/propuesta_grafica_ago_2026/)

**Sitio en vivo:** [jrodriguezpcs.github.io/propuesta_grafica_ago_2026](https://jrodriguezpcs.github.io/propuesta_grafica_ago_2026/)

---

## Objetivo

Impregnar los medios de difusión de la compañía con una imagen **fresca, moderna y pensada** para reforzar la promoción de productos mediante el atractivo visual. El trabajo se organiza en tres frentes:

1. **Revisión de perfil** de redes sociales (Instagram y Facebook).
2. **Optimización de formato** para post e historias.
3. **Optimización de formato** para campaña de masivos.

## Qué cubre la pieza

### Revisión de perfil
- Nombre de usuario y nombre de perfil correctos (`pcsforall.co` / PCS For All), sin el handle incorrecto ni la razón social como nombre público.
- Enlaces de «más información» y página de about/embudo con rediseño más limpio.
- Foto de perfil con **isotipo** (no el logo completo) para que se lea en 32–40 px.

### Piezas para redes
- Dejar de publicar solo información del producto sobre azul saturado.
- Jerarquía tipográfica, peso visual y orden de lectura de izquierda a derecha / arriba abajo.
- Retícula compartida entre piezas, con color secundario y acento, para evocar modernidad y progreso tecnológico.

### Metodología de publicación
- Posts (lunes a miércoles) en **4:5**.
- Historias (jueves y viernes) en **9:16**, reencuadrando la misma pieza sin rediseñarla desde cero.

---

## Cómo funciona el visor

El `index.html` de la raíz es un visor a pantalla completa:

- La lámina ocupa todo el ancho; no hay zoom interno.
- Barra superior fija con título y botón de pantalla completa.
- Capa de protección sobre la imagen (sin menú contextual ni arrastre) para presentación ante cliente.
- `robots.txt` + meta `noindex` para que el sitio no se indexe.

### Estructura

```text
.
├── index.html                         # visor principal (GitHub Pages)
├── favicon.svg
├── robots.txt
├── .nojekyll
└── slides/
    ├── index.html                     # visor alterno
    ├── README.md                      # notas de la pieza
    └── slides/
        └── propuesta-grafica.jpg      # lámina 1920 × 9720
```

### Ver en local

```bash
git clone https://github.com/jrodriguezPCS/propuesta_grafica_ago_2026.git
cd propuesta_grafica_ago_2026
# cualquier servidor estático; por ejemplo:
python3 -m http.server 8080
```

Abrir [http://localhost:8080](http://localhost:8080).

Si GitHub Pages no carga: *Settings → Pages → Source: Deploy from a branch → `main` / root → Save*.

---

## Créditos

**Autor:** Javier Esteban Rodríguez Medina  
**Cliente:** PCS For All — mayorista TI en partes y accesorios  
**Fecha:** agosto 2026

# Presentaciones

Visor web de diapositivas y propuestas de **Javier Esteban Rodríguez Medina**.

La primera pieza es la **Propuesta gráfica — redes y campañas** para PCSFORALL: una lámina vertical de **1920×9720 px** que se escala al **100% del ancho** de cualquier dispositivo y crece en altura de forma proporcional.

## Ver

Cuando GitHub Pages esté activo:

**https://jrodriguezpcs.github.io/presentaciones/**

Si aún no carga, en el repo: *Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` → folder `/ (root)` → Save*.

## Cómo está armada

- `index.html` — visor a pantalla completa, sin márgenes laterales.
- `slices/parte-0N.b64` — la lámina partidas en 6 franjas JPEG (calidad web) en Base64, para poder versionarlas en Git.
- El navegador las une en una sola columna. No hay zoom interno: el único factor de escala es el ancho del viewport.

## Contenido de esta pieza

1. Revisión de perfil de redes (Instagram y Facebook)
2. Optimización de formato para post e historias
3. Optimización de formato para campaña de masivos

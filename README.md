# Antony Rice · Vitrina estática

Vista previa de solo lectura de la web de canastas navideñas de **Negocios Antony Rice EIRL**, publicada con GitHub Pages:

**https://jef-prog26.github.io/antony-rice-vitrina/**

Es una copia de la página de inicio en un solo archivo (`index.html`). Los botones de WhatsApp funcionan y el formulario de contacto envía los datos por WhatsApp. No incluye el panel de administración: el proyecto completo vive en un repositorio privado aparte.

## Actualizar la vitrina

En el proyecto principal (`negocios-antony-rice`):

```bash
npm run export:html
```

Copia `export/antony-rice-inicio.html` sobre `index.html` de este repositorio y súbelo:

```bash
git add index.html
git commit -m "Actualiza la vitrina"
git push
```

GitHub Pages publica el cambio en uno o dos minutos.

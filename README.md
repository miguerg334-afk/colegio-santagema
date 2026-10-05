# Colegio Santa Gema

Sitio web institucional del Colegio Santa Gema, desarrollado con Astro, React y Tailwind CSS. Incluye información del colegio, galería, calendario escolar y canales de contacto.

## Requisitos

- Node.js 22.12 o superior
- npm

## Desarrollo local

```bash
npm ci
npm run dev
```

## Compilación

```bash
npm run build
```

Astro genera el sitio estático en `dist/`. Para publicarlo en el hosting actual, se sube **el contenido de `dist/`** a `public_html/`. El directorio `dist/` y los ZIP de despliegue no se guardan en Git.

## Configuración

No se necesitan variables de entorno para compilar el sitio. Los enlaces de contacto, redes sociales y admisión están definidos en los componentes de `src/`. Las imágenes y otros archivos públicos se encuentran en `public/`.

Las URL canónicas del sitio, `robots.txt` y `sitemap.xml` apuntan a `https://colegiosantagema.edu.ve/`. Si cambia el dominio, deben actualizarse esos archivos y `src/components/SeoHead.astro`.

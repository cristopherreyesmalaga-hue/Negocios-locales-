# Negocios-locales-

Servicio de creación de anuncios en video e imagen, con página web, para negocios locales (clientes externos).

## Qué ofrece el servicio
- Videos verticales 9:16 (1080×1920) para Instagram y TikTok.
- Imágenes para anuncios y publicaciones.
- Página web de presentación y pedidos para cada negocio.

Los precios se cotizan en USD.

## Estructura
- `docs/reglas-clientes.md`: reglas fijas con clientes externos (costos, aprobaciones, permisos, privacidad).
- `web/`: página pública del servicio y de pedidos (pendiente).
- `.gitignore`: excluye datos de clientes y archivos de trabajo.

## Dónde NO van los datos de clientes
Este repositorio es **público**. Contratos, datos de contacto, credenciales, videos de referencia y archivos de cada cliente van en un repositorio privado o en `trabajo/`, que no se sube.

## Producción de videos
La generación y montaje de videos usa el motor de `fabrica-reels` (repositorio privado). Cada cliente tiene su propia carpeta de marca y sus propios pedidos; ninguno se mezcla con los de otro.

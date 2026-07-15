# Propuesta local para Track 13

Rediseño one-page estático orientado a conversión, velocidad y SEO. La dirección artística se plantea como un showreel audiovisual editorial: tipografía condensada, composición de gran formato y trabajos reales como principal activo de marca.

La propuesta incorpora 20 fotografías de la biblioteca pública de Track 13, optimizadas a WebP. La página completa pesa aproximadamente 1,7 MB, pero solo la imagen principal se carga con prioridad; todo el archivo situado fuera de la primera pantalla usa carga diferida y decodificación asíncrona.

## Ver en local

```bash
python3 -m http.server 8080
```

Después abre `http://localhost:8080`.

## Trasladarlo a Divi

La estructura puede reproducirse por secciones en Divi: hero escénico, manifiesto, portfolio editorial, capacidades, historia, clientes, FAQ, contacto y pie. Para conservar la composición irregular del portfolio y las animaciones conviene añadir CSS propio desde un child theme.

Antes de publicar hay que sustituir la URL de la imagen social por una imagen final de 1200 × 630 px, comprobar que las páginas legales mantienen sus URLs actuales y generar el sitemap desde WordPress.

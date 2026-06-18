# LideresMaps

Web estatica para LideresMaps, un servicio que analiza oportunidades de SEO local en Google Maps por sector y ciudad, y las traduce en decisiones comerciales: que mercado merece la pena, cuanto puede mover el Top 3 y que trabajo hace falta para competir.

## Paginas actuales

- `index.html`: home principal. Presenta la propuesta "Webs y SEO con datos", el analisis previo, las cards de servicios, el proceso compacto y las oportunidades por sector.
- `informes-disponibles.html`: pagina general de sectores analizados e informes disponibles. Agrupa mercados, categorias e informes destacados.
- `fontaneros.html`: pagina especifica del sector Fontaneros. Lista informes por ciudad y resume cifras del sector.
- `fontaneros-madrid.html`: informe especifico de Fontaneros en Madrid. Muestra metricas, preview del analisis, comparativas del Top 3 y el trabajo que haria LideresMaps.

## Archivos principales

- `styles.css`: estilos globales, header, footer y componentes compartidos.
- `home.css`: estilos de la home.
- `sectores.css`: estilos de `informes-disponibles.html`.
- `fontaneros.css`: estilos de `fontaneros.html`.
- `informe.css`: estilos de `fontaneros-madrid.html`.
- `assets/`: imagenes locales usadas por las paginas.

## Navegacion actual

Flujo principal:

```text
Home -> Informes disponibles -> Fontaneros -> Fontaneros Madrid
```

Rutas locales:

```text
http://127.0.0.1:4173/index.html
http://127.0.0.1:4173/informes-disponibles.html
http://127.0.0.1:4173/fontaneros.html
http://127.0.0.1:4173/fontaneros-madrid.html
```

## Ejecutar en local

Desde la raiz del proyecto:

```bash
python -m http.server 4173 --bind 127.0.0.1
```

Luego abrir:

```text
http://127.0.0.1:4173/index.html
```

## Estado del proyecto

Proyecto HTML/CSS estatico. La web no debe enlazar a paginas externas ni a rutas que no existan todavia; la navegacion debe mantenerse entre las paginas reales del proyecto.

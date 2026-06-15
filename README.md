# LideresMaps

Web estática para **LideresMaps**, un servicio que analiza oportunidades de SEO local en Google Maps por sector y ciudad.

La idea principal de la web es explicar, de forma visual y comercial, qué negocios aparecen arriba en Google Maps, cuánto puede mover cada mercado local y qué trabajo habría que hacer para competir con los líderes.

## Páginas actuales

- `index.html`: home principal. Presenta el servicio, el problema de visibilidad local y los mercados destacados.
- `informes-disponibles.html`: página general de sectores e informes disponibles.
- `fontaneros.html`: página específica del sector Fontaneros, con informes por ciudad.
- `fontaneros-madrid.html`: informe específico de Fontaneros en Madrid. Muestra métricas, preview del análisis, Top 3, comparativas y el bloque de trabajo que haría LideresMaps.

## Estructura

- `styles.css`: estilos globales compartidos.
- `home.css`: estilos de la home.
- `sectores.css`: estilos de la página general de sectores.
- `fontaneros.css`: estilos de la página del sector Fontaneros.
- `informe.css`: estilos del informe específico.
- `assets/`: imágenes locales usadas por las páginas.

## Ejecutar en local

Desde la raíz del proyecto:

```bash
python -m http.server 4173
```

Luego abrir:

```text
http://127.0.0.1:4173/index.html
```

## Navegación actual

El flujo principal es:

```text
Home -> Informes disponibles -> Fontaneros -> Fontaneros Madrid
```

La web no enlaza a servicios externos. Los enlaces que aún no tienen página final permanecen como enlaces internos o inertes.

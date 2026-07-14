# Casas a <30 min de Roda de Barà 🔥

Filtro automático de **DaBoss** para encontrar una casa de alquiler cerca de **Roda de Barà** (Tarragona, Costa Daurada).

## Criterios
- 📍 **Radio:** < 30 min en coche — Roda de Barà, Creixell, Torredembarra, Altafulla, Calafell y El Vendrell.
- 💶 **Presupuesto:** ≤ 1.000 €/mes.
- 🏠 **Tipo:** casas, chalets y adosados (no pisos ni apartamentos).
- 📷 **Calidad:** fotos revisadas una a una para descartar *cuchitriles* y *lujo* (>1.000 €).
- 🚫 Se descartan anuncios de temporada/vacacional cuando se identifican.

## Resultado
8 candidatas buenas en [`index.html`](index.html) (web estática) y en [`data.json`](data.json).

## Metodología y limitaciones
Los portales inmobiliarios (Idealista, Fotocasa, Nuroa) cargan los **precios por JavaScript**, por lo que no se pueden extraer de forma fiable por scraping de HTML estático. En cambio, las **fotos SÍ son accesibles** y se han valorado visualmente para cada anuncio.

- Los **precios son bandas por pueblo** (datos de búsqueda): Roda de Barà mediana ~899 €, El Vendrell desde ~627 €, Altafulla desde ~1.100 €.
- El precio exacto y la disponibilidad se confirman al clicar en "Ver anuncio".
- Fuentes: Nuroa, casasenventaypisosalquiler (CVP), Idealista, Fotocasa.

## Estructura
- `index.html` — web autónoma (responsive, sin dependencias) con las 8 candidatas.
- `data.json` — datos estructurados de las candidatas (reutilizables).
- `README.md` — este archivo.

---
*Hecho por DaBoss 🔥 · datos a 2026-07-14 · proyecto de demostración.*

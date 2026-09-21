# Odyssey Resource Atlas

Guía comunitaria e interactiva de materiales para **LEGO Fortnite Odyssey**, con énfasis en **NINJAGO: Rise of the Ninja + Embers of Chaos**.

## Funciones

- Buscador por material, fuente y método de farmeo.
- Mapa **esquemático** por región/bioma (no coordenadas universales: los mundos son procedurales).
- Filtros por madera, piedra, mineral, gema, drops, orgánicos y procesados.
- Favoritos guardados localmente en el navegador.
- Lista de farmeo con cantidades y enlace compartible.
- Planner del **NINJAGO Monastery** (niveles 1–4; nivel 5 = completado).
- Selector Español / English.
- Deep links: `?material=dragon-opal`.
- Funciona como sitio estático: no requiere servidor ni base de datos.

## Abrir localmente

Abre `index.html` en un navegador moderno. La mayoría de las funciones funcionan sin servidor. El botón de copiar puede depender de permisos del navegador cuando se abre con `file://`.

## Publicarlo gratis con GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `odyssey-resource-atlas`.
2. Sube `index.html`, `README.md` y `LICENSE` a la raíz.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige `main` y `/ (root)` y guarda.
6. GitHub mostrará la URL pública, normalmente `https://TU-USUARIO.github.io/odyssey-resource-atlas/`.

## Actualizar materiales

La base de datos está dentro de `index.html` en la constante `M`. Cada material tiene:

`id, icon, name, world, category, zones, rarity, where, how, tool, tip, route`.

Al actualizar tras un parche, conviene confirmar primero fuentes oficiales de Epic y después usar una fuente comunitaria actualizada para drops específicos.

## Fuentes principales (revisadas el 20 Sep 2026)

- Epic Games — NINJAGO: Rise of the Ninja: https://www.fortnite.com/news/master-your-true-potential-in-lego-fortnite-odysseys-ninjago-update
- OdysseyWiki — Crafting & Resource Finder: https://odysseywiki.com/crafting
- OdysseyWiki — NINJAGO / Embers of Chaos: https://odysseywiki.com/

## Nota sobre el mapa

El mapa de esta herramienta es intencionalmente **esquemático**. Indica zonas, actividades y relaciones de progresión. No afirma coordenadas exactas ni posiciones universales de nodos, porque la distribución puede variar entre mundos/semillas y con actualizaciones del juego.

## Licencia

MIT. Puedes copiar, modificar, alojar y compartir el código respetando el aviso de licencia.

Este proyecto es fan-made y no está afiliado con Epic Games ni The LEGO Group.

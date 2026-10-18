<!-- managed-by-telegram-cursor-bot:agent-kit -->
# Contexto del proyecto

## Produccion
- URL: https://github.com/Marcos1995/Crochet
- Vista: https://marcos1995.github.io/Crochet/ (repo público; Chrome)
- Vista local: `index.html`

## Estado
- `index.html` trae el patrón de un vestido y un traje (pantalón y chaqueta) para una muñeca de crochet de 25 cm, y cómo ponérselos.
- Vista en GitHub Pages (main, `/`). Antes la URL respondía 404 porque Pages no estaba activado.
- Supuesto: no había medidas en el pedido. La talla está fijada; la tabla sirve para comprobar la muñeca antes de tejer.

## Stack
- Un solo `index.html` (HTML, CSS y JS). Sin build ni dependencias.

## Comandos utiles
- Instalar: no hace falta
- Test: abrir `index.html` en Chrome
- Dev: abrir `index.html`

## Notas para el agente
- Talla y patrón: decisión en `docs/DECISIONES.md`. Aspecto: `DESIGN.md`.
- No cambiar la talla ni convertir el patrón en calculadora salvo que haya medidas reales.
- Lean kit (ver AGENTS.md)

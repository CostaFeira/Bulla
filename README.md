# BULLA! — Carta de precios

Carta de precios de BULLA! (Costa Feira 2026, Sanxenxo) en formato web,
pensada para consultarse desde un QR en el recinto.

**URL pública:** https://costafeira.github.io/Bulla/

## Cambiar un precio

El único archivo que se edita es **`index.html`** (el de la raíz).

1. Ábrelo en GitHub y pulsa el lápiz.
2. Busca la línea del producto, por ejemplo:
   `<div class="item"><span class="n">Ron Brugal</span><span class="p">120,00 €</span></div>`
3. Cambia el importe y guarda (*Commit changes*).

La web se republica sola en 1–2 minutos.
**El QR impreso no hay que tocarlo nunca**: apunta a la URL, no al contenido.

> La carpeta `bulla/` es una redirección heredada. No editar nada ahí dentro.

## Añadir productos

Copia una línea `<div class="item">…</div>` entera y cambia nombre y precio.
Para una categoría nueva, duplica un bloque `<div class="grupo">…</div>` completo.

## Dominio personalizado

No usar `costafeira.com` como *custom domain*: es el dominio principal del festival
y lo tumbaría. Si se quiere URL propia, usar el subdominio `carta.costafeira.com`
con un registro CNAME apuntando a `costafeira.github.io`.

---

Costa Feira 2026 · Polígono Empresarial de Nantes, Sanxenxo (Pontevedra)

# Pieza Exacta

Sitio web de Pieza Exacta — repuestos de auto de segunda mano, cotizados con
precio de zona franca y despachados desde Iquique a todo Chile.

Sitio en línea: https://pieza-exacta.vercel.app

## Contenido

Es un sitio estático de una sola página (`index.html`), sin build step ni
dependencias: todo el CSS y JS están en el mismo archivo. Incluye:

- Home con catálogo por categorías
- Cotizador (formulario de cotización, demo funcional sin backend)
- Seguimiento de pedido (demo funcional sin backend)
- Cobertura y despacho (zonas, tiempos, logística)
- Footer con contacto y medios de pago

## Editar

Todo el sitio vive en `index.html`. Los colores de marca están como variables
CSS al principio del archivo (bloque `:root`), así que se pueden ajustar
paleta y tipografía desde un solo lugar.

Pendiente de definir/confirmar antes de lanzar (marcado en el propio sitio):
- Dominio (piezaexacta.cl) y redes sociales (@piezaexacta)
- Medio de pago definitivo (Mercado Pago / Webpay / transferencia)
- Testimonios reales (se removieron los de ejemplo por normativa chilena de
  protección de datos/publicidad hasta contar con reseñas reales y
  autorizadas por los clientes)

## Desplegar

Este proyecto no requiere build: cualquier hosting estático (Vercel, Netlify,
GitHub Pages) puede servir `index.html` directamente sin configuración.

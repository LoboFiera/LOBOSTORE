# LOBO STORE · Purple Edition (prototipo)

Prototipo de la Fase 1 de LOBO STORE, tienda de productos y servicios digitales con identidad gaming premium en tonos morados.

> **Estado:** prototipo de diseño con datos de demostración. No procesa pagos ni hace entregas automáticas.

## Qué incluye

- Página de inicio responsive con la paleta Purple Edition.
- Catálogo por categorías en recuadros: **Gift Cards** (Steam) y **Suscripciones** (licencias y membresías).
- Carrito funcional y solicitud de pedido con validación y número de referencia. El pedido se envía por WhatsApp.
- Chat de Marina, la asistente virtual, con respuestas por reglas (sin IA todavía).

## Estructura

Todo el prototipo está en un único archivo:

```
index.html   # HTML, CSS y JavaScript integrados (incluye las imágenes de Marina)
```

## Configuración

Abre `index.html` y busca el objeto `CONFIG` dentro de la etiqueta `<script>`:

- `whatsapp`: número con código de país y sin «+» (por ejemplo `"5491112345678"`).
- `categories`: categorías y productos. Para añadir un producto, agrega un objeto a la lista de su categoría. Con `price:null` el producto muestra «Consultar precio» en lugar de comprar.
- Colores: variables CSS al inicio del archivo (`--color-primary`, `--color-background`, etc.).

## Ver el prototipo

Descarga el repositorio y abre `index.html` en el navegador, o publícalo con GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / `(root)`).

## Hoja de ruta

1. Fase 1: landing y Steam Gift Cards (este prototipo).
2. Fase 2: backend, pedidos y panel administrativo.
3. Fase 3: catálogo de videojuegos.
4. Fase 4: streaming y música.
5. Fase 5: chatbot Marina con IA.
6. Fase 6: pruebas, optimización y publicación.

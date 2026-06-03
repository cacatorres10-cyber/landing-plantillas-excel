# Landing — Pack +15.000 Plantillas Excel

Página de ventas (low ticket) para un pack de +15.000 plantillas y dashboards de
Excel / Google Sheets. Mercado hispano, tráfico pago (Meta Ads).

- **Página única** autocontenida: [`index.html`](index.html) (HTML + CSS + JS, sin dependencias).
- **Imágenes** del producto y dashboards: carpeta [`img/`](img/).
- **Diseño**: sistema visual "Forest and Sage" (Anton + Inter, paleta orgánica, animaciones suaves).

## Configuración antes de publicar

Editar el bloque `CONFIG` al inicio del `<script>` en `index.html`:

| Campo | Qué poner |
|-------|-----------|
| `hotmartBasico` | Link de checkout Hotmart — Plan Básico |
| `hotmartPremium` | Link de checkout Hotmart — Plan Premium |
| `fbPixelId` | ID del Pixel de Facebook (opcional) |
| `timerHours` | Duración del contador de oferta |

Los links de checkout preservan automáticamente los parámetros UTM y `fbclid`.

## Pendiente
- Reemplazar fotos de testimonios (generadas por IA) por reseñas reales de clientes.

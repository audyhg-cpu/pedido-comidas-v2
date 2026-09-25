# Pedido de comidas v2

Versión nueva y aislada de la app de pedidos de comida.

## Incluye
- Pegado del mensaje completo y detección asistida de comidas.
- Revisión manual de opciones antes de crear la encuesta.
- Nombres de menú completos, sin recortes.
- Pedido propio + pedidos para otros compañeros.
- Resumen por opción, total de comidas y lista “Come hoy”.
- Envío directo por WhatsApp sin número fijo.
- Persistencia de nombres usados.

## Publicación
Cloudflare Workers + D1.

Comando de despliegue:

```bash
npx wrangler deploy
```

Esta versión usa tablas `v2_*`, por lo que no mezcla los datos de prueba de la versión anterior.


## Instalación
Esta versión funciona como PWA instalable en Android y iPhone, con icono propio.

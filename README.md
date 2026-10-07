# Profilaxis ATB · Quirófano — iPhone

Esta carpeta es una PWA (Progressive Web App) basada en el protocolo hospitalario aportado.

## Cómo instalarla en iPhone

La forma más sencilla para todo el servicio es publicarla en una URL HTTPS.

1. Sube todos los archivos de esta carpeta a un alojamiento web HTTPS (por ejemplo, GitHub Pages).
2. Abre la URL desde **Safari** en el iPhone.
3. Pulsa **Compartir**.
4. Selecciona **Añadir a pantalla de inicio**.
5. Pulsa **Añadir**.

Quedará como una app independiente en la pantalla de inicio y funcionará también sin conexión después de haberla abierto/cargado.

## Importante
No es posible distribuir directamente un `.ipa` sin firma de Apple. Para una app nativa distribuida al servicio mediante TestFlight/App Store hace falta una cuenta de Apple Developer y firmar la aplicación.

La PWA evita ese proceso y permite compartir un único enlace con todos los miembros del servicio.

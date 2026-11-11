# Vocyra

**Soundboard y cambiador de voz con IA para Windows.** Sonidos ilimitados en Discord, juegos y
llamadas, con atajos que siguen funcionando dentro del juego. Gratis, portable y en español.

**Página oficial:** https://br105.github.io/Vocyra-releases/

## Descarga

Descarga **[Vocyra-portable.zip](https://github.com/BR105/Vocyra-releases/releases/latest/download/Vocyra-portable.zip)**,
descomprímelo y la primera vez abre «Abrir Vocyra (primera vez).bat».

## Qué hace

- **Sonidos ilimitados.** Es una carpeta, no una lista de espacios: caben los que quepan en tu disco,
  con su color, su atajo y sus categorías.
- **Atajos globales.** Se registran en Windows, así que funcionan con el juego en pantalla completa,
  sin alt-tab.
- **Efectos de voz en vivo** (grave, agudo, radio) y **compuerta de ruido** que corta el ventilador y
  el teclado cuando no hablas.
- **Voz IA en tiempo real** (experimental): cambia tu voz por una voz que tú entrenas desde la app,
  basada en Applio/RVC. Necesita tarjeta NVIDIA y un complemento de ~6 GB que se descarga una sola
  vez desde la propia app. Entrena solo voces tuyas o de quien te haya dado permiso; ver las
  [condiciones](https://br105.github.io/Vocyra-releases/terminos.html).
- **Repetición instantánea:** guarda los últimos segundos de lo que sonó, con pistas por app.
- **Control desde el celular** por código QR, en tu red local.
- **Packs** para compartir sonidos y voces por enlace de Google Drive o en un archivo `.vocyra`.
- **Recorte no destructivo** y exportar un clip a MP3.
- **Respaldo opcional** en tu propio Google Drive.

## Requisitos

- Windows 10 u 11 (64 bits).
- [VB-Cable](https://vb-audio.com/Cable/) (gratis). Vocyra puede instalarlo por ti desde Ajustes.
- Para la voz IA: tarjeta NVIDIA.

## Uso rápido

1. Abre `Vocyra.exe`.
2. En Discord (o el juego/app de llamadas) elige **CABLE Output** como micrófono.
3. En Vocyra → Ajustes, elige tu micrófono real. Tu voz y los sonidos llegan juntos.

En Discord usa el perfil de voz **«Estudio»**: el aislamiento de voz borra todo lo que no sea tu
boca, y con él se pierden los sonidos.

## Seguridad

Vocyra está firmada con un certificado propio, no con uno comercial de pago, así que SmartScreen o
Defender pueden avisar la primera vez. Cada versión publica el SHA-256 de su ZIP en
[`seguridad.json`](seguridad.json), y la página enlaza el análisis de VirusTotal correspondiente.

---

Este repositorio solo publica las versiones oficiales y la página. El código fuente no es público.
Una app de [Gecko Apps](https://br105.github.io/).

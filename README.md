# estudios-audio

Los audios de las clases del [Mapa de estudios](https://delvinsmart.github.io/estudios/), para escucharlas
con la pantalla del teléfono bloqueada. Un archivo `.m4a` por cada parte de cada clase, y `audio/indice.json`
con la lista.

Se generan gratis con [Piper](https://github.com/OHF-Voice/piper1-gpl) y se publican **solos**: cada vez que se
sube una clase al repositorio del mapa, GitHub Actions (`.github/workflows/audios.yml` de `estudios`) rehace solo
los audios de las partes que cambiaron y los sube aquí. La voz y el interruptor están en
`herramientas/audio/motor.json` del mapa (`node herramientas/audio/voz.mjs` para verlos o cambiarlos).

No se editan a mano. Este repositorio no guarda historial: cada publicación reemplaza a la anterior, así pesa
siempre lo mismo.

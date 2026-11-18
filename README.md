# Estudio

Estudio de grabación multipista en el navegador, pensado como un Pro Tools o Ableton sencillo para músicos. Graba tus pistas encima de una base, una toma tras otra; edita, mezcla con efectos y exporta en WAV. By Anggelo Berdejo.

**Abrir la app:** https://anggeloberdejo1-byte.github.io/Estudio/

## Qué hace

- **Proyectos** con nombre, tempo (BPM) y compás (4/4, 3/4, 2/4, 5/4, 6/8, 7/8, 12/8). Se guardan solos en el equipo.
- **Empezar con una base o canción:** la importa como primera pista, detecta el tempo y la acomoda en la rejilla.
- **Multipista:** pistas con armar (R), mudo (M), solo (S) y escucharme (🎧). Al armar una pista te escuchas por ella como en Pro Tools, con escucha rápida (directo a la salida, sin compresores) y el retraso a la vista, con aviso si el micrófono y la salida van a distinta frecuencia (automático, siempre o apagado; tecla I). Cada pista elige qué entrada graba: 1, 2, 1+2 o estéreo — con una interfaz de dos entradas se graban dos pistas a la vez.
- **Grabación** con cuenta de 1 o 2 compases, metrónomo, compensación de latencia (automática o calibrada con 6 clics) y alineación al cuadro exacto. Se puede pinchar sobre la marcha (grabar mientras suena).
- **Tomas en loop:** marca un tramo, graba vueltas seguidas y cada vuelta queda como una toma. Clic derecho sobre el clip para elegir la mejor.
- **Edición:** mover (también entre pistas), recortar los bordes, fundidos de entrada y salida, cortar en el cabezal, duplicar, copiar con Alt, normalizar y ganancia del clip. Rejilla de compás, pulso, 1/8, 1/16 o libre. Deshacer y rehacer ilimitados. Marcas en la regla.
- **Entrada:** ganancia, ecualizador gráfico de 10 bandas con presets, compresor completo (presets como en Pro Tools, umbral, proporción, ataque, liberación y ganancia, knee, A/B y make-up automático, con medidor de cuánto aprieta), «Alcance del micrófono» (todo el cuarto, medio o solo lo cercano, con «Calibrar con mis dedos»), limpiador de ruido del navegador opcional, compuerta de ruido con «Medir el ruido» (umbral, cuánto baja, mantener, liberación), reverb para escucharte afinador y aviso de nivel (bajo, bien, se satura). Se elige si la toma se graba con o sin efectos.
- **Mezclador:** por pista corte de graves, EQ de 3 bandas, compresor, envíos a reverb y delay (el delay sigue el tempo), paneo, fader y medidor. Maestro con retornos y limitador.
- **Exportar** la mezcla o cada pista por separado, todo el proyecto o solo el loop, en WAV de 16 o 24 bits, con o sin metrónomo.
- **Banco de sonidos propio:** 24 sonidos fabricados por la app (bombos, rumble, hats, ride, clap, percusión, acid, stabs, pad, subida, impacto). Los loops siguen el tempo del proyecto. Se oyen con ▶ y se agregan en el cabezal.
- **Ejemplo de hard techno:** un proyecto a 155 BPM ya armado y mezclado (intro, groove, break, drop y final) con una guía paso a paso de cómo se hace.
- **Ajustes:** español o inglés, 12 paletas, micrófono y salida de audio, cuenta, metrónomo (clic, cencerro, madera o baqueta) y latencia. Más de 30 atajos de teclado al estilo Pro Tools, incluido el teclado numérico; toca ? para verlos.
- **Exportar:** fundido de salida al final (3, 6 o 10 s).

Todo pasa en tu equipo: nada se sube a internet y funciona sin conexión. Mejor en computadora con audífonos; también funciona en el celular.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Toda la app (HTML, CSS y JS): grabación, motor de audio, línea de tiempo y mezclador |
| `sello.webp` | Sello "By Anggelo Berdejo" |
| `manifest.json`, `sw.js`, íconos | Para instalarla como app y usarla sin internet |

Cada vez que se actualice `index.html`, hay que subir la versión del caché en `sw.js` (`estudio-v1` → `estudio-v2`…).

---

Hecha por Anggelo Berdejo — El Ñañe · [@anggelo.berdejo](https://instagram.com/anggelo.berdejo) · [Otras herramientas](https://anggeloberdejo1-byte.github.io/apps/)

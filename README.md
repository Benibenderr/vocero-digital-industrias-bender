# 4.2.2 · Creación de Voceros Digitales Personalizados

**Benicio Gerez Bender · Coderhouse · Creación de contenido con AI**

[Ver el video](output/Vocero_Digital_Industrias_Bender.mp4) · [Descargar MP4](output/Vocero_Digital_Industrias_Bender.mp4?raw=1)

38 s · 1920 × 1080 · 25 fps · subtítulos en español integrados.

## Pieza y continuidad con los módulos anteriores

Para Industrias Bender, el vocero explica qué tres datos conviene reunir antes de consultar por el mecanizado de una pieza. La audiencia principal es Compras y Abastecimiento. El guion amplía el gancho del 24/11 de la Pre-entrega 2 y conserva su secuencia de revisión del plano, cantidad y criterio de aceptación. El cierre invita a compartir los datos por el canal comercial.

El técnico ficticio es el personaje C01 del Manual de Identidad Visual del Módulo 3. Conserva el casco marino, los lentes transparentes, la barba, la campera azul y las bandas reflectivas. El montaje utiliza azul Bender (`#004484`), grafito y blanco frío, junto con las imágenes C02, A01 y A03 del manual.

| Tramo | Imagen | Mensaje |
| --- | --- | --- |
| 00:00–00:07 | Vocero C01 animado | ¿Tenés el plano? |
| 00:07–00:14 | C02, mesa de inspección | Revisá la versión vigente del plano. |
| 00:14–00:20 | A01, pieza mecanizada | Indicá cuántas unidades necesitás. |
| 00:20–00:27 | A03, instrumental | Acordá qué medidas o requisitos se verifican. |
| 00:27–00:38 | Vocero C01 animado | Compartí los tres datos por el canal comercial. |

## Guion

**Prompt de adaptación**

> Adaptá a un video de 30 a 60 segundos el gancho del pilar Consultas de Industrias Bender, «Tenés el plano. ¿Qué más hace falta para consultar por una pieza?». Hablale a Compras y Abastecimiento con voseo argentino, tono técnico y sobrio y frases fáciles de decir. Explicá en orden la revisión vigente del plano, la cantidad y el criterio de aceptación. Cerrá con una sola invitación a compartir esos datos por el canal comercial. Evitá prometer factibilidad, plazos y precios. Escribí cinco párrafos breves con espacio para pausas.

**Texto locutado**

¿Tenés el plano? Para consultar por una pieza mecanizada, hay tres datos que nos ayudan a entender tu pedido.

Primero, la revisión vigente del plano. Así conversamos sobre la versión correcta de la pieza.

Segundo, la cantidad. Indicá si necesitás una unidad o una serie.

Y tercero, el criterio de aceptación. Decinos qué medidas o requisitos necesitás verificar al recibirla.

En Industrias Bender evaluamos tu requerimiento desde Neuquén. Compartí esos tres datos por nuestro canal comercial para que podamos revisar el alcance con vos.

## Voz y sincronización

- **Voz.** Tomás (`es-AR-TomasNeural`), voz neuronal de catálogo de Microsoft. Ritmo −5 % y tono −2 Hz. Se generó una toma por párrafo y se insertaron pausas cortas entre ideas. La locución limpia está en `assets/02_locucion_Tomas_AR.wav`. [Catálogo de voces de Microsoft](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support?tabs=text-to-speech)
- **Avatar.** Wav2Lip + GAN procesó localmente el retrato C01 y la locución sola. Se calculó el movimiento labial a 25 fotogramas por segundo y se combinó la zona de la boca con la fotografía original. La apertura y el cierre muestran al vocero. Los tres apoyos visuales ocupan el desarrollo y marcan cada idea. [Proyecto Wav2Lip](https://github.com/Rudrabha/Wav2Lip)
- **Edición.** Los subtítulos se temporizaron con las marcas de palabra de la locución. La música se incorporó después de sincronizar la boca. El MP4 es una pieza académica con un personaje y escenas generadas por IA.

## Música

**Prompt utilizado en MusicGen Small**

> Instrumental underscore for a sober industrial training video. Steady 84 BPM in D minor, soft felt electric piano chords, warm low analog pad, restrained sub bass, a soft brushed metallic rim pulsing quietly, and spacious clean production. A seamless repeating four-bar phrase, sparse middle frequencies so Spanish narration stays clear, no voices, no lead melody, no dramatic hits, no crescendo.

La pista se generó en MusicGen Streaming con semilla 5 y una duración solicitada de 15 s. El WAV original está en `assets/03_musica_MusicGen.wav`. Se repitió con fundidos cruzados de 0,48 s y se ajustó la base al **18 %** tras nivelarla. La pista entra y sale con fundidos. [MusicGen Small](https://huggingface.co/facebook/musicgen-small)

Se usó MusicGen porque el plan gratuito de Suno ofrece cero descargas y Udio indica que las descargas están deshabilitadas. [Ayuda de Suno](https://help.suno.com/en/articles/13876865) · [Ayuda de Udio](https://help.udio.com/en/articles/12683565-changes-associated-with-the-universal-music-group-umg-partnership)

## Versión entregada

La sincronización de esta versión se realizó localmente con Wav2Lip. Los archivos `assets/01_vocero_C01.png` y `assets/02_locucion_Tomas_AR.wav` permiten reutilizar el mismo personaje y la misma voz en HeyGen. En Photo Avatar se selecciona el retrato y se usa el WAV como entrada de la voz si la cuenta habilita esa función. El instrumental se incorpora en el montaje posterior al 18 %. [Guía de Photo Avatars de HeyGen](https://help.heygen.com/en/articles/10034438-how-to-get-started-with-photo-avatars)

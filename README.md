# Hola, soy Rafael 👋

**Desarrollo herramientas de escritorio en Python para automatizar tareas con imágenes, audio y vídeo.**

Me interesa convertir procesos repetitivos en aplicaciones prácticas: una interfaz clara, procesamiento en segundo plano y resultados que puedas usar.

[Proyectos](#proyectos-destacados) · [Tecnologías](#tecnologías) · [Contacto](#contacto)

## Proyectos destacados

### 📦 [Compressor JPEG](https://github.com/rafaeltorres8/Compressor_JP_E_G_v0)

Comprime y redimensiona imágenes JPEG por lotes, conservando la estructura de subcarpetas.

- Ajusta la calidad y el tamaño máximo, y corrige la orientación según EXIF.
- Procesa las imágenes en un hilo separado y permite cancelar el trabajo.
- Incluye validaciones de archivos y rutas, límites de tamaño y pruebas automatizadas.

**Tecnologías:** Python · Tkinter · Pillow · pytest  
[Ver código y guía de uso →](https://github.com/rafaeltorres8/Compressor_JP_E_G_v0#readme)

### 🎙️ [Transcriptor Pro](https://github.com/rafaeltorres8/Transcriptor_Pro_v0)

Transcribe audio y vídeo en el equipo con Whisper y FFmpeg, desde una interfaz gráfica.

- Exporta a **TXT, Markdown, SRT, VTT y JSON**.
- Usa GPU con CUDA cuando está disponible y CPU como alternativa.
- Ejecuta la transcripción en segundo plano, muestra el progreso y guarda preferencias.
- Separa la lógica de procesamiento de la interfaz e incluye pruebas automatizadas.

**Tecnologías:** Python · PySide6 · Whisper · FFmpeg · PyTorch · pytest  
[Ver código y guía de uso →](https://github.com/rafaeltorres8/Transcriptor_Pro_v0#readme)

> La transcripción es local y no requiere una clave de la API de OpenAI. Whisper puede descargar los modelos cuando no están disponibles en la caché.

## Tecnologías

| Área | Herramientas que uso en estos proyectos |
| --- | --- |
| Aplicaciones de escritorio | Tkinter, PySide6 |
| Imágenes | Pillow |
| Audio y vídeo | Whisper, FFmpeg, PyTorch |
| Calidad y mantenimiento | pytest, Git, separación entre interfaz y lógica |

## Lo que estoy explorando

- Interfaces de escritorio con CustomTkinter y Flet.
- Ampliar las herramientas a otros formatos, como RAW, PDF, vídeo y DGN.

Estas ampliaciones son líneas de exploración; no forman parte de las funciones actuales del compresor JPEG.

## Contacto

Puedes encontrarme en **X: [@rafaeltorres_b](https://twitter.com/rafaeltorres_b)**.

Si tienes una sugerencia o encuentras un problema, puedes abrir una incidencia en el repositorio correspondiente.

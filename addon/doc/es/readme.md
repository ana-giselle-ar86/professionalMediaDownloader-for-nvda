# Professional Media Downloader #
* Autor: Umesh Rathore
* Versión: 2.0

Professional Media Downloader es una herramienta de alto rendimiento y totalmente accesible, diseñada para que los usuarios de NVDA puedan descargar contenido de audio y vídeo de más de 1.000 plataformas de streaming, incluyendo YouTube, Facebook, Instagram y más.

## Atajos de teclado principales ##
* **NVDA+Shift+Y**: Abre el diálogo del descargador desde cualquier aplicación.
* **Alt+E**: Enfoca el campo de edición Introducir URL.
* **Alt+P**: Pega la URL directamente desde el portapapeles.
* **Alt+D**: Acciona el botón Descargar.
* **Alt+O**: Abre el directorio de Descargas en el Explorador de Windows.

## Cómo usarlo ##
1. Copia la URL del medio que deseas descargar desde tu navegador web.
2. Presiona **NVDA+Shift+Y** para lanzar la interfaz del descargador.
3. **Obtención automática**: El complemento detectará y pegará automáticamente la URL de tu portapapeles al abrirse. Si no es así, utiliza el botón **Pegar desde el portapapeles**.
4. Usa la tecla **Tab** para navegar hasta el cuadro de **Selección de formato** y elige el formato deseado (por ejemplo, MP3, MP4, AAC, OPUS).
5. Presiona **Enter** o haz clic en el botón **Descargar** para iniciar el proceso.
6. **Monitoreo del progreso**: Aparecerá un diálogo de progreso accesible. Escucharás un pitido de inicio, seguido de un tono de éxito una vez que la descarga se haya completado.

## Nuevas funciones en la versión 2.0 ##
* **Detección automática del portapapeles**: Obtiene y anuncia automáticamente la URL al abrir el diálogo.
* **Soporte multi-idioma**: Localización completa para los idiomas hindi (hi), ruso (ru) y ucraniano (uk).
* **Señales sonoras**: Retroalimentación de sonido en tiempo real (usando winsound) para el inicio, la finalización y los errores de descarga.
* **Rendimiento mejorado**: Extracción de metadatos optimizada utilizando tecnología FFprobe.

## Formatos compatibles ##
* **Formatos de audio**: MP3, M4A, AAC, OGG, OPUS, WAV, FLAC.
* **Formatos de vídeo**: MP4, MKV, WEBM (Máxima calidad disponible).
* **Integración**: Se integra perfectamente en el menú Herramientas de NVDA.
* **Organización**: Categoriza automáticamente los archivos en carpetas dedicadas de 'Audio' y 'Video'.

## Requisitos técnicos ##
Este complemento requiere que `yt-dlp.exe`, `ffmpeg.exe` y `ffprobe.exe` estén presentes dentro del directorio del complemento para el procesamiento y la conversión.

***
© 2026 Umesh Rathore. Todos los derechos reservados.  
Construido con tecnología yt-dlp y FFmpeg.

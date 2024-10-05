### Implementación de seguimiento de manos usando OpenCV y MediaPipe

Este código utiliza OpenCV para capturar un flujo de video y la biblioteca MediaPipe para realizar el seguimiento de las manos en tiempo real.

- **Bibliotecas utilizadas**: 
  - `cv2` para la captura y procesamiento de video.
  - `mediapipe` para el procesamiento y seguimiento de las manos.

- **Funcionalidad principal**:
  1. Captura un flujo de video desde una URL específica.
  2. Convierte el video a un formato RGB necesario para el procesamiento con MediaPipe.
  3. Usa MediaPipe para detectar la posición de las manos en cada cuadro del video.
  4. Dibuja las marcas de referencia en las manos, destacando con un círculo el pulgar (id 4).
  5. Muestra el video con las anotaciones en una ventana.

- **Mejoras visuales**:
  - Se dibuja un círculo en el punto correspondiente al pulgar.
  - Se usan las conexiones entre los puntos de referencia de la mano para visualización.

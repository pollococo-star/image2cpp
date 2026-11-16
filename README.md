# image2cpp

Herramienta web para convertir imágenes en arreglos de bytes listos para pantallas OLED, Arduino, ESP y Raspberry Pi.

**Todo el procesamiento se realiza localmente en tu navegador.** Ninguna imagen se sube a ningún servidor.

## Uso online

👉 **[Abrir image2cpp](https://pollococo-star.github.io/image2cpp/)**

## Características

- Importar una o varias imágenes (PNG, JPG, GIF, etc.)
- Reconstruir imagen a partir de un arreglo de bytes existente
- Tramado: Binario, Bayer, Floyd–Steinberg y Atkinson
- Escalado, centrado, rotación, volteo e inversión de colores
- Modos de dibujo: 1 bit (horizontal/vertical), RGB565, RGB888 y mapa alfa
- Salidas: bytes simples, código Arduino (individual o combinado) y fuentes Adafruit GFX
- Intercambio de bits (útil para u8g2)
- Descarga directa como archivo `.bin`

## Créditos

Basado en el excelente trabajo original de [javl/image2cpp](https://github.com/javl/image2cpp).

## Licencia

Código abierto. Usa y modifica libremente.

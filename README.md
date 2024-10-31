# Cifrado de Imágenes con AES: Comparación de Modos ECB y CBC

Este proyecto muestra el efecto del cifrado de imágenes utilizando el algoritmo AES en los modos **ECB (Electronic Code Book)** y **CBC (Cipher Block Chaining)**. Las diferencias visuales entre los modos permiten observar el impacto en la seguridad.

## Comparación de Imágenes

A continuación, puedes ver la imagen original y las versiones cifradas con cada modo de operación:

### Imagen Original
![Imagen Original](tux.bmp)

### Imagen Cifrada en Modo ECB
![Cifrado ECB](tux_ecb.png)

### Imagen Cifrada en Modo CBC
![Cifrado CBC](tux_cbc.png)

## Análisis de Resultados

- **Cifrado ECB**: Este modo revela patrones visibles de la imagen original en la imagen cifrada, lo cual lo hace inseguro para imágenes y otros datos con estructuras repetitivas.
- **Cifrado CBC**: Este modo elimina patrones visibles, proporcionando un cifrado más seguro y visualmente aleatorio.

## Conclusión
El modo ECB no es adecuado para el cifrado de imágenes, ya que conserva patrones visibles de la imagen original, mientras que CBC ofrece mayor seguridad al ocultar estos patrones.

## Licencia
Este proyecto está bajo la licencia MIT.

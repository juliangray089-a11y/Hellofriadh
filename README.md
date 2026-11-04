# MiWaifu2x

Réplica visual en español inspirada en la estructura de una herramienta de mejora de imágenes.

## Publicar con GitHub Pages

1. Crea un repositorio público llamado `miwaifu2x` en https://github.com/new
2. Sube `index.html` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que termine el despliegue. La URL tendrá el formato:
   `https://TU-USUARIO.github.io/miwaifu2x/`

## Qué incluye

- Interfaz adaptable a móviles.
- Carga local y arrastrar/soltar imágenes.
- Vista previa.
- Controles visuales para tipo, reducción de ruido, escala y formato.
- Descarga de la imagen original (con conversión a WebP en archivos locales).

## Limitación importante

Esta versión es solo una réplica visual/prototipo de interfaz. No implementa los algoritmos de Waifu2x: los controles de ruido y escala no procesan la imagen ni crean píxeles nuevos. Para ofrecer mejora real por IA hace falta integrar un backend o un modelo que se ejecute en el navegador. GitHub Pages solo aloja archivos estáticos.

El nombre y el diseño son independientes; este proyecto no está afiliado a Waifu2x.

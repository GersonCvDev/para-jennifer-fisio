# Para Jennifer 💜 · Día Mundial de la Fisioterapia

Carta interactiva de 11 pantallas, con música de fondo y un video final.

## Estructura

```
index.html
img/
  foto01.jpg   (pantalla 1)
  foto02.jpg   (pantalla 3)
  foto03.jpg   (pantalla 5)
video/
  mensaje.mp4        (video final, 47 s)
  portada-video.jpg  (miniatura del video)
audio/
  (opcional) musica.mp3
```

## Cómo subirlo a GitHub Pages

1. Crea el repo (por ejemplo `para-jennifer-fisio`) o usa una carpeta nueva dentro del que ya tienes.
2. Sube **todo el contenido de esta carpeta** manteniendo los nombres y las subcarpetas (`Add file → Upload files`, arrastra `index.html`, `img`, `video` y `audio`).
3. `Settings → Pages → Branch: main / (root) → Save`.
4. En un par de minutos tendrás el enlace `https://GersonCvDev.github.io/para-jennifer-fisio/`.

> El `mensaje.mp4` pesa 7.8 MB, muy por debajo del límite de 100 MB por archivo de GitHub.

## Cómo funciona la música

- Al pulsar **Abrir 💌** empieza la canción de fondo (YouTube, id `GShxN7ONPmI`, reproducido en un iframe oculto y en bucle).
- El botón ♪ de arriba a la derecha la pausa y la reanuda.
- Al entrar en la **última pantalla** la música de fondo se corta sola, se oculta el botón ♪ y arranca el video con su propio audio. Si vuelves atrás, el video se detiene y la música regresa.

### Si YouTube te falla

Algunos videos no permiten incrustarse y algunas redes bloquean YouTube. Para no depender de eso: coloca un archivo llamado `musica.mp3` dentro de la carpeta `audio/` y la página lo usará automáticamente en lugar de YouTube (no hay que tocar el código).

## Notas

- Ábrelo con Live Server en VS Code o desde GitHub Pages. Con doble clic (`file://`) YouTube no suena.
- Los navegadores solo dejan sonar audio después de un toque del usuario, por eso la música arranca al pulsar **Abrir 💌**.
- Si el video no arranca solo en el iPhone de ella, basta con tocar ▶ (el aviso aparece debajo del video).
- Para cambiar cualquier texto, busca el comentario `═══ N ═══` de la pantalla en `index.html`.

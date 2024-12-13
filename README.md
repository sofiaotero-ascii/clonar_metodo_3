


# Clonado del Repositorio: audacity/audacity

Este README documenta el proceso que seguí para clonar el repositorio `audacity/audacity` y crear una copia en mi cuenta de GitHub como `sofiaotero-ascii/clonar_metodo_3.git`, utilizando el método de fork.

## Pasos realizados

### 1. Realicé un fork del repositorio original
- En GitHub, navegué al repositorio oficial de **Audacity**:  
  [`https://github.com/audacity/audacity`](https://github.com/audacity/audacity).
- Hice clic en el botón **Fork** en la parte superior derecha de la página.
- Esto creó una copia del repositorio en mi cuenta personal de GitHub, con la dirección:  
  [`https://github.com/sofiaotero-ascii/clonar_metodo_3.git`](https://github.com/sofiaotero-ascii/clonar_metodo_3.git).

### 2. Creé una carpeta para el proyecto
- Abrí la terminal en mi computadora y cambié al directorio donde quería trabajar.
- Creé una carpeta específica para el proyecto:
  ```bash
  cd C:\Users\Jacobo\Pictures\metodo_clonado_3
  ```

### 3. Cloné mi repositorio forked
- Usé el comando `git clone` para clonar mi repositorio en mi máquina local. Este fue el comando:
  ```bash
  git clone https://github.com/sofiaotero-ascii/clonar_metodo_3.git
  ```
- Esto descargó todos los archivos y la estructura del proyecto desde mi copia en GitHub a mi computadora.

### 4. Resultado del clonado
- Los mensajes en la terminal confirmaron que:
  - Se enumeraron y contaron los objetos del repositorio (`Enumerating objects`, `Counting objects`).
  - Los archivos se comprimieron y descargaron al 100%.
  - A medida que avanzaba, el progreso de descarga se mostraba como porcentaje (`Receiving objects: 65%` en la imagen).

### 5. Estado final
- Ahora tengo una copia del repositorio en mi computadora, lista para trabajar en ella.
- El repositorio local se encuentra en la ruta:
  ```
  C:\Users\Jacobo\Pictures\metodo_clonado_3\clonar_metodo_3
  ```


---

¡Y eso es todo! Ahora estoy lista para explorar y trabajar con los archivos del proyecto. 🚀
```







# Audacity


[**Audacity**](https://www.audacityteam.org) is an easy-to-use, multi-track audio editor and recorder for Windows, macOS, GNU/Linux and other operating systems. More info can be found on https://www.audacityteam.org

## This repository is currently undergoing major structural change.

We're currently working on Audacity 4, which means an entirely new UI and also refactorings aplenty. As such, master is currently not particularly friendly to new contributors. It still is possible to submit patches to Audacity 3.x; make sure you branch off release-3.7.x if you choose to do so. Build instructions for 3.x can be found [here](https://github.com/audacity/audacity/blob/release-3.7.0/BUILDING.md); build instructions for Audacity 4 are not available yet.

You can stay updated with our efforts on [YouTube](https://youtube.com/@audacity), [discord](https://discord.gg/audacity) and [our blog](https://audacityteam.org/blog).

## License

Audacity is open source software licensed GPLv3. Most code files are GPLv2-or-later, with the notable exceptions being /lib-src (which contains third party libraries), as well as VST3-related code. Documentation is licensed CC-by 3.0 unless otherwise noted. Details can be found in the [license file](LICENSE.txt).

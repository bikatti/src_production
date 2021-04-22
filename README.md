# src_production

Este repositorio contiene las carpetas y archivos base que debe contener todo proyecto de Website que se haga en Monlogo. Este contiene:
+ #### Carpeta Dist 
  Esta carpeta contendrá todos los archivos que vayan a subirse al website en host. Desde los archivos HTML, CSS, Javascript hasta los videos o imágenes de website. Aquí no debe haber ningún archivo que no haya sido procesado, ni archivos de .psd o .ai que no sean usado en la página. El único archivo que se podrá modificar desde esta carpeta será de Javascript.
+ #### Carpeta Recursos 
  Aquí tendremos tanto archivos que iran a dist como archivos que son de ayuda para el programador. Esta carpeta no se subirá a git, ni al host. Se supone que cuando el programador reciba de Monlogo que son para el website o de ayuda para el programador, este pondrá los archivos aquí antes organizarlos y ponerlos en donde van.
+ #### Carpeta src
  Esta carpeta contendrá todos los archivos preprocesados de lenguajes como SASS o PUG, también librerías o frameworks de Javascript que necesiten ser preprocesados. Dentro de habrá carpetas correspondientes a los lenguajes y dentro un organización que hará más fácil poder crear el código más rápido y terminar de tener ser rebundante y utilizar código de más.
  
## .gitignore
En el archivo de .gitignore debe especificarse que no copie:
+ La carpeta de **recursos**
+ La carpeta de **img** y **video** de la carpeta Dist
+ Los archivos que sean videos, imgs o audios

## ¿Cómo descargo el repositorio?
Te recomendamos clonar el repositorio directamente desde la **Git bash** así:

```bash
git clone git@github.com:bikatti/src_production.git
```

Recuerda que tienes que crear un reposiotio antes de poder clonar.

## Autor ✒️

Los autores de este proyecto son:

* **Bikatti** (María Sierra Bohorquez) - Desarrollo Frontend - [website](https://bikatti.com)

---
⌨️ con ❤️ por [Bikatti](https://github.com/bikatti) 😊

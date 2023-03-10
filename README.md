# Principios sobre `Git`

<div style="display: flex">
  <img src="imagenes/git-2.gif" width=200>
  <img src="imagenes/git-2.gif" width=200>
  <img src="imagenes/git-2.gif" width=200>
  <img src="imagenes/git-2.gif" width=200>
</div>
> ¿QUE ES GIT? (https://git-scm.com/)

> Es un controlador de versiones, que nos va a ayudar a ser eficientes, como tambien nos ayudara a la mantenivilidad de un proyecto, ya que vamos a tener multiples verciones del proyecto. 

## Concepto de Git

![Alt text](/imagenes/git.png    "Proceso de git")

> Como se puede apreciar en la imagen,  para por subir archivos a un proyecto, este proceso se divide en tres partes importantes 



## El flujo de trabajo básico en Git es algo así:

    Modificas una serie de archivos en tu directorio de trabajo.

    Preparas los archivos, añadiéndolos a tu área de preparación.

    Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantánea de manera permanente en tu directorio de Git.



## Tu Editor

> Ahora que tu identidad está configurada, puedes elegir el editor de texto por defecto que se utilizará cuando Git necesite que introduzcas un mensaje. Si no indicas nada, Git usará el editor por defecto de tu sistema, que generalmente es Vim. Si quieres usar otro editor de texto como Emacs, puedes hacer lo siguiente:

     $ git config --global core.editor emacs

     git code . 

> Con `git code . ` vas a poder habir tu editor por defecto, este comando te va servir de mucho a la hora de edicion de proyectos 


## Codigo de ayuda

> En este comando vas a poder sobre escribir todo tu repositorio, al momento de hacer una modificacion general (implementacion de carpetas o cambio de nombre)


> `Error`
```
! [rejected]  master -> master (fetch first)'"
```

> Solucion

```
git push origin master --force
```

## Ignorar capetras o Archivos 

Para evitar que ciertos archivos o carpetas se suban a Github, puedes crear un archivo llamado <b>.gitignore</b> en la raíz de tu repositorio local.

> Por ejemplo, si deseas omitir todos los archivos con extensión .log y la carpeta venv, puedes crear un archivo <b>.gitignore</b> con el siguiente contenido:

```
*.log
venv/
```

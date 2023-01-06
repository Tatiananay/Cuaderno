# CLASE 4: Introducción a Git 
*Date:* *15 de noviembre del 2022*

*Author:* *Nayeli Leiva*
## ¿Qué es Git?
Git fue creadoen 2005 por el mismo Linus Torvalds (el creador de Linux)como herramienta para facilitar el desarrollo colaborativode software. Desde entonces han surgido incluso populares plataformas,como GitHub o GitLab, que permiten su uso online.
![git](git.png)
## Comandos de Git
**Tu Identidad**

$ gitconfig--global user.name "Emma Paris“

$ gitconfig--global user  emailjohndoe@example.com
 
**Verificando**
 
 $ gitconfiguser.name
 
 $ gitconfiguser.email
 
 **inicio del control de versiones**
 
 $ gitinit$ gitstatus
 
 $ gitadd.
 
 $ gitadd
 
 **NombreCarpeta/NombreArchivo**
 
 $ gitcommit-m 'mensaje : initialprojectversion'
 
 **inicio del control de versiones** 

-clonando$ gitclone https://github.com/xxyyy/abc$ gitclone https://github.com/xxyyy/abc miPropioNombre

**Quitar archivos del control**

$echonombreArchivo.ext>>.gitignore

$echo*.txt>>.gitignoreVer 

**archivos ignorados**

$ cat.gitignore

**Forzar agregar archivo excluido**

$gitadd-fNombreArchivo.log 
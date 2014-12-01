# ¿Aún no usás git y Github?

Este material es el apoyo para la charla de git/github del día 1 de diciembre de 2014, dictado en [la Ofi](http://www.laofi.co) por [delucas](http://delucas.github.io), de [wecode](http://www.wecode.io).

## Consigna

Trabajarán de a dos en este proyecto, para sacar una mejor experiencia.

1. Forkear el repositorio desde el usuario de github de uno de los integrantes.
2. Brindar acceso de escritura al otro usuario, para poder trabajar juntos.
3. Uno de los integrantes trabajará el contenido de la página. El otro, el aspecto de la misma.
4. Ambos intentarán subir sus cambios al mismo repositorio.
5. Si aún no surgieron conflictos, ambos editen el mismo aspecto de la página, en direcciones diferentes. Ejemplo: ambos editen el color de fondo, con colores distintos.
6. Resuelvan el conflicto optando por una de las opciones.
7. Utilizar un issue en github, y asignarlo/resolverlo la persona que no lo creó.

## Comandos útiles

### clonar el repositorio

    git clone https://github.com/usuario_github/2014-git-laofi.git

### agregar mis cambios

    git add nombre_del_archivo

### realizar un commit

    git commit -m "Mensaje del commit"

### publicar el commit

    git pull --rebase origin master
    # arreglar conflictos de merge en caso de suceder
    git push origin master

### comandos de todos los días

    git status
    git log
    git diff

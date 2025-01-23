## Ejercicio 1
### ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé `git reset HEAD~1`, porque con solo 2 commits podía volver al commit anterior.
### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé `git reflog` para ver el identificador del commit que había deshecho y `git reset --hard 28978fc` para llevar el puntero a dicho commit.
###  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque los cambios en la rama `styled` no sobreescriben el contenido en el estado en el que se encuentra en `main`.
### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, porque hay diferencias en el formato del texto cuando se actualizó el fichero en la rama `styled` y cuando se ha modificado en la rama `htmlify`
### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque en la resolución del conflicto anterior se dejó el contenido del fichero tal y como estaba en la rama `styled`, por lo que no sobreescribe el contenido en la rama `main`.
### ¿Qué comando o comandos utilizaste en el paso 25?
Utilicé `git log --graph --decorate --oneline`
###  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No, porque no hay un commit en la rama `main` que permita al merge cambiar su puntero y sería necesario generar un commit de merge para combinar ambas ramas.
### ¿Qué comando o comandos utilizaste en el paso 27?
Utilicé `git reflog` para ver el identificador del merge que había deshecho y `git reset --hard ef70252` para llevar el puntero a dicho commit.
### ¿Qué comando o comandos utilizaste en el paso 28?
Utilicé `git restore git-nuestro.md`
### ¿Qué comando o comandos utilizaste en el paso 29?
Utilicé `git branch -D title`
### ¿Qué comando o comandos utilizaste en el paso 30?
Utilicé `git reflog` para ver el identificador del merge que había deshecho y `git reset --hard 535f3a5` para llevar el puntero a dicho commit.
### ¿Qué comando o comandos usaste en el paso 32?
Utilicé `git reflog` para ver el identificador del primer commit y `git checkout 4855086f` para llevar el puntero a dicho commit.
### ¿Qué comando o comandos usaste en el punto 33?
Utilicé `git reflog` para ver el identificador del último commit y `git checkout 535f5a5f` para llevar el puntero a dicho commit.
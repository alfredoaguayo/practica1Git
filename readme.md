# Práctica del curso de git, gitHub y Sourcetree.


## Ejercicio 1.

* - ¿Qué comando utilizaste en el paso 11? ¿Por qué? *
El comando "git chekout master" para regresar directamente al commit que requería.
Emplee este comando para saltar de un solo paso al commit requerido. De usar "git reset --hard HEAD~1" regreso al estado anterior perdienod los cambios realizados, pero me es más práctico mo>

* - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? *
El comando "git checkout styled". de hacer un commit, crearía un punto de referencia pero al no tener cambios, no se requiere hacerlo.

* - El merge del paso 13 ¿Causó algún conflicto? ¿Por qué? *
No causó ningún conflicto.
Se trata de un merge fast forward ya que al ser commit en lista, los cambios se toman sólo como edición sencilla del contenido.

* - El merge del paso 19 ¿Causó algún conflicto? ¿Por qué? *
Sí hubo conflicto.
Se trata de dos commit con diferencia en el contenido del archivo con el mismo nombre en las mismas líneas. En este caso, la diferencia son las etiquetas MD y HTML en las mismas palabras.

* - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? *
No causó ningún conflicto.
A pesar de ser dos commit con diferencias en el contenido de las líneas del archivo git-nuestro.md, sólo se trata de agregar o eliminar un dato, no de definir entre dos datos diferentes.

* - ¿Qué comando o comandos utilizaste en el paso 25? *
El comando git graph.
Desde la clase definí un Alias en la configuración de git bash, con el comando git config --global alias.graph "log --graph --pretty=oneline".

* - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? *
Sí, pordría ser un fast forward.
En el paso anterior se hizo un merge desde Master y se creo la rama title, lo que quiere decir que master es padre directo de title y eso lo convierte en un commit de lista.

* - ¿Qué comando o comandos utilizaste en el paso 27? *
El comando "git reset HEAD~1"
Regrespe al commit anterior, y quedaron los cambios en el staging area.

* - ¿Qué comando o comandos utilizaste en el paso 28? *
El comando "git restore git-nuestro.md".

* - ¿Qué comando o comandos utilizaste en el paso 29? *
El comando "git branch -D title".

* - ¿Qué comando o comandos utilizaste en el paso 30? *
El comando "git reflog" para conocer los HASH de los commit realizados.
El comando "git chechout + (HASH del merge realizado)" para restaurar el merge.


* - ¿Qué comando o comandos usaste en el paso 32? *
El comando "git reflog" para conocer el historial de commit realizados y sus HASH.
El comando "git chechout + (HASH del commit marcado como initial)" cuando se creó el poema.

* - ¿Qué comando o comandos usaste en el punto 33? *
El comando "git reflog" para conocer el historial de commit realizados y sus HASH.
El comando "git chechout + (HASH del commit marcado con el comentario de la inclusión del título)".

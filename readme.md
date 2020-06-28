# Ejercicio 1

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1`

El comando reset permite posicionarse en cualquier otro commit, hard lo hace de forma que restaura el working copy, perdiendo lo que se tenía y HEAD~1 indica que es el commit anterior

-------

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog`

`git reset --hard 77b533b`

Con reflog identifico el SHA del commit y de igual forma que antes, utilizo reset hard para llegar a él actualizando el working copy

-------

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causa ningún conflicto. Indica que está actualizado, ya que la rama que se intenta mergear es la de un commit padre, y por tanto, no hay nada que ya sea alcanzable desde la propia rama.
  
-------

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si que causa conflictos, porque el mismo archivo ha sido modificado en la misma línea en dos ramas distintas.

-------

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causa conflicto, porque el merge que realiza es fast forward.

-------

**¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph --pretty=oneline`

-------

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, porque se tendría acceso a ambos commits desde donde realizo el merge. De hecho se fuerza que sea no fast forward, ya que por defecto lo hace fast forward, y en este caso podría.

-------

**¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

-------

**¿Qué comando o comandos utilizaste en el paso 28?**

`git restore git-nuestro.md`

-------

**¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

-------

**¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`

`git reset --hard 45aee93`

-------

**¿Qué comando o comandos usaste en el paso 32?**

`git reflog`

`git reset --hard fe3b4dd`

-------

**¿Qué comando o comandos usaste en el punto 33?**

`git reflog`

`git reset --hard 45aee93`

-------

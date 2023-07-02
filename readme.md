- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
**Comando:**git reset --hard HEAD~1
**Explicación** 
*git reset: Este comando se utiliza para mover la rama actual y el puntero HEAD a un commit específico en el historial del repositorio.
--hard: Esta opción indica que se realizará un restablecimiento "duro", lo que significa que todos los cambios en el árbol de trabajo (working tree) y en el área de preparación (staging area) se descartarán por completo. Cuidado, esta opción es destructiva y puede eliminar permanentemente los cambios no guardados.
HEAD~1: Especifica el commit al que se desea retroceder. En este caso, HEAD~1 se refiere al commit inmediatamente anterior al commit actual al que está apuntando el puntero HEAD.
En resumen, git reset --hard HEAD~1 deshará el último commit, moviendo la rama y el puntero HEAD al commit anterior y descartando todos los cambios realizados en ese último commit. Ten en cuenta que esta acción es permanente y no se puede deshacer fácilmente una vez realizada. Por lo tanto, es importante asegurarse de que se desea descartar completamente los cambios realizados en el commit anterior.*

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
**Comandos:**
git reflog
git cherry-pick ec4d435
**explicacion:*con ref log encontramos el id necesario. Cuando ejecutamosGit aplica los cambios realizados en los commits seleccionados al punto actual en el historial del repositorio. Esto significa que los cambios introducidos por los commits seleccionados se aplicarán en la rama actual. *

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?sí por que había cambios realizados no añadidos 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?sípor que había cambios realizados no añadidos 

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?No, resolví el conflicto en el paso anterior

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --oneline --all


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?Sí pero mejor no ffparapreservar el historial claro y detallado de las fusiones, aislar los cambios relacionados con la fusión en commits 

- ¿Qué comando o comandos utilizaste en el paso 27?
git log
git reset --hard 23590303f26617cb2c93f73148cb1bb040a194cb

- ¿Qué comando o comandos utilizaste en el paso 28?

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -d title

- ¿Qué comando o comandos utilizaste en el paso 30?

- ¿Qué comando o comandos usaste en el paso 32?
git log para obtener el id
git reset --hard ec4d435

- ¿Qué comando o comandos usaste en el punto 33?
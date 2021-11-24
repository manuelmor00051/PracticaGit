- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    git reset --hard HEAD ~1 utilizamos este porque es el que hace que todo quede como estaba antes del ultimo commit, a diferencia de git reset HEAD~1 que mantiene lo que hay en el working copy
    
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    git reflog para coger la referencia del ultimo commit, ya que no tengo acceso a el y posteriormente git reset --hard + referencia último commit
    
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    No me crea ningún conflicto, ya que aparece un mensaje diciendo que ya esta actualizado.
    
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    Si causa conflicto , ya que hemos modificado el archivo en las mismas líneas en dos ramas diferentes
    
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    No causa conflicto ya que el archivo en la rama master no ha sido modificado.
    
- ¿Qué comando o comandos utilizaste en el paso 25?
    git log --graph que da mas detalle, aunque también de puede utilizar git log --graph --decorate --pretty=oneline que lo muestra mas resumido
    
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    Si podría ser ya que estaban alineados
    
- ¿Qué comando o comandos utilizaste en el paso 27?
    Git log para coger la referencia del commit de antes de hacer el merge y git resert + referecia
    
- ¿Qué comando o comandos utilizaste en el paso 28?
    git restore git-nuestro.md
    
- ¿Qué comando o comandos utilizaste en el paso 29?
    git branch -D title
    
- ¿Qué comando o comandos utilizaste en el paso 30?
    git reflog para tomar la referencia del commit donde se creo el titulo y la referencia del commit del merge de master con title.
    Luego git checkout + referecia creacion titulo para moverme a ese commit y volver a crear la rama con git branch title. 
    Finalmente hago git checkout master para volver a master y posteriorment git reset + referencia del commit del merge con title
    
- ¿Qué comando o comandos usaste en el paso 32?
    git branch -D + nombreRama en cada una de las ramas, menos en master que no puedo ya que me encuentro en ella
    
- ¿Qué comando o comandos usaste en el punto 33?
    git log para obtener la referencia del commit inicial y luego git reset + referencia

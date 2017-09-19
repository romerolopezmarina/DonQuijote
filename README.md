# Práctica GIT

### Romero López, Marina 

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1`

PCon el comando *git reset* muevo el indicador HEAD al paso anterior (Indicado con ~1). Al indicar --hard en el comando estoy especificando que se pierdan los cambios que se han hecho en el *working copy* 

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
 
`git reflog`
`git reset --hard 083a15 (número del commit)`

Con el primer comando puedo visualizar el número del commit al que quiero volver, lo copio, y después lo pego en el egundo comando para volver al paso número 11.

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No surge ningún conflicto ya que al contener la rama styled un commit en línea directa con la rama master se trata de un merge Fast Foward.

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Surge un conflicto debido a que hemos modificado el archivo en dos ramas distintas de manera que al hacer el merge nos sale un cuadro de diálogo donde especificamos el merge que vamos a hacer. Al salir del cuadro de diálogo se efectuará el merge indicado. 

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No ha causado ningún conflicto ya que ha sido un merge de tipo fast forward. 

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph`

He empleado este comando ya que en mi versión de git `git graph` no lo reconocía.
 
**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí que podría ser fast-forward ya que ambas ramas se conforman siguiendo una línea.

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

Para deshacer el merge sin perder cambios en el working copy empleé este comando que ya que no contiene el parámetro --hard.

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD` 

Para descartar los cambios empleo este comando ya que no vuelvo ningún paso atrás pero deshace los cambios de donde estamos.

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title"

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`
`git reset --hard 092a21`

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog`
`git reset --hard 210a72`

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git tag -a "nombre del tag" 092a21`


 

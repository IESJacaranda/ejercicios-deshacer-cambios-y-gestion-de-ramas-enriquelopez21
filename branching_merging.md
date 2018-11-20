# Branching and merging

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**branch_time**_
  **Ejecutamos mkdir branch_time**
2. Cámbiate a dicho directorio.
  **Ejecutamos el comando cd brach_time**
3. Inicializa un repositorio vacío.
  **Ejecutamos el comando git init**
4. Crea un fichero llamado first.txt después añade y haz commit con un solo comando.
  **Ejecutamos el comando touch first.txt && git add && git commit -m 'Hecho"**
5. Crea una nueva rama llamada _**amazing_feature**_.
   **Ejecutamos el comando git checkout -b amazing_feature**
6. Cámbiate a dicha rama.
  **Se cambia automaticamente una vez realizado el anterior comando**
7. Crea un nuevo fichero llamado best.txt con el contenido "this is the best file".
  **Ejecutamos el comando nano best.txt e introducimos this is the best file**
8. Añade el fichero al área de preparación.
  **Ejecutamos el comando git add best.txt**
9. Haz commit del fichero con el mensaje "added best.txt".
    **Ejecutamos el comando git commit -m "added best.txt**
10. Vuelve a la rama master.
   **Ejecutamos el comando git checkout master**
11. Une (merge) la rama feature a la rama master.
  **Ejecutamos el comando git merge amazing_feature**
12. Borra la rama feature.
   **Ejecutamos el comando git branch -d amazing_feature**
13. Crea la rama _**conflict**_ y cámbiate a ella con un solo comando.
   **Ejecutamos el comando git checkout -b conflict**
14. Crea tu propio conflicto al mezclar dos ramas! Para ello trabaja en el mismo fichero en dos ramas separadas y une (merge) las dos ramas. Arregla los conflictos y finaliza la unión. En el mundo real nunca intentarás crear un conflicto en una unión de ramas, pero es importante que no te sientas intimidado por los conflictos al realizar una unión de ramas y ser capaz de arreglarlos con confianza.
**Creamos un archivo first en la rama master y le añadimos cualquier contenido le hacemos el git add y despues el git commit , una vez creado, creamos la otra rama y creamos el mismo archivo de antes pero con otro contenido y le hacemos un git add y un git commit al archivo. Una vez que hemos hecho esto le hacemos un git merge y la rama con la que quiero mezclar.**

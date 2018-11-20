# Ejercicios Checkout y Reset

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**destruction**_
   **Ejecutamos el comando mkdir destruction**
2. Cámbiate a dicho directorio
   **Ejecutamos el comando cd destruction**
3. Inicializa un repositorio git vacío.
   **Ejecutamos el comando git init**
4. Crea un fichero llamado **stage_me.txt**
    **Ejecutamos el comando nano stage_me.txt**
5. Añade el fichero stage_me.txt al área de preparación (staging area).
    **Ejecutamos el comando git add stage_me.txt**
6. Mueve el fichero stage.txt del área de preparación al directorio de trabajo.
    **Ejecutamos el comando mv stage.txt /home/estudiante/destruction**
7. Añade el fichero stage_me.txt al área de preparación.
    **Ejecutamos el comando git add stage_me.txt**
8. Elimina el fichero stage_me.txt del área de preparación y del directorio de trabajo.
    **Ejecutamos el comando rm stage_me.txt**
9. Crea un fichero nuevo llamado commit_me.txt.
    **Ejecutamos el comando commit_me.txt**
10. Añade el fichero commit_me.txt al área de preparación.
    **Ejecutamos el comando git add commit_me**
11. Haz un commit con el mensaje "adding commit_me.txt"
    **Ejecutamos el comando commit -m "adding commit_me.txt"**
12. Crea otro fichero llamado second.txt.
    **Ejecutamos el comando nano second.txt**
13. Añade el fichero second.txt al área de preparación.
    **Ejecutamos el comando nano second.txt**
14. Haz commit con el mensaje "adding second.txt".
    **Ejecutamos el comando git commit -m "adding second.txt"**
15. Muestra los commits previos uno por línea mostrando el identificador únicao (SHA) y el comentario asociado.
     **Ejecutamos el comando git log --oneline**
Para realizar los siguientes ejercicios debes investigar sobre los parámetros --soft --mixed y --hard del comando git reset.

16. Utilizando git reset, deshaz el commit previo y devuelve los cambios al directorio de trabajo.
     **Ejecutamos el comando git reset y el log del commit**

17. Añade el fichero second.txt otra vez al área de preparación.
     **Ejecutamos el comando git add second.txt**
18. Haz un commit con el mensaje "Trying to commit again".
 **Ejecutamos comando git commit -m "Trying to commit again"**
19. Utilizando git reset deshaz el commit previo y devuelve los cambios al área de preparación.
    **Ejecutamos el comando git reset <log del commit>**
20. Haz commit con el mensaje "Trying to commit again and again".
    **Ejecutamos el comando git commit -m "Trying to commit again and again"**
21. Utilizando git reset deshaz el commit previo para que ningún cambio aparezca en el directorio de trabajo.
     **git reset <log del commit anterior>**
22. ¡Date una palmadita en la espalda! ¡Acabas de realizar un flujo de trabajo bastante complejo de git!
    :)

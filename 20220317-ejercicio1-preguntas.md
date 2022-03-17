
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas:

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: git config --global user.email "daniellopezmartinez91@gmail.com"

2. ¿Qué es un Pull Request?
Respuesta: Los pull requests son la forma de contribuir a un proyecto grupal o de código abierto.

3. ¿Para qué sirve HEAD en GIT?
Respuesta: HEAD apunta a la rama donde estemos, y cada vez que cambiamos de rama HEAD cambia su valor.

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: confirmado (committed), modificado (modified), y preparado (staged).

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: Utiliza un hash SHA-1 pero se puede utilizar los primeros 6 digitos.

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: git log --oneline -all
            git checkout <hash>

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: La rama a fusionar y la rama actual modifican la misma parte en un archivo en particular y git no puede decidir cuál versión elegir.

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: rm -rf .git

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git remote add origin <URL>

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta:

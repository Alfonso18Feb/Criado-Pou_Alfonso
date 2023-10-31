#AlfonsoCriado-Pou Castellanos 
##https://github.com/Alfonso18Feb/Criado-Pou_Alfonso

1º Explica que es un “Pull Request” en Github. (1 pts)
**Un Pull request es cuando una persona quiere subir los cambios echos en su repositorio remoto a otro repositorio local o de otra persona trabajando en GitHub**
2º ¿Qué es un conflicto de fusión (merge conflict) en Git? Explica como resolverías este conflicto. (1 pts)
**El conflicto de fusion en Git es cuando dos ramas differentes se integran y porque tienen differente codigo entran en conflicto**.***Esto se puede resolver editando la rama mergeada para cabiar los errores al integrarlas.***
3º Imaginemos que tenemos dos ramas, la principal llamada “main” y la rama “examen_parcial”. ¿Qué procedimiento se debería seguir para fusionar (merge) ambas ramas? (0.5 pts)
**Primero se tien que utilizar el comando ***git branch*** para ver en que rama estamos**
**Si estamos en la rama examen_parcial se utiliza el comando ***git checkout main*** para cambiar a la rama main**
**Por ultimo en la rama main escribimos en git bash el comando ***git merge examen_parcial*** para hacer merge a las dos ramas**
4º Has realizado un commit, pero luego descubres un error importante en los cambios que has incluido. Necesitas revertir este último commit para regresar tu proyecto al estado anterior, pero deseas mantener los cambios realizados en tu área de trabajo. Explica el comando de Git que utilizarías para llevar a cabo esta acción. (0.5 pts)
**El comando utilizado para revertir los cambios de este commit seria el comando ***git reverse <la id del commit que quieres ir>*** despues de escribir este comando puedes hacer estos cambios manteniendo los cambios que deseas en tu area de trabajo**  

5º ¿Cómo se realiza un fork de un repositorio en GitHub y para qué se utiliza comúnmente esta acción? (1 pts).
**Para realizar un fork es simple tienes que clicar el boton Fork en el repositorio que quieres copiar. Luego este repositorio se clonaria en la cuenta tuya de GitHub y guardas cambios**.***El fork se utiliza muchas veces cuando quieres añadir algo a un repositorio de otra persona (ej: el profesor). Esto te permite clonar su repositorio en tu cuenta en github y desde hay puedes hacer todos los cambios que quieras hasta que quierass volver a poner lo editado a el github del repositorio de el individuo (profesor). Esto se hace haciendo un Pull Request.*** 
6º Te encuentras trabajando en un proyecto y necesitas llegar a un archivo específico llamado "archivo.txt". Este archivo está ubicado dentro de una estructura de directorios en tu sistema.

a)      Desde tu posición actual en el directorio raíz (home) de tu proyecto, ¿cómo llegarías al directorio que contiene "archivo.txt", el cual está dentro del directorio "UAX", el cual a su vez está dentro del directorio "Universidad", que se encuentra dentro del directorio "Nombre_del_alumno (raíz)"? Proporciona el comando exacto que usarías y especifica qué tipo de ruta es. (0.5 pts)
**Para llegar al repositorio que contiene el archivo.txt desde ***la raiz Alfonso*****.**Tenemos que utilizar el comando ***cd Universidad/UAX*****
***Esto seria una ruta absoluta ya que llegamos al repositorio que contiene el archivo.txt paasando por la raiz y no es directo ya que tenemos que pasar primero por el repositorio Universidad***
b)       Si te encuentras actualmente dentro del directorio "Universidad", ¿cómo accederías al directorio que contiene "archivo.txt"? Proporciona el comando exacto que usarías y especifica qué tipo de ruta es. (0.5 pts)
**Para acceder al repositorio con el archivo.txt tendria que utilizar el comando ***cd UAX*****
***Esto seria una ruta relativa ya que no pasa por el directorio raiz y llegamos directamente al repositorio con el archivo.txt***
7º Te han asignado la tarea de trabajar en un proyecto de código abierto alojado en GitHub. Como nuevo colaborador, se espera que sigas las mejores prácticas para el manejo del código fuente utilizando Git. Que comandos de Git utilizaría para las siguientes tareas: (2 pts) (0.2 cada pregunta):

***Las respestas correctas estan en negrita como este texto***



1) Clonar el Repositorio:

a) git pull

***b) git clone***

c) git fetch

d) git branch

2) Crear una Nueva Rama:

***a) git branch***

b) git checkout

c) git merge

d) git add

3) Cambiar entre Ramas:

a) git merge

b) git branch

***c) git checkout***

d) git pull

4) Añadir Cambios al Área de Preparación (Staging):

a) git commit

***b) git add***

c) git push

d) git checkout

5) Realizar un Commit:

a) git add

***b) git commit***

c) git push

d) git merge

6) Publicar la Rama en el Repositorio Remoto:

a) git pull

***b) git push***

c) git merge

d) git branch

7) Actualizar tu Rama Local con Cambios del Remoto:

a) git push

b) git branch

***c) git pull***

d) git checkout

8) Fusionar Cambios de otra Rama a tu Rama Actual:

a) git checkout

b) git branch

c) git pull

***d) git merge***

9) Revertir Cambios Locales:

***a) git reset --hard***

b) git pull

c) git merge

d) git branch

10) Revisar el Historial de Commits:

a) git commit

b) git push

***c) git log***

d) git add


8º Eres parte de un equipo de desarrollo trabajando en un proyecto de software matemático. La estructura de ramas de tu proyecto en Git se ve de la siguiente manera:

·         main: La rama principal donde el código es estable y listo para producción.

·         develop: Una rama de desarrollo donde se integran las nuevas características antes de pasar a main.

·         matemáticas: Una rama donde tú y tu equipo están trabajando en resolver un problema.

·         Diseño UX: Una rama donde el equipo de diseño trabaja en desarrollar la vista de las integraciones por parte del equipo de matemáticas.

Durante el desarrollo, tu equipo ha completado una serie de algoritmos importantes en la rama matemáticas y está listo para integrarlos en la rama develop. Simultáneamente, el equipo de diseño ha hecho cambios significativos en la rama diseño-UX, que también deben ser integrados en develop.

Tu tarea es coordinar la integración de estas dos ramas en develop asegurándote de que se manejen adecuadamente los conflictos, se mantenga la calidad del código y se respete la funcionalidad tanto del lado matemático como del diseño UX.

Describe detalladamente los pasos y consideraciones que tomarías para lograr esta tarea, incluyendo cómo manejarías los posibles conflictos de fusión y cómo asegurarías que la integración final en develop sea estable y funcional. (2 pts)

9º Pregunta práctica del módulo 3: Repositorios local y remoto

Recientemente, has completado una práctica en la que creaste un repositorio tanto local como remoto para una calculadora web sencilla. La práctica implicaba varios pasos clave, incluyendo la creación del repositorio, la adición y el registro de cambios, y finalmente la subida del repositorio local al remoto en GitHub.


Considerando los pasos realizados durante la práctica, responde la siguiente pregunta:

¿Cuál de las siguientes afirmaciones describe mejor el proceso que seguiste para añadir el botón de "x^4" a tu calculadora web y subir los cambios al repositorio remoto? (1 pts)

Opciones:

A) Editaste directamente el archivo "index.html" en GitHub y creaste un nuevo commit en la rama principal (master).

B) Clonaste el repositorio remoto, hiciste cambios en el archivo "index.html" en una rama secundaria, y luego hiciste un pull request a la rama principal (master).

C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).

D) Creaste un nuevo archivo para el botón "x^4", lo añadiste al índice en tu repositorio local, pero no creaste un commit ni subiste los cambios al repositorio remoto.

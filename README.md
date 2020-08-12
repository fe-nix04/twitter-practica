# twitter-practica

Acerca Git

0. Git Flow.
->Para evitar desordenes, me dice de donde saco una rama y cuando sacarla.
->En un proyecto se tiene una rama principal (estable). Esto es lo que se entrega al cliente.
->Se tiene una rama de desarrollo, que también debería ser estable para correr allí las pruebas y si pasan, llevarlas a master. La idea es no trabajar en cambios directos sobre la rama de desarrollo.
->De la rama de desarrollo saco otra para realizar mis actividades (features). Es decir, saco una rama para hacer una tarea o historia de usuario.
->Un caso de uso de lo anterior: se tiene un backend y frontend. Cada uno de estos tiene distintos componentes. En el equipo de trabajo va a haber una o varias personas trabajando sobre un componente X. Esto quiere decir que habría una rama que se saca de develop y sobre esta trabajarian uno o muchos.

1. Conceptos

Remoto: Servidor Principal (puedo tener varios)
Commit: Cambios que me interesa guardar
Branch: Copia del código, que se puede modificar independientemente de las otras ramas
Merge: Combinar una rama con otra
.gitignore: Archivo que permite ignorar cosas

2. Flujo de trabajo
Realizar cambios -> Agrego los cambios -> Commit -> Push

3. Comandos
●	git status
●	git log
●	git add <file>
●	git commit -m “Mensaje del commit”
●	git branch <nombre de la rama> (Crea una rama)
●	git checkout <nombre de la rama> (Cambiarse de rama)
●	git merge <rama a combinar> -m "mensaje"
●	git push
●	git pull

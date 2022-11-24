#Respuestas a l ejercicio1 de git

##¿Qué comando utilizaste en el paso 11? ¿Por qué?
	He utilizado el comando git reset --hard HEAD~1 porque me dice que lo haga perdiendo los cambios realizados en el working copy,
	éste comando hace un reset y un restore a la vez.

##¿Qué comando o comandos utilizaste en el paso 12?¿Por qué?
	He utilizado el comando git reflog para ver el id del commit al que quiero volver, luego he utilizado el comando git reset 5a57d40 para volver a dicho commit
	y finalmente un git restore al archivo

##¿El merge del paso 13 causó algún conflicto? ¿Por qué?
	No causo ningún conflicto, already up to date.

##¿El merge del paso 19 causó algún conflicto? ¿Por qué?
	Sí causo conflicto porque en el documento habia dos versiones y había que resolverlo editándolo y quedandose con la version deseada, luego hacer un git add.

##¿El merge del paso 21 causó algún conflicto?
	Ningún conflicto

##¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph

##El merge del paso 26 podria ser fast forward? 
	No , porque perderiamos todos los cambios

##¿Qué comando o comandos utilizaste en el paso 27? 
	git reset "Nombre del commit"

##¿Qué comando o comandos utilizaste en el paso 28?
	git restore git-nuestro.md

##¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title

##¿Qué comando o comandos utilizaste en el paso 30?
	git reflog, git reset 6fa5eeb

##¿Qué comando o comandos utilizaste en el paso 32?
	git reflog para ver el id del commit al que quiero ir, git reset 70cdadb / git restore git-nuestro.md

##¿Qué comando o comandos utilizaste en el paso 33?
	git reflog para ver el id del commit al que quiero volver, git reset 003d4c2 / git restore git-nuestro.md

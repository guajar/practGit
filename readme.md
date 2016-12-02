# Readme - Práctica Git

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	
	"git reset --hard HEAD~1", porque con --hard cambio de WC, perdiendo los cambios realizados y HEAD~1 para volver al commit padre.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	
	"git reflog" para ver el commit donde hicimos los cambios desde *STYLED*
	"git reset --hard <id commit>", como anteriormente utilizando --hard, pero añadimos el id del commit donde queremos ir.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	
	"Already up to date", porque desde *STYLED* ya tenemos acceso a los commits de master, por lo tanto no hace falta hacer un merge.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	
	Sí, causó conflictos, porque en las mismas líneas había dos versiones y Git te da a elegir cual eliges.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	
	No, hizo un merge Fast Forward automáticamente, ya que forman una lista, con lo que master se situal a la altura donde estaba el commit de Styled.

- ¿Qué comando o comandos utilizaste en el paso 25?
	
	"git graph", pero porque tengo configurado el alias de Git para graph
	"git graph --decorate --pretty=oneline" sino recuerdo mal.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	
	Sí, porque estaríamos en el mismo caso anterior, formaban una lista y tendría acceso a todos los commits.

- ¿Qué comando o comandos utilizaste en el paso 27?
	
	"git reflog" y "git reset HEAD@{2}", no uso --hard para no perder los cambios del *WC* y HEAD@{2}, para ir al commit anterior del último comando.

- ¿Qué comando o comandos utilizaste en el paso 28?
	
	"git checkout -- git-nuestro.md" 

- ¿Qué comando o comandos utilizaste en el paso 29?
	
	"git branch -D title"

- ¿Qué comando o comandos utilizaste en el paso 30?
	
	"git reflog" y "git checkout <id commit>", voy al commit donde hice el merge, pero me encuentro en detached HEAD. Para volver a master y traerla al commit del merge...
	"git checkout master" para ir donde esta master
	"git reset <id commit>" para llevar la rama master al commit que hice el merge. Y ya tendríamos el merge hecho de nuevo.

- ¿Qué comando o comandos usaste en el paso 32?
	
	"git log" para ver el id del commit inicial
	"git checkout <id commit>" para ir al commit inicial

- ¿Qué comando o comandos usaste en el punto 33?
	
	"git checkout master", como no moví la rama puedo vover de manera fácil con "checkout".

*José Antonio Maldonado*
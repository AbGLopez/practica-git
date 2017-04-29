# Ejercicio 1
- ***¿Qué comando utilizaste en el paso 11? ¿Por qué?***
	 ```git reset --hard HEAD~1``` Con ```--hard``` indicamos que se descarten los cambios y no se queden en mi workingCopy. Con ```HEAD~1``` indicamos que sea el anterior commit.
- ***¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?***
	Para ver el localizador ```git reflog``` y tras saber el Hash correspondiente ```git reset 'miHash'```
- ***El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?***
	No, porque las ramas forman una lista y styled ya tiene los commits de la rama master
- ***El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?***
	Sí, porque ambos modificaron las mismas lineas del mismo fichero.
- ***El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?***
	No, con este merge fast-forward la referencia de la rama master se mueve a styled.
- ***¿Qué comando o comandos utilizaste en el paso 25?***
	```git log --graph --decorate```
- ***El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?***
	No porque necesitamos que las ramas del grafo sean una lista, y en este momento hay mas ramas y  la refencia de master esta junto la rama styled.
- ***¿Qué comando o comandos utilizaste en el paso 27?***
	```git reset HEAD-1```
- ***¿Qué comando o comandos utilizaste en el paso 28?***
	```git checkout .``` ó ```git checkout git-nuestro.git```
- ***¿Qué comando o comandos utilizaste en el paso 29?***
	```git branch -D title```
- ***¿Qué comando o comandos utilizaste en el paso 30?***
	 ```git reset --hard 'miHash'```
- ***¿Qué comando o comandos usaste en el paso 32?***
	```git reflog``` y ```git reset --hard 'miHashInicial'```
- ***¿Qué comando o comandos usaste en el punto 33?***
	```git reflog``` y ```git reset --hard 'miHash'```

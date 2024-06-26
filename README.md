## Configuración Básica

**Configurar Nombre que salen en los commits**
```
git config --global user.name "GabrielBaezB"
```
**Configurar Email**
```
git config --global user.email youremail@****.com
```
## Iniciando repositorio

**Iniciamos GIT en la carpeta donde esta el proyecto**
```
git init
```
**Clonamos el repositorio de github**
```
git clone <url>
```
**Añadimos todos los archivos para el commit**
```
git add .
```
**Vemos el estado del de los archivos para el commit**
```
git status
```
**Hacemos el primer commit**
```
git commit -m "Texto que identifique por que se hizo el commit"
```
**Subimos al repositorio**
```
git push origin master
```

**GIT ADD**
```
git add .				<!-- Añadimos todos los archivos para el commit -->
git add <archivo>			<!-- Añadimos el archivo para el commit -->
git add --all				<!-- Añadimos todos los archivos para el commit omitiendo los nuevos -->
git add *.txt				<!-- Añadimos todos los archivos con la extensión especificada -->
git add docs/*.txt			<!-- Añadimos todos los archivos dentro de un directorio y de una extensión especifica -->
git add docs/				<!-- Añadimos todos los archivos dentro de un directorios -->
```
**GIT COMMIT**
```
git commit -m "Texto que identifique por que se hizo el commit"			<!-- Cargar en el HEAD los cambios realizados -->
git commit -a -m "Texto que identifique por que se hizo el commit"		<!-- Agregar y Cargar en el HEAD los cambios realizado -->
git commit -a 									<!-- De haber conflictos los muestra -->
git commit --amend -m "Texto que identifique por que se hizo el commit"		<!-- Agregar al ultimo commit, este no se muestra como un nuevo commit en los logs. Se puede especificar un nuevo mensaje -->
```
**GIT PUSH**
```
git push <origien> <branch>		<!-- Subimos al repositorio -->
git push --tags				<!-- Subimos un tag -->
```
**GIT DIFF**
```
git diff				<!-- Muestra los cambios realizados a un archivo -->
git diff --staged
```
**GIT HEAD**
```
git reset HEAD <archivo>	<!-- Saca un archivo del commit -->
git reset --soft HEAD^		<!-- Devuelve el ultimo commit que se hizo y pone los cambios en staging -->
git reset --hard HEAD^ 		<!-- Devuelve el ultimo commit y todos los cambios -->
git reset --hard HEAD^^		<!-- Devuelve los 2 ultimo commit y todos los cambios -->
git log
git reset --hard <commit_sha>   <!-- Rollback merge/commit -->
```
**GIT REMOTE**
```
git remote add origin <url>       <!-- Agregar repositorio remoto -->
git remote set-url origin <url>   <!-- Cambiar de remote -->
git remote rm <name/origin>       <!-- Remover repositorio -->
git remote -v                     <!-- Muestra lista repositorios -->
git remote show origin            <!-- Muestra los branches remotos -->
git remote prune origin           <!-- Limpiar todos los branches eliminados --> 
```

**GIT BRANCH**
```
git branch <nameBranch>         <!-- Crea un branch -->
git branch                      <!-- Lista los branches -->
git branch -d <nameBranch>      <!-- Comando -d elimina el branch y lo une al master -->
git branch -D <nameBranch>      <!-- Elimina sin preguntar -->
```


<!--
**GabrielBaezB/GabrielBaezB** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

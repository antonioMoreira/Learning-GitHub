README
============================================================
## » Main Branch - MASTER

We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line

	$ echo "# Learning-GitHub" >> README.md
	$ git init
	$ git add README.md
	$ git commit -m "first commit"
	$ git remote add origin https://github.com/antonioMoreira/Learning-GitHub.git
	$ git push -u origin master

…or push an existing repository from the command line

	$ git remote add origin https://github.com/antonioMoreira/Learning-GitHub.git
	$ git push -u origin master


```bash
	# Basic 1 
	antonio$antonio:~$ mkdir ~/NewProject
	antonio$antonio:~$ cd ~/NewProject
	antonio$antonio:~$ git init #cria um .git com as config default

	# Basic 2
	antonio$antonio:~$ git clone <https/ssh>
	antonio$antonio:~$ git add <files>
	antonio$antonio:~$ git commit -m "<message>"
	antonio$antonio:~$ git push
	antonio$antonio:~$ git pull	
	antonio$antonio:~$ git status
	antonio$antonio:~$ git log
	antonio$antonio:~$ git reset
		» antonio$antonio:~$ git reset --hard <commit> #ver antes no git log

	# Branching
	antonio$antonio:~$ git branch
	antonio$antonio:~$ git checkout
	antonio$antonio:~$ git merge

		#Exemple
		antonio$antonio:~$ git branch
		*	master # '*' indica que a branch atual é a master
		antonio$antonio:~$ git checkout -b <New_Branch> #cria uma nova branch
		antonio$antonio:~$ git checkout <New_Branch>
		antonio$antonio:~$ git branch
		*	<New_Branch> # '*' indica que a branch atual é <New_Branch>
			master
		antonio$antonio:~$ git commit -am "New_Branch is up"
		antonio$antonio:~$ git push --set-upstream origin <New_Branch>
		antonio$antonio:~$ git checkout master # volta para master após algumas modificação em <New_Branch>
		antonio$antonio:~$ git merge <New_Branch>
		antonio$antonio:~$ git checkout -D <New_Branch>

```

### Pull Requests on github.com/.../pulls

	Used to sugest changes from a branch to another, ie, you can use 'Pull Requests' to sugest some change from a secundary branch to the main branch.

### Sas - extension to CSS

### .gitignore
Used to ignore some files.

```bash
	antonio$antonio:~$ touch ./.gitignore
	antonio$antonio:~$ vim ./.gitignore

	#On VIM
	./toIngore/ #Ignora a pasta toIgnore 
	toIngore.txt #Igora o arquivo toIgnore.txt

```
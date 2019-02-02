README
============================================================
## New Branch

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
	# Basic
	antonio$antonio:~$ git clone <https/ssh>

	antonio$antonio:~$ git add <files>

	antonio$antonio:~$ git commit -m "<message>"

	antonio$antonio:~$ git push

	antonio$antonio:~$ git pull	

	antonio$antonio:~$ git status

	antonio$antonio:~$ git log

	antonio$antonio:~$ git reset
		» antonio$antonio:~$ git reset --hard <commit> #ver antes no git log

	# Brancing
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
		antonio$antonio:~$ git checkout master # volta para master após algumas modificação em <New_Branch>
		antonio$antonio:~$ git merge <New_Branch>
		antonio$antonio:~$ git checkout -D <New_Branch>

```

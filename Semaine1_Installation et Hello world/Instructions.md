# Visual Studio Code pour Windows note d'installation basé sur: 
+ https://code.visualstudio.com/docs/setup/windows & 
+ https://code.visualstudio.com/docs/python/python-tutorial

### 1.- Téléchargez Visual Studio Code pour windows : 
[Cliquer ici pour télécharger Visual Studio Code](https://go.microsoft.com/fwlink/?LinkID=534107)

### 2- Installation des Composants couramment utilisés : 
+ Git: Gestionnaire de code source: https://git-scm.com/download
+ Extension VS Code Python: https://marketplace.visualstudio.com/items?itemName=ms-python.python
+ Interpréteur Python 3: https://www.python.org/ftp/python/3.8.0/python-3.8.0.exe

### 3- Vérifiaction de l'installation de l'interpréteur Python
+ ouvrir une invite de commande: 
```console
cmd.exe
```
+ taper la commande: 
```shell
py -3 --version
```
+ Création d'un répertoire Hello: 
```shell
mkdir hello
```
+ déplacement dans le répertoire Hello: 
```shell
cd hello
```
+ lancement de visual studio code: 
```shell 
code .
```

### 4- Selectionner l'interpréteur Python dans visual studio code. 
+ Palette de commandes: <kbd>Ctrl</kbd>+<kbd>Maj</kbd>+<kbd>P</kbd>

![](https://code.visualstudio.com/assets/docs/python/environments/select-interpreters-command.png)

+ Choisir une ligne parmi les choix proposés.

![](https://code.visualstudio.com/assets/docs/python/environments/interpreters-list.png)

### 5- premier programme Hello.py
+ Nouveau fichier dans le répertoire hello: hello.py
+ puis taper dans le fichier hello.py: 
```python
	msg = "Hello World"
	print(msg)
```
+ Enregistrer le fichier <kbd>CTRL</kbd>+<kbd>S</kbd>
+ Exécuter le fichier Python dans le terminal dans le coin supérieur droit de l'éditeur
![Launch button image](https://code.visualstudio.com/assets/docs/python/tutorial/run-python-file-in-terminal-button.png)
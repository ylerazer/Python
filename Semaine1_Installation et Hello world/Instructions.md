# Visual Studio Code pour Windows note d'installation bas� sur: 
+ https://code.visualstudio.com/docs/setup/windows & 
+ https://code.visualstudio.com/docs/python/python-tutorial

### 1.- T�l�chargez Visual Studio Code pour windows : 
[Cliquer ici pour t�l�charger Visual Studio Code](https://go.microsoft.com/fwlink/?LinkID=534107)

### 2- Installation des Composants couramment utilis�s : 
+ Git: Gestionnaire de code source: https://git-scm.com/download
+ Extension VS Code Python: https://marketplace.visualstudio.com/items?itemName=ms-python.python
+ Interpr�teur Python 3: https://www.python.org/ftp/python/3.8.0/python-3.8.0.exe

### 3- V�rifiaction de l'installation de l'interpr�teur Python
+ ouvrir une invite de commande: 
```console
cmd.exe
```
+ taper la commande: 
```shell
py -3 --version
```
+ Cr�ation d'un r�pertoire Hello: 
```shell
mkdir hello
```
+ d�placement dans le r�pertoire Hello: 
```shell
cd hello
```
+ lancement de visual studio code: 
```shell 
code .
```

### 4- Selectionner l'interpr�teur Python dans visual studio code. 
+ Palette de commandes: <kbd>Ctrl</kbd>+<kbd>Maj</kbd>+<kbd>P</kbd>

![](https://code.visualstudio.com/assets/docs/python/environments/select-interpreters-command.png)

+ Choisir une ligne parmi les choix propos�s.

![](https://code.visualstudio.com/assets/docs/python/environments/interpreters-list.png)

### 5- premier programme Hello.py
+ Nouveau fichier dans le r�pertoire hello: hello.py
+ puis taper dans le fichier hello.py: 
```python
	msg = "Hello World"
	print(msg)
```
+ Enregistrer le fichier <kbd>CTRL</kbd>+<kbd>S</kbd>
+ Ex�cuter le fichier Python dans le terminal dans le coin sup�rieur droit de l'�diteur
![Launch button image](https://code.visualstudio.com/assets/docs/python/tutorial/run-python-file-in-terminal-button.png)
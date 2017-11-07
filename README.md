A generator of scrum cards for physical board.

Before use it, make sure you have access to the JIRA REST API of your choice.
Settings are saved in the localStorage. All you need is to enter the keys of JIRA you want to print.

* Cloner le repository git
* Se placer dans le projet et lancer la commande npm install
* Lancer la commande gulp build
* Toujours dans le même répertoire, ouvrir le fichier index.html dans chrome (ou autre navigateur, mais ça marche bien dans chrome)
* si chrome, installer l'extension Allow-Control-Allow-Origin (attention, l'installation de ce plugin chrome fait merder l'édition des fichiers google doc, sheet, et compagnie, et google agenda, mais j'ai pas d'autres solutions pour l'instant lol)
* Activer le partage cross origin : "Enable cross origin ressource sharing"
* Sur le générateur, aller dans paramètres (la petite molette)
* Renseigner les deux champs avec les valeurs suivantes :
premier champ : http://jira.photobox.com/rest/api/latest
deuxième champ : Level of effort
* Sur l'écran d'accueil, saisir un numéro de ticket et le tour est joué !

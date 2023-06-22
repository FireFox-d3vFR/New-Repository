# New-Repository
Petit test d'insertion de fichier un partir de VsCode ;)

Quelques petits tips pour utiliser Git (sur VScode Terminal):
Initialisation  |
  ~ git config  --global user.name "Votre nom"  <!-- Nom d'utilisateur git ou nom réel -->
  ~ git config --global user.email "votre-email@example.com" <!-- adresse mail associé à GitHub-->
  ~ git config --global core.editor "nom-de-votre-editeur" <!-- "code" pour Vscode par exemple -->
  ~ git config --global color.ui auto <!-- Facultatif: configurer la couleur de l'interface -->
  
PS : Pour vérifier si les champs ont bien  été remplis: il renvoie une nouvelle ligne de commande
sans erreurs. Vous avie la possibilé de renvoyer uniquement la commande **git config** [...] et il renvoie la  réponse.

Voici quelques commandes Git courantes pour vous aider à démarrer :

~ git init : Initialise un nouveau dépôt Git dans le répertoire courant.<br>
~ git clone <URL> : Clone un dépôt distant existant sur votre machine.<br>
~ git add <nom du fichier> : Ajoute un fichier spécifique à l'index pour préparer un commit.<br>
~ git commit -m "Message du commit" : Crée un nouveau commit avec les modifications en cours, en y associant un message descriptif.<br>
~ git push <remote> <branche> : Pousse les commits locaux vers un dépôt distant.<br>
~ git pull <remote> <branche> : Récupère les modifications depuis un dépôt distant et les fusionne avec votre branche locale.<br>
~ git status : Affiche l'état actuel du dépôt, montrant les fichiers modifiés, ajoutés ou supprimés.<br>
~ git log : Affiche l'historique des commits du dépôt.

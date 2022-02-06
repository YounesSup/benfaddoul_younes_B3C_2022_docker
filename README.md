# Projet Docker

### Première étape :
Nous allons tout d'abord installer Docker Desktop à partir de ce lien : https://www.docker.com/products/docker-desktop.<br>
Par la suite si vous voulez vous pouvez créer un compte Docker Hub à partir de ce lien : https://hub.docker.com/signup.
<br>
<br>

### Deuxième étape :
Avant de commencer la pratique nous allons vérifier que nous possédons bien Docker, pour cela nous allons taper la commande docker --help, si nous avons tout une liste de commande qui s'affiche cela veut dire que nous avons bien docker d'installer sur notre PC.
<br>
<br>

### Troisième étape :
Après avoir récupérer le projet API REST qui comporte une partie backend (API rest) et une partie frontend (reactJS), nous allons entrer dans le dossier qui comporte ses dossiers via le terminal de commande, pour ma part j'ai entrer cd C:\Users\youne\benfaddoul_younes_B3C_2022_docker.
<br>
<br>

### Quatrième étape :
Une fois les fichiers DockerFile (pour builder notre image) et Docker-compose (démarrer les containers/services) créer, nous allons lancer la commande docker-compose up -d.
<br>
<br>

### Dernière étape :
Une fois l'image et les containers créer nous allons nous rendre sur http://localhost:3000 pour le résultat (/!\ Ne pas oublier de bien modifier le port sur le fichier server.js).

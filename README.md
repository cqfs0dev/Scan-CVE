# Création d’un scanner CVE avec Trivy
Compétence apprise 
```
- Analyste de vulnérabilté 
- Compréhension de fichier yml dpuis un Dossier .github
- Utilisation de Linux - Commande 
- Utilisation de Trivy 
- Analyse de CVE d'une image
- Fonctionnemnt d'une API Dicord pour afficher des rapport de scan
- Utilisation de Docker Image 
- Utilisation de Regex101 pour des raccouris 
- Github sur la gestion des secrets (pour l'url du webhook Discord)
- designer le "wireframe" (le croquis en +/- ASCII)
```

Dépendance installer :
```
- WSL via internet 
- pyenv pour plusieur image python dans le même environemment via internet
- Docker Desktop via internet 
- Trivy  via intrnet 
- Discorde
- GitHub 
```
## Raccourcis les + utilisées
```
cd = sert à ce déplacer de fichier ou dossier
. = le fichier où on est
.. = Pour ce déplacer à un autre dossier
git add  (ton fichier ou dossier) = Ajoute Ton fichier (sauvgarde)
git commit -m "Ton texte" = Donne une description à ton fichier Github
git push = Expédier du code (Fichier, Dossiers) sur Github
git status = voirs fichier modifier / supprimer
```

```
git pull = Mettre à jours le code depuis Github
cat (ton fichier) = permet de voirs le contenue dedans 
```



## Docker Desktop
- Il sert à sauvgarder mes images en Local sur le Pc - il st réliée à mon compte Docker 
Me sert à vérifier les logs de me images (Toute moddification, scan ect..)

- Commande pour "envoyer" l'image sur Docker ```docker push TON-ID-DOCKER/scanner:latest```
- Commande pour build une image Docker ```docker buildx build --platform linux/amd64 -t TON-ID-DOCKER/scanner:latest .```
- Commande pour excuter un scan avec Python = ```python scan.py --image=TON-IMAGE-INSTALLER```
Attention : Ajouter une API (Discorde, Google Chat..) pour avoir les rapport du scan, et télécharger une image 


# bdd-client

TD1 : 

Question 1 :

API -> GitHub : 
  - Informations sur utilisateur
  - Informatons sur un repository
  - Authentification
  - Pagination
  - Requêtes conditionelles
  - Redirection HTTPS
  
API -> Weather : 
  - Données de météo actuelles
  - Données sur 5 jours avec précision de 3 heures
  - Données sur 16 jours avec précision journalière
  - Historique des données
  - Stations météo
  - Carte météo
  - Indice UV

Question 2 :

Liste de requêtes POST :
  - POST /repos/:owner/:repo/pulls
  - POST /gists
  - POST /gists/:id/forks

Liste de requêtes GET :
  - GET /orgs/octokit/repos (Shema résumé)
  - GET /repos/octokit/octokit.rb (Shema détaillé)
  - GET /users/:username/gists (users Gist)
  - GET /gists (gist)
  - GET /gists/public (gist publique)
  
Liste des requêtes authentifiés : 
  - curl https://api.github.com/?access_token=OAUTH-TOKEN
  - curl -H "Authorization: token OAUTH-TOKEN" https://api.github.com
  
Question 3 : 

La requête en POST ne fonctionne pas mais celle en GET marche.

Exemple de résultat : 

"[
  {
    "url": "https://api.github.com/gists/36723f5daa60965a2685",
    "forks_url": "https://api.github.com/gists/36723f5daa60965a2685/forks",
    "commits_url": "https://api.github.com/gists/36723f5daa60965a2685/commits",
    "id": "36723f5daa60965a2685",
    "git_pull_url": "https://gist.github.com/36723f5daa60965a2685.git",
    "git_push_url": "https://gist.github.com/36723f5daa60965a2685.git",
    "html_url": "https://gist.github.com/36723f5daa60965a2685",
    "files": {
      "task1.coffee": {
        "filename": "task1.coffee",
        "type": "text/x-coffescript",
        "language": "CoffeeScript",
        "raw_url": "https://gist.githubusercontent.com/isaacrg/36723f5daa60965a2685/raw/e9f345e9a19ea26c27ce38b336ac10d7110d32ce/task1.coffee",
        "size": 71
      }"

Queston 4 : 

Sur mobile:
  - Tri dans les versions
  - Historique de la version de projet
  - Affichage des branches
  
![Image 1](http://img11.hostingpics.net/pics/329966Wireframe1.png)

Sur le Web:
  - Tri dans les versions
  - Historique de la version de projet
  - Affichage des branches
  
![Image 2](http://img11.hostingpics.net/pics/586242wireframesmockups.png)

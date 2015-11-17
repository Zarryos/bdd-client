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

Queston 4 : 

Sur mobile:
  - Tri dans les versions
  - Historique de la version de projet
  - Affichage des branches
  
http://hpics.li/e0ac4d6

Sur le Web:
  - Tri dans les versions
  - Historique de la version de projet
  - Affichage des branches
  
http://www.hostingpics.net/viewer.php?id=586242wireframesmockups.png

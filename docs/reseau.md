# Fiche réseau

## Mes adresses IP

| Machine                | Adresse IP      | Privée ou publique ? |
| ---------------------- | --------------- | -------------------- |
| Mon Ubuntu             | …172.20.152.110 | …Privée              |
| Mon ordinateur (Wi-Fi) | …172.16.51.33   | …Privée              |
| Ma connexion Internet  | (non publiée)   | publique             |

## Résultats du DNS

| Nom de domaine  | Adresse IP     |
| --------------- | -------------- |
| `github.com`    | …140.82.121.4  |
| `wikipedia.org` | …185.15.59.224 |

## Les outils réseau

| Commande          | Ce qu'elle fait                                          |
| ----------------- | -------------------------------------------------------- |
| `hostname -I`     | Affiche l'adresse IP de mon Ubuntu                       |
| `ping -c 4 <nom>` | … Vérifie la connexion avec un ordinateur ou un site web |
| `nslookup <nom>`  | …Recherche l'adresse IP associée à un nom de domaine     |

## Le trajet d'une requête

Quand je tape `https://github.com` dans mon navigateur :

1. Le navigateur vérifie l'adresse URL saisie.
2. Le DNS recherche l'adresse IP correspondant au nom de domaine `github.com`.
3. Le navigateur établit une connexion sécurisée avec le serveur grâce au protocole HTTPS.
4. Le navigateur envoie une requête HTTP au serveur de GitHub.
5. Le serveur traite la demande et renvoie une réponse contenant les données de la page web.
6. Le navigateur reçoit les données, interprète le HTML, le CSS et le JavaScript, puis affiche la page GitHub

## Les codes de réponse HTTP

| Code | Nom                   | Ce qu'il veut dire                                            | Exemple que j'ai vu                           |
| ---- | --------------------- | ------------------------------------------------------------- | --------------------------------------------- |
| 200  | OK                    | La requête a réussi, la page a été chargée correctement.      | Ouverture de https://github.com               |
| 301  | Moved Permanently     | La page a été déplacée définitivement vers une autre adresse. | Redirection automatique vers une nouvelle URL |
| 404  | Not Found             | La page demandée n'existe pas ou est introuvable.             | Ouverture d'une page qui n'existe pas         |
| 500  | Internal Server Error | Une erreur interne s'est produite sur le serveur.             | (Pas vu)                                      |

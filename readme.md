# AREA EPITECH

Création d'une plateforme d'actions réactions utilisant de multiples API

## Installation

Prérequis: - Avoir docker d'installé.
           - Avoir créer un fichier .env à la racine avec les valeurs valides (voir suite)
1. `sudo docker-compose build` Création des containers avec leur dépendences.
1. `sudo docker-compose up` Lancer le serveur, le web, et construire l'apk mobile.

## Environnement

DB: Base de données

| Nom | Description | Type | Valeur par défaut |
|:----|:------------|:-----|:------------------|
| <span style="color: #FF5500; text-decoration: underline;">***BASE DE DONNEE***</span> | | | | 
| **POSTGRES_PASSWORD** | Mot de passe de la DB | `string` | 'postgres' | 
| **POSTGRES_USER** | Utilisateur de la DB | `string` | 'postgres' | 
| **POSTGRES_SCHEMA** | Nom de la DB | `string` | 'postgres' | 
| **POSTGRES_HOST** | Host de la DB | `string` | 'postgres' | 
| **POSTGRES_PORT** | Port de la DB| `number` | '5432' | 
| **APP_PORT** | Port de l'application | `number` | '8080' | 
| **JWT_SECRET** | Clé d'encryption pour les calls API | `string` | 'secret' | 
| **APP_HOST** | Url d'host de l'application | `string` | 'http://localhost/' |
| **ERASE_DB** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TWITCH_REDIRECT_URI** | Clé d'application API de league of legend | `string` | *Pas de valeur par défaut* |
| **TWITCH_CLIENT_ID** | Clé d'encryption pour les tokens de mail | `string` | *Pas de valeur par défaut* |
| **TWITCH_CLIENT_SECRET** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TWITTER_REDIRECT_URI** | Mot de passe de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TWITTER_CLIENT_ID** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **TWITTER_CLIENT_SECRET** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **GITHUB_REDIRECT_URI** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **GITHUB_CLIENT_ID** | Mot de passe de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **GITHUB_CLIENT_SECRET** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **GITHUB_STATE** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_CLIENT_ID** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_STATE** | Mot de passe de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_CLIENT_SECRET** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_REDIRECT_URI** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_CLIENT_ID** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **REDDIT_STATE** | Mot de passe de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_LOGINCALLBACK** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_APPNAME** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_AUTHORIZE_URL** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_ACCESS_URL** | Mot de passe de l'application Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_REQUEST_URL** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_SECRET** | Lien de redirection pour l'OAUTH Twitch | `string` | *Pas de valeur par défaut* |
| **TRELLO_TOKEN** | Nom de client de l'application Twitch | `string` | *Pas de valeur par défaut* |

github = access_token stored
reddit = refresh_token stored
twitch = refersh_token stored
twitter = refresh_token stored
trello = acces_token stored

twitch => 
    - recup message => OK
    - poster message => OK
    - SubAction ?

twitter =>
    - poster tweet => OK
    - recup follower => OK
    - recup following => OK

github =>
    - => CreateRepo OK  
    - => Issue OK
    - => FOllow OK

trello => 
    - poster un board => OK
    -
    -

reddit => 
    - post => OK
    - hot => OK
    - best => OK

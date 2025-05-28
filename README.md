# HyperChat OAuth Redirect

Cette page statique sert de point de redirection OAuth pour l’application HyperChat Desktop.

## Utilisation

- Ce fichier `redirect.html` est utilisé comme `redirect_uri` pour l’authentification OAuth sur différentes plateformes (Kick, Google, Discord, etc.).
- Il permet de récupérer le code ou le token d’authentification et de le transmettre à l’application Electron HyperChat.

## URL publique

À utiliser comme `redirect_uri` sur les portails développeur :

```
https://cryptos-services.github.io/hyperchat-oauth-redirect/redirect.html
```

## Sécurité

Aucune donnée n’est stockée sur ce dépôt.  
La page ne fait qu’afficher et transmettre le code/token à l’application HyperChat.

---

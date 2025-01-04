# CommuSyncro - Panneau d'Administration

Panneau d'administration privé pour CommuSyncro. Ce repository est privé et contient les outils d'administration du bot.

## Configuration

1. Ajoutez votre token admin dans le fichier `.env` :
```env
ADMIN_TOKEN=votre_token_secret
```

2. Configurez l'URL de l'API dans `admin.html` :
```javascript
const API_URL = 'https://votre-serveur.com/api';
```

## Sécurité

- Ce panneau doit être hébergé sur un repository privé
- Utilisez un token admin fort et sécurisé
- Ne partagez jamais le token admin
- Limitez l'accès au panneau admin

## Fonctionnalités

- 🟢 Gestion du statut du bot (Opérationnel, Maintenance, Incident)
- 📢 Envoi de mises à jour aux serveurs
- 🔒 Interface sécurisée avec authentification
- 🚀 Mise à jour en temps réel
# commusyncro-admin

# Notre Mariage — Isaora & David (version web installable)

## Ce que fait cette première version
- Interface mobile romantique, adaptée à l'iPhone
- Tableau de bord et compte à rebours jusqu'au 7 juillet 2029
- Tâches ajoutables/modifiables/supprimables et cases terminées
- Invités, réponses, groupe et notes repas
- Budget, devis et paiements
- Prestataires, coordonnées, devis, statut
- Inspirations et documents (titre et notes)
- Sauvegarde automatique locale dans le navigateur
- Export/import manuel d'une sauvegarde JSON
- Manifest et service worker pour permettre l'installation PWA une fois hébergée en HTTPS

## Important : sauvegarde en ligne
La sauvegarde automatique en ligne n'est PAS encore activée. Elle nécessite un hébergement HTTPS et un service de base de données avec authentification (par exemple Firebase). Je n'ai pas accès à un compte d'hébergement ou Firebase à votre place. Ne saisissez pas de vraies données personnelles d'invités avant d'avoir configuré une solution sécurisée.

## Utilisation rapide
1. Héberger les fichiers sur un site HTTPS.
2. Ouvrir l'URL dans Safari sur l'iPhone.
3. Appuyer sur Partager > Sur l'écran d'accueil.
4. Les modifications sont conservées sur ce navigateur/appareil. Pour le moment, utiliser le bouton de sauvegarde/export et garder le fichier dans un endroit sûr.

## Hébergement et synchronisation multi-appareils
Il faut publier les fichiers sur un hébergement web HTTPS (par exemple GitHub Pages via l'interface web) et configurer une base de données/authentification. Une fois hébergée, la PWA peut être installée depuis Safari. Le stockage local seul ne synchronise pas les appareils. Une synchronisation cloud fiable nécessite encore cette étape de configuration.

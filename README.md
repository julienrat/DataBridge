# DataBridge API Viewer

Interface web minimaliste pour interroger n'importe quelle API JSON, filtrer les champs et générer un JSON allégé pour microcontrôleurs (ex : ESP32).

## Fonctionnalités
- Saisie d'une URL complète d'API JSON ou de paramètres (gid, key, crs pour Bordeaux).
- Requête HTTPS (fetch) pour récupérer les données JSON.
- Affichage du JSON brut dans une section "Résultats".
- Sélection dynamique des champs à afficher (cases à cocher).
- Affichage des données filtrées et version allégée pour ESP32.
- Rafraîchissement manuel ou automatique (intervalle configurable).
- Interface responsive, claire et commentée pour la maintenance.

## Démo
Accédez à la page web ici :

➡️ [DataBridge sur GitHub Pages](https://julienrat.github.io/DataBridge/index.html)

## Exemple d'utilisation
- Saisissez l'URL d'une API JSON (ex : `https://api.tutiempo.net/json/?lan=fr&apid=zwDX4azaz4X4Xqs&lid=3768`)
- Filtrez les champs à afficher
- Copiez le JSON allégé pour l'intégrer dans votre projet ESP32

## Déploiement
La page est hébergée sur GitHub Pages. Toute modification du fichier `index.html` sur la branche `main` met à jour automatiquement la page publique.

---

© 2025 julienrat
# DataBridge
DataBridge est une page web hébergée sur GitHub Pages qui récupère et filtre des données JSON d’une API pour un ESP32. Elle affiche uniquement les informations utiles, se rafraîchit automatiquement et simplifie la visualisation et l’exploitation des données en temps réel.

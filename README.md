# 🌉 DataBridge - Interface API JSON

Une interface web moderne et responsive pour récupérer, filtrer et traiter des données JSON depuis n'importe quelle API, spécialement conçue pour l'intégration avec des microcontrôleurs comme l'ESP32.

## ✨ Fonctionnalités

- **🌐 Saisie d'URL complète** : Support de n'importe quelle API JSON
- **🔄 Requête fetch automatique** : Récupération des données avec proxy CORS intégré
- **📊 Affichage lisible** : Présentation claire des données JSON
- **🎛️ Filtrage dynamique** : Sélection des champs à afficher via cases à cocher
- **⏰ Rafraîchissement automatique** : Mise à jour périodique configurable (5-300 secondes)
- **🔌 Génération URL ESP32** : Création d'URLs allégées pour microcontrôleurs
- **📱 Interface responsive** : Design adaptatif en 2 colonnes
- **🛡️ Proxy CORS** : Contournement des restrictions CORS

## 🚀 Utilisation

1. **Saisir l'URL de l'API** dans le champ prévu à gauche
2. **Cliquer sur "Récupérer les données"** pour charger les données
3. **Sélectionner les champs** qui vous intéressent dans la liste des filtres
4. **Consulter les résultats filtrés** dans le panneau de droite
5. **Copier l'URL ESP32** générée automatiquement pour votre microcontrôleur

## 🔧 Configuration

### Rafraîchissement automatique
- Définissez l'intervalle (5-300 secondes)
- Cliquez sur "Démarrer" pour activer
- Cliquez sur "Arrêter" pour désactiver

### Filtrage des données
- Tous les champs sont désélectionnés par défaut
- Utilisez "Tout sélectionner" / "Tout désélectionner" pour gérer rapidement
- Les filtres s'appliquent en temps réel

### URL ESP32
L'URL générée suit le format : `https://votre-api.com?filters=champ1,champ2,champ3`

## 🌐 Déploiement GitHub Pages

1. Poussez ce repository sur GitHub
2. Activez GitHub Pages dans les paramètres du repository
3. Sélectionnez la branche `main` comme source
4. Votre interface sera accessible à `https://votre-username.github.io/DataBridge-1`

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Design responsive avec Grid et Flexbox
- **JavaScript ES6+** : Logique interactive et gestion des données
- **Proxy CORS** : api.allorigins.win pour contourner les restrictions

## 📝 Exemples d'APIs testées

- JSONPlaceholder : `https://jsonplaceholder.typicode.com/posts/1`
- APIs météo, crypto-monnaies, etc.
- Toute API retournant du JSON

## 🔒 Sécurité

- Utilisation d'un proxy CORS fiable
- Validation des URLs saisies
- Gestion d'erreurs robuste
- Pas de stockage de données sensibles

## 📱 Compatibilité

- ✅ Navigateurs modernes (Chrome, Firefox, Safari, Edge)
- ✅ Mobile et desktop
- ✅ GitHub Pages
- ✅ Intégration ESP32/Arduino

---

*Développé pour simplifier l'intégration de données JSON dans des projets IoT et de microcontrôleurs.*
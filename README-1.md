# LotoVision Pro — PWA

App mobile installable d'analyse de loterie avec stratégie optimale combinée.

## Déploiement sur GitHub Pages (5 min)

### Étape 1 : Créer un repo GitHub
1. Va sur https://github.com/new
2. Nom du repo : `lotovision` (ou ce que tu veux)
3. Visibilité : **Private** (c'est que pour toi)
4. Clique "Create repository"

### Étape 2 : Upload les fichiers
1. Sur la page du repo, clique **"uploading an existing file"**
2. Glisse-dépose les 4 fichiers :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
3. Clique **"Commit changes"**

### Étape 3 : Activer GitHub Pages
1. Va dans **Settings** → **Pages** (menu gauche)
2. Source : **Deploy from a branch**
3. Branch : **main** / **/ (root)**
4. Clique **Save**
5. Attends 1-2 minutes

### Étape 4 : Accéder à l'app
- Ton URL sera : `https://TON-PSEUDO.github.io/lotovision/`
- Ouvre cette URL sur ton téléphone

### Étape 5 : Installer sur l'écran d'accueil
- **Android** : Menu ⋮ → "Ajouter à l'écran d'accueil" (ou la bannière apparaît automatiquement)
- **iPhone** : Bouton partage ↑ → "Sur l'écran d'accueil"

## Fonctionnalités

- **Stratégie Optimale Combinée** (5 phases) : score composite, consensus 7 algos, Monte Carlo, pool + wheeling
- **Mise à jour auto** : à chaque ouverture, l'app cherche les nouveaux tirages
- **Ajout manuel** : si l'auto-update ne marche pas, tu peux ajouter les tirages à la main
- **Offline** : fonctionne sans internet (avec les données en cache)
- **50 tirages EuroMillions + 50 tirages Loto** pré-intégrés
- **Historique** : toutes tes grilles générées sont sauvegardées

## Mettre à jour l'app elle-même

Si je te fais une nouvelle version :
1. Va sur ton repo GitHub
2. Clique sur `index.html` → icône crayon (Edit)
3. Remplace tout le contenu → Commit
4. L'app se met à jour automatiquement en ~1 min

# Les malheurs de Lulu 🎡

Une roue de la fortune interactive inspirée du dessin animé "Les malheurs de Sophie" pour enfants.

🌐 **[Voir le site en ligne](https://romanetvin.github.io/roulette-lulu/)**

## 🎨 Caractéristiques

- **Roue interactive** : Cliquez pour faire tourner et découvrir un résultat aléatoire
- **Gestion des options** : Ajoutez ou supprimez des options à tout moment
- **Sauvegarde automatique** : Vos options sont sauvegardées dans le navigateur
- **Design coloré** : Palette de couleurs inspirée de "Les malheurs de Sophie"
- **Responsive** : Fonctionne sur ordinateur, tablette et mobile

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer un dépôt GitHub

1. Connectez-vous à [GitHub](https://github.com)
2. Cliquez sur le bouton "+" en haut à droite et sélectionnez "New repository"
3. Nommez votre dépôt (par exemple : `roulette-lulu`)
4. Laissez-le public
5. Cliquez sur "Create repository"

### Étape 2 : Pousser votre code

Dans le terminal, depuis ce dossier, exécutez :

```bash
git add .
git commit -m "Initial commit: Les malheurs de Lulu"
git branch -M main
git remote add origin https://github.com/romanetvin/roulette-lulu.git
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Sur la page de votre dépôt GitHub, cliquez sur "Settings" (Paramètres)
2. Dans le menu de gauche, cliquez sur "Pages"
3. Sous "Source", sélectionnez la branche `main`
4. Cliquez sur "Save"
5. Après quelques minutes, votre site sera disponible à l'adresse :
   `https://romanetvin.github.io/roulette-lulu/`

## 📝 Utilisation

### Faire tourner la roue

Cliquez simplement sur le bouton "Tourner la roue !" pour obtenir un résultat aléatoire.

### Ajouter une option

1. Tapez votre nouvelle option dans le champ texte en bas de la page
2. Cliquez sur "Ajouter" ou appuyez sur Entrée
3. La roue se met à jour automatiquement

### Supprimer une option

Cliquez sur le bouton "Supprimer" à côté de l'option que vous souhaitez retirer.

**Note** : Vous devez garder au minimum 2 options sur la roue.

## 🎭 Options par défaut

Le site démarre avec ces options inspirées de "Les malheurs de Sophie" :

- Tomber dans la boue
- Perdre son chapeau
- Casser un jouet
- Renverser son goûter
- Se salir en jouant
- Déchirer sa robe
- Oublier ses devoirs
- Se faire gronder

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (animations et gradients)
- JavaScript vanilla (pas de dépendances)
- LocalStorage pour la persistance des données

## 📱 Compatibilité

- Chrome, Firefox, Safari, Edge (versions récentes)
- Fonctionne sur mobile et tablette
- Aucune installation requise

## 🎨 Personnalisation

Pour modifier les couleurs ou le style, éditez les variables CSS dans la section `<style>` du fichier `index.html`.

Les couleurs principales sont :
- Rose vif (#FF69B4) - inspiré de la robe de Sophie
- Bleu ciel (#87CEEB) - inspiré du jersey de Paul
- Or (#FFD700) - accents dorés
- Rose pâle (#FFB6C1) - fond doux

## 📄 Licence

Projet libre d'utilisation.

---

**Amusez-vous bien avec la roue de Lulu ! 🎉**

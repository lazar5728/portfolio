# Configuration GitHub - Instructions

## Étapes pour créer et publier votre repository sur GitHub

### 1. Créer un nouveau repository sur GitHub

1. Allez sur [GitHub](https://github.com)
2. Cliquez sur le bouton **"+"** en haut à droite, puis **"New repository"**
3. Remplissez les informations:
   - **Repository name**: `portfolio` (ou le nom de votre choix)
   - **Description**: "Portfolio professionnel - Développeur Full Stack"
   - **Visibilité**: Public (pour que tout le monde puisse voir votre portfolio)
   - **NE PAS** cocher "Initialize with README" (nous en avons déjà un)
4. Cliquez sur **"Create repository"**

### 2. Lier votre repository local à GitHub

Après avoir créé le repository, GitHub vous donnera des commandes. Utilisez celles-ci dans votre terminal:

```bash
# Ajouter le remote (remplacez USERNAME par votre nom d'utilisateur GitHub)
git remote add origin https://github.com/lazar5728/portfolio.git

# Pousser votre code vers GitHub
git push -u origin main
```

### 3. Activer GitHub Pages (pour héberger votre site gratuitement)

1. Allez dans votre repository sur GitHub
2. Cliquez sur **"Settings"** (Paramètres)
3. Dans le menu de gauche, cliquez sur **"Pages"**
4. Sous "Source", sélectionnez:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Cliquez sur **"Save"**
6. Attendez quelques minutes, votre site sera disponible à: `https://lazar5728.github.io/portfolio/`

### 4. Commandes Git utiles pour la suite

```bash
# Voir le statut de vos fichiers
git status

# Ajouter des modifications
git add .

# Créer un commit
git commit -m "Description de vos modifications"

# Envoyer vers GitHub
git push

# Voir l'historique des commits
git log --oneline

# Créer une nouvelle branche
git checkout -b nom-de-la-branche

# Revenir à la branche main
git checkout main
```

### 5. Mettre à jour votre portfolio

Chaque fois que vous modifiez votre portfolio:

```bash
git add .
git commit -m "Description des modifications"
git push
```

Les changements seront automatiquement déployés sur GitHub Pages en quelques minutes.

### 6. Personnaliser l'URL (optionnel)

Si vous voulez un nom de domaine personnalisé:
1. Achetez un domaine (ex: chez Namecheap, GoDaddy)
2. Dans les paramètres GitHub Pages, ajoutez votre domaine personnalisé
3. Configurez les DNS de votre domaine pour pointer vers GitHub Pages

## Conseils

- Faites des commits réguliers avec des messages clairs
- Utilisez des branches pour tester de nouvelles fonctionnalités
- Gardez votre README.md à jour
- Ajoutez des captures d'écran de votre portfolio dans le README

## Ressources

- [Documentation GitHub Pages](https://docs.github.com/en/pages)
- [Guide Git](https://git-scm.com/book/fr/v2)
- [Markdown Guide](https://www.markdownguide.org/)

---

Bon courage avec votre portfolio! 🚀

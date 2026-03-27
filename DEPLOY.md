# 🚀 Guide de Déploiement - Portfolio Lazar

## Étape 1: Créer le repository sur GitHub

1. Allez sur [GitHub](https://github.com) et connectez-vous
2. Cliquez sur le bouton **"+"** en haut à droite → **"New repository"**
3. Remplissez:
   - **Repository name**: `portfolio` (ou `lazar-portfolio`)
   - **Description**: "Portfolio professionnel - Développeur Full Stack"
   - **Visibilité**: ✅ Public
   - ❌ NE PAS cocher "Initialize with README"
4. Cliquez sur **"Create repository"**

## Étape 2: Lier votre projet local à GitHub

Copiez et exécutez ces commandes dans votre terminal (Git Bash):

```bash
# Ajouter le remote GitHub (remplacez par votre URL)
git remote add origin https://github.com/lazar5728/portfolio.git

# Vérifier que le remote est bien ajouté
git remote -v

# Pousser votre code vers GitHub
git push -u origin main
```

## Étape 3: Activer GitHub Pages

1. Sur GitHub, allez dans votre repository
2. Cliquez sur **"Settings"** (⚙️ Paramètres)
3. Dans le menu de gauche, cliquez sur **"Pages"**
4. Sous "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Cliquez sur **"Save"**

⏳ Attendez 2-3 minutes...

## Étape 4: Accéder à votre site

Votre portfolio sera disponible à:
```
https://lazar5728.github.io/portfolio/
```

## 🎉 C'est fait!

Votre portfolio est maintenant en ligne et accessible à tous!

## 📝 Mettre à jour votre portfolio

Chaque fois que vous faites des modifications:

```bash
# 1. Ajouter les fichiers modifiés
git add .

# 2. Créer un commit
git commit -m "Description de vos modifications"

# 3. Pousser vers GitHub
git push
```

Les changements seront automatiquement déployés en 1-2 minutes.

## 🔧 Commandes utiles

```bash
# Voir l'état de vos fichiers
git status

# Voir l'historique des commits
git log --oneline

# Voir les différences avant de commiter
git diff

# Annuler les modifications non commitées
git restore nom-du-fichier
```

## 🌐 Domaine personnalisé (optionnel)

Pour utiliser votre propre domaine (ex: www.lazar-dev.com):

1. Achetez un domaine chez un registrar (Namecheap, GoDaddy, etc.)
2. Dans GitHub Pages settings, ajoutez votre domaine personnalisé
3. Configurez les DNS de votre domaine:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   
   Type: CNAME
   Host: www
   Value: lazar5728.github.io
   ```

## 📊 Statistiques et Analytics (optionnel)

Pour suivre les visiteurs, ajoutez Google Analytics ou Plausible:

1. Créez un compte sur [Google Analytics](https://analytics.google.com)
2. Obtenez votre ID de suivi (ex: G-XXXXXXXXXX)
3. Ajoutez le script dans `index.html` avant `</head>`

## ❓ Problèmes courants

### Le site ne s'affiche pas
- Vérifiez que GitHub Pages est activé dans Settings
- Attendez 5 minutes après l'activation
- Vérifiez que le repository est public

### Les images ne s'affichent pas
- Vérifiez les chemins des images (doivent être relatifs)
- Assurez-vous que les images sont bien commitées

### Les modifications ne s'affichent pas
- Videz le cache du navigateur (Ctrl + F5)
- Attendez 2-3 minutes après le push

## 📞 Besoin d'aide?

- [Documentation GitHub Pages](https://docs.github.com/en/pages)
- [Guide Git](https://git-scm.com/book/fr/v2)

---

Bon déploiement! 🎊

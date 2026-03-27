# 🚀 Guide Rapide - Publier votre Portfolio sur GitHub

## Étape 1: Créer le repository sur GitHub (2 minutes)

1. Allez sur https://github.com/new
2. Remplissez:
   - **Repository name**: `portfolio`
   - **Description**: "Mon portfolio professionnel"
   - **Public** ✅
   - **NE PAS** cocher "Add a README file"
3. Cliquez sur **"Create repository"**

## Étape 2: Publier votre code (1 minute)

Copiez et collez ces commandes dans votre terminal (PowerShell):

```powershell
# Lier votre projet à GitHub (remplacez lazar5728 par votre username)
git remote add origin https://github.com/lazar5728/portfolio.git

# Envoyer votre code
git push -u origin main
```

Si on vous demande de vous connecter, utilisez vos identifiants GitHub.

## Étape 3: Activer GitHub Pages (1 minute)

1. Sur GitHub, allez dans votre repository
2. Cliquez sur **Settings** (en haut)
3. Dans le menu de gauche, cliquez sur **Pages**
4. Sous "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: main
   - **Folder**: / (root)
5. Cliquez sur **Save**

⏰ Attendez 2-3 minutes, puis votre site sera en ligne à:
**https://lazar5728.github.io/portfolio/**

## ✅ C'est tout!

Votre portfolio est maintenant en ligne et accessible à tous!

## 📝 Pour mettre à jour votre portfolio plus tard

Chaque fois que vous modifiez un fichier:

```powershell
git add .
git commit -m "Description de vos modifications"
git push
```

Le site se mettra à jour automatiquement en 1-2 minutes.

## 🎯 Prochaines étapes recommandées

1. ✅ Partagez le lien de votre portfolio sur LinkedIn
2. ✅ Ajoutez le lien dans votre CV
3. ✅ Mettez à jour régulièrement vos projets
4. ✅ Ajoutez des captures d'écran dans le README

## ❓ Problèmes courants

**"Permission denied"**: Utilisez un Personal Access Token au lieu du mot de passe
- Allez sur GitHub → Settings → Developer settings → Personal access tokens
- Créez un token avec les permissions "repo"
- Utilisez ce token comme mot de passe

**"Repository not found"**: Vérifiez que vous avez bien remplacé `lazar5728` par votre username

**Le site ne s'affiche pas**: Attendez 5 minutes et videz le cache de votre navigateur (Ctrl+F5)

## 📞 Besoin d'aide?

- Documentation GitHub Pages: https://pages.github.com/
- Support GitHub: https://support.github.com/

---

Bonne chance! 🎉

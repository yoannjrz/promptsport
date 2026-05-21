# 🎯 PromptSport

Générateur d'analyses IA pour paris sportifs (Foot, Tennis, Basket).

## 🚀 Déploiement Vercel

### Étape 1 : Push sur GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yoannjrz/promptsport.git
git push -u origin main
```

### Étape 2 : Connecter à Vercel
1. Va sur https://vercel.com/new
2. Importe le repo `yoannjrz/promptsport`
3. **AVANT de déployer**, ajoute la variable d'environnement :
   - Nom : `RAPIDAPI_KEY`
   - Valeur : `52356da5abmsh709f35629c9e122p127ee1jsn6eccc0261b5a`
4. Clique "Deploy"

### Étape 3 : C'est en ligne
- URL : `https://promptsport.vercel.app` (ou similaire)
- Bookmark sur ton iPhone

## 📂 Structure
- `index.html` — Interface complète (foot/tennis/basket)
- `api/sofa.js` — Proxy serverless Sofascore (cache la clé + règle CORS)
- `vercel.json` — Config Vercel

## 🔧 Modification ultérieure
Tout est dans `index.html`. Édite directement, push sur GitHub → Vercel redéploie auto.

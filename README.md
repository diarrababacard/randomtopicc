# Daily Speaking Trainer

Application d'entraînement à l'expression orale, propulsée par Gemini AI.

## Structure du projet

```
speaking-trainer/
├── api/
│   └── gemini.js        ← fonction serverless (clé API protégée côté serveur)
├── public/
│   └── index.html       ← l'application frontend
├── vercel.json          ← configuration Vercel
└── README.md
```

## Déploiement sur Vercel

### 1. Installer Vercel CLI (optionnel)
```bash
npm i -g vercel
```

### 2. Déployer via GitHub (recommandé)
1. Crée un repo GitHub et push ce dossier
2. Va sur https://vercel.com et importe le repo
3. Vercel détecte automatiquement la config

### 3. Ajouter la variable d'environnement
Dans le dashboard Vercel de ton projet :
- Settings → Environment Variables
- Ajoute : `GEMINI_API_KEY` = ta clé Google AI Studio

### 4. Redéployer
Après avoir ajouté la variable, clique sur "Redeploy" dans Vercel.

---
Ta clé API n'est jamais exposée dans le code frontend.

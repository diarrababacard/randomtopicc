# Daily Speaking Trainer — Structure Vercel

```
speaking-trainer/
├── api/
│   └── gemini.js     ← fonction serverless (clé API sécurisée)
├── index.html        ← frontend à la racine
└── vercel.json
```

## Déploiement

1. Push ce dossier sur GitHub
2. Importe sur vercel.com
3. Settings → Environment Variables → ajoute :
   GEMINI_API_KEY = ta_clé_google_ai_studio
4. Redeploy

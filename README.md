# Ma Boutique — Ready to deploy

Contenu: un projet Vite + React utilisant Tailwind CSS (démo).  

## Comment lancer en local
1. Installer Node.js (>=16).
2. Dans le dossier du projet:
```bash
npm install
npm run dev
```
3. Ouvrir `http://localhost:5173`.

## Déployer sur Vercel (recommandé)
1. Crée un compte sur https://vercel.com (ou connecte ton GitHub).
2. Dans Vercel, `New Project` → import repository (ou `Deploy from Git`).
3. Si tu téléverses les fichiers directement, choisis `Framework: Vite`.
4. Build command: `npm run build`  — Output dir: `dist`.
5. Lancer le déploiement; Vercel te fournira un lien (ex: `https://ma-boutique.vercel.app`).

## Déployer sur Netlify
1. Crée un compte sur https://app.netlify.com.
2. `Add new site` → `Deploy manually` or connect Git.
3. Build command: `npm run build` — Publish directory: `dist`.
4. Déployer et copy l'URL fournie.

## Paiements
Ce projet contient un **checkout mock** (simulation). Pour activer de vrais paiements:
- Utilise Stripe (recommandé) : créer un compte Stripe, puis implémenter un backend (Node/Express) qui crée des PaymentIntents.
- Je peux fournir le code backend prêt à l'emploi pour Stripe si tu veux.

## Personnalisation que je peux faire pour toi
- Ajouter tes produits réels à `src/data` ou via CMS.
- Connecter Stripe / PayPal (nécessite tes clés).
- Modifier logo, couleurs, textes.
- Déployer pour toi si tu me fournis accès (GitHub/Vercel) — sinon je te guide pas à pas.


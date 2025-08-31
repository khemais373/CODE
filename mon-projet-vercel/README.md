# Mon Projet – Vercel

Projet statique prêt à déployer via **GitHub → Vercel**.

## Structure
- `index.html` — page d’accueil
- `style.css` — styles de base
- `vercel.json` — configuration des routes (SPA-friendly)
- `admin/` — dossier pour tes fichiers (conservé avec `.gitkeep`)

## Déploiement

### 1) GitHub
1. Crée un nouveau dépôt (public ou privé).
2. Téléverse ces fichiers (bouton **Upload files**) et valide (**Commit changes**).

### 2) Vercel
1. Va sur https://vercel.com/new
2. **Importer depuis GitHub** → choisis ton dépôt.
3. **Paramètres de compilation et de sortie** :
   - **Commande d’installation** : (laisse par défaut)
   - **Commande de build** : (laisser vide)
   - **Répertoire de sortie** : `.`
   - **Dossier racine** : (laisser vide)
4. Clique **Déployer**.

> Si tu utilises un framework (Next.js, etc.), adapte la commande de build et le répertoire de sortie (ex: `.next`, `dist`).

Bonne mise en ligne !

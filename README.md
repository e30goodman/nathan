# BassMastery — Espace Nathan

Site personnel pour Nathan (cours de basse).

**URL après déploiement :** `https://e30goodman.github.io/nathan/`

## Contenu

- Leçon 1 — Mini-blocs diatoniques (théorie + pratique)
- Schéma : `images/schema-structure.jpg` (à ajouter)

## Déploiement (repo séparé)

Ce dossier est conçu comme **racine d'un repo GitHub indépendant** (pas dans le repo `maja`).

```powershell
cd nathan
git init
git add .
git commit -m "Initial commit — Espace Nathan"
git branch -M main
git remote add origin https://github.com/e30goodman/nathan.git
git push -u origin main
```

Ensuite : **Settings → Pages → Source : GitHub Actions**.

## Ajouter le schéma

Placez votre dessin du manche dans :

```
images/schema-structure.jpg
```

Puis commit + push.

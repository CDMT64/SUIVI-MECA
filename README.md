# 🚁 Cougar — Suivi Entretiens

Application PWA de suivi des échéances mécaniques et calendaires du Cougar.

---

## 🚀 Déploiement sur GitHub Pages

### Étape 1 — Créer le dépôt
1. Aller sur [github.com](https://github.com) → **New repository**
2. Nom : `cougar-maintenance`
3. Visibilité : **Private** (recommandé)
4. Cliquer **Create repository**

### Étape 2 — Uploader les fichiers
Depuis la page du dépôt → **Add file → Upload files**

Uploader ces 5 fichiers :
```
index.html
manifest.json
sw.js
icon.svg
README.md
```

### Étape 3 — Activer GitHub Pages
1. **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : `main` / `/ (root)`
4. Cliquer **Save**

### Étape 4 — Accéder à l'app
URL : `https://<votre-pseudo>.github.io/cougar-maintenance/`

*(disponible après ~2 minutes)*

---

## 📱 Installation sur téléphone

**Android (Chrome)**
> Menu ⋮ → **Ajouter à l'écran d'accueil**

**iPhone (Safari)**
> Bouton Partager → **Sur l'écran d'accueil**

---

## ✈️ Fonctionnalités
- Entretiens mécaniques (H cellule + tolérance)
- Entretiens calendaires (date + tolérance en jours)
- Frise chronologique avec grilles horaires/journalières
- Statuts automatiques : OK / Bientôt / Dépassé
- Impression PDF paysage
- Sauvegarde locale (localStorage)
- Mode hors-ligne (Service Worker)

---

## 📁 Structure
```
cougar-maintenance/
├── index.html      ← Application complète
├── manifest.json   ← Config PWA
├── sw.js           ← Cache hors-ligne
├── icon.svg        ← Icône installable
└── README.md
```

**Version : V1.0**

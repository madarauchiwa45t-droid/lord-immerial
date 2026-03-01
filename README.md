# 👑 LORD-IMPERIAL PWA

Application sociale royale - Progressive Web App (PWA) + APK Android

## 🚀 Déploiement Gratuit

| Service | Usage | Coût |
|---------|-------|------|
| GitHub Pages | Hébergement web | **GRATUIT** |
| GitHub Actions | Build APK automatique | **GRATUIT** |
| localStorage | Base de données | **GRATUIT** |

## 📱 Installation

### Méthode 1 : PWA (Direct depuis le navigateur)
1. Ouvre l'app sur Chrome/Android
2. Clique sur **"Installer l'app"** (bouton flottant)
3. L'app s'installe comme une vraie app Android

### Méthode 2 : APK (Releases GitHub)
1. Va dans **Releases** de ce dépôt
2. Télécharge `lord-imperial.apk`
3. Active "Sources inconnues" et installe

## 🔧 Configuration GitHub Pages

1. Paramètres du dépôt → **Pages**
2. Source : **GitHub Actions**
3. Le workflow se lance automatiquement

## 📁 Structure

```
lord-imperial/
├── index.html          # App principale
├── manifest.json       # Config PWA
├── sw.js              # Service Worker
├── icons/             # Icônes PWA (72 → 512px)
│   ├── icon-192.png
│   ├── icon-512.png
│   └── ...
└── .github/
    └── workflows/
        └── deploy-and-build.yml  # CI/CD
```

## ⚙️ Fonctionnalités PWA

- ✅ **Installable** sur Android (bouton flottant)
- ✅ **Mode hors-ligne** (Service Worker + Cache)
- ✅ **Splash screen** natif
- ✅ **Plein écran** (standalone)
- ✅ **Mise à jour automatique**
- ✅ **Bannière offline/online**
- ✅ **Push notifications** (prêt)

## 🛠️ Tech Stack

- HTML/CSS/JS (Vanilla)
- Service Worker API
- Web App Manifest
- Bubblewrap (TWA → APK)
- GitHub Actions (CI/CD)

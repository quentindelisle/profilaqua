# 🌊 Profil Aquatique

> **Es-tu à l'aise dans l'eau ?**  
> Quiz de 12 questions pour découvrir son profil aquatique et mesurer son niveau d'aquaphobie ou de thalassophobie.

Développé dans le cadre du **GIPTIC EPS Paris** pour aider les professeur·es d'EPS à identifier les élèves aquaphobes et leur proposer des solutions pédagogiques adaptées (vidéo 360° / casques VR).

---

## 🎯 Fonctionnalités

- **12 questions** organisées en 2 axes : *Aquaphobie* et *Thalassophobie*
- **5 profils** de résultat avec description personnalisée
- **Barres de score animées** par axe
- **Contact direct** avec Sophie Cheyrou (GIPTIC EPS Paris) pour le prêt de casques VR
- **PWA installable** sur smartphone et tablette (Android, iOS, Windows, Samsung, Huawei…)
- **100 % offline** grâce au Service Worker
- **Aucune donnée collectée** — tout reste dans le navigateur

---

## 📲 Installation PWA (sur l'écran d'accueil)

| Appareil | Marque / OS | Comment installer |
|---|---|---|
| iPhone / iPad | Apple iOS ≥ 11.3 | Safari → Partager → « Sur l'écran d'accueil » |
| Android | Samsung, Xiaomi, OnePlus… | Chrome → menu ⋮ → « Ajouter à l'écran d'accueil » |
| Android | Google Pixel | Chrome → bannière automatique ou menu ⋮ |
| Tablette Android | Samsung Galaxy Tab | Chrome → menu ⋮ → « Installer l'application » |
| Windows / PC | Edge ou Chrome | Barre d'URL → icône d'installation ⊕ |
| macOS | Safari ≥ 17 | Partager → « Ajouter au Dock » |
| Huawei (HMS) | Huawei Browser | Menu → « Ajouter à l'écran d'accueil » |

---

## 🗂️ Structure du repository

```
profil-aquatique/
├── index.html          ← Application principale (HTML single-file)
├── manifest.json       ← Web App Manifest (PWA)
├── sw.js               ← Service Worker (cache offline)
├── browserconfig.xml   ← Config tuiles Windows / Edge
├── favicon.ico         ← Favicon multi-tailles (16→256px)
├── logo.png            ← Logo source original (1254×1254)
├── icons/
│   ├── apple-touch-icon.png          ← iOS principal (180×180)
│   ├── apple-touch-icon-{57…180}.png ← Toutes tailles Apple
│   ├── icon-{72…512}.png             ← PWA Android / Chrome
│   ├── favicon-{16,32,48}.png        ← Favicons navigateur
│   └── mstile-{70,150,310}.png       ← Tuiles Windows
└── README.md
```

---

## 🚀 Déploiement GitHub Pages

1. **Fork** ou clone ce repository
2. `Settings` → `Pages` → Source : **Deploy from a branch** → `main` → `/ (root)`
3. L'URL sera : `https://<username>.github.io/profil-aquatique/`

Aucune dépendance externe, aucun build nécessaire. Tout est statique.

---

## 🧪 Profils de résultats

| Emoji | Profil | Conditions |
|---|---|---|
| 🐬 | Nageur·euse serein·e | Aquaphobie basse + Thalassophobie basse |
| 🌊 | Baigneur·euse prudent·e | Aquaphobie modérée + Thalassophobie basse |
| 💧 | Signes d'aquaphobie | Aquaphobie élevée + Thalassophobie modérée |
| 🌑 | Aquaphobie marquée | Aquaphobie très élevée OU Thalassophobie très élevée |
| 🦈 | Phobie mixte | Les deux axes très élevés |

---

## 💡 Solution pédagogique intégrée

Pour les élèves identifiés aquaphobes, l'app propose directement de **contacter Sophie Cheyrou (GIPTIC EPS Paris)** pour emprunter un casque VR et utiliser des **vidéos 360°** immersives en milieu aquatique.

---

## ✍️ Auteur & licence

Créé avec le soutien du **GIPTIC EPS Paris**.  
Licence : usage pédagogique libre — merci de conserver la mention GIPTIC EPS Paris.

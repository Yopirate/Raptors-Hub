# 🚀 GUIDE COMPLET GITHUB - RAPACES MAROC

## 📋 ÉTAPES DÉTAILLÉES

### ✅ CE QUE VOUS AVEZ DÉJÀ FAIT

1. ✅ Installé GitHub Desktop
2. ✅ Créé le dossier "raptors hub"

### 🎯 PROCHAINES ÉTAPES

---

## **ÉTAPE 1 : Télécharger les fichiers du projet**

### A) Télécharger le package GitHub

📦 **Fichier à télécharger :** `RaptorsMaroc-GitHub-Complete.zip`

Ce fichier contient :
- ✅ Code source Android complet
- ✅ Configuration GitHub Actions (compilation automatique)
- ✅ Documentation
- ✅ Licence MIT

### B) Extraire dans votre dossier

```
1. Télécharger RaptorsMaroc-GitHub-Complete.zip
2. Clic-droit → Extraire tout
3. Copier TOUT le contenu dans votre dossier "raptors hub"
```

**Structure finale de "raptors hub" :**
```
raptors-hub/
├── .github/
│   └── workflows/
│       └── build.yml          ← Compilation automatique
├── app/                        ← Code Android
├── docs/                       ← Documentation
├── build.gradle
├── gradlew
├── settings.gradle
├── README.md
└── LICENSE
```

---

## **ÉTAPE 2 : Publier sur GitHub**

### Via GitHub Desktop (SIMPLE)

```
1. Ouvrir GitHub Desktop

2. File → Add Local Repository

3. Choisir votre dossier "raptors hub"

4. Cliquer "Create Repository" (si demandé)

5. En bas à gauche :
   - Summary : "Initial commit - Rapaces Maroc v0.2"
   - Cliquer "Commit to main"

6. Cliquer "Publish repository" en haut

7. Choisir :
   ☑️ Keep this code private (si vous voulez)
   ☐ Keep this code public (recommandé pour partage)

8. Cliquer "Publish repository"

9. ✅ Code publié sur GitHub !
```

---

## **ÉTAPE 3 : Activer GitHub Actions (Compilation automatique)**

```
1. Aller sur votre dépôt GitHub dans le navigateur :
   https://github.com/VOTRE-NOM/raptors-hub

2. Cliquer sur l'onglet "Actions" en haut

3. Si demandé : Cliquer "I understand my workflows, go ahead and enable them"

4. Vous verrez "Build APK" workflow

5. La compilation démarre automatiquement ! ⚙️
```

---

## **ÉTAPE 4 : Attendre la compilation (~10 minutes)**

```
1. Dans l'onglet "Actions", vous verrez :
   🟡 "Initial commit - Rapaces Maroc v0.2" (en cours)

2. Cliquer dessus pour voir les logs en temps réel

3. Attendre que ça devienne :
   ✅ "Initial commit - Rapaces Maroc v0.2" (succès)

4. Compilation terminée ! 🎉
```

---

## **ÉTAPE 5 : Télécharger l'APK**

### Méthode A : Via Releases (Automatique)

```
1. Sur votre dépôt GitHub, cliquer "Releases" (colonne droite)

2. Vous verrez "Release v0.2 Build 1"

3. Cliquer dessus

4. Télécharger "app-debug.apk" (8-10 MB)

5. ✅ APK téléchargé !
```

### Méthode B : Via Artifacts (Manuel)

```
1. Actions → Cliquer sur le workflow terminé

2. Section "Artifacts" en bas

3. Cliquer "app-debug" pour télécharger

4. Extraire le ZIP → app-debug.apk

5. ✅ APK téléchargé !
```

---

## **ÉTAPE 6 : Installer sur Samsung S25 Ultra**

```
1. Transférer app-debug.apk sur téléphone (USB/Cloud/Email)

2. Ouvrir le fichier APK sur téléphone

3. Autoriser "Installation depuis sources inconnues"

4. Installer

5. ✅ App installée !
```

---

## 🔄 **MODIFICATIONS FUTURES**

Si vous voulez modifier le code :

```
1. Modifier fichiers dans "raptors hub" localement

2. GitHub Desktop :
   - Summary : "Description modification"
   - Commit to main
   - Push origin

3. GitHub Actions recompile automatiquement

4. Nouvelle release créée automatiquement

5. Télécharger nouvel APK !
```

---

## 📊 **AVANTAGES GITHUB ACTIONS**

✅ **Compilation automatique** dans le cloud  
✅ **Releases automatiques** avec lien direct APK  
✅ **Historique des versions** (v0.2-build-1, build-2, etc.)  
✅ **Gratuit** pour dépôts publics (2,000 min/mois)  
✅ **Notifications email** quand compilation terminée  
✅ **Partageable** - Envoyez juste le lien GitHub  

---

## 🎯 **RÉSUMÉ VISUEL**

```
Votre PC                GitHub.com              GitHub Actions
─────────              ───────────             ───────────────

[raptors hub]    →     [Dépôt GitHub]    →    [🔨 Compilation]
  (code)              (code stocké)              (automatique)
                                                       ↓
                                                [✅ APK prêt]
                                                       ↓
                                            [📦 Release v0.2]
                                                       ↓
                                          [⬇️ Téléchargement]
```

---

## ⏱️ **TEMPS ESTIMÉ**

| Étape | Temps |
|-------|-------|
| Télécharger package GitHub | 1 min |
| Extraire dans raptors hub | 1 min |
| Publier sur GitHub Desktop | 2 min |
| Activer Actions | 1 min |
| Compilation automatique | 10-15 min |
| Télécharger APK | 1 min |
| Installer sur téléphone | 2 min |
| **TOTAL** | **~20-25 min** |

---

## 🔧 **DÉPANNAGE**

### ❌ GitHub Actions échoue

**Vérifier logs :**
```
Actions → Workflow échoué → Cliquer dessus → Voir logs rouges
```

**Erreurs communes :**
- `gradlew not found` → Vérifier que fichier gradlew est bien présent
- `Build failed` → Vérifier syntaxe Kotlin dans app/
- `Timeout` → Relancer workflow (Actions → Re-run jobs)

### ❌ Pas de Release créée

**Solution :**
```
1. Settings → Actions → General
2. Workflow permissions → Read and write permissions ✅
3. Save
4. Re-push commit
```

---

## 💡 **ASTUCE PRO**

**Ajouter badge build dans README :**

```markdown
[![Build APK](https://github.com/VOTRE-NOM/raptors-hub/actions/workflows/build.yml/badge.svg)](https://github.com/VOTRE-NOM/raptors-hub/actions/workflows/build.yml)
```

Affichera : ![Build APK](https://img.shields.io/badge/build-passing-brightgreen)

---

## 📞 **BESOIN D'AIDE ?**

Si vous êtes bloqué à une étape, dites-moi :
- **Quelle étape** pose problème
- **Message d'erreur** exact
- **Capture d'écran** si possible

Je vous aiderai ! 🚀

---

**Version** : 0.2-NoMaps  
**Build** : 2  
**Date** : 20 février 2026

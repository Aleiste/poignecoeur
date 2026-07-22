# PoigneCœuR 💘🖐️

Appli de rencontre **100 % humoristique** basée sur la « compatibilité morphologique ».
L'appli complète tient dans un seul fichier : [`index.html`](index.html).

## Tester tout de suite (sans rien installer)
Ouvre `index.html` dans un navigateur (double-clic).

## Générer l'APK Android (build cloud, gratuit)
Aucun outil à installer : GitHub compile l'APK pour toi.

1. Crée un dépôt vide sur https://github.com/new (ex. `poignecoeur`).
2. Pousse ce dossier (voir commandes ci-dessous).
3. Va dans l'onglet **Actions** du dépôt → le workflow *Build APK* se lance tout seul.
4. Quand il finit (✅, ~3-5 min), ouvre le run → section **Artifacts** → télécharge **PoigneCoeur-APK**.
5. Décompresse le `.zip`, transfère `app-debug.apk` sur ton téléphone et installe-le
   (autorise « installer des applis inconnues » pour ton navigateur/gestionnaire de fichiers).

L'APK est signée avec la clé *debug* (parfait pour un usage perso/entre potes ;
non destinée aux stores).

## Structure
```
index.html                 ← l'appli (HTML/CSS/JS autonome)
android/                   ← wrapper natif WebView (affiche index.html en plein écran)
.github/workflows/         ← build automatique de l'APK
```

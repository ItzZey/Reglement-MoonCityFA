# Mise à jour du GitBook MoonCity

Cette version contient la bannière officielle MoonCity dans :

`assets/mooncity-banner.png`

Le fichier `README.md` l'affiche automatiquement tout en haut de la page d'accueil avec :

```md
![Bannière MoonCity](assets/mooncity-banner.png)
```

## Pour remplacer la version actuelle

1. Ouvrir le dossier `MoonCity_GitBook` de votre dépôt GitHub.
2. Remplacer les fichiers actuels par ceux de ce pack.
3. Vérifier que le dossier `assets` est bien présent.
4. Conserver `gitbook-docs.yaml` dans le dossier racine du GitBook.
5. Commit les modifications sur la branche `main`.
6. GitBook récupérera ensuite les changements via Git Sync.

Le dossier attendu ressemble à :

```text
MoonCity_GitBook/
├── assets/
│   └── mooncity-banner.png
├── notions-de-base/
├── reglement-legal/
├── reglement-illegal/
├── README.md
├── SUMMARY.md
├── gitbook-docs.yaml
├── sanctions-et-support.md
└── changelog.md
```

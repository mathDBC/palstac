# PalStac

Outil de saisie et de suivi de ramasses de palettes pour chauffeurs, en HTML/JS
autonome — aucun build, aucun backend.

**Démo en ligne : [protransdock.com/palstac](https://www.protransdock.com/palstac)**

## Fonctionnalités

- Saisie rapide des unités ramassées (bac, palettes, dosserets, demi-palettes) par tournée
- Rapports journée et semaine par chauffeur
- Export CSV et HTML
- Fond bleu, avec un choix de couleur pour l'interface

## Usage

Ouvrir `index.html` dans un navigateur, ou servir le dossier avec n'importe
quel serveur statique :

```bash
python3 -m http.server 8080
```

Les données restent dans le `localStorage` du navigateur. Il n'y a pas de
serveur ni de base de données. Un profil correspond à un chauffeur.

## Stack

HTML, CSS et JavaScript, sans outil de build.

## Licence

MIT — voir [LICENSE](./LICENSE).

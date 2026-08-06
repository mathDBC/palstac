# PalBack

Outil de saisie et de suivi de ramasses de palettes pour chauffeurs, en HTML/JS
autonome — aucun build, aucun backend.

**Démo en ligne : [protransdock.com/palback](https://www.protransdock.com/palback)**

## Fonctionnalités

- Saisie rapide des unités ramassées (palettes, demi-palettes, ...) par tournée
- Rapports journée / semaine par chauffeur
- Export CSV / Excel (via [SheetJS](https://sheetjs.com/)) et HTML

## Usage

Ouvrir `index.html` dans un navigateur, ou servir le dossier avec n'importe
quel serveur statique :

```bash
python3 -m http.server 8080
```

Les données sont stockées uniquement dans le `localStorage` du navigateur —
il n'y a pas de serveur ni de base de données. Un profil correspond à un
chauffeur ; l'app n'est pas conçue pour gérer plusieurs chauffeurs dans la
même session.

## Stack

- HTML/CSS/JS vanilla, sans dépendance de build
- [SheetJS (xlsx.full.min.js)](https://sheetjs.com/) embarqué en local pour
  les exports Excel

## Licence

MIT — voir [LICENSE](./LICENSE).

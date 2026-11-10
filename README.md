# Goals Tracker

Application mobile de liste d'objectifs personnels, développée avec React Native et Expo. On y ajoute, modifie et supprime ses objectifs en quelques gestes.

## Fonctionnalités

- Ajouter un objectif
- Modifier un objectif existant
- Supprimer un objectif, avec une fenêtre de confirmation
- Message d'erreur si le champ est vide
- Interface Material Design avec React Native Paper

## Technologies

- React Native 0.76
- Expo 52
- React Native Paper
- Hooks React (`useState`)

## Structure

```
App.js                 point d'entrée
components/
  Accueil.js           écran d'accueil
  Liste.js             liste des objectifs : ajout, modification, suppression
```

## Lancer le projet

Prérequis : Node.js 18 ou plus récent et l'application **Expo Go** sur votre téléphone (ou un émulateur).

```bash
git clone https://github.com/imene-be/goals-tracker-app.git
cd goals-tracker-app
npm install
npx expo start
```

Scannez ensuite le QR code affiché dans le terminal avec Expo Go.

## Pistes d'amélioration

- Conserver les objectifs entre deux ouvertures de l'application (stockage local)
- Marquer un objectif comme atteint

---

Réalisé par [Imène Bentifraouine](https://imenebe.fr).

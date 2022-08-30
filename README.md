# Template CI

## Description

Template pour permettre l'animation de cours CI et Tests Unitaires (voir branchesp lus bas).

Il contient une application angular simple qui affiche une calculatrice.
Le composant calculatrice appelle un service qui contient l'ensemble de la logique.

## Branches

Ce template inclu deux branches : 
- main
- tests

### main

Branche par défaut de l'application. Utilisez cette dernière pour réaliser des exercices dans lesquels les stagiaires devront rédiger les tests unitaires eux même.
Est donc adapté aux cursus ayant déjà fait de l'Angular et du TypeScript

### tests

Comme pour la main, mis à part que l'ensemble des tests ont déjà été rédigés.
Cours adapté pour les modile `CI` des cursus qui n'ont pas encore vu les tests unitaires et/ou angular.

## Utilisation

1. Cliquez sur 'utiliser ce template'
2. Choisissez votre propre répo en répo de destination
3. Si vous souhaitez utiliser la branche `tests`, pensez à cocher la case "dupliquer toutes les branches". Dans le cas contraire, passer à l'étape 5.
4. Effectuez un merge de la branche `tests` vers la branche `main`
5. Partagez le répo en public à vos élèves et réalisez les exercices.

## Démarrer le projet


1. Clonez le projet et positionnez vous à sa racine
2. Tapez `npm i`
3. Tapez `ng serve -o` ou `npm start`

### Tests

- `npm run test` pour démarrer les tests unitaires avec JEST
- `npm run test:coverage` pour démarer les tests unitaires en mode coverage

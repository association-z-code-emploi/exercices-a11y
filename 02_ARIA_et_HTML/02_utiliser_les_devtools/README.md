---
tags:
  - exercises
  - a11y
---

# Exercice 02 : vérifier l'accessibilité ARIA avec les DevTools

Savoir utiliser l'onglet **Accessiblity** de Chrome DevTools pour lire le rôle, le nom et l'état d'un élément HTML est important pour un développeur qui s'intéresse ou code pour améliorer l'accessiblité d'un site web.

Cet exercice fait office de guide pour découvrir l'utilisation des DevTools.

## Consignes

Vous trouverez un fichier "index.html" dans ce dossier d'exercice que vous n'avez pas besoin de modifier ; vous n'avez qu'à l'ouvrir dans le navigateur Google Chrome pour commencer !

Une fois la page ouverte dans Chrome :

- faites un clic droit sur la page puis "**Inspecter**" (ou F12 pour ouvrir directement les DevTools)
- sélectionnez le bouton (`<button>`) puis cherchez la section "**Accessibility**" dans le panneau de l'inspecteur pour y voir :
  - **Role** : qui doit être `switch`
  - **Name** : c'est à dire `Mode sombre activé`
  - **Properties** : qui, pour `aria-checked`, est `false`

> ℹ️ Si "**Accessibility**" n'est pas visible, il faudra alors cliquer sur les "trois points" en haut à droite des DevTools puis "More tools" et enfin "**Accessibility**"

À vous maintenant pour la `<div>` :

- quel est son **rôle** ?
- quel est son **nom** ?
- quelle est sa **propriété** ?

### Conseils

- Les objectifs de cet exercice sont :
  - savoir ouvrir et utiliser l'onglet **Accessibility** dans les DevTools
  - savoir trouver et comprendre les **attributs**
- Même si vous n'avez pas tout juste du premier coup, l'important est de bien comprendre où lire l'info dans les DevTools, pas d'être parfait immédiatement.

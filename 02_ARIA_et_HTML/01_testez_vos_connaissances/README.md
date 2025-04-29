---
tags:
  - exercises
  - a11y
---

# Exercice 01 : testez vos connaissances !

## Consignes

Les questions ci-dessous contiennent entre 1 à 3 réponses correctes.

### À quoi permet l'utilisation de la sémantique HTML ?

- À améliorer la navigation pour les utilisateurs de technologies d'assistance
- À rendre le site plus rapide à charger
- À structurer la page pour la rendre plus compréhensible

### Quel est le rôle des balises `<h1>`, `<h2>`, etc... en terme d'accessibilité ?

- Définir des sections interactives de la page
- Organiser les titres de manière hiérarchique
- Faciliter la navigation

### À propos d'ARIA, que peut-on faire avec ses attributs ?

- Définir le fonction d'un élément
- Changer le style visuel d'un élément
- Donner des informations sur l'état d'un élément

### Quand faut-il utiliser ARIA ?

- Toujours, sans exceptions, pour maximiser l'accessibilité
- Uniquement si la sémantique HTML de base ne suffit pas
- Pour améliorer des éléments qui n'attirent pas assez l'oeil

### Dans l'exemple suivant, à quoi sert l'attribut `aria-describedby="warning"` ?

```html
<button aria-pressed="false" aria-describedby="warning">Supprimer</button>
<div id="warning">La suppression est définitive.</div>
```

- Il permet d'associer une description supplémentaire au bouton
- Il modifie l'action du bouton
- Il rend le bouton invisible

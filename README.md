# Frontend Mentor - Solution de profil de liens sociaux

Il s'agit d'une solution au [Défi de profil de liens sociaux sur Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Les défis Frontend Mentor vous aident à améliorer vos compétences en codage en construisant des projets réalistes.

## Table des matières

- [Aperçu](#aperçu)
  - [Le défi](#le-défi)
  - [Capture d'écran](#capture-décran)
  - [Liens](#liens)
- [Mon processus](#mon-processus)
  - [Construit avec](#construit-avec)
  - [Ce que j'ai appris](#ce-que-jai-appris)
  - [Développement continu](#développement-continu)
  - [Ressources utiles](#ressources-utiles)
  - [Collaboration IA](#collaboration-ia)
- [Auteur](#auteur)
- [Remerciements](#remerciements)

## Aperçu

Création d'une carte de profil d'un avatar proposée par Frontend Mentor. Ce projet couvre l'utilisation des variables CSS, des états de survol et de la responsivité.

### Le défi

Créer une carte de profil d'un avatar avec une accessibilité claire, un design fidèle à la maquette, l'utilisation des variables CSS et une bonne compatibilité pour tous les appareils.

### Capture d'écran

![Carte de profil avec une bonne accessibilité](./screenshot.png)

### Liens

- URL de la solution : [GitHub Repository](https://github.com/Harena-debug/social-links-profile)
- URL du site en direct : En cours de déploiement

## Mon processus

Voici le processus que j'ai mis en œuvre pour ce profil :

### Construit avec

- HTML5 sémantique
- Variables CSS personnalisées
- Flexbox pour le centrage et le layout
- Workflow mobile-first
- États CSS `:hover` et `:focus` pour l'interactivité
- Design responsive

### Ce que j'ai appris

Ce troisième projet m'a permis d'apprendre :

**Accessibilité CSS avec `:focus`**

J'ai découvert comment rendre les liens accessibles au clavier avec un état de focus visible :
```css
a:focus {
  outline: 3px solid var(--background-hover);
  outline-offset: 2px;
}
```

**Variables CSS pour la cohérence**

L'utilisation de variables CSS m'a permis de maintenir une cohérence dans tout le design :
```css
:root {
  --main-color: hsl(0, 0%, 8%);
  --content-color: hsl(0, 0%, 12%);
  --color-text: hsl(0, 0%, 100%);
  --font-family: "Inter", sans-serif;
  --background-text: hsl(0, 0%, 20%);
  --radius: 15px;
  --size: 0.875rem;
  --weight: 600;
  --background-hover: hsl(75, 94%, 57%);
}
```

Cela facilite grandement les modifications futures et assure une harmonie visuelle.

### Développement continu

Ce projet m'a permis de découvrir l'accessibilité en CSS, mais dans les projets futurs, j'aimerais vraiment mettre en pratique :

- **CSS Grid** pour des layouts plus complexes
- **Responsive Design optimisé** avec des media queries avancées
- **Accessibilité avancée** avec les attributs ARIA
- **Animations CSS** avec `@keyframes`

### Ressources utiles

- [freeCodeCamp](https://www.freecodecamp.org/) - Un nouvel endroit que j'ai découvert et qui est plutôt efficace pour apprendre de façon structurée.
- [W3Schools](https://www.w3schools.com/) - Toujours un endroit parfait pour apprendre et tester du code en temps réel.
- [MDN Web Docs](https://developer.mozilla.org/) - Documentation de référence pour HTML, CSS et JavaScript.

### Collaboration IA

J'ai collaboré avec des outils IA de la manière suivante :

- **Outils utilisés** : Claude et ChatGPT
- **Type d'aide** : Ils m'ont aidé sur des points spécifiques qui bloquaient mon projet (centrage, variables CSS, accessibilité)
- **Apprentissage** : J'ai pris le temps de comprendre leurs explications plutôt que de simplement copier-coller le code

## Auteur

- GitHub - [Harena-debug](https://github.com/Harena-debug)
- Frontend Mentor - [@Harena-debug](https://www.frontendmentor.io/profile/Harena-debug)

## Remerciements

Merci à Frontend Mentor de m'avoir proposé ce défi qui m'a fait pas mal progresser. Merci aussi aux outils IA qui m'ont accompagné dans ce parcours d'apprentissage.
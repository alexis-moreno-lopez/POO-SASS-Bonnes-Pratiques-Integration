# Les bonnes pratiques d'intégration

## 📺 Présentation

- [BEM Vs OOCSS : Les Bonnes pratiques CSS](https://docs.google.com/presentation/d/1fNYTcwJZwqy8fyE_CusmaBNlDHRCp9mgbsUyS3k2CvE/edit#slide=id.g56eb9f83d5_1_628)
- Veilles Techno :
    - [SMACSS](https://docs.google.com/presentation/d/1fNYTcwJZwqy8fyE_CusmaBNlDHRCp9mgbsUyS3k2CvE/edit#slide=id.g56eb9f83d5_1_628)
    - [OOCSS BEM](https://docs.google.com/presentation/d/1y9uWHdaach_pp8L_mG78WAmMAdFsDvrj3TZJtVboJas/edit#slide=id.gceaddd6305_0_50)

## 💡Les bonnes pratiques d'intégrations

### **Syntaxe OOCSS** (exemple : Bootstrap)

```css
<style>
  .btn {}            // Button structure
  .btn-small {}      // Button sizing
  .btn-blue {}       // Button colour
</style>
```

```html
<a href="#" class="btn btn-small btn-blue">Click me!</a>
```

### **Syntaxe BEM** (exemple : Material Design Lite)

```html
<div class="block block--modifier">
  <div class="block__element"></div>
  <div class="block__another-element"></div>
  <div class="block__element--modifier"></div>
  <div class="block__another-element--another-modifier"></div>
</div>
```

## ⛳ Exercices

### Cascade et héritage :
- [Exercice 1](https://codepen.io/J-r-my-Michel/pen/NWJXBxe)
- [Exercice 2](https://codepen.io/PedroIdmkr/pen/ZZdGYK)

### La spécificité :
#### Ressources :
- [Calculer la spécificité css](https://cours-web.ch/css/specificite.html)
- [Calculer la spécificité css 2](https://enseignement.leomartin.net/upem/2020-2021/modules/css/3-selecteurs/5-specifite/1-calcul.html)
- [Assigning property values, Cascading, and Inheritance](https://www.w3.org/TR/CSS2/cascade.html#specificity)

#### Exercices :
- [Exercice](https://codepen.io/J-r-my-Michel/pen/xxBYZKP)


### BEM :
- [Exercice BEM](https://codepen.io/PedroIdmkr/pen/eoagjO)

## 🛠 TP
- Clonez le projet suivant et suivez les consignes du README : [GitHub - simplon-roanne/yellow-sass: Intégration d'une...](https://github.com/g404-dev-web/yellow-sass)

## Pour aller plus loin...
- [Cascade et héritage - Apprendre le développement Web | MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)
- [8 règles pour organiser son code CSS – alticreation](https://alticreation.com/8-regles-organiser-code-css/) / [30 CSS Best Practices for Beginners](https://webdesign.tutsplus.com/30-css-best-practices-for-beginners--net-6741t)
- [CSS objet et CSS fonctionnel – 24 jours de web](https://www.24joursdeweb.fr/2018/css-objet-et-css-fonctionnel/)
- [Atomic Design by Brad Frost](https://atomicdesign.bradfrost.com/)

# 🏆 Objectifs

1. Comprendre les concepts de cascade, d'héritage et spécificité.
2. Comprendre et maîtriser les bonnes pratiques de nommage de classes CSS.
3. Choisir et respecter une méthodologie d'intégration dans un projet web.
4. Comprendre et utiliser les fonctionnalités avancées du langage (mixin, fonction, liste, etc.).
5. Utiliser un compileur CSS pour le développement optimal d'une interface.

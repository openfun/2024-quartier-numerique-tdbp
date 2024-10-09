---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background:
# some information about your slides (markdown enabled)
title: Les tableaux de bord pédagogiques chez FUN
# info: 
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# Les tableaux de bord pédagogiques chez FUN

Les indicateurs existants

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
transition: fade-out
layout: center
---

# Pourquoi construire des tableaux de bord ?

1. Répondre à une demande accrue de suivi des cours en ligne
2. Acquérir des insights précis sur l'activité des cours et leur suivi
3. Permettre à toutes les parties prenantes de monitorer et de prendre des décisions
   informées sur les cours.
4. Aligner les actions sur les objectifs spécifiques de chaque acteur dans
   l'apprentissage en ligne
5. Maximiser la réussite et l'efficacité de l'apprentissage en ligne

<!-- Objectif: Présenter les indicateurs que FUN propose aujourd'hui dans ses différentes
activités

1. Pourquoi FUN propose ces indicateurs là ?
Car ils répondent au besoin des utilisateurs de la plateforme

2. Pourquoi répondent-ils au besoin des utilisateurs ? 
Car les utilisateurs veulent connaître ses informations sur l'activité des cours

3. Pourquoi les utilisateurs veulent connaitre des infos sur l'activité des
   cours ? 
    a. Car en tant qu'apprenant, on veut savoir où on en est
    b. Car en tant qu'enseignant, on veut savoir ce qu'apprennent et comment ils
apprennent
    c. Car en tant qu'équipe pédagogique, on veut savoir comment réagissent les
apprenants face au contenu proposé pour dispenser le cours
    d. Car en tant qu'administrateur, on veut savoir l'efficacité des cours dispensés
par l'établissement

4.a. Pourquoi l'apprenant veut savoir où il en est ? 
Pour orienter ses efforts, avoir confiance en lui dans sa réussite, planifier
son travail
4.b. Pour savoir si son contenu est de bonne qualité et est adapté pour le cours
4.c. Pour savoir si le cours a été bien construit
4.d. Pour savoir si le cours est utile et la stratégie de diffusion est bonne

5. Pourquoi veulent-ils ça ? 
Pour réussir la mission de l'apprentissage en ligne
a. réussir son cours
b. transmettre son savoir
c. assurer la bonne transmission du cours
d. dispenser des cours de qualité

 -->

---
transition: fade-out
layout: image
image: ./cycle-vie.png
backgroundSize: 80%
---

---
transition: fade-out
layout: image
image: ./dimensions.png
backgroundSize: 45%
---

---
transition: fade-out
layout: image
image: ./metiers.png
backgroundSize: 45%
---

---
transition: fade-out
layout: section
---

# 🏭
# Construire l'outil de learning analytics de FUN

---
transition: fade-out
layout: default
---

## Étapes clés pour la mise en place des tableaux de bord

![Stack Analytics](./stack-analytics.png)

## Avantages des choix techniques

* Interopérabilité et standardisation
* Collecte et analyse en temps réel
* Flexibilité et évolutivité

---
transition: fade-out
layout: section
---

# 📈
# Calculer et définir les indicateurs pédagogiques

---
transition: fade-out
layout: default
---

## Bibliothèque d'indicateurs par ressource pédagogique

* Système de plugins dédiés par type de ressource pédagogique
* Calcul réalisé sur des données xAPI générés depuis la ressource concernée par
  le plugin 

```bash
$ pip install warren-video

$ npm i @openfun/warren-video
```

## Exemple. Plugin `document`

- Indicateurs de téléversement et de téléchargement des documents sur une
  plateforme
- Données requêtées sont générées par cette plateforme et respectent la syntaxe
  du profil xAPI `document`
- Composants frontend de vue quotidienne de téléchargements, de nombre de
  personnes ayant téléchargés les documents pour un cours...

> Ajouter visuels

---
transition: fade-out
layout: section
---

# 💬
# Récolter les besoins utilisateurs

---
transition: fade-out
layout: section
---

## Co-construction avec les utilisateurs finaux

* Groupe de travail
* Co-construction avec le recueil des besoins 

*A developper*

---
transition: fade-out
layout: section
---

## Quels indicateurs pour la formation initiale ? 

---
transition: fade-out
layout: section
---

## Quels indicateurs pour la formation professionnelle ?

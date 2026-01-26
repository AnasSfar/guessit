# 🎯 GuessIt

**GuessIt** est un jeu de devinettes de mots développé en **Elm**.  
À partir de définitions, le joueur doit retrouver le mot correspondant selon le **mode de jeu** et la **difficulté** choisis.

Le projet est jouable directement dans le navigateur et déployé via **GitHub Pages**.
Voici le lien : 
---

## 🕹️ Modes de jeu

### 🎯 Mode Classique
- Temps illimité
- Tentatives illimitées
- Bouton **“Afficher le mot”** disponible
- Mode idéal pour découvrir le jeu et apprendre

### ⏱️ Mode Express
- Temps limité (sélectionnable via un **curseur** avant de lancer la partie)
- **Une seule tentative par mot**
- En cas d’erreur :
  - la bonne réponse est affichée
  - le score diminue (-1)
  - passage automatique au mot suivant

---

## 🎚️ Difficultés

- 🌱 **Beginner** : définitions simples
- ⚡ **Medium** : difficulté intermédiaire
- 🔥 **Expert** : définitions plus complexes et précises

La difficulté influence le nombre et le type de définitions affichées.

---

## 🚀 Lancer le jeu

### En ligne (GitHub Pages)
👉 https://anassfar.github.io/guessit/

---

### En local (après avoir installer tout les fichiers)

Assure-toi d’être dans le dossier contenant `index.html`, `elm.js` et `README.md`.

```bash
elm reactor

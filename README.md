# BigWallQuest2000

# BigWallQuest — Notes de version (v0.2 → v0.14)
Généré le 2026-10-20 · version courante : **L7 v0.14** · fichier unique HTML, hors-ligne, zéro traceur, zéro compte.

> Lecture rapide : le schéma `BigWallQuest_NotesDeVersion_L7_v0.12_2026-10-16.png` résume tout sur une page. Ce fichier donne le détail.

## Comment lire les numéros
Chaque livraison porte un **lot (L3…L7)** et une **version (v0.x)**. Le compteur « v » est reparti à v0.1 au lot 4 (L3 v0.2 → L4 v0.1), puis a continué à v0.5 au lot 5 : l'ordre chronologique ci-dessous fait foi, pas le numéro seul.

---

## L7 — Mettre le jeu entre les mains des amis

### v0.14 · 2026-10-19 — Problèmes Tension Board
- 🟦 **Bouton « Problème Tension Board »** dans « Gym bloc » : nom du problème, angle du mur (20° → 50°) et nombre d'essais, tout optionnel.
- ⚡ Choisir « À vue » ou « Flash » remet les essais à 1.
- 🔒 Ces infos restent sur le téléphone : **jamais envoyées** sur la carte de cordée. Elles sont gardées dans la sauvegarde complète et dans l'export CSV (colonne `probleme_tension`).
- 📄 Mode d'emploi : `docs/BigWallQuest_TensionBoard_L7_v0.14_2026-10-19.md`.

### v0.13 · 2026-10-16 — Une salle par séance
- 📍 La salle se choisit une fois au début de la séance.

### v0.12 · 2026-10-16 — Scénettes, cams, fin de séance
- 🪢 **Cams Black Diamond** : 9 tailles (#0.2 → #4) avec les bonnes couleurs ; le tri de rack tire 5 cams parmi les 9.
- 🟣 **Question « meilleure cam de la Terre ? »** : Violet, violet, violet ou violet (toutes bonnes).
- 🎬 **Scénettes par résultat** : à vue = pose de dieu grec, biceps en feu 💪🏼 · après essais = hochement de tête · tombé à sec = un ami te frotte le dos. Flash (éclairs) et échec (chute + cri) inchangés. Option « Scénettes » pour les couper.
- 🎺 **Fin de séance** : écran TADAAA + son, XP gagnés, 7 barres de stats, 2 messages d'encouragement (black bean, cris d'Adam, Malik, Bernard).
- 🧗 **Voie indoor** : seulement Zéro Gravité, Allez Up (Pointe-Saint-Charles) et Monolithe.
- 🪨 **Roche** : texture générée dans le jeu, prises bien visibles, mains et pieds posés dessus.

### v0.11 · 2026-10-15 — Séance multi-activités
- 🏁 **Séance = plusieurs activités** (bloc, voie, muscu, stretching) : on démarre, on ajoute, on clôture. 1 séance = 1 dans l'objectif de la semaine. Oubli de clôture : fermeture auto après 16 h.
- ⭐ **Mes exercices de muscu** (30 max) + stretching + durées courtes (10 et 20 min).
- 🍍 **Bouton ananas à lunettes** : proposer une idée / un bug / une question par partage du téléphone, WhatsApp, SMS, courriel. Aucun contact dans le jeu, rien ne part tout seul.

### v0.10 · 2026-10-15 — Cordée « boîte aux lettres »
- 👥 3 persos jouables par défaut ; limite de persos réels portée de 3 à 6 ; fusion de sauvegarde par prénom (pas de doublons).
- 📬 **Cordée sans code ni serveur** : le jeu lit les cartes publiques `cordee/<prénom>.json` de son propre site GitHub Pages. Aucune clé, aucun jeton.

---

## L6 — Son, échec, intro

### v0.9.1 · 2026-10-15 — Correctif iOS
- 🔊 Corrige « Failed to start the audio device » : le son repart au prochain toucher quand iOS reprend la main (appel, autre appli).

### v0.9 · 2026-10-14 — Intro
- 🎞️ Intro allongée de 10 s, transitions « morphing » entre les scènes (WebGL, simple coupure si indisponible), scène finale = ascension et transformation divine.

### v0.8 · 2026-10-15 — Échec
- 💥 Résultats « Échec » et « Tombé / à sec, mais toppé » pour bloc, corde et voie.
- Cinématique de chute dans le décor de l'intro, avec cri et petite musique.

### v0.7 · 2026-10-14 — Son
- 🔊 Moteur audio v2 (bus, limiteur, mode doux), ~25 effets, ambiances, écran « Boîte à sons ».

---

## L5 — Mini-jeu et matériel

### v0.6 · 2026-10-14 — Refonte du matériel
- 🧰 Dessins 2D réalistes (cams à lobes, slings, dégaines, portaledge) et modèles 3D. Marque fictive, rien de réel copié.

### v0.5 · 2026-10-14 — Tri de rack
- 🎯 Mini-jeu « Tri de rack » (3 niveaux, meilleurs scores sauvegardés).
- ⚡ Mini-défi rapide après chaque bloc enregistré, avec « Passer » toujours possible.
- 👁️ Cinématique « éclair dans chaque œil » pour un à vue / flash.

---

## L4 — Cordée, skills, objectifs

### v0.4 · 2026-10-13
- 🎯 Objectif « Max flash en corde » (défaut 5.11b, réglable par perso). Skill big wall « Montage du portaledge ».

### v0.3 · 2026-10-13
- 📈 Skills = chaînes de semaines en « Maîtrisé » (5 de suite = 100 %). 8e skill « Rescue en cordée ». Stats ralenties pour viser le niveau 8 à l'été 2027.

### v0.2 · 2026-10-13
- ✅ Boîte de confirmation dans le jeu (le `confirm()` natif est bloqué sur certains appareils). Bouton Supprimer / Réinitialiser toujours visible. Skills en % d'expérience.

### v0.1 · 2026-10-13 — Cordée
- 🔐 Synchro chiffrée **sans serveur** : code d'invitation + paquets copiés-collés (AES-GCM). Rien ne part tout seul, barre de progression à chaque envoi.

---

## L3 — Séances guidées

### v0.2 · 2026-10-13
- 🏋️ Catalogue de séances guidées (force, endurance, technique, mobilité) sans aucune charge ni donnée perso, lien public vers la vidéo Black Bean.

---

## Ce qui n'a pas changé depuis le début
- Un seul fichier HTML ; aucun traceur ; aucun compte ; aucune donnée personnelle dans le code.
- Réseau : uniquement le propre site du jeu (version hébergée GitHub Pages).
- Les anciennes sauvegardes se chargent telles quelles.

## Limites connues (v0.14)
- Rien n'a été essayé sur un vrai iPhone ni Android : les tests tournent sur un navigateur de test.
- La texture de roche prend ~1 s à générer sur un ordinateur, davantage sur un vieux téléphone.
- Sur certaines combinaisons de personnages, la main de l'ami peut chevaucher un peu le joueur dans la scène de réconfort.
- Mise à jour : déposer `index.html` et `sw.js`, puis fermer et rouvrir l'app 1 à 2 fois.

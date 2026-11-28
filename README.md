# WOD HUB — ROWOD & TAROT WOD

Jeux de fitness en groupe pour la box, dans une seule page web qui s'installe comme une app sur iPhone ou Android. Pas de compte, pas de serveur : tout tourne dans le téléphone.

**👉 Ouvrir l'app : https://TON-NOM.github.io/NOM-DU-DEPOT/**

---

## Les jeux

### 🚣 ROWOD — Row. Rep. Repeat.

Un rameur, une équipe, des combos *distance + mouvement*.

- À chaque tour, **un joueur rame** la distance du combo le plus vite possible.
- Pendant ce temps, **les autres enchaînent le maximum de reps** du mouvement.
- L'app chronomètre le rameur et compte les reps de chacun.
- **Rotation** : tout le monde passe au rameur sur chaque combo.

**3 modes de jeu**

| Mode | Principe |
|---|---|
| All Fixed | Combos fixés à l'avance, vous choisissez l'ordre |
| Dice Combo | Combos fixés, le dé choisit lequel jouer |
| Full Random | Distance et mouvement tirés au hasard, indépendamment |

**Options** : nombre de rounds ou limite de temps · ordre des joueurs (fixe, tournant, aléatoire) · combos répétables · pénalités si la distance exacte n'est pas atteinte (burpees ou autre au round suivant) · bonus « distance exacte » qui pénalise les autres · coefficients de distance par joueur (10–200 %) pour équilibrer les niveaux.

**Scores** : classement par joueur et par mouvement, avec les vrais ex æquo.

### 🃏 TAROT WOD

On tire des cartes de tarot, chaque carte donne un exercice.

- **La couleur** (♥ ♦ ♣ ♠ et les atouts) définit le mouvement, choisi avant la partie.
- **La valeur** donne le nombre de reps : As = 1 · 2 à 10 = valeur · Valet 11 · Cavalier 12 · Dame 13 · Roi 14 · Atouts 1 à 21 = valeur.
- **L'Excuse** donne un jeton réutilisable : le joueur peut l'utiliser à tout moment pour absorber les reps d'une carte sans faire le mouvement.
- **Les Jokers (option)** sont des cartes pénalité ajoutées au jeu : tirer un Joker = faire la pénalité choisie (burpees, run, row…). Un Joker vaut 0 rep au classement.

**Options** : un paquet partagé ou un paquet par joueur · plusieurs paquets · design Classique ou CrossFit · fin de partie quand toutes les cartes sont jouées ou à la fin d'un temps limite.

**📸 Selfies (option)** : la caméra frontale prend une photo environ 1 s après chaque carte tirée, pour capter la réaction. Chaque photo porte la carte, les reps et le mouvement. À la fin : galerie par joueur, film des selfies, et enregistrement dans Photos (images ou vidéo) via le menu de partage. Les photos restent dans le téléphone et disparaissent en quittant les scores si on ne les enregistre pas.

### ⏱ Workouts & Timers

- **Timers** : Stopwatch (For Time), Countdown (AMRAP), Interval (EMOM), Tabata.
- **Classics** : les WODs de référence (Fran, Grace, Helen, Murph…) avec chrono intégré.
- **Custom** : créez et enregistrez vos propres WODs.

---

## Installer l'app

### iPhone / iPad

1. Ouvrir le lien de l'app dans **Safari** (pas Chrome).
2. Toucher le bouton **Partager** (carré avec une flèche vers le haut).
3. Choisir **Sur l'écran d'accueil**, puis **Ajouter**.

L'app s'ouvre alors en plein écran, comme une vraie app.

### Android

1. Ouvrir le lien dans **Chrome**.
2. Menu **⋮** → **Ajouter à l'écran d'accueil** (ou **Installer l'application**).

### Ordinateur

Le lien marche aussi dans n'importe quel navigateur (pratique sur un grand écran dans la box).

---

## Utilisation

1. **Players** : ajoutez les joueurs (nom, avatar emoji ou photo), puis touchez-les pour les sélectionner.
2. **Exercises** : cochez les mouvements disponibles dans la box (poids du corps, barre, haltères, kettlebell, cardio).
3. Choisissez un jeu, réglez les options, lancez.

**Sauvegarder une config** : dans *Games*, *Save config* garde joueurs + réglages pour la relancer plus tard avec *Load config*.

## Vos données

- Joueurs, exercices, configs et WODs perso sont enregistrés **dans le téléphone uniquement** (stockage du navigateur). Rien n'est envoyé sur internet.
- **Changer de téléphone ou réinstaller l'app efface ces données.** Avant, faites **Players → Export** : l'app donne un code à copier (Notes, mail…). Sur le nouvel appareil : **Players → Import** et collez le code.

## Mettre à jour

L'app se met à jour quand le fichier `index.html` du dépôt change (déploiement GitHub Pages en 1 à 2 minutes). Si l'ancienne version reste affichée :

- fermer complètement l'app et la rouvrir ;
- sinon, ouvrir le lien dans Safari en ajoutant `?v=2` à la fin pour forcer le rechargement ;
- en dernier recours, supprimer l'icône et réinstaller (faire un Export avant).

## Fichiers du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Toute l'application (une seule page) |
| `apple-touch-icon.png` | Icône sur l'écran d'accueil iPhone |
| `README.md` | Ce fichier |

---

Conception : Jean-Baptiste Sibarita · Développement avec Claude (Anthropic) · Fait avec 🧡 à Bordeaux

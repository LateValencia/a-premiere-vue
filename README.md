# À première vue

Entraînement à la lecture de notes : **150 notes, 3 minutes**. Version web installable sur iPhone, adaptée de l'appli Mac « À première vue » (v0.6). Le clavier et la charte graphique viennent de [Clé de lecture](https://github.com/LateValencia/cle-de-lecture).

## Règles

- +1 par note juste **à la bonne octave**, −1 maximum par note à trouver, quel que soit le nombre d’essais ; la note reste active tant qu'elle n'est pas trouvée.
- 100 points valident le niveau, qui passe en vert ; tous les niveaux restent accessibles (★ dès 100, ★★ dès 140, ★★★ à 150).
- **Le chrono de 3 minutes ne démarre qu'à la première note jouée.**
- La séance s'arrête dès que les 100 points ne sont plus atteignables.
- **Points bonifiés** : chaque niveau rapporte 25 % de plus que le précédent (×1 ; ×1,25 ; ×1,56 ; ×1,95 ; ×2,44). Les points de chaque séance s'ajoutent à un total, même quand le niveau n'est pas réussi.
- Douze notes par ligne (3 mesures de 4 noires) ; la ligne suivante apparaît pendant la dernière mesure.

## Niveaux (par clé)

Cinq niveaux, dont la tessiture s'élargit : en clé de sol de Do4–Sol4 jusqu'à La3–La5, en clé de fa de Mi2–Si2 jusqu'à Mi2–Mi4 (avec lignes supplémentaires).

### Partitions bonus

Chaque niveau réussi débloque une **partition bonus** : une vraie chanson du domaine public, écrite uniquement avec les notes du niveau (mêmes touches que l'exercice), avec ses durées, ses mesures et ses ligatures. Pas de chrono ; à la fin, l'appli rejoue la mélodie. Points : score × bonus du niveau, plus 50 points (× bonus) si la partition est jouée sans faute.

| Niveau | Clé de sol | Clé de fa |
|---|---|---|
| 1 | Ode à la joie (Beethoven) | Au clair de la lune |
| 2 | Ah ! vous dirai-je, maman | Ode à la joie |
| 3 | Frère Jacques | Frère Jacques |
| 4 | Joyeux anniversaire | Ah ! vous dirai-je, maman |
| 5 | Douce nuit (Gruber) | Joyeux anniversaire |

## Clavier

Un seul clavier, sur une rangée, aux proportions d'une vraie touche de piano (23,5 × 150 mm), 21 % plus large : **seulement les touches de l'exercice**, de la note la plus grave à la plus aiguë du niveau, dans la limite de 73 touches (Do1 → Do7). La séance se joue **en mode paysage**, le clavier centré sous la portée. Aucune touche ne porte de nom ; seul le do central a une pastille.

## Installer sur iPhone

Ouvrir l'adresse GitHub Pages dans Safari, puis Partager → « Sur l'écran d'accueil ». Tout fonctionne en local : la progression et les 200 dernières séances restent sur l'appareil. Le son passe par le haut-parleur (désactiver le mode silencieux si besoin).

## Son

Le clavier joue de vrais échantillons de piano à queue : **Salamander Grand Piano** d'Alexander Holm (licence [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)), dans la version MP3 diffusée par [Tone.js](https://github.com/Tonejs/audio). Un échantillon toutes les trois demi-tons, du La0 au Do8 ; les notes intermédiaires sont transposées. Seules les octaves du niveau choisi sont chargées. Sur iPhone (iOS 17 et plus), le son passe même en mode silencieux.

## Jouer avec un vrai piano

Activer « Écouter le piano » et autoriser le micro. Une note à la fois : la touche reconnue s’assombrit brièvement, même hors séance. Pendant la séance, les notes reconnues répondent à l’exercice. L’analyse reste sur l’appareil, sans enregistrement ni envoi de son. La reconnaissance dépend du micro et du bruit ambiant ; les accords ne sont pas pris en charge.

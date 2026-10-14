# labStudio-images
Laboratoire créatif dédié à la génération d'images par IA : méthodes de prompting, styles artistiques, techniques visuelles, modèles réutilisables et expérimentations.
### 1. Notre philosophie : tout prévoir, sans tout imposer  
Je propose de classer chaque option selon son niveau de prise en charge.
1. Notre philosophie : tout prévoir, sans tout imposer
Je propose de classer chaque option selon son niveau de prise en charge.
Statut	Signification
Native	Réglage directement pris en charge par l'outil
Prompt	Instruction exprimée en langage naturel
Experimental	Technique à tester, résultat non garanti
Future	Capacité envisagée pour de futurs modèles
Unsupported	Non disponible dans l'outil actuel, mais conservée dans notre catalogue
Ainsi, on pourra documenter un objectif comme « profondeur de champ très précise » même si le modèle ne propose pas de réglage numérique correspondant.
On ne bride pas notre imagination. On garde simplement une trace fiable de ce qui fonctionne réellement.

| **Statut**       | **Signification**                                                                 |
|--------------|-------------------------------------------------------------------------------|
| Native       | Réglage directement pris en charge par l'outil                                 |
| Prompt       | Instruction exprimée en langage naturel                                       |
| Experimental | Technique à tester, résultat non garanti                                      |
| Future       | Capacité envisagée pour de futurs modèles                                     |
| Unsupported  | Non disponible dans l'outil actuel, mais conservée dans notre catalogue       |

> Ainsi, on pourra documenter un objectif comme « profondeur de champ très précise » même si le modèle ne propose pas > de réglage numérique correspondant.
> On ne bride pas notre imagination. On garde simplement une trace fiable de ce qui fonctionne réellement.

2. Le catalogue des possibilités du laboratoire
Voici les grandes familles que je prévois. Ce n'est pas une liste fermée : nous pourrons ajouter des propriétés sans reconstruire tout le système.
```
01 **Sujet et narration**
    >Sujet principal, action, interactions, époque, contexte, émotion, histoire racontée


02

Style et techniques artistiques
Mouvements, médiums, aplats, silhouettes, traits, textures, niveaux d'abstraction, références artistiques


03

Composition
Règle des tiers, symétrie, rythme, espaces négatifs, points focaux, couches visuelles


04

Caméra et optique
Angle, focale, objectif, ouverture, zoom, distance, perspective, profondeur de champ, distorsion


05

Lumière
Direction, intensité, température, diffusion, ombres, contre-jour, éclairage de studio, sources multiples


06

Couleur
Palettes, harmonie, saturation, luminance, contraste, color grading, LUT, profils colorimétriques


07

Matières et surfaces
Rugosité, réflexion, transparence, translucidité, usure, grain, rendu plat ou volumétrique


08

Atmosphère et environnement
Brume, pluie, poussière, fumée, météo, saison, particules, perspective atmosphérique


09

Références et contrôles visuels
Images de style, composition, personnage, pose, profondeur, masques, esquisses, cartes de contrôle


10

Sortie et qualité
Ratio, résolution, cadrage, transparence, cohérence de série, upscaling, variations


11

Contraintes et exclusions
Éléments obligatoires, éléments interdits, priorités, zones à préserver


12

Génération et reproductibilité
Modèle, version, seed, paramètres natifs, prompt exact, références utilisées, historique des essais
```

Cela nous donne déjà 12 familles de paramètres à explorer. Chaque famille pourra contenir des dizaines de propriétés et de techniques.

# 3.Comment les intégrer à notre GitHub  
Je conserverais notre structure validée et j'ajouterais un catalogue transversal d'options.  
```
labStudio-images/
│
├── README.md
│
├── Styles/
│   └── Atmospheric-Silhouette/
│       ├── README.md
│       ├── prompt.md
│       ├── References/
│       ├── Images/
│       └── Experiments/
│           └── v3-test.md
│
└── Options/
    ├── README.md
    ├── Camera/
    ├── Composition/
    ├── Lighting/
    ├── Color/
    ├── Materials/
    ├── Atmosphere/
    ├── References/
    └── Output/
```
### 4. Une propriété doit être testable  
Prenons une option ambitieuse : Depth of Field.
Au lieu d'écrire simplement « profondeur de champ », notre catalogue pourra conserver :
```
Depth of Field — Profondeur de champ
Propriété	Exemple
Catégorie	Camera / Optics
Ouverture	f/1.4, f/2.8, f/8, f/16
Distance de mise au point	2 m
Focale	85 mm
Plan focal	Sujet principal
Arrière-plan	Flou progressif
Méthode	Native / Prompt / Experimental
Résultat du test	À documenter
```
Même si une IA ignore f/2.8, nous conservons cette valeur et nous testons son effet. Nous ne prétendons simplement pas qu'elle contrôle physiquement l'optique.
### 5. Notre règle pour Experiments/  
Chaque expérience devra permettre de répondre à quatre questions :
1. Qu'avons-nous demandé ?
2. Qu'avons-nous envoyé réellement à l'IA ?
3. Qu'avons-nous obtenu ?
4. Qu'avons-nous appris ?
Cela permettra de tester les propriétés isolément, puis de les combiner pour découvrir des interactions intéressantes.
Et surtout, nous pourrons comparer les résultats entre différents modèles, au lieu de dépendre d'une seule IA.

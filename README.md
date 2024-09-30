<h1 style="text-align:center;">AQUARIUM</h1>

## <span style="color:#66CCFF">Idées</span><br>
**Concept :**
Le projet utilise des télévisions cathodiques pour afficher des poissons en 3D dans un aquarium virtuel. Quand une personne s'approche de l'écran, des capteurs déclenchent une réaction des poissons, qui viennent à sa rencontre. Après quelques minutes, les poissons se mettent à danser.

**Objectif :**
Divertir les visiteurs dans un environnement rétro et nostalgique.
<br>

**Inspiration :**
J'ai eu l'idée de conceptualiser ce projet pendant que j'envoyais le signal de mon lecteur VHS par antenne à un Watchman (petite télévision portative des années 90). J'ai par la suite été inspirée par les mondes aquatiques dans la série de jeux Donkey Kong Country sur SNES, les télévisions/iMac converti en aquarium et aussi le département des aquariums dans les animaleries.
<hr>

## <span style="color:#66CCFF">Scénario</span><br>
**Logigramme de l'interactivité**
```mermaid
graph TD;
    A[ENTRÉE]-- État initial sans visiteur -->B([Les poissons nagent tranquillement]);
    B-->C{Interaction};
    C-- Visiteur en mouvement -->D([Les poissons suivent le mouvement]);
    C-- Visiteur en observation -->E([Après quelques minutes, les poissons dansent]);
    D-->F[SORTIE];
    E-->F[SORTIE];
    
```
**Expérience utilisateur :**
Les visiteurs circulent dans un corridor composé de télévisions cathodiques superposées qui simulent les installations d'aquarium dans une animalerie. Des bandes de lumières RGB encadrent chacunes des télévisions et diffusent une teinte personnalisée selon l'environnement diffusé. Des haut-parleurs diffusent de la musique d'ambiance et des lumières éclairent indirectement le corridor.<br>
<br>
Des capteurs de mouvements détectent la présences des visiteurs et attirent des poissons 3D vers ceux-ci. Après un certain temps, les poissons s'animent selon l'emplacement du visiteur pour exécuter une danse au rythme d'une musique plus mouvementée. Les lumières changent de couleurs et s'animent au rythme de la musique.
<br>
<hr>

## <span style="color:#66CCFF">Ambiance</span>
**Moodboard visuel**
![Moodboard visuel](./images/moodboard_visuel.png)<br>
**Moodboard sonore**<br>
[État initial et en mouvement](https://pixabay.com/music/ambient-deep-in-the-ocean-116172/) <br>
[Danse des poissons](https://pixabay.com/music/ambient-wondrous-waters-119518/)
<br>
<hr>

## <span style="color:#66CCFF">Technologie</span>
**Logiciels :**
TouchDesigner, Arduino IDE, Maya, Illustrator, After Effect <br>
<br>
**Matériel**
- M5Stack :
    - AtomPoE
    - AtomLite
    - PbHub unit
    - PIR unit
    - Light unit
    - RGB LED strip

- Affichage :
    - Télévisions CRT ou LCD

- Éclairage :
    - American DJ 5P HEX

- Autres :
  - Ordinateur
  - Barres d'alimentation
  - Rallonges électriques
  - Câbles USB type C
  - Câbles XLR
  - Adaptateur XLR à USB
  - Câbles HDMI/ RCA/ S-Video/ YPbPr (selon le type de TV) + adaptateurs
  - Meuble DIY pour installer les écrans
  - Structure + accessoires pour installer les lumières
  - Haut-parleurs
  - Trépieds pour haut-parleurs



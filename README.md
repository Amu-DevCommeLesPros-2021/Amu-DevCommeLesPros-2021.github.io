- toc
{:toc}

# Introduction

## Thierry Seegers

Né à Montréal, Québec, Canada, il travaille pendant une vingtaine d’années dans la Silicon Valley jusqu’en 2019 quand il immigre à Marseille, France.
Il a donc un accent un peu bizarre parfois, il a un vocabulaire anglophone du travail et il a aussi compris qu’on ne dit pas du mal de l’OM.

<figure>
    <img src="assets/images/devpro-d-ou-je-viens.png" width=400>
</figure>

Vous pouvez le joindre :
- sur Slack à [https://devcommelespros.slack.com](https://devcommelespros.slack.com) ([invitation](https://join.slack.com/t/devcommelespros/signup))
- par courriel à [thierry.seegers@univ-amu.fr](mailto:thierry.seegers@univ-amu.fr)
- [site perso](https://thierry-seegers.pedaweb.univ-amu.fr/)

Pourquoi Slack ?
Je me doute bien que vous préféreriez un serveur Discord plutôt que d'installer un énième outil de communication.
Seulement Slack est aujourd'hui l'outil de communication préféré de la gent ingénieure californienne.
Du coup, je suis essentiellement toujours disponible sur Slack.
Je peux vous rejoindre sur Discord (`CPP_Medium_Rare#9310`) mais je n'y suis pas «par défaut».

## Objectif du cours

Je viens vous faire profiter de mes connaissances et de mon expérience de la pratique du développement de logiciel en milieu professionnel.
J’ai travaillé dans plusieurs compagnies, des grandes multinationales et des petites d’une vingtaine d’employés.
Les domaines ont été divers : l’audio dans des systèmes embarqués, les plugins de navigateurs web, le [livre numérique](https://fr.wikipedia.org/wiki/Livre_num%C3%A9rique), l'analyse de réseau, la vidéo-conférence sur mobile, etc.

Nous verrons les outils, méthodes et pratiques utilisés pour le développement de logiciel en milieu professionnel de nos jours.
L'objectif est d'améliorer votre qualité de vie en tant qu'étudiant·e en génie logiciel, de faciliter l'accomplissement de vos travaux académiques, présents et futurs, et de vous faire travailler dès à présent comme des professionnels·les.
Je souhaite que vous faire cochez le plus de cases possible lors de vos entretiens d'embauche.

Je donne ce cours avec l'idée que dans à peine plus de deux ans, vous serez parmi mes collègues de travail.
Je communiquerai donc avec vous avec cette perspective.
C'est aussi dans cette optique que je vous encourage lorsque vous avez des questions hors des heures de TPs, à les poser sur [Slack](https://devcommelespros.slack.com).
La communication y sera plus immédiate (dans la limite du raisonable !) et fluide que par mail.
Vous trouverez sur Slack une chaîne «général» et une chaîne pour chaque exercice.

# Structure du cours

Le cours consiste en des enseignements sur la pratique de la programmation en tant que professionnel·le, cinq exercices et un projet.
Ce cours est évalué «en continu» et il n'y aura pas d'examen final.

## Modalité d'enseignement

Nous essayons tous d'être flexible étant donné les circonstances.
Jusqu'à nouvel ordre tous les CMs et les TPs seront donné via AMUZoom par ma «[salle Zoom personelle](https://univ-amu-fr.zoom.us/j/2421033910)» (numéro d'identification : 242 103 3910).
L'URL de la conférence Zoom pour chaque cours et TP reste donc le même pour toute la durée du cours.
## La théorie

Le matériel théorique du cours est [ici](https://thierryseegers.github.io/DevCommeLesPros-CoursMagistral/).
Les cours magistraux ne seront pas que de la théorie.
Je vais au maximum démontrer devant vous ce dont il est discuté.
Ces parties «démos» des cours seront par la suite mises en ligne.
Les liens seront mis à jour dans cette table.
Ils seront aussi ajoutés à [cette playlist](https://youtube.com/playlist?list=PLetmUjNPuBalv30pXt4F75ZzV8I3MEoMJ).

| Date | Liens Démos |
| - | - |
| lundi 8 février, 13:30 | [tasks.json](https://youtu.be/fzrJLBHPOZ8), [débogage](https://youtu.be/FCWav7WDP4A), [journal](https://youtu.be/WeWelga5KVI) |
| mercredi 10 février, 10:15 | [git basics](https://youtu.be/3x_g2A4pNFY), [git branching](https://youtu.be/MeZTm9Ye7yM), [makefile](https://youtu.be/PD_9MTguNTU) |
| lundi 22 février, 13:30 | |
| vendredi 12 mars, 13:30 | |
| mardi 23 mars, 10:15 | |

## Les exercices

Les trois premiers exercices sont à compléter seul.
Les deux derniers, en binôme.
Chaque exercice comporte une partie «Préparation» qui devraient être complétée avant son TP.

Les exercices seront évalués par défaut à la date indiquée, essentiellement sept jours après votre TP correspondant.
Seule exception : le zérotième exercice qui doit être complété avant le premier TP.
Si vous désirez être évalué·e plus tard, vous devez me le signaler mais vous encourrez une perte de 10% des points pour chaque jour de retard.

Je désire recevoir du code qui sera le fruit de votre réflection et écrit de votre main.
Dans le cas contraire, le travail reçoit une note de zéro.
Une récidive entraîne une note de zéro pour le cours entier.
Pour information, j'utilise l'outil [MOSS](http://moss.stanford.edu).

Il y a cinq exercices à compléter.
Comme ce cours est en évaluation continue, votre note finale est la somme des points obtenus pondérés comme indiqué.

| Exercice | Points | Disponibilité | Échéance Q1 | Échéance Q2 | Échéance Q3 | Échéance Q4 |
| - | - | - | - | - | - | - |
| [Exercice&nbsp;0](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Exo0) | 1/20  | lundi 8 fév. | vendredi 12 fév., à midi | vendredi 12 fév., à midi | vendredi 12 fév., à midi | vendredi 12 fév., à midi |
| [Exercice 1](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Exo1) | 4,25/20 | lundi 15 fév. | vendredi 26 fév., à midi | mardi 23 fév., à midi | vendredi 26 fév., à midi | vendredi 26 fév., à midi |
| [Exercice 2](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Exo2) | 4,25/20 | lundi 22 fév. | mardi 2 mars, à midi | vendredi 5 mars, à midi | jeudi 4 mars, à midi | jeudi 4 mars, à midi |
| [Exercice 3](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Exo3) | 4,25/20 | lundi 8 mars | lundi 22 mars, à midi | mardi 23 mars, à midi | mercredi 24 mars, à midi | mardi 23 mars, à midi |
| [Exercice 4](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Exo4) | 4,25/20 | lundi 8 mars | mardi 23 mars, à midi | jeudi 25 mars, à midi | vendredi 26 mars, à midi | jeudi 25 mars, à midi |

## Les bonus

«Mais, dites-donc... Ça ne fait qu'un total 18 points ?!»

En effet.
C'est pourquoi il y a des exercices bonus.

Le bonus individuel est ouvert à tous.
C'est-à-dire que chacun d'entre vous peut accomplir son objectif et obtenir un point additionel sur votre note finale.
Ce point est cumulable avec un point de bonus compétitifs.

Les bonus compétitifs adjugent un point au·à la premier·ère étudiant·e qui en accomplit l'objectif.
Un seul point maximum de bonus compétitifs sera attribué par étudiant·e.
Ce point est cumulable avec le point de bonus individuel.

| Bonus | Points | Disponibilité | Échéance |
| - | - | - | - |
| [Bonus&nbsp;individuel](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Bonus-Individuel) | 1/20 | lundi 1 mars | vendredi 12 mars, à midi |
| [Bonus&nbsp;compétitif&nbsp;1](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Bonus-Competitif-1) | 1/20 | lundi 1 mars | vendredi 2 avril, à midi |
| [Bonus compétitif 2](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Bonus-Competitif-2) | 1/20 | lundi 1 mars | vendredi 2 avril, à midi |
| [Bonus compétitif 3](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Bonus-Competitif-3) | 1/20 | lundi 1 mars | vendredi 2 avril, à midi |

## Le projet

Ce projet de plus grande envergure sera réalisé en deuxième moitié de semestre.
Il doit être réalisé par équipe de deux ou trois.
Ce projet sera noté séparément.

Il est prévu une soutenance qui sera faite à distance.
Plus de détails seront fournis en temps voulu.

| Projet | Disponibilité | Échéance |
| - | - | - |
| [Projet](https://github.com/Amu-DevCommeLesPros-2021/DevCommeLesPros-2021-Projet) | mardi 6 avril | lundi 31 mai, à midi |

<!-- Formule pour calculer sa note finale ajustée pour une moyenne de groupe de 12 et un écart-type de 3. -->
<!-- 
<div align="center">
(3.0 / ???) x (
<input type="text" name="input" id="input" value="" size="4" oninput="adjust()" disabled/>
<script>
    function adjust() {
        var moyenne_groupe = ???;
        var moyenne_desiree = 12;
        var ecart_type_groupe = ???;
        var ecart_type_desire = 3.0;

        var avant = document.getElementById("input").value;
        var apres = (ecart_type_desire / ecart_type_groupe) * (avant - moyenne_groupe) + moyenne_desiree;
        
        // On arrondi au demi-point près et on borne entre 0 et 20.
        var rounded_clamped = Math.min(Math.max((Math.round(apres * 2) / 2).toFixed(1), 0), 20);

        document.getElementById("output").value = rounded_clamped;
    }
</script>
 - 14) + ??? = 
<input type="text" name="output" id="output" size="4" disabled>
</div> -->

:::blue Le 24 septembre 2025
:::

# Qu'est-ce qu'une direction artistique ?
**A votre avis ?** Quelqu'un veut tenter une définition ?
:::green La direction artistique dans un jeu vidéo, c'est :
la **gestion** et le **suivi** des équipes artistiques du projet, en plus de la **cohérence graphique du jeu**
:::

## La high level artistic vision
Pour créer une direction artistic, il faut avoir des conversations avec l'équipe de design pour ensuite discuter avec l'équipe pour obtenir du feedback.

:::green Le feedback = Une constante dans le développement de jeux vidéo
:::

## Les implications de la DA
Déterminer ce qui est important pour le design spécifique de notre jeu.
:::green qu'est-ce qui le rend unique
:::

**Comment déterminer tout ça ?**

## Etapes
### **Etape 1** : Comprendre la vision en faisant des recherches sur le genre du jeu et suivres les attentes de notre audience.

:::green Comment notre vision à nous se démarque ?
:::


**D'autres façons de faire...**

Une mindmap session pour identifier les thèmes visuels principaux et déterminer les piliers viuels.
(En général 3 piliers)
___
### **Etape 2** : Collecter des références en faisant des recherches sur la vision souhaitée.
:::green Les références sont des autres oeuvres artistiques et médiatiques den lien avec la vision.
:::
**Qu'est-ce que ce matériel est censé montrer ?**
:::green C'est spécifique au genre de jeu que l'on fait.
:::
Ces **early concepts** doivent se concentrer sur les aspects visuels les plus importants du jeu et essayer de trouver des approches existantes pour des éléments qui pourraient se ressembler.

:::red Remarque !
Les personnages ou l'environnement ne sont pas toujours les aspects les plus importants.
Si le jeu a un écran bien chargé, ou transmet son interface d'une certaine manière, la direction artistique se doit de collecter des références adéquates en UI pour ces éléments à travers d'autres jeux.
:::

**En cas de doute** : revenir à la vision établié et décider en équipe de ce qui est important.

**Exercice** : Prenez la direction artistique d'un jeu et essayez de retrouver les piliers qui ont été définis pour le réaliser.
:::yellow Subnautica : 
L'inspiration de Subnautica provient de :
- **De films** comme ceux de James Cameron pour son exploration sous-marine.
- Pour **les environements et les véhicules**. Les artistes s'inspirent des films comme **Star Wars**.
- L'open world s'inspire de **Minecraft** car :  « La sortie de **Minecraft** coïncidait avec la sortie de **Natural Selection 2** par **Unknown Worlds** . Épuisée, l'équipe a voulu innover et a décidé de créer un tel jeu ».
- Le jeu est dépourvu de **missions ou de quêtes traditionnelle**. Il s'agissait d'un choix délibéré : « Avec des récompenses intrinsèques, les joueurs sont encouragés à effectuer les activités uniquement pour leur propre mérite, ce qui les motiverait moins. Mais, s'ils surmontaient cette période d'apprentissage, ils parviendraient à assimiler cette activité comme un plaisir en soi et continueraient. » Ils ont opté pour cette option après avoir lu un essai de **Jamie Cheng**.
:::
___
### **Etape 3** : Le fake screenshot ou key art.

**La création d'un élément clé** souvent lié à un sketch détaillé, il peut être n'importe quel élément suivent la vision artistique et la direction du jeu.

**Pousser la réflexion** en créant un fake screenshot se basant sur les réfs.

![image.png](https://cdn.alexandrie-hub.fr/623251508854411294/625966214597726311.png)

___
### **Etape 4** : S'aligner avec la tech et rendre l'art possible.
(**Quel engine choisir ?**)

On ne fait pas la même **DA** si on utilise Unreal ou GameMaker (les deux ont leurs avantages et inconvénients).

Il est important d'aligner la team tech avec la direction visuelle désirée.
:::green Préprod = phase initiale cruciale de planification et de conception
**Prod = l'ensemble des processus de conception, de développement et de test d'un jeu vidéo**
:::
___
### **Etape 5** : La création des keys art assets.
Elle servent à délivrer la vision du jeu en format game-ready. Ces délivrables vont être dépendants du type de jeu et des éléments-clé du gameplay.

**Une vision, oui. Le bugs ? C'est OK ici.**

Ces assets sont typiquement créées en alpha ou pre-bug fix. Elles vont ressembler à ce que l'on veut shipper, mais nécéssitent encore de l'itération pour fonctionner correctement dans le jeu.

:::red Remarque !
**L'importance du feedback** : On va devoir améliorer ces assets, non seulement dans le programme utilisé pour les créer... (Mais aussi in-engine et tout optimiser)

**Ces assets ont un poids dans les décisions de développement du jeu**

 Le plus tôt l'équipe a des assets dans les mains, le plus vite elle peut travailler autour de la vision artistique.
:::
___
### **Etape 6** : Une séquence de gameplay.

**La première Build de démo, ou la VSD**
Pour que les stakeholders et autres partenaires/directeurs puissent tester le jeu.

On peut enfin montrer ce que le jeu a dans le ventre en termes d'expérience de gameplay et comprendre la vision artistique. **(aussi appelé Vertical slice)**

**La core gameplay loop**
On peut viser plus petit que la VSD avec le core gameplay loop. **(Contient les modèles, textures, animations, léments du HUD, ...)**

**{color:green}(Vertical slice validée = On part en prod !)**
___
### **Etape 7** : La production.

**Le scope artistique du jeu**
Créer une liste de toutes les assests nécéssaires qui ont besoin d'être créées.
Faire des estimations sur le temps individuel pour compléter ces tâches.
S'assurer qu'on a la capacité d'exécuter la vision.

:::green Must-have et Nice-to-have.
:::

:::red Remarque !
Il est important de garder en tête que le design du gameplay peut changer au cours du développement du jeu, et il faudra de la place dans le planning pour itérer sur les assets au besoin.
:::

**Les "chunks"** sont une manière de diviser le travail.
:::green Ca permet d'avoir un minimum du jeu qui est dans un état "terminé" si l'on manque de temps en fin de prod.
:::
___
### **Etape 8** : Tuning et bugfix.
**Le tuning** (ou ajustement) c'est faire des playtests, qui donneront lieu à des feedbacks et donc des itérations.
Ici les commentaires des stakeholders et directeurs seront très importants pour faire les derniers changements.

:::green Cette partie ne prend que très peu de temps si le travail a été suivi correctement tout au long de la prod. (On se focus sur les assets high impact)
:::

**Le bugfix** c'est quand l'équipe QA va tester la build constamment et faire des retours, donner un ordre de priorité des bugs rencontrés. (La team art doit suivre pour corriger ces bugs).
:::green Les bugs rencontrés sont spécifiques au type de jeu que l'on crée.
:::

:::red Remarque !
On ne fixera jamais tous les bugs d'un jeu, **et c'est OK**. A un moment faut juste se dire que l'on a terminé le développement du jeu.
:::
___
### **Etape 9** : Les assets marketing.

**Qu'est-ce qu'on entend par assets marketing**
Ca peut comprendre : des posts pour les réseaux sociaux, des interviews, l'optimisation des store pages, les trailers, le key art final...

**Ce qu'on demande à la team art**
- Des screenshots
- Des captures vidéo
- Des assets customs
- Etc (tout ce qui nécéssite de la création artistique)

:::green C'est important que le public sache que le jeu existe !
:::
___
## Conclusion
Une *direction artistique* se travaille tout au long du développement du jeu, et avec toute l'équipe. C'est important de recueillir du feedback afin d'itérer le matériel sur lequel on travaille.

Une bonne *direction artistique* permettra aussi de faire connaître votre jeu et de le mettre en valeur, car c'est en général le premier contact que les joueurs auront avec votre jeu.
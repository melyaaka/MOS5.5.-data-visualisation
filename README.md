# Diagrams Sankey

Les diagrames de Sankey sont des cas particuliers de diagrammes de flux. Ils se présentent sous la forme de flèches dont l'épaisseur est proportionnelle à la quantité de flux. Des bifurcations permettent de séparer la flèche principale en plusieurs sous-flèches qui représentent donc les parties. Ils sont très utilisés pour représenter les flux d'énergies, mais ce sont généralisés et sont utilisés aujourd'hui dans différents domaines:  Economie, biologie ... 

## Histoire

Les diagrammes doivent leur nom à Mattew Sankey, qui a été l'un des premier à utiliser pour démontrer l'efficacité énergétique d'une machine à vapeur. 

![MachineVapeur](/Img/Picture30.png/)

Quand les diagrammes de Sankey représentent une perte, ils sont utiles pour identifier les points faibles d'un processus, ce qui est utile pour l'optimisation

Il est difficile de faire des recherches sur les diagrammes de Sankey sans tomber sur celui-ci. Il s'agit d'une représentation par l'ingénieur français Charles Minard des pertes des effectifs de l'armée française dans la campagne de Russie. L'idée derrière la représentation est ingénieuse car elle superpose à la fois un diagramme de flux Sankey à une carte géographique en ajoutant aussi une courbe de température. 

![CompagneRussie](/Img/Picture29.png/)

Les diagrammes Sankey permettent de comprendre visuellement où et quand se passent les transferts les plus importants. Ici en l'occurence, on voit que la quasi totalité des pertes d'hommes a été encaissée dans le chemin vers Moscow. La représentation explique donc que les pertes sont dues aux températures très basses et aux conditions climatiques difficiles durant le voyage plutot qu'au combat. 

## Quelques exemples intéressants

### Catégorisation
Les diagrammes Sankey sont aussi utiles pour la catégorisation. 
Sur l'un de mes subreddit préférés "r/dataisbeautiful", un utilisateur a créé un diagramme Sankey pour classifier le top 100 des visualisations sur le site par upvotes. Il classifie d'abord par type de visualisation puis par domaine puis enfin par sujets. Incidemment, les diagrammes les plus populaires sur le site sont des diagramme de type sankey ! 
On remarque que la moitié des top 100 visualisations sont de ce type. Le diagramme est très parlant et permet de rapidement identifier les visualisations et les sujets populaires. 

![Classification](/Img/Picture31.png/)

Un autre exemple du même subreddit créé par un professeur montre les différentes manières dont ses étudiants ont écrit le mot "camouflage". Ce qui est intéressant dans ce diagramme, c'est qu'il indique les étapes où s'effectuent les transitions par des barres verticales et le nombre d'élèves dans chaque étape. 

![Catégorisation](/Img/Picture30.png/)

### Flux d'immigration
Un diagramme de Bloomberg très bien fait illustre bien ce cas d'utilisation. Il est similaire au diagramme de Charles Minard car il essaye de superposer plusieurs données dans un seul graphique. Par contre, la forme de ce diagramme est différente des précédents car il présente des branchements des 2 cotés. L'originalité en plus, c'est que les branches viennent pointer de manière harmonieuse vers les points d'entrées des USA. La partie sud du texas reçoit la majorité des immigrants. 

![Immigration](/Img/Picture37.png/)

Un autre diagramme similaire concerne les recrutements par les entreprises des étudiants, et montre pour chaque entreprise la part des 5 universités qui pourvoient le plus d'étudiants. La particularité de ce diagramme, c'est qu'il y'a beaucoup de chevauchements des flux. Ce qui est logique car on doit lier chaque entreprise à 5 universités.  
Ce qui est impressionant, c'est que les intersections les flux sont clairs malgré les intersections. Le choix de couleurs de la transparence et d'emplacement des troncs est très bien fait, et le résultat est bluffant !
https://www.wired.com/2014/05/alumni-network-2/

![Jobs](/Img/Picture33.jpg/)

On peut diviser le diagramme Sankey au milieu pour exprimer une balance. Par exemple, le diagramme ci-dessous représente le budget de l'état. D'un coté nous avons toutes les sources de revenu du gouvernement. De l'autre toutes les dépenses du gouvernement.  

![BudgetGouvernement](/Img/Picture32.jpg/)

### Visualisation ou Art ? 

Les exemples précédents sont preuves de la variété des diagramme Sankey possible. C'est sans doute l'un des diagrammes les plus flexibles et les plus parlant. Les possibilités sont illimitées et peuvent permettre d'ajouter une touche artistique.
Voici quelques exemples : 

![Trump](/Img/Picture34.png/)

![Artistes](/Img/Picture35.jpg/)


### Conclusion 
A sankey diagram says more than a 1000 pie chart 



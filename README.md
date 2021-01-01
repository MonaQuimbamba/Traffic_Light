# Feu Tricoleur

## Description 

Un objet métier « FeuTricolore » possède 2 attributs. Le premier indique si le feu est à l’arrêt ou en
marche. Lorsque le feu est en marche, le second indique la couleur du feu (vert, orange ou rouge). Si le feu
est à l’arrêt, la sémantique du second est indéfinie. Les opérations « arreterDemarrer() » et « changer() »
modifient circulairement les valeurs de ces deux attributs.
NB : Lors de sa mise (ou remise) en marche, le feu est obligatoirement rouge.
A cette classe métier sont associées deux interfaces (au sens IHM, pas Java) :
- L’une graphique qui représente le feu avec l’une de ses trois couleurs : vert, orange, rouge . Quand le
feu est à l’arrêt la couleur affichée est le gris.
- L’autre qui est un simple panneau sur lequel figure un texte parmi : « feu arrêté», « passez »,
« attention » ou « stop »
Les deux interfaces possèdent chacune 2 boutons :
• l'un permettant de changer de couleur dans l'ordre habituel ;
• L'autre permettant d’arrêter ou de remettre en service le feu.
Un clic sur l’un quelconque de ces boutons modifie l'état de l'objet métier. Les 2 interfaces doivent toujours
être cohérentes avec l’objet métier.

## Contraintes

- Les deux interfaces (graphique et texte) sont indépendantes et ne communiquent pas entre elles
- Le Feu est indépendant des interfaces.

## Langage Informatique 
-Java

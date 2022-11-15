Julie NONNON
Rendu Integration Simplon du 16/11/2022

Notes:

Responsive:

--> Le site n'est pas au pixel près, mais se montre responsive
--> Le Responsive de la section "Notre impact" est à reprendre
--> Utilisation de "display:none" (éléments en "doublure") pour faciliter intégration en reponsive (cf section "Apprentis Simplon" et Footer)
--> La font est non responsive (oubli du clamp)

Menu Burger:

--> Animation du menu burger ok mais pas au bon emplacement
--> non fonctionnel: pas de menu déroulant
--> Tuto utilisé sourcé dans le main.js


Carrousel Témoignage:

--> Le Carrousel est fonctionel: Défilement par clic ok et retour 1ere slide
--> Boutons de navigation pas au bon emplacement
--> Les slides sont les unes à coté des autres et non les unes sur les autres, quand j'active le  /* overflow: hidden; */ (CSS en ligne 334), au lieu de mettre les slides les unes derriere les autres, tout disparait.
--> Le Carrousel étant configuré avec des positions relatives et absolues, il cache la section suivante. Utilisation de <br> pour l'instant, mais trouver une meilleure solution à l'avenir.
--> Tuto utilisé sourcé dans le main.js


Carrousel Partenaires:

--> Le Carrousel est fonctionel: Défilement auto avec pause si "hover"
--> Boutons de navigation non-programmés
--> Tuto utilisé sourcé dans le main.js

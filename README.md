
Calculons la largeur totale de cette carte avec le box-sizing par défaut et expliquons ce que change box-sizing : border_box avec cette classe:

.carte {
    box-sizing: border-box;
    width: 300px;
    margin: 15px;
    padding: 15px;
    border: 1px solid #ddd;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    border-radius: 8px;
}



Largeur totale	300 px
Padding gauche + droite	30 px
Bordures gauche + droite	2 px
Largeur du contenu restante	268 px

300 px est la largeur totale de la carte, hors marges.
Avec les marges, l'espace horizontal occupé est de 330 px.
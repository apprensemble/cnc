# Prise en main CNC

Pour cette prise en main nous partons d'une CNC Eleks mill avec grbl version 0.9i.

## etapes 


04/09/2017 13h à 14h

1. préparation : OK
1. branchement serie : OK
1. installation bCNC : OK

  Je sais à présent que la CNC est en version grbl 0.9i et repond aux commandes g-code.

### preparation

* arduino IDE
* Fritzing
* git
* vim

### Branchement port serie

1. je donne les droit d'acces au port usb à mon user(ajout au groupe dialout)
1. branchement et lancement console arduino 
   1. passage en 115200 baud la version s'affiche
   1. forçage retour chariot comme indiqué dans la doc
1. essai de commandes grbl

### programmes de creation et d'envoi de commandes grbl

  la liste se trouve sur la page suivante :

https://github.com/gnea/grbl/wiki/Using-Grbl

1. bCNC : https://github.com/vlachoudis/bCNC
  * dependances :
    * python-serial
    * python-tk

    optionnelles : 

    * python-opencv
    * python-imaging-tk
     


# Séance du 25 Février 2019

* Avec Jessica, nous sommes aller chercher notre boîte chez Castorama. Elle convient parfaitement(image).
* J'ai installé la lumière sur notre 3ème roue.
* Avec Jessica, on a travaillé sur l'ensemble roues + monnayeur. Le programme qu'on utilise est le suivant :
Du côté du monnayeur, la sortie des pièces fonctionne bien.
Mais on a eu quelques problèmes. Tout d'abord, lorsqu'on connectait tous les servomoteurs sur la carte Arduino (4 servomoteurs), nos roues tournaient trop longtemps et incorrectement. On a donc mis une capacité. Au final, ce problème a été réglé.
Un autre problème est qu'on n'arrive pas encore à contrôler les positions des 3 roues en même temps, alors que séparément oui.
* J'ai réalisé le programme de l'initialisation des 3 roues grâce au programme qui initialise une roue. Voici le programme : https://github.com/JessicaJulien/projet/blob/master/Codes/Initialisation3roues.ino
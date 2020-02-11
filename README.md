# MiniWatt_2020
MiniWatt UPGRADE

## Cahier des charges ELECTRONIQUE MINIWATT 2020 

Actuellement sur Minilitre :
 
 Carte moteur V5 : version 01 sans coupure TRACCO (1J/s) / version 02 avec coupure
TRACCO (0,5J/s). 
 Carte puissance : TRACCO 36V to 12V pour le klaxon / Relais OMRON général arrêt
d’urgence 36V-16A. 
Carte BMS 1S to 13S.
Carte adaptation BMS 10S pour équilibrage des batteries sur le proto pendant la course.
Carte interface RASPI.
RASPI : pilotage du crabot, gestion du chrono course, du nombre de tours, coupure vitesse, 
affichage vitesse proto.
Klaxon 12V-1,5A-105dB avec relais automobile 12V-20A + relais automobile 12V-30A situé 
juste à côté.
Batterie Lipo 10S-4000mAh (2 x 5S en série sous 1 pack). 

A prévoir sur MiniWatt :
 
 Enlever :
 RASPI.
 Carte interface RASPI.
 Carte de puissance.
 Kaxon 12V.
 Batterie lipo 10S-4000mAh.
 Carte d’adaptation BMS 10S. 

 Carte générale avec à y intégrer : 
 La carte moteur V5 à modifier avec coupure du TRACCO (possible de la
supprimer avec un shunt) + enlever l’optocoupleur ON/OFF moteur par le
RASPI et remplacer la commande ON/OFF par une simple commande par
interrupteur (pull down) + mettre driver de MOS sur support + passer le max
de composants en CMS + fixer mécaniquement les radiateurs pour éviter de
tirer sur les soudures des MOS + souder les MOS de type CMS. 
 Le relais OMRON général arrêt d’urgence à modifier en 48V-16A.
 Le relais klaxon OMRON 48V- ?? A (à choisir).
 1 ou 2 embase(s) RJ45 pour liaison avec les commandes poste de pilotage.
 1 connecteur pour le klaxon.
 1 connecteur pour la batterie.
 1 connecteur pour le moteur.
 1 système de connexion du joulemètre (possible de shunter pour utilisation 
hors course sans joulemètre) + penser à la position au plus près du moteur et
partie carte moteur. 

 Carte d’adaptation BMS 12S.
 Carte interface RJ45.
 Batterie Lipo 6S-2600mAh (x 2) + cordon Y pour mise en série.
 Klaxon 48V- ?? A-105dB.
 Liaison entre la carte générale et les commandes de pilotage avec un câble RJ45. 
  

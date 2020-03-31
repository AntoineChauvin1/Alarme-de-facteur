# Alarme-de-facteur
Première prise en main de Blynk, une alerte quand je recoit du courrier postal.

Le principe est d'utiliser un capteur de mouvement situé dans la boite aux lettres pour m'envoyer une notification sur mon smartphone.  
Le PIR  une fois au' il a detecté un mouvement, active un relais qui alimente un Wemos D1 et un JQ6500.  
Le Wemos se connecte au Wifi et envoi une notification sur mon smartphone par l'intermediaire de Blynk.
Le lecteur audio est un petit plus rigolo pour faire un clin d'oeil au facteur.
Après 15s le PIR coupe l'alimentation. Cela donne une autonomie de 6 mois environ.

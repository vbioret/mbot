# mBotControl

> Projet forké de [https://github.com/vrbaj/mbot](https://github.com/vrbaj/mbot)

Permet le contrôle du mBot en Wifi (via le dongle), par un script python.

## Installation

- Installer [Arduino](https://www.arduino.cc/en/Main/Software)
- Installer [python 2.x](https://www.python.org/)

Le fichier DOD.ino correspond au firmware, à uploader avec Arduino

Le mBot est contrôlé via le pavé numérique :

- 8 : Tout droit
- 2 : Recule
- 4 : Tourne à gauche
- 6 : Tourne à droite
- 5 : Arrêt

Le fichier comm.py Permet de tester la connexion entre le pc ou le raspberry équipé du dongle et le mBot.

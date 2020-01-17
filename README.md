# Autostart-piweb
Script pour démarrage du Raspberry PI sur une page web en automatique et en mode kiosk + suppression du pointeur de la souris.

---

**Fonction :**

- Désactive la mise en veille (écran noir) du Raspberry 
- Ouvre chromiom en mode kiosk et en pleine écran
- Désactive le pointeur de la souris si plus de mouvement au bous de 3 secondes

**Tester sur :**

- Rasberry Pi 2,3 et 4
- Rasbian buster et stretch

--- 

Commande : 

```sudo nano /etc/xdg/lxsession/LXDE-pi/autostart``` → commande pour accéder au script.

```sudo apt-get install unclutter``` → package pour suppression du pointeur de la souris.

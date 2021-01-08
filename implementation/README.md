# Description des fichiers

- `access.log` : le fichier de log commun à l'allience (logs appache2)
- `vagrant.box` : archive compressée de la VM vagrant à [télécharger via FileX (~3Go)](https://ent.normandie-univ.fr/filex/get?k=kVeXpNuIGYheECztxKc). A l'heure actuelle, elle est set up telle que le localhost par défaut renvoie sur un site bidon et le localhost:5601 renvoie sur l'appli elastic. Sauf que eslatic a pris le dessus donc par défaut on n'arrive plus à aller sur le site.

# Pré-requis
Installer les paquets `vagrant` et `virtual box`.

# Utilisation

Placez-vous dans le dossier contenant `vagrant.box`.

Décompressez la VM : `vagrant init [machine name as it shows in virtual box] /Users/myuser/Documents/Workspace/my.box`.

Lancer la VM : `vagrant up`.

Se connecter à la VM : `vagrant ssh`

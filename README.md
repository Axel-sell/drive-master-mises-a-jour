# Driver Master

Le matériel d'un PC Windows 10 et 11, en un seul logiciel : les pilotes (vérifier, sauvegarder, réparer, mettre à
jour) et les disques (partitions, santé, sauvegardes de la table, copie), avec les températures et les capteurs.
Chaque changement se prépare en fiche et ne se fait qu'après « Appliquer ».

## Télécharger

La dernière version est dans **Releases**, à droite de cette page :

- `Driver-Master-<version>-installateur.exe` installe Driver Master pour tous les comptes du PC. Ensuite, il
  regarde à chaque ouverture si une nouvelle version existe, et la propose ; il peut aussi l'installer tout seul
  (Réglages › Mises à jour de Driver Master).
- `Driver-Master-<version>-portable.exe` fait tourner Driver Master sans rien installer.

Driver Master s'appelait Driver Partition jusqu'à la version 0.7.0 : un Driver Partition déjà installé se met à
jour vers Driver Master tout seul.

Ce dépôt ne contient que les versions publiées. Chacune est accompagnée d'une fiche signée (`driver-partition-version.json`) :
Driver Master n'installe une mise à jour que si la signature de la fiche et l'empreinte de chaque fichier
concordent. La seule chose qu'il demande à Internet de lui-même : « y a-t-il une nouvelle version ? ».

Conçu par Alex NGASSA.

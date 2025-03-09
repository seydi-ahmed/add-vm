# add-vm (3e projet de la branche admisys)
## avoir virtualbox
Télécharger virtualbox si ce n'est pas encore fait: https://www.virtualbox.org/

## télécharger l'iso de debian
Télécharger netinst de debian qui est plus léger: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-12.9.0-amd64-netinst.iso

## instaler debian
Suivre les étapes de l'installation selon ton ordi

## Télécharger l'archive appropriée
Pour X86-64 : Télécharger 01_add-vm.tar.gz --> https://assets.01-edu.org/sys/01_add-vm.tar.gz

## Extraction de l'archive
Extraire 01_add-vm.tar.gz dans le dossier VirtualBox VMs de ton répertoire personnel

## Ajouter la machine virtuelle
1) Ouvrir VirtualBox
2) Sélectionner Machine → Ajouter
3) Ouvrir le fichier 01_add-vm.vbox
4) La VM "01_add-vm" devrait apparaître dans la liste

## Créer un snapshot
1) Sélectionner la VM
2) Rechercher Instantannées
3) Prendre un snapshot
4) Lui donner un nom

## Ouverture de la machine virtuelle
1) nom d'utilisateur: root
2) mot de passe: Un Espace

## Vérification de quelques informations
1) faites quelques commandes comme celles-ci
- df -h
- ip a
2) éteindre la machine
- shutdown -h now
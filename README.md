# NEOTEKNIX
Distribution NixOS pour **Néotechnique**.
# NixOS
Nix est un outil prenant une approche unique à la gestion de **paquets** et à la configuration système.
Les paquets (ou packages) sont des logiciels "empaquetés" et prêts à l'emploi.

NixOS est une distribution linux **déclarative**, c'est-à-dire que la configuration du système et les paquets installés sont décrits dans **un unique fichier** : nixos.conf
# Installation
## Sur MacOS :
Consulter le lien :
https://determinate.systems/solutions/nix-for-macos/
Télécharger puis installer le **.pkg**
## Sur Windows (dual-boot):
Appuyer simultanément sur les touches "Windows + X".
Sélectionner "Gestion des disques" dans le menu déroulant.
Cliquer-droit sur votre disque système (C:).
Sélectionner "Réduire le volume".
Dans "Quantité d'espace à réduire", entrez 5000 pour **50Go**.
Cliquer réduire.

Consulter ce lien :
https://nixos.org/download/
Télécharger "Graphical ISO image".

Consulter ce lien :
https://rufus.ie/fr/#download
Télécharger l'outil.

Une fois le téléchargement terminé, munissez-vous d'une clef USB vierge de données.
Lancer rufus et charger le fichier "nixos-graphical-xx-xx-linux.iso"
Sélectionner la clef USB et lancer l'écriture.

Une fois l'écriture terminée, vous pouvez redémarrer votre ordinateur et entrer dans le **BIOS** de votre carte mère, voir : https://www.bsc-informatique.fr/2026/06/21/comment-entrer-bios-menu-demarrage/

| **UEFI: SanDisk**, **UEFI: Kingston DataTraveler**… | Votre clé USB, en mode UEFI | **Oui**, c'est la bonne entrée pour installer NixOs |
| --------------------------------------------------- | --------------------------- | --------------------------------------------------- |
Suivre les instructions d'installation, voir : https://nixos.org/manual/nixos/stable/#sec-installation

Votre système Linux est prêt à l'emploi !

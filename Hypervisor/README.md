# Hypervisor
 # Français
  - Notre hyperviseur sera un peu le chef d'orchestre de nos services
  - Pour le projet je décide de me pencher vers l'idée des VMs étant très peu renseigné sur la techno Docker et plus familier avec l'infra des VMs, Pourquoi ?
    Les VMs (Machine virtuelle) me permettent de créer un environnement pour chaque service que je me décide de déployer sur mon réseau. Comme ça si un  environnement tombe les autres ne seront pas impactés. Mais pour gérer toutes ces VMs, il va me falloir un chef d'orchestre pour du coup donner les directives à mes machines.
  - Le choix de l'hyperviseur
    - Proxmox VE
     Proxmox est open-source donc ça veut dire que déjà c'est gratuit mais bon c'est un peu archaïque comme fonctionnement et surtout que pour se documenter c'est très compliqué à mon goût. Par contre : c'est puisssant et c'est très modulable.
    - VMWare VSphere/ESXi
     VMWare est connu pour son outil pour virtualiser des machines sous nos PCs mais ils ont une solution pour créer une flotte de VMs, une version gratuite est à disposition et l'interface est plus ergonomique. Par contre je ne sais pas encore à quel limitations je vais être confrontés. 

    - Conclusion : 
      - Bon au début je devais prendre Vsphere mais bon c'est pas possible donc je me tourne vers Proxmox VE.
   # Installation

   - Pour installer notre "chef d'orchestre" il nous faut :
    - Une clé USB de 8GB (même moins ça se trouve)
    - L'ISO de Proxmox VE disponible sur leur site gratuitement
    - Etcher ou Rufus (choisissez votre préf)
    - Notre petit rig donc mon bon vieux i7
    - Une connexion Internet
    - Un cerveau
    - Un autre pc pour l'interface web
   - Donc maintenant on crée notre clé avec notre software fav
   - Après on lance notre rig et boot sur la clé
   - L'installation est muni d'une interface pour faire l'installation chercher des guides ils vous expliqueront mieux que moi. 
    

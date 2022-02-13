# Hypervisor
# Français
 - Notre hyperviseur sera un peu le chef d'orchestre de nos services
 - Pour le projet je décide de me pencher vers l'idée des VMs étant très peu renseigné sur la techno Docker et plus familier avec l'infra des VMs, Pourquoi ?
    Les VMs (Machine virtuelle) me permettent de créer un environnement pour chaque service que je me décide de déployer sur mon réseau. Comme ça si un environnement tombe les autres ne seront pas impactés. Mais pour gérer toutes ces VMs, il va me falloir un chef d'orchestre pour du coup donner les directives à mes machines.
 - Le choix de l'hyperviseur
   - Proxmox VE
    Proxmox est open-source donc ça veut dire que déjà c'est gratuit mais bon c'est un peu archaïque comme fonctionnement et surtout que pour se documenter c'est très compliqué à mon goût. Par contre : c'est puisssant et c'est très modulable.
   - VMWare VSphere/ESXi
    VMWare est connu pour son outil pour virtualiser des machines sous nos PCs mais ils ont une solution pour créer une flotte de VMs, une version gratuite est à disposition et l'interface est plus ergonomique. Par contre je ne sais pas encore à quel limitations je vais être confrontés. 

   - Conclusion
    Je choisis VMWare car il sera plus simple pour commencer et ça va pouvoir m'apporter des connaissances pour le monde professionnel en matière de DevOps. 
    
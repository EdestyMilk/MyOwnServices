# openmediavault
   # Français
   - Pour le premier service ce sera openmediavault qui est un service permettant de faire un NAS dans notre réseau.
   - Son installation m'aura demandé de refaire une template Proxmox mais avec Debian car openmediavault est très dépendant des packages de Debian.
   - Après il faut monter nos disques qui stockeront nos données, alors plusieurs façons s'ouvrent à nous :
   - On peut utliser les identitiés que Linux nous donnent donc ```sda, sda1, sda2, sdb, sdb1, etc``` , mais ces noms peuvent changer sans qu'on soit prévenu. Proxmox nous conseille d'utiliser par leurs identifiants, une commande nous est donnée pour récupérer ses identifiants uniques. Avec ces identifiants on est sûr de ne pas avoir de problème de changment d'identité.  

# Plex
   # Français
   - Je me suis décidé d'installer un Plex pour trier toute la bibliothèque multimédia que j'ai
   - J'ai décidé d'utliser la vm de openmediavault car les montages sont déjà faits et les besoins sont les mêmes
   - Dans le panel de openmediavault, on peut installer Docker et Portainer (qui est une interface pour gérer nos différentes images)
   - Des guides sont dispos pour faire tout ça, un problème auxquelles j'ai fais face avec ma connaissance pauvre en Docker et qui n'était pas marqué dans le guide, il faut d'abord télécharger l'image Docker de plex et après faire le container. Après il faut bien sûr donner les chemins vers les montages faits par OMV et aussi donner les GID et UID du compte pour avoir quelque chose de solide pour la connexion au CLI.
   - Après la mise en route de plex à partir de leur interface web est très simple on donnes les différentes bibliothèque, la base de données à utiliser et il analyse toutes les données comme un grand. 
   - Problème : je me retrouve face à un grand nombre de doublons désormais. Je dois trouver une solution pour effacer les doublons sans effort.
    

# Network
    # Français
        - Au cours de mon montage je me suis retrouvé face à un problème qui me bloquait :
            - J'habite en pleine campagne donc la fibre là-bas on ne sais pas ce que c'est encore, pour palier j'ai investi dans un modem 4G Huawei, ce modem je veux qu'il soit relié à mon Freebox Server pour que les appareils connectés dessus puissent avoir accès aux différents services établis sur le réseau.
            - N'ayant pas de multiwan à ma disposition j'ai dû faire du bricolage : j'ai modifié le serveur DHCP de la freebox en changant le ``` net-id ``` pour correspondre à celui du routeur 4G mais bien-sûr les plages d'attribution diffèrent entre les deux routeurs pour éviter des appareils qui aient la même adresse IP. 
            - 
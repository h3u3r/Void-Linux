# Pós Instalação do Void Linux

1 - Configurar bash para usuário root.

    chsh -s /usr/bin/bash

Em seguida, saia (“ Ctrl+D “) e faça login para que a alteração possa ser aplicada.

2 - Utualizar sistema

    xbps-install -Suv

3- Instalar interface gráfica.

Mate Desktop

    xbps-install -S 

Já com o sudo ativado para o usuário normal, instalação do XOrg, OpenBox mínimo e o gerenciador de login LXDM:

    $ su - edps
    
    $ sudo xbps-install xorg lxdm openbox obconf obmenu lxappearance lxappearance-obconf leafpad sakura thunar-archive-plugin thunar-volman Thunar

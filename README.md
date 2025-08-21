# Pós Instalação do Void Linux

1. Configurar bash para usuário root.

    chsh -s /usr/bin/bash

Em seguida, saia (“ Ctrl+D “) e faça login para que a alteração possa ser aplicada.

2. Utualizar sistema
   
    xbps-install -Suv

3. Repositórios Adicionais
   
    xbps-instal void-repo-nonfree ; Adiciona Repositório Não Livre
   
Instalar interface gráfica.

Mate Desktop

    xbps-install mate

Instalação do XOrg

    xbps-install  xorg 

OpenBox mínimo e o gerenciador de login LXDM

   xbps-install lxdm openbox obconf obmenu lxappearance lxappearance-obconf leafpad sakura thunar-archive-plugin thunar-volman Thunar

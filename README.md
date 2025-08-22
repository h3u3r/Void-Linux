# Pós Instalação do Void Linux

## 1. Configurar bash para usuário root.
````
    # chsh -s /usr/bin/bash
````   
Em seguida, saia (“ Ctrl+D “) e faça login para que a alteração possa ser aplicada.

## 2. Atualizar sistema e repositórios adicionais.

__Autalização__
````
    # xbps-install -Suv
````
**Instalar repositório não livre (non-free)**
````
    # xbps-instal void-repo-nonfree
````
**Instalar repositório multilib**
````
    # xbps-install void-repo-multilib
````
**Instalar repositório multilib/não livre (non-free)**
````
    # xbps-install void-repo-multilib-nonfree
````

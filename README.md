# Pós Instalação do Void Linux

Todos os comando devem serem feitos com privilégios de super-usuário (root).

## 1. Configurar bash para usuário root.
````
    chsh -s /usr/bin/bash
````   
Em seguida, saia (“ Ctrl+D “) e faça login para que a alteração possa ser aplicada.

## 2. Atualizar sistema e repositórios adicionais.

**Atualização**
````
    xbps-install -Suv
````
**Instalar repositório não livre (non-free)**
````
    xbps-instal void-repo-nonfree
````
**Instalar repositório multilib**
````
    xbps-install void-repo-multilib
````
**Instalar repositório multilib/não livre (non-free)**
````
    xbps-install void-repo-multilib-nonfree
````

## 3. Interface gráfica

**Mate Desktop**
````
    xbps-install mate
````
**Plasma Desktop**
````
    xbps-install kde-plasma
````

Opcionalmente pode-se instalar os app adicionais como o comando a seguir.

````
    xbps-install kde-baseapp
````

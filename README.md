# Installation du serveur (Debian)

## Installation de steamcmd:

````bash
    apt-get install lib32gcc1
    mkdir ~/steamcmd
    cd ~/steamcmd
    wget http://media.steampowered.com/installer/steamcmd_linux.tar.gz
    tar -xvzf steamcmd_linux.tar.gz
````

## Utilisation de steamcmd
````bash
    cd ~/steamcmd
    ./steamcmd.sh
````

## Installation/MAJ de csgo (using steamcmd)
````
    force_install_dir /home/lanets/csgo
    app_update 740 validate # Installation de csgo
    app_update 740 # Simple MAJ
````

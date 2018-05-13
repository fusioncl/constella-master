# Constella
=====================================

<img src="https://constellacoin.cl/wp-content/uploads/2018/03/logo_default.png">

Sean todos bienvenidos al código fuente de Constella, el código es libre por supuesto bajo licencia GNU GPL.

Constella es un proyecto criptografico digital para #Chile, queremos motivar a el resto de las personas a crear e interactuar con nosotros y con el resto de las demas #Áreas
tanto en el desarrollo Agrícola y el Turismo.

El nombre de constella viene de Constellation (Constelaciones), es un nombre unico y atractivo!

Queremos ser el plus, tanto para los emprendimientos como para el desarrollo.

# Info

El día Miercoles 16 en la tarde se hará el lanzamiento de la Red de constella, las wallets linux y windows, pool y blockchain!

Cualquier problema Crear un "Issue", en este proyecto.

Haremos constantes actualizaciones al código.


# Instalacion SRC Linux


```Terminal / Bash

///Dependencias///

$ sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3

$ sudo apt-get install libboost-all-dev

$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:bitcoin/bitcoin
$ sudo apt-get update
$ sudo apt-get install libdb4.8-dev libdb4.8++-dev

$ sudo apt-get install libminiupnpc-dev
$ sudo apt-get install libzmq3-dev

$ sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler

$ sudo apt-get install libqrencode-dev

//////////////////

///Proceso de instalacion///

$ apt-get update
$ apt-get upgrade
$ git clone https://github.com/ConstellaTeam/constella-master
$ cd constella-master
$ sudo ./autogen.sh
$ ./configure
$ sudo make
$ sudo make install #Opcional > si quieres un output de los archivos seria $ sudo make install DATADIR="/usr/bin/" bla bla... (Donde quieras!)
$ cd src/

$ ./constellad -printtoconsole
$ ./constella-cli getinfo

/////////////////////////////
```

# Soporte y redes sociales.

[Soporte] $ soporte@constellacoin.cl
[Web] $ https://constellacoin.cl
 
[Telegram]

Canal -> $ https://t.co/LAdo6laCrE

Grupo -> $ https://t.co/hbTKCoi3VS

# Licencia

GNU GPL v3.0

=====================================
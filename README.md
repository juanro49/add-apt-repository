# add-apt-repository
Agrega repositorios ppa (Personal Package Archives) a distribuciones como debian o bunsenlabs de la misma forma como los harías en las distribuciones basadas en ubuntu.

## pasos a ejecutar para su instalación

	git clone https://github.com/juanro49/add-apt-repository.git
	cd add-apt-repository
	sudo cp add-apt-repository /usr/bin/add-apt-repository
	sudo chmod o+x /usr/bin/add-apt-repository
	sudo chown root:root /usr/bin/add-apt-repository

Luego ingresar el repositorio ppa en la terminal como lo harían en las distribuciones basadas en ubuntu.

ejemplo:  sudo add-apt-repository ppa:nome


fuente: [linuxdifficile.wordpress.com](https://linuxdifficile.wordpress.com/2011/01/09/come-aggiungere-ppa-in-debian-e-derivate/)

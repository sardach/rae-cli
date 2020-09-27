rae-cli
=======
El Diccionario de la Real Academia Española desde la terminal.

Este simple script puede:

* Mostrar definiciones del DRAE.
* Mostrar una definición aleatoriamente.
* Mostrar los anagramas posibles de una palabra.
* Mostrar palabras segun las letras que contienen.
* Mostrar palabras segun las letras con las que empiezan.
* Mostrar palabras segun las letras con las que terminan.
* Mostrar las posibles conjugaciones de una palabra.
* Mostrar la palabras del dia.

##### Instalación
###### Es necesario tener los paquetes elinks y curl instalados.
Si usas Arch o alguna distro basada en este, puedes encontrar rae-cli en el AUR

      $ yay -S rae-cli

En cualquiera otra versión de Linux:
	$ git clone https://github.com/sardach/rae-cli/
	$ cd rae-cli
	$ sudo install -Dm755 "/rae-cli/rae" "/usr/bin/rae"
	$ rae --ayuda
     
Tambien puedes simplemente ejecutar "bash rae"


##### Uso
      rae [PALABRA], muestra la definición de la palabra, si existe.
      rae -td [PALABRA],  muestra todas las definiciones de la palabra e información adicional.
      rae -p, muestra la palabra del dia.
      rae -A, muestra la definicion de una palabra aleatoriamente.
      rae -a [PALABRA], muestra anagramas de la palabra.
      rae -C [LETRAS], muestra palabras que contengan las letras introducidas.
      rae -e [LETRAS], muestra palabras que empiecen con las letras introducidas.
      rae -t [LETRAS], muestra palabras que terminen con las letras introducidas.
      rae -c [PALABRA], muestra las posibles conjugaciones de la palabra.

##### Notas
No soy un programador experto. El script usa metodos rudimentarios para funcionar.
Por hacer: Mejorar la presentación de las conjugaciones.

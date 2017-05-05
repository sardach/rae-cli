rae-cli
=======
El Diccionario de la Real Academia Española desde la terminal.

Este simple script puede:

* Buscar y mostrar definiciones del DRAE.
* Mostrar una definición aleatoriamente.
* Mostrar los anagramas posibles de una palabra.
* Mostrar palabras segun las letras que contienen.
* Mostrar palabras segun las letras con las que empiezan.
* Mostrar palabras segun las letras con las que terminan.
* Mostrar las posibles conjugaciones de una palabra.
* Mostrar la palabras del dia.

##### Instalación
No hay paquete de instalación, copia rae en /usr/bin para poder usar el script.
> $ sudo cp rae /usr/bin

> $ rae

Tambien es valido:
> $ ./rae

Es necesario tener los paquetes elinks y curl instalados (apt-get install curl elinks, en cualquier distro basada en debian).

##### Uso
      rae [PALABRA], muestra la definición de la palabra, si existe.
      rae -b [PALABRA], busca la palabra, si existe muestra la definición o muestra otras que podrian estar relacionadas.
      rae -p, muestra la palabra del dia.
      rae -A, muestra la definicion de una palabra aleatoriamente.
      rae -a [PALABRA], muestra anagramas de la palabra.
      rae -C [LETRAS], muestra palabras que contengan las letras introducidas.
      rae -e [LETRAS], muestra palabras que empiecen con las letras introducidas.
      rae -t [LETRAS], muestra palabras que terminen con las letras introducidas.
      rae -c [PALABRA], muestra las posibles conjugaciones de la palabra.

##### Notas

Buscare la forma de agregar el diccionario esencial y panhispánico de dudas si alguién me lo pide. Por el momento el script cubre todas mis necesidades.

La solución para saltar el problema de "Please enable JavaScript to view the page content." con cURL podría no ser permanente.

Por hacer: Mejorar la presentación de las conjugaciones.

# speedtestgui
speedtest-cli es una aplicación utilizada para testear el ancho de banda utilizando el sitio speedtest.net. Tal como indica el sitio: (la traducción es mía)

        Speedtest.net es un servicio web que pone a prueba tu ancho de banda bajando un archivo alojado en algún servidor speedtest.net cercano… 

Para utilizar esta GUI es necesario tener instalado el programa speedtest-cli, pueden instalarlo mediante la consola con el siguiente comando:

    sudo apt-get install speedtest-cli

Por defecto, el programa elige el servidor óptimo para realizar la prueba de velocidad. Sin embargo, es posible elegir un servidor específico a través de una lista (a la que se puede acceder con el botón Lista) y utilizar el servidor elegido ingresando el ID en la pantalla principal.

Como agregado, el programa permite también realizar pings a una lista de ip’s proporcionada por el usuario. Para ello utiliza el comando nmap.

    sudo apt install nmap

    (si no lo tenemos instalado) 

Sé que esta función no está estrictamente relacionada con el speedtest-cli pero la encuentro útil para comparar la latencia entre servidores proxy.

Y además, por qué no? :)

Si te interesó esta pequeña app ingresá a mi blog y mirá mis otros proyectos!
https://thenerdyapprentice.blogspot.com

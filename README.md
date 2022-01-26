# StreamVideo2WebBrowser
 Programa en Python que usa Flask para construir un servidor de video en una Raspberri Pi.

También hace uso del GPIO para controlar unos LEDs mediante botones incrustados en la pagina web del servidor de video.

El programa pide como argumentos de entrada el ip y el puerto donde se corre el servidor de video.

$ python3 webstreamingPledcontrol.py --ip 0.0.0.0 --port 8000
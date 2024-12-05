# URL-X
URL-X es un extractor de videos multiplataforma de código abierto mediante PHP.

</br>
  <h1>URL-X / VIDEOS EXTRACTOR</h1></br>                         
<h3>Ejecución en Termux</h3><br>
 <p>Inf | Exit/logout/cancel:CTRL+C</p>                                  
</p>-> Plataformas: Youtube, Facebook, Instagram,etcétera.</p>

<p>-> Información de URL-X:</p>                                           
<p>Es un extractor url multimedia multiplataformas de código abierto.</p>

 <p>-> Inf. Extracción:</p>                   • El tiempo de extracción varia según el tamaño del video y calidad requerida.

• URL-X no muestra proceso de ejecución de extracción.                                                                             
<p>-> Inf. Ejecución:</p>                                                
 <p>1) Ejecute los siguientes comandos para la utilización e ejecución de URL-X.</p>

 <p>~ $ yes | termux-setup-storage</p>

 ~ $ yes | pkg update && pkg upgrade

1.1) La ejecución del siguiente comando es de obligatoriedad ejecutar en el directorio predispuesto para la ejecución de 'URL-X'.

1.1.1) Comando(s) obligatorio(s)/dir:

~ $ mkdir storage/downloads/URL

El comando mkdir le ayudará a crear el directorio predispuesto para la ejecución de URL-X y del comando del indice N° 1.1.1.1 el cuál es sumamente indispensable para la ejecución de URL-X desde Termux o otra terminal linux.

~/.../downloads/URL-X $ cd storage/downloads/URL-X

1.1.1.1) ~/.../downloads/URL-X $ composer require norkunas/youtube-dl-php:dev-master

1.1.2)Ejecute los siguientes comandos que son al igual que el comando del indice N° 1.1.1.1 de caracter obligatorio para ejecutar URL-X.

Inf:

La ejecución de estos comandos no es obligatoria en el directorio predispuesto para la ejecución de URL-X, excepto el comando ~ $ git clone, o excepto el comando con el cual clonamos el repositorio con el cuál ejecutarán URL-X.

 ~ $ pkg install php

 ~ $ pkg install git

 ~/.../downloads/URL-X $ git clone https://github.com/wolkrypter/URL-X.git

1.2) Ejecute 'URL-X', e utilice según su preferencia y según los requerimientos de 'URL-X'.

 ~/.../downloads/URL-X $ php -f URL-X.php

2) Ejemplo Ruta de almacenamiento:

2.1) Utilicé el comando 'pwd' para obtener la dirección del directorio de su preferencia para el almacenamiento de las extracciones.

2.1.1)Example pwd:

 ~ $ termux-setup-storage
 ~ $ cd storage/downloads/URL-X
 ~ $ pwd
/data/data/com.termux/files/home/storage/downloads/URL-X


 --> Ruta de almacenaje:


3) Ejemplo Resolución de video:

Youtube/etc

-->Resolución de video: best[height<=144p] --> 'Resolución 144p'

Facebook/Instagram/etc

-->Resolución de video: b --> 'best=> Mejor resolución de video'

Facebook/Instagram/etc

-->Resolución de video: b --> 'best=> Mejor resolución de video'

Lista de resoluciones

Youtube/etc:

a) 144p
b) 240p
c) 360p
d) 480p
e) 720p
f) 1080p
g) 1440p
h) 2160p



 -->Resolución de video:


 4) Example:

 URL: https://m.youtube.com/shorts/mzX3DSh-AW4


 --> URL:


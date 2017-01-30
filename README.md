# Vagrant con LAMP
Para desplegar este entorno: 
  1. Descargar el repositorio
  2. Inicializar el box en nuestra máquina virtual:
  
     $vagrant box add https://www.dropbox.com/s/449jkj8pizkto94/precise32LAMP.box?dl=0 --name=BOX_NAME
     
  3. Dentro de la carpeta descargada: 
  
     $vagrant init BOX_NAME
     $vagrant up
     $vagrant ssh
  
Con este último comando ya tendréis la máquina corriendo y con el LAMP instalado.

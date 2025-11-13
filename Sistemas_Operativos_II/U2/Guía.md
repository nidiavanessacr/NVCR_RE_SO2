Wordpress: ==Sistema de gestión de contenidos== de código abierto para crear y administrar páginas web y blogs

MariaDB: ==Sistema de gestión de bases de datos relacionales== de código abierto y alto rendimiento (Creado en 2009)

# ¿Qué es Docker?
Plataforma de contenedores para empaquetar aplicaciones y sus dependencias en unidades ligeras portables y aislados
# ¿Qué es la virtualización?
==Tecnología que permite crear versiones simuladas o virtuales de recursos físicos como servidores, dispositivos de almacenamiento, redes o sistemas operativos==, utilizando software para dividir un único sistema físico en múltiples entornos virtuales que pueden operar de forma independiente
# ¿Qué es un sistema operativo distribuido?
 Tipo de sistema operativo que gestiona un conjunto de computadoras independientes y las presenta a los usuarios como un único sistema unificado
- # Diferencias entre sistema operativo distribuido y virtualización?

SOD: Múltiples máquinas físicas como un único sistema
Virtualización: Una única máquina como múltiples máquinas independientes
==**ES LO CONTRARIO**==

SOD: Podemos usar uno o más hardware
Visrtualización: Mucho software en un hardware
# Diferencias entre Docker y una máquina virtual

Maquina virtual se ejecuta sobre el sistema operativo
Docker se conecta al kernel
# Comandos básicos de Docker
## Consultar imágenes
- docker ps
- docker images
## Consultar contenedores
- docker ps / docker ps -a
## Instalar una imagen (templeits)
- docker pull para descarga 
- docker run para instalar
## Arrancar un contenedor
- docker start 
## Parar un contenedor
- docker stop
## Eliminar un contenedor y una imagen
- docker rm para eliminar un contenedor
- docker container prune para eliminar contenedores detenidos
- docker rmi para eliminar una imagen
## Respaldar
- docker save para respaldar una imagen
- docker commit y docker save para respaldar un contenedor




# Paso a paso
Este paso  a paso requiere tener un conocimiento previo acerca de dockers.
## 1.-Montar jenkins 
A traves de docker compose montar Jenkins,y dentro de Jenkins consultar la version de linux e instalar dockers dentro de la maquina. Al mismo tiempo montar SonarQube, 
a traves de docker compose usuario default admin
### https://docs.docker.com/engine/install/debian/--> Instala docker en jenkins
### Asegurate de sincronizar el agente de docker de jenkins con el docker de tu maquina a traves de un volumen -->      - /var/run/docker.sock:/var/run/docker.sock
## 2.- Instalar Plugins
Dentro del administrador de Jenkins instalar el plugin Sonar scanner. Entrar al container de jenkins e instalar SonarScaner por comandos.

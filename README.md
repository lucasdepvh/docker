# docker
Comandos docker
--------------

DOCKER RUN -> EXECUTA UM CONTAINER OU CRIA UM CONTAINER APARTIR DE UMA IMAGEM BAIXADA
DOCKER START -> LEVANTA UM CONTAINER JA CRIADO QUE ESTEJA DESLIGADO

--------
docker info


----------
docker images

-----------
Repository: repositório;
TAG: tag utilizada no repositório;
IMAGE ID: o id na nossa imagem;
Created: data de quando nós criamos a nossa imagem;
Size: tamanho da imagem;



------------------
docker search (parametro)


--------
docker pull (nome da imagem)

Para que nós possamos criar um contêiner, nós precisamos de uma imagem. Caso você não tenha essa imagem no seu host ainda ele irá até o repositório central e irá baixar ela para o seu host, em seguida ele irá criar o contêiner. Vamos criar um exemplo com o famoso Hello World. Para isso, execute o comando a baixo:
-
docker run hello-world
------


docker ps -a (listando todos os nosso containers)


https://medium.com/xp-inc/principais-comandos-docker-f9b02e6944cd (Link qualquer duvida)

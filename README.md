# Anotacoes curso de docker

docker pull = Baixar img do container para usar dps 

docker ps = mostra todos os processos que estão rodando relacionado ao docker

docker ps -a = mostra todos os containers que foram executados 

docker run [nome do container ] sleep 1d = roda o comando por um dia 

docker exec -it [id do container] bash = comando para interagir com o container e entrar no bash do container do ubuntu

docker stop [id do conteiner ] = parar o container 
 
 docker stop -t=[tempo desejado de quando é para parar o conteiner] [id do conteiner]

docker pause [id do conteiner] = pausa o conteiner e não interrompe os processos, assim quando inicia novamente, o tempo que o processo está rodando continua

docker rm = remove o conteinr

docker rm --force = remove o conteiner a força

docker run -d = irá rodar o container e não ira travar o terminal 

docker run -d -P [nome do container] = irá rodar o container e irá especificar a porta para acessar o container

docker run -d -p [especificar porta] [nome do container] = voce pode especificar a porta por exemplo 'docker run -d -p 3000:80 docker/voting-app-vote'

docker stop $(docker container ls -q) = irá parar todos os containers que estiverem rodando 

dcoker image ls = lisatr as imgs que estão disponiveis

docker history [id do conteiner] = lista as camadas do conteiner

docker inspect [id do conteiner] = listar as camadas do conteiner de outro formato 
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



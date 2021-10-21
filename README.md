## rabbitMQ

Repositório para o Trabalho Prático I da disciplina Sistemas Distribuídos. Neste projeto rodamos uma API do Twitter utilizando RabbitMQ sobre 5 nós/máquinas virtuais, sendo estes criados através do Google Kubernetes Engine.

# Configuração
1. Após iniciar o Google Cloud Shell, clonamos este repositório.
2. Utilizando do comando `cd`, vamos para dentro da pasta rabbitMQ.
3. Rodamos o docker com os comandos:
```
docker pull lucifer8591/rabbitmq-server:3.7.17
docker run  lucifer8591/rabbitmq-server:3.7.17
```
4. 

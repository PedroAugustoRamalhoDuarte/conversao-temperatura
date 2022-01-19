# AULA 1 – CONTAINERS E DOCKER SIMPLIFICADOS

Para criar a imagem, dentro da pasta src, rode o seguinte comando:

`docker build -t conversao:v1 .`

Para criar o container

`docker run -d -p 8080:8080 conversao:v1`
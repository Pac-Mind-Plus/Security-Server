# Security-Server
Grupo: Arthur, Otávio e Gabriel

Security Server do site Mind Plus
Instale o arquivo no link https://drive.google.com/file/d/1gow-rkHeqXj0f-Sjtybv0A120Yl2q7T7/view?usp=sharing
Para adicionar a imagem do docker, use o comando
´´´bash
docker load -i mind-plus-keycloak.tar
´´´
no path em que a imagem está baixada
Para executar a image, use o comando
´´´bash
docker run -p 8081:8080 mind-plus-keycloak:1.0.0
´´´

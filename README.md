# Com o docker e docker-compose instalados pode seguir os passos para subir o servidor com a imagem criada

## 1 - Criando a imagem apartir do dockerfile usando o comando build.
### docker build -t exemplo1/dockernode .
## 2 - Subindo o a imagem para o servidor usando o comando docker run. Informando a porta e a imagem.
### docker run -p 3000:3000 -d exemplo1/dockernode
## 3 - Pare o servidor com docker stop image para usar o horquestrador de mudanças do projeto docker-compose
### crie um arquivo docker-compose.yml
### apos criar informe os dados do arquivo como no exemplo e use o comando docker-compose up para subir o servidor

# exemplos de links
## https://www.youtube.com/watch?v=AVNADGzXrrQ

# Referencia
## https://www.vultr.com/docs/install-docker-ce-on-ubuntu-18-04/?utm_source=performance-max-latam&utm_medium=paidmedia&obility_id=17096555207&utm_adgroup=&utm_campaign=&utm_term=&utm_content=&gclid=CjwKCAjwscGjBhAXEiwAswQqNOMAZbFi9jFobx6SfhRb_9TuWyeSMkHhZZLwcXzTuHiOZ5Ki4xWD0BoC5T4QAvD_BwE

## https://www.hostinger.com.br/tutoriais/install-docker-ubuntu?ppc_campaign=google_search_generic_hosting_all&bidkw=defaultkeyword&lo=1001552&gclid=CjwKCAjwscGjBhAXEiwAswQqNEpcxpMJDJTMBPEZtn4UWcTXxyrfRzMzPfkroBrRqou82iqrhPTnmBoCHCYQAvD_BwE


# Instalando o Docker compose
## https://www.vultr.com/docs/install-docker-compose-on-ubuntu-20-04/?utm_source=performance-max-latam&utm_medium=paidmedia&obility_id=17096555207&utm_adgroup=&utm_campaign=&utm_term=&utm_content=&gclid=CjwKCAjwscGjBhAXEiwAswQqNDxJsU8pyxvK7gLQuiNOve2T49FHC_VsSCZnZmDtTZ5kLdA6Tk-VwBoCCnIQAvD_BwE




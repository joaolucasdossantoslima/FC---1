# FC---1
aula 1 de full cycle
-Hello World com Docker 
1- Baixar o Docker no computador (Verificar se o Docker foi instalado com "docker --version"
2- Clonar repositório com "git clone" e "cd" para entrar na pasta
3- Na pasta do projeto criar um arquivo chamado "Dockerfile"
4- Dentro do arquivo adicionar 
  FROM alpine:latest
  CMD ["echo", "Hello World!"]
5- Criar uma imagem Docker no terminal do projeto executando "docker build -t meu-hello-world . "
(O parâmetro -t hello-world dá o nome hello-world para a imagem.)
6- Em seguida execute "docker run hello-world"
7- E o resultado será: "Hello World!"

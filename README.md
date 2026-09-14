# FC — Aula 1: Full Cycle

## Hello World com Docker

**primeiro foi criado um dockfile contendo**
```bash
"FROM alpine:latest"
"CMD ["echo", "Hello World"]
```
**em seguida eu criei a imagem com o comando**
```bash
'docker build -t meu-hello-world .'
```
**e executei o container com**
```bash
docker run meu-hello-world
```
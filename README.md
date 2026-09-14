# FC — Aula 1: Full Cycle

## Hello World com Docker

**Primeiro foi criado um dockfile contendo**
```bash
"FROM alpine:latest"
"CMD ["echo", "Hello World"]
```
**Em seguida eu criei a imagem com o comando**
```bash
'docker build -t meu-hello-world .'
```
**E executei o container com**
```bash
docker run meu-hello-world
```

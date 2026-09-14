# FC — Aula 1: Full Cycle

## Hello World com Docker

**Primeiro digitamos no terminal para baixar a imagem:**
```bash
'docker pull hello-world'
```
**Em seguida executei o container com:**
```bash
'docker run hello-word'
```
**Para rodar o código pelo local host :8080 é necessário digitar esse comando no cmd do windows:**
```bash
docker run -d --name fc-1 -p 8080:80 -v "${PWD}:/usr/share/nginx/html:ro" nginx:alpine
```

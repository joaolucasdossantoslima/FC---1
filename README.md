# FC — Aula 1: Full Cycle

## Hello World com Docker

### Passo a Passo

1. **Instalar o Docker:**
   - Baixe e instale o Docker no computador.
   - Verifique se a instalação foi bem-sucedida executando o comando:
     ```bash
     docker --version
     ```

2. **Acessar o Projeto:**
   - Clone o repositório usando `git clone`.
   - Navegue até a pasta do projeto com o comando `cd`:
     ```bash
     cd nome-do-projeto
     ```

3. **Criar o Dockerfile:**
   - Na raiz da pasta do projeto, crie um arquivo chamado **`Dockerfile`** (sem extensão).

4. **Escrever as Instruções no Dockerfile:**
   - Abra o arquivo e adicione as seguintes linhas:
     ```dockerfile
     FROM alpine:latest
     CMD ["echo", "Hello World!"]
     ```

5. **Gerar a Imagem Docker:**
   - Execute o comando de build no terminal na mesma pasta onde está o `Dockerfile`:
     ```bash
     docker build -t meu-hello-world .
     ```
   > **Nota:** O parâmetro `-t meu-hello-world` define a tag (nome) da imagem como `meu-hello-world`, e o ponto (`.`) indica o diretório atual.

6. **Executar o Container:**
   - Em seguida, rode a imagem criada:
     ```bash
     docker run meu-hello-world
     ```

7. **Resultado Esperado:**
   - O terminal exibirá a saída:
     ```text
     Hello World!
     ```

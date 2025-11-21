<p align="center">
    <img src="https://assets.dio.me/AmCIKNey47db8GCPI9cbPK_ylWiACnT1SQyBoujOYmo/f:webp/h:413/q:80/w:413/L3JhbmtpbmcvOThiMDRkNzktMjI5Ni00MGZlLThjNjctMjI0OTc4Y2E0ZjZkLnBuZw" alt="Imagem Bootcamp Automação n8n Santander" width="177">
</p>
## ✨ n8n em Docker

### 📃 Descrição

Ambiente para criar automações n8n em Docker

### ⚙️ Pré-requisitos

- Docker

### 🔥 Como Utilizar

1. Clone o repositório

        git clone git@github.com:wsawebmaster/docker-n8n.git

2. Suba aplicação em container Docker

        docker-compose up -d

### Acessar o
Projeto: [http://localhost:5678/](http://localhost:5678/)<br />

No primeiro acesso exibirá um formulário para cadastro semelhante a imagem abaixo, faça seu cadastro

![Imagem ao acessar pela primeira vez](assets/img/primeiro-acesso.png)

Exemplo para preenchimento
![Imagem exemplo de preenchimento](assets/img/exemplo-preenchimento.png)

Confirmar para receber chave de ativação para uso da versão comunidade
![Imagem receber chave de ativação](assets/img/chave-comunidade.png)

Para ativar, clique no canto inferior esquerdo, Settings, Enter activation key e cole o código de ativação enviado em seu email
![Imagem como ativar](assets/img/como-ativar.png)

Clique em Start from Scratch para iniciar um novo projeto
![Imagem iniciar novo projeto](assets/img/novo-projeto.png)

---
---

### Encerrar containers em execução

    docker-compose down

### Rebuild

    docker-compose up --build -d

### Remover Todos os Contêineres e Imagens em Um Comando

    docker stop $(docker ps -aq) && docker rm $(docker ps -aq) && docker rmi $(docker images -q) && docker network rm $(docker network ls -q)


### 🌍 Links Úteis

- 📚 [Documentação n8n](https://docs.n8n.io)
- 🔧 [400+ Integrações](https://n8n.io/integrations)
- 💡 [Workflows Exemplo](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/advanced-ai/)
- 👥 [Fórum](https://community.n8n.io)
- 📖 [Tutoriais](https://community.n8n.io/c/tutorials/28)

---
---

### 👨‍💻 Expert

<p>
<img 
      align="left" 
      style="margin: 10px; width: 80px; border-radius: 50%;" 
      src="https://avatars.githubusercontent.com/u/52001930?s=400&u=fb999c966c5c652a8357cbede4b1112e79cbfe18&v=4" 
/>
    <p style="padding-top:25px">&nbsp&nbsp&nbsp Wagner Andrade<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/wsawebmaster">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/
wsawebmaster">LinkedIn</a>
&nbsp;|&nbsp;
<a href="mailto:wsawebmaster@yahoo.com.br">
    Email</a>
  &nbsp;|&nbsp;
</p>
</p>
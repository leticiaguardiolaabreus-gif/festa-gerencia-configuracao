# Festa - Gerência de Configuração

Projeto desenvolvido para a disciplina de **Gerência de Configuração**, do curso de **Engenharia de Software**.

O projeto consiste em páginas HTML de um sistema de gerenciamento de festas, utilizando **Bootstrap** para a interface.

## 👥 Grupo

- **Letícia Guardiola**
- **João Marcelo Cruz**
- **Gustavo Vilela**

**Professor:** Ewerton Menezes

## 📁 Estrutura do Projeto

```text
festa-gerencia-configuracao/
│
├── .github/
│   └── workflows/
│       └── workflow.yml
│
├── Baloes/
│   ├── inserir.html
│   ├── procurar.html
│   ├── alterar.html
│   └── excluir.html
│
├── Bolos/
│   └── ...
│
├── Docinhos/
│   ├── Create.html
│   ├── Read.html
│   ├── Update.html
│   └── Delete.html
│
├── .gitignore
├── Dockerfile
├── index.html
└── README.md
```

- `index.html`: página inicial e menu de acesso às entidades.
- `Docinhos/`: páginas do CRUD de Docinhos.
- `Baloes/`: páginas do CRUD de Balões.
- `Bolos/`: páginas do CRUD de Bolos.
- `.github/workflows/`: arquivos de configuração do GitHub Actions.
- `Dockerfile`: configuração para executar o projeto em um container Docker.
- `README.md`: documentação do projeto.

## ▶️ Como executar

### Executando diretamente

Como o projeto é composto por páginas HTML, basta abrir o arquivo:

```text
index.html
```

no navegador.

### Executando com Docker

Com o Docker instalado, na raiz do projeto execute:

```bash
docker build -t festa-app .
```

Depois, execute o container:

```bash
docker run -p 8080:80 festa-app
```

A aplicação poderá ser acessada em:

```text
http://localhost:8080
```

## 🛠️ Tecnologias

- HTML5
- Bootstrap 5
- Docker
- GitHub Actions
- Git/GitHub

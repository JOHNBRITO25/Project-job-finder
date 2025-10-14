# 🧭 Job Finder

O **Job Finder** é uma aplicação web desenvolvida com **Node.js** e **Express**, que permite cadastrar e buscar vagas de emprego.  
Este projeto foi desenvolvido **acompanhando as aulas de um curso**, passo a passo com o professor, com o objetivo de **aprender e praticar conceitos fundamentais de back-end e integração com banco de dados**.

---

## 🚀 Tecnologias utilizadas

- **Node.js**
- **Express**
- **Express-Handlebars**
- **Sequelize**
- **SQLite (banco local - app.db)**
- **HTML / CSS**
- **JavaScript**

---

### 📁 Estrutura do projeto

db/

├── app.db # Banco de dados SQLite

└── conection.js # Conexão com o banco de dados

models/

└── Job.js # Modelo da tabela de vagas

routes/

└── jobs.js # Rotas principais da aplicação

views/

├── layouts/ # Layout principal

├── add.handlebars # Página de cadastro de vaga

├── index.handlebars # Página inicial com listagem

└── view.handlebars # Página de detalhes da vaga

public/

├── css/ # Arquivos de estilo

└── img/ # Imagens utilizadas

app.js # Arquivo principal da aplicação

package.json # Dependências do projeto

---

####🧩 Funcionalidades

Cadastrar novas vagas de emprego

Listar todas as vagas disponíveis

Buscar vagas por palavra-chave

Visualizar detalhes de uma vaga específica

---

#####🗃️ Banco de dados

O projeto utiliza SQLite, salvo localmente no arquivo app.db.
As interações com o banco são feitas através do Sequelize, o que permite fácil adaptação para outros bancos (MySQL, PostgreSQL, etc).

---

######💡 Aprendizados

Durante o desenvolvimento, foram praticados conceitos como:

Criação de rotas com Express

Organização de projetos Node.js em estrutura MVC

Integração com banco de dados via Sequelize

Uso de templates com Handlebars

CRUD básico de vagas

Configuração de servidor e templates dinâmicos

Este projeto foi feito como exercício de aprendizado, acompanhando o professor e aplicando os conceitos passo a passo.

---

📘 Este projeto faz parte do meu processo de aprendizado em desenvolvimento back-end com Node.js.

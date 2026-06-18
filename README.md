# 🤖 Criação do Primeiro Agente de IA com N8N

Este projeto demonstra a criação de um **Agente de IA para Recursos Humanos**, utilizando automação com **N8N**, banco de dados **MySQL** hospedado no **Railway** e integração com o **Telegram**.

A empresa utilizada como exemplo é a **ChocolaTech**, uma empresa fictícia criada para fins de estudo.

## 📋 Tecnologias Utilizadas

* N8N
* Cohere
* Telegram Bot
* MySQL
* Railway

## 📄 Base de Conhecimento

O agente utiliza como fonte de conhecimento o Manual de RH da empresa ChocolaTech.

**Documento:**
https://raw.githubusercontent.com/ericmonne/chocolatech-imersao/refs/heads/main/Manual%20de%20RH%20ChocolaTech.txt

---

# 🔄 Workflow 1 - Carregamento do Documento

Neste primeiro fluxo, o N8N realiza a leitura do documento hospedado no GitHub através do link RAW. O conteúdo é processado e armazenado para ser utilizado posteriormente pelo agente.

### Fluxo

![Workflow 1](https://github.com/user-attachments/assets/2862e0a5-1712-45b0-b403-56ffa51dee9e)

### Objetivo

* Buscar o documento do GitHub Raw;
* Processar o conteúdo;
* Preparar os dados para consulta pelo agente de IA.

---

# 🤖 Workflow 2 - Criação do Agente HR Buddy

Após a carga dos dados, foi criado o agente **HR Buddy**, responsável por responder perguntas relacionadas ao RH da empresa.

O agente está conectado ao banco de dados MySQL hospedado no Railway e integrado ao Telegram para interação com os usuários.

### Fluxo Completo

![Workflow 2](https://github.com/user-attachments/assets/ec83db20-0968-42db-b371-619d2c625c0e)

### Funcionalidades

* Consulta à base de conhecimento da empresa;
* Respostas contextualizadas usando IA;
* Persistência de dados no MySQL;
* Atendimento via Telegram;
* Automação completa através do N8N.

---

# 🗄️ Integração com Banco de Dados

O agente utiliza um banco MySQL hospedado no Railway para armazenar informações e auxiliar na recuperação de contexto durante as conversas.

### Exemplo de utilização

![Banco de Dados Integrado](https://github.com/user-attachments/assets/afd07469-e4c7-43af-af23-a633c83dfa52)

---

# 📱 Integração com Telegram

O bot **HR Buddy** foi integrado ao Telegram para permitir que colaboradores realizem consultas diretamente pelo aplicativo.

### Exemplo de Conversa

![Telegram](https://github.com/user-attachments/assets/0f5a4e98-c7b9-4000-a525-3d8350055234)

---

# 🚀 Resultado Final

Ao final do projeto, foi criado um agente de IA capaz de:

✅ Consultar o manual interno da empresa;

✅ Responder dúvidas relacionadas ao RH;

✅ Utilizar contexto armazenado em banco de dados;

✅ Interagir em tempo real pelo Telegram;

✅ Automatizar processos utilizando N8N.

Este projeto demonstra como combinar IA, automação e banco de dados para criar assistentes corporativos inteligentes e escaláveis.

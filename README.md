# 🎫 Sistema de Chamados

Sistema simples de **abertura e gerenciamento de chamados**, desenvolvido em **PHP**, com envio automático de e-mails utilizando uma **classe MAIL**.

O principal objetivo deste projeto é demonstrar que é possível **enviar e-mails com PHP utilizando código limpo, organizado e reutilizável**, além de integrar banco de dados para persistência das informações.

---

## 🚀 Objetivo do Projeto

Este projeto foi criado para demonstrar:

* Envio de e-mails com PHP usando classe própria
* Organização de código backend
* Registro de chamados em banco de dados
* Integração entre aplicação web e e-mail
* Boas práticas básicas em PHP

---

## 🛠️ Tecnologias Utilizadas

* **PHP**
* **MySQL**
* **phpMyAdmin**
* **SMTP / MAIL**
* **HTML / CSS (interface básica)**

---

## 📋 Funcionalidades

* Abertura de chamados
* Envio automático de e-mail ao registrar um chamado
* Armazenamento das informações no banco de dados
* Organização do código em classes
* Fácil adaptação para outros sistemas

---

## 📂 Estrutura do Projeto

```text
.
├── config/
│   └── database.php
├── mail/
│   └── Mail.php
├── chamados/
│   └── criar_chamado.php
├── index.php
└── README.md
```

---

## ⚙️ Configuração do Banco de Dados

1. Crie um banco de dados no **MySQL**
2. Importe as tabelas necessárias via **phpMyAdmin**
3. Configure as credenciais no arquivo de conexão

```php
define('DB_HOST', 'localhost');
define('DB_NAME', 'sistema_chamados');
define('DB_USER', 'root');
define('DB_PASS', '');
```

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/sistema_chamados.git
```

2. Copie o projeto para o diretório do servidor (ex: `htdocs`)

3. Configure o banco de dados

4. Acesse no navegador:

```text
http://localhost/sistema_chamados
```

---

## 🧠 O que este projeto demonstra

* Domínio básico de PHP backend
* Criação de classes reutilizáveis
* Envio de e-mails com PHP
* Integração com banco de dados relacional
* Organização e clareza no código

---

## 🚀 Possíveis Melhorias Futuras

* Autenticação de usuários
* Status do chamado (aberto, em andamento, fechado)
* Dashboard administrativo
* Histórico de chamados
* Logs de envio de e-mail

---

## 📄 License

This project is licensed for **educational and portfolio purposes only**.

---

## 👤 Autor

Felipe

Projeto desenvolvido com foco em **estudo, prática de PHP e construção de portfólio**.

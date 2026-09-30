# 🗄️ Banco de Dados (`database/`)


## 📌 Introdução

A pasta `database/` abriga todo o ecossistema de **persistência e modelagem de dados** do módulo de **Agenda de Contatos**. 

Uma aplicação orientada a objetos precisa de um mecanismo confiável para armazenar e recuperar informações de forma persistente — como credenciais de usuários, perfis de acesso, logs de autenticação e tokens de recuperação de senha. Este diretório centraliza desde a modelagem conceitual e lógica do banco de dados até os scripts SQL necessários para a criação das tabelas e população inicial dos dados.

---

## 📁 Estrutura de Diretórios

```text
database/
│
├── README.md                 # Documentação do diretório database/
│
├── DER/                   # Diagrama Entidade-Relacionamento (Modelo Conceitual)
├── DL/                    # Diagrama Lógico de Dados (Modelo Lógico)
└── scripts/               # Scripts SQL DDL e DML
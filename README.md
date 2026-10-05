# 📇 AgendaContatos

<p align="center">
  <img src="resources/images/logo_SDAMK _STUDIOS.png" alt="Logo SDAMK Studios" width="320"/>
</p>

<p align="center">
  <b>Módulo de Gestão de Contatos com Persistência de Dados</b><br/>
  <i>Desenvolvido por: SDAMK Studios — IFCE Campus Maranguape</i>
</p>

---

## 📝 Descrição

A **AgendaContatos** é a segunda aplicação integrante do ecossistema do projeto, operando de forma conectada e integrada ao jogo **pokeIF**.

Trata-se de um sistema focado no ecossistema de operações **CRUD** (Criação, Leitura, Atualização e Remoção) com persistência de dados local. A aplicação foi concebida para assegurar que todas as informações registradas permaneçam salvas com total segurança mesmo após o encerramento do programa, respaldada por estratégias de **redundância e tolerância a falhas** desenvolvidas pela equipe.

---

## 🎯 Objetivos e Funcionalidades

* **Operações CRUD Completas:** Gerenciamento estruturado de registros de contatos.
* **Atributos de Cadastro:** Cada contato conta com informações essenciais cadastradas:
  * Nome completo
  * Número de telefone
  * Endereço de e-mail
* **Mecanismo de Pesquisa:** Sistema de consulta rápida com filtro principal por **Nome**, com planejamento para expansão de busca por **Telefone** e **E-mail**.
* **Persistência Offline & Segurança:** Armazenamento local de dados via **MySQL**, garantindo funcionamento confiável e sem dependência de conexão com a internet.

---

## 📌 Versão do Projeto

* **Versão Atual:** `V0.0.0` *(Fase inicial de estruturação de pastas, padronização de repositórios e documentação teórica)*.

---

## 🚀 Como Executar o Projeto

A **AgendaContatos** é distribuída de forma integrada à aplicação principal **pokeIF**:

1. Faça o download do pacote comprimido (`.zip`) contendo a aplicação.
2. Extraia o conteúdo no diretório de sua preferência.
3. A aplicação estará **pronta para uso**, armazenada e executável de forma 100% offline no seu aparelho.

---

## 👥 Integrantes da Equipe & Divisão de Papéis

<p align="center">
  <sub><b>SDAMK Studios:</b> Saulo, Davi, Andresson, Matheus, Kalleo e Caio</sub>
</p>

| Integrante | Papéis e Responsabilidades no Projeto |
| :--- | :--- |
| **Davi** | Desenvolvedor Java, Banco de Dados, GitHub, UX |
| **Kalleo** | Desenvolvedor Java, Banco de Dados, UX |
| **Saulo** | Desenvolvedor Java, UX, UI |
| **Matheus** | GitHub, UI, Relatório |
| **Andresson** | UI, Testes |
| **Caio** | UI |

---

## 📁 Estrutura do Diretório

A organização do repositório segue uma estrutura padronizada para separar código-fonte, recursos visuais, documentação técnica e materiais de suporte:

```text
```text
PokeIf/
├── .gitignore             # Arquivos e pastas ignorados pelo Git
├── LICENSE                # Licença de uso do projeto (MIT License)
├── README.md              # Documentação principal do repositório
│
├── database/              # Modelagem e scripts de Banco de Dados
│   ├── DER/               # Diagrama Entidade-Relacionamento (Modelo Conceitual)
│   ├── DL/                # Diagrama Lógico (Modelo Lógico)
│   └── scripts/           # Scripts SQL (Criação de tabelas e inserção de dados)
│
├── docs/                  # Documentação técnica e visual do sistema
│   ├── diagrams/          # Diagramas explicativos do fluxo do jogo
│   ├── presentations/     # Apresentações e slides do projeto
│   ├── ui-ux/             # Protótipos e design da interface do usuário
│   │   ├── mockups/       # Designs de alta fidelidade das telas
│   │   ├── prototypes/    # Protótipos interativos
│   │   └── wireframes/    # Esboços e estruturas de tela
│   └── uml/               # Diagramas UML (Classes, Casos de Uso, Sequência, etc.)
│
├── resources/             # Recursos estáticos e visuais da interface
│   ├── icons/             # Ícones utilizados na UI
│   └── images/            # Imagens, logos e fotos da equipe
│
├── src/                   # Código-fonte da aplicação em Java / JavaFX
│
└── support/               # Materiais complementares e de apoio
    ├── documents/         # Documentos de apoio e especificações
    ├── references/        # Referências bibliográficas e links úteis
    ├── tutorials/         # Guias e tutoriais de utilização e execução
    └── videos/            # Recursos audiovisuais usados no desenvolvimento


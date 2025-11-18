# 💼 JobsCalc - Calculadora de Jobs Freelancer

Uma aplicação web para estimativa e gerenciamento de custos e valores de projetos freelancer. O objetivo é ajudar o profissional a calcular o valor ideal de um projeto, considerando horas de trabalho, valor da hora e custos fixos.

Este projeto foi desenvolvido durante a **Maratona Discover** da **Rocketseat** (edição 05).

## 🛠️ Tecnologias Utilizadas

O projeto utiliza um stack focado em Back-end com renderização de templates:

| Categoria | Tecnologia | Uso |
| :--- | :--- | :--- |
| **Back-end** | **Node.js** | Ambiente de execução. |
| **Back-end** | **Express.js** | Framework para o servidor e roteamento. |
| **Banco de Dados** | **SQLite** | Persistência de dados (jobs, custos e perfil). |
| **Front-end** | **EJS** (Embedded JS) | Motor de template para renderizar HTML dinâmico. |

## 🚀 Instalação e Execução

### Pré-requisitos

Certifique-se de ter o **Node.js** (versão LTS recomendada) e o **npm** (ou yarn) instalados em sua máquina.

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/stochiconrado/nlw05-jobscalc.git](https://github.com/stochiconrado/nlw05-jobscalc.git)
    ```
2.  **Acesse o diretório do projeto:**
    ```bash
    cd nlw05-jobscalc
    ```
3.  **Instale as dependências:**
    ```bash
    npm install
    # ou yarn install
    ```
4.  **Execute o servidor:**
    O projeto deve criar automaticamente o arquivo do banco de dados (`database.sqlite`) e as tabelas necessárias na primeira execução.
    ```bash
    npm start
    ```

O servidor será iniciado e estará acessível em **`http://localhost:3000`**.

## 💡 Como Contribuir

* Faça um **fork** do projeto.
* Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
* Faça commit de suas alterações (`git commit -m 'feat: Adiciona nova funcionalidade'`).
* Abra um **Pull Request**.

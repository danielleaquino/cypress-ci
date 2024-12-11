# Projeto Cypress CI/CD

## Descrição
Este projeto é uma automação de testes end-to-end utilizando **Cypress**. É integrado a um pipeline de **Integração Contínua (CI)** para garantir que todos os testes sejam executados de forma automatizada, ajudando a detectar falhas e manter a qualidade do código. Este projeto foi desenvolvido como parte do curso **"Cypress: automatização de testes web e CI"** da **Alura**.

## Estrutura do Projeto
O projeto está estruturado da seguinte forma:
- **`cypress/`**: Contém os testes automatizados, com pastas para `integration`, `fixtures`, `support`, etc.
- **`cypress.json`**: Configuração principal do Cypress.
- **`package.json`**: Gerencia as dependências do projeto e scripts de execução.
- **`cypress/plugins/`**: Plugins e configurações específicas do Cypress.
- **`cypress/support/`**: Arquivos auxiliares, como comandos customizados e configuração de pré-testes.

## Funcionalidades
- **Testes E2E**: Automação de testes em navegadores para simular a experiência do usuário.
- **Integração Contínua**: Configuração de integração contínua para rodar testes em ambientes de CI, foi utilizado o GitHub Actions
- **Relatórios**: Geração de relatórios de execução para análise.

## Tecnologias Utilizadas
- **Cypress**: Framework de teste para aplicações web.
- **Node.js**: Ambiente de execução do JavaScript.
- **CI/CD**: Integração com ferramentas de integração contínua, como GitHub Actions.
- **NPM**: Gerenciador de pacotes para dependências.

## Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas no seu computador:
- **Node.js**: [Baixe aqui](https://nodejs.org/).
- **Git**: [Baixe aqui](https://git-scm.com/).

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/danielleaquino/cypress-ci.git
   cd cypress-ci

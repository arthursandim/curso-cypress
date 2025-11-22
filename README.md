# Cypress - Estudos e Implantação

Este repositório foi criado com o objetivo de estudar e praticar a implantação de **testes end-to-end (E2E)** utilizando o **Cypress**, seguindo o curso da plataforma **Alura**.

## 📚 Curso de Referência

**Cypress: automatização de testes web e CI** - Alura

- **Carga Horária:** 8h
- **Avaliação:** 9.0
- **Atualização:** 30/08/2024
- **Instrutor:** Camila Pessôa

## 🎯 Objetivos do Estudo

Este curso aborda:

- Automatizar testes E2E com Cypress para garantir a qualidade do software
- Implementar pipelines de integração contínua com GitHub Actions
- Integrar o Cypress Cloud para colaboração em testes
- Utilizar faker.js e plugins para enriquecer cenários de testes com dados realísticos
- Usar inteligência artificial para melhorar a escrita e eficiência dos testes
- Aplicar boas práticas para aumentar a produtividade em testes automatizados

## 🏗️ Estrutura do Projeto

O repositório contém dois projetos complementares que serão utilizados nos testes:

### 1. **Frontend** (`/web/vollmedclient`)
Aplicação frontend desenvolvida em **React** com **TypeScript**. Este é o alvo principal dos testes Cypress, onde serão automatizados os cenários de interação com a interface do usuário.

### 2. **Backend** (`/server/3745-cypress-volserver`)
Aplicação backend desenvolvida em **Node.js** com **TypeScript**. Fornece as APIs necessárias para suportar os testes E2E do frontend.

## 📖 Módulos do Curso

### 1. Aprimorando o uso de seletores
- Configuração do ambiente e URL base
- Asserções encadeadas no Cypress
- Especificação de contextos de testes
- Integração com VSCode e Cypress
- Testes de regressão

### 2. Melhorando asserções
- Recuperação de sessões com `cy.session()`
- Testes em diferentes navegadores
- Captura de elementos com seletores específicos
- Uso de plugins do Cypress
- Validações com seletores não determinísticos

### 3. Requisições via Cypress
- Testes de API com Cypress
- Validações em respostas do servidor
- Testes de API GraphQL
- Estratégias com Mocks e Stubs
- Validação de cenários negativos

### 4. Integração Contínua e Cypress
- GitHub Actions para automação de testes
- Cypress Cloud para colaboração
- Paralelismo na execução de testes
- Cypress Split para otimização
- Arquitetura de diretórios para testes

### 5. IA Generativa e Produtividade
- Geração de dados com faker.js
- Automação com ChatGPT e Gemini
- Testes de performance com Cypress

## ⚙️ Configuração do Cypress

A configuração do Cypress está centralizada no arquivo `cypress.config.js` na raiz do projeto.

**Recursos configurados:**
- ✅ Testes E2E
- 📹 Gravação automática de vídeos dos testes
- 📊 Relatórios em HTML com **Mochawesome**
- 📁 Resultados armazenados em `cypress/results`

## 🚀 Como Iniciar

### Pré-requisitos
- Node.js instalado
- npm ou yarn

### Instalação de dependências
```bash
npm install
```

### Executar os testes
```bash
npm run cypress:open   # Abre a interface Cypress (modo interativo)
npm run cypress:run    # Executa os testes em headless (modo CI)
```

## 📝 Notas

Os testes E2E serão implementados ao longo do curso para validar fluxos completos da aplicação, integrando frontend e backend em cenários reais de uso.

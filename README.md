# 🏫 Projeto Integrador – Sistema de Cadastro Universitário

Este repositório reúne o material produzido para o Projeto Integrador, incluindo:

- Diagramas UML e modelagem (fase 1)
- Protótipos de interface (fase 2)
- Documentação em formato Markdown

O objetivo do sistema é apoiar a gestão acadêmica da instituição, permitindo o cadastro e manutenção de **Alunos**, **Professores** e **Fornecedores**, com diferentes níveis de acesso (RH, Secretaria Acadêmica, Compras e Administrador).

---

## 👥 Integrantes do Grupo

- Samuel David Paz Ferreira
- Emily de Oliveira Ramos
- Anna Leticia da Silva
- Thamires Silva Raposo
- Ana Milena Queiroz Silva
- Pedro dos Santos Júnior

---

## 📂 Estrutura do Repositório

Estrutura atual dos arquivos de documentação e protótipos:

- [`diagramas-fase1/casos-de-uso.md`](diagramas-fase1/casos-de-uso.md)  
  Arquivo com a documentação dos **casos de uso** elaborados na fase 1.

- Pasta de protótipos da fase 2:  
  [`Protótipos de interface-fase2/`](Prot%C3%B3tipos%20de%20interface-fase2/)
  - [`login-page.png`](Prot%C3%B3tipos%20de%20interface-fase2/login-page.png)
  - [`dashboard-rh.png`](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-rh.png)
  - [`dashboard-secretaria.png`](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-secretaria.png)
  - [`dashboard-compras.png`](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-compras.png)
  - [`dashboard-adm.png`](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-adm.png)
  - [`listagem-alunos.png`](Prot%C3%B3tipos%20de%20interface-fase2/listagem-alunos.png)
  - [`listagem-professores.png`](Prot%C3%B3tipos%20de%20interface-fase2/listagem-professores.png)
  - [`listagem-fornecedores.png`](Prot%C3%B3tipos%20de%20interface-fase2/listagem-fornecedores.png)
  - [`cadastro-alunos.png`](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-alunos.png)
  - [`cadastro-professores.png`](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-professores.png)
  - [`cadastro-fornecedores.png`](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-fornecedores.png)

---

## 🧩 Visão Geral dos Perfis e Módulos

O sistema considera diferentes perfis de usuário, cada um com acesso a operações específicas:

- **RH**
  - Manter Professores (dados pessoais, endereço, contato, documentos, CPF)
- **Secretaria Acadêmica**
  - Manter Alunos (dados pessoais + dados acadêmicos)
  - Manter Professores (dados pessoais + vínculos acadêmicos)
- **Compras**
  - Manter Fornecedores (Pessoa Jurídica)
- **Administrador**
  - Acesso completo: Alunos, Professores e Fornecedores

---

## 🖼 Protótipos de Interface (Fase 2)

> As imagens abaixo estão todas na pasta  
> [`Protótipos de interface-fase2/`](Prot%C3%B3tipos%20de%20interface-fase2/).

---

### 1. Tela de Login

Protótipo da tela de autenticação, onde o usuário informa **e-mail** e **senha**.  
A partir das credenciais, o sistema identifica o **perfil de acesso** (RH, Secretaria, Compras, Administrador).

![Protótipo – Tela de Login](Prot%C3%B3tipos%20de%20interface-fase2/login-page.png)

---

### 2. Dashboards por Perfil

#### 2.1 Dashboard – RH

Dashboard voltado ao perfil de **Recursos Humanos**, com foco na gestão de professores  
(dados pessoais, endereço, contato e documentos com validação de CPF).

![Protótipo – Dashboard RH](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-rh.png)

#### 2.2 Dashboard – Secretaria Acadêmica

Dashboard voltado ao perfil da **Secretaria Acadêmica**, com acesso às jornadas de Alunos e Professores.

![Protótipo – Dashboard Secretaria](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-secretaria.png)

#### 2.3 Dashboard – Compras

Dashboard voltado ao perfil de **Compras**, com acesso à **listagem de fornecedores**  
e operações relacionadas a **Pessoa Jurídica / Fornecedores**.

![Protótipo – Dashboard Compras](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-compras.png)

#### 2.4 Dashboard – Administrador

Dashboard do **Administrador**, com acesso consolidado às operações de Alunos, Professores e Fornecedores.

![Protótipo – Dashboard Administrador](Prot%C3%B3tipos%20de%20interface-fase2/dashboard-adm.png)

---

### 3. Listagens

#### 3.1 Listagem de Alunos

![Protótipo – Listagem de Alunos](Prot%C3%B3tipos%20de%20interface-fase2/listagem-alunos.png)

#### 3.2 Listagem de Professores

![Protótipo – Listagem de Professores](Prot%C3%B3tipos%20de%20interface-fase2/listagem-professores.png)

#### 3.3 Listagem de Fornecedores

![Protótipo – Listagem de Fornecedores](Prot%C3%B3tipos%20de%20interface-fase2/listagem-fornecedores.png)

---

### 4. Telas de Cadastro

#### 4.1 Cadastro de Alunos

![Protótipo – Cadastro de Alunos](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-alunos.png)

#### 4.2 Cadastro de Professores

![Protótipo – Cadastro de Professores](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-professores.png)

#### 4.3 Cadastro de Fornecedores

![Protótipo – Cadastro de Fornecedores](Prot%C3%B3tipos%20de%20interface-fase2/cadastro-fornecedores.png)

---

## 📊 Diagramas UML (Fase 1) em Markdown

Os diagramas da fase 1 foram documentados em:

- [`diagramas-fase1/casos-de-uso.md`](diagramas-fase1/casos-de-uso.md)

Abaixo, um exemplo de como os casos de uso podem ser descritos também diretamente no README:

### 1. Diagrama de Casos de Uso (Exemplo de descrição)

- **Manter Aluno**
  - Ator(es): Secretaria, Administrador
  - Ações: cadastrar, editar, inativar, consultar
- **Manter Professor**
  - Ator(es): RH, Secretaria, Administrador
  - Ações: cadastrar, editar, inativar, consultar
- **Manter Fornecedor**
  - Ator(es): Compras, Administrador
  - Ações: cadastrar, editar, inativar, consultar

flowchart LR
    %% ===========================================
    %% Gestão de Cadastros — Universidade (Caso de Uso)
    %% ===========================================

    %% ---------- Atores ----------
    C[Compras]
    B[Administrador]
    S[Secretaria Acadêmica]
    R[RH]
    UA[Usuário Autenticado]

    %% Generalização dos perfis para Usuário Autenticado
    C -->|generalização| UA
    B -->|generalização| UA
    S -->|generalização| UA
    R -->|generalização| UA

    %% ---------- Casos de uso principais ----------
    UC_Fornecedores((Manter Fornecedores))
    UC_Alunos((Manter Alunos))
    UC_Professores((Manter Professores))
    UC_Login((Autenticar-se))

    %% ---------- Casos de uso genéricos ----------
    UC_PJ((Manter Pessoa Jurídica<br/>(Criar/Editar/Consultar/Inativar)))
    UC_PF((Manter Pessoa Física<br/>(Criar/Editar/Consultar/Inativar)))
    UC_Endereco((Manter Endereço e Contatos))
    UC_Docs((Anexar/Validar Documentos))
    UC_ValidarCNPJ((Validar CNPJ))
    UC_ValidarCPF((Validar CPF))

    %% ---------- Ligações Atores x Casos de Uso ----------
    %% Autenticação
    R --> UC_Login
    UA --> UC_Fornecedores
    UA --> UC_Alunos
    UA --> UC_Professores

    %% Perfis em relação aos casos de uso
    C --> UC_Fornecedores
    B --> UC_Fornecedores

    B --> UC_Alunos
    S --> UC_Alunos

    B --> UC_Professores
    S --> UC_Professores
    R --> UC_Professores

    %% ---------- Relações «extend» ----------
    UC_Fornecedores -. «extend» .-> UC_PJ
    UC_Alunos -. «extend» .-> UC_PF
    UC_Professores -. «extend» .-> UC_PF

    %% ---------- Relações «include» Pessoa Jurídica ----------
    UC_PJ -. «include» .-> UC_ValidarCNPJ
    UC_PJ -. «include» .-> UC_Endereco
    UC_PJ -. «include» .-> UC_Docs

    %% ---------- Relações «include» Pessoa Física ----------
    UC_PF -. «include» .-> UC_ValidarCPF
    UC_PF -. «include» .-> UC_Endereco
    UC_PF -. «include» .-> UC_Docs


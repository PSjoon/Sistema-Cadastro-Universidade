<img width="1342" height="826" alt="diagrama" src="https://github.com/user-attachments/assets/cf3aa10c-4ff8-47cc-93a1-3db1917fc40f" />

# Casos de Uso – Fase 1

Este documento reúne os casos de uso modelados na primeira etapa do Projeto Integrador.

---

## 1. Autenticar-se  
**Atores:** Usuário  
**Fluxo principal:**
1. Usuário informa login e senha.  
2. Sistema valida credenciais.  
3. Sistema concede acesso.  

**Fluxo alternativo / Exceções:**
- Credenciais inválidas → Exibe mensagem de erro.

---

## 2. Manter Alunos  
**Atores:** Administrador, Secretaria Acadêmica  
**Extende:** Manter Pessoa Física  
**Inclui:**  
- Validar CPF  
- Manter Endereço e Contatos  
- Anexar Documentos  

**Fluxo principal:**
1. Seleciona “Manter Alunos”.  
2. Sistema solicita dados pessoais e acadêmicos.  
3. Usuário informa ou edita dados.  
4. Sistema valida as informações.  
5. Sistema salva os dados.  

**Exceções:**
- CPF inválido  
- Documentos ausentes  
- Dados incompletos

---

## 3. Manter Professores  
**Atores:** Administrador, RH  
**Extende:** Pessoa Física  
**Inclui:**  
- Validar CPF  
- Endereço  
- Contatos  
- Documentos  

**Fluxo principal:**
1. Seleciona “Manter Professores”.  
2. Sistema solicita dados pessoais, de formação e documentos.  
3. Sistema valida.  
4. Sistema salva.

---

## 4. Manter Fornecedores  
**Ator:** Compras  
**Extende:** Pessoa Jurídica  
**Inclui:**  
- Validar CNPJ  
- Endereço  
- Contatos  
- Documentos  

**Fluxo principal:**
1. Seleciona “Manter Fornecedores”.  
2. Sistema solicita dados da empresa.  
3. Sistema valida as informações.  
4. Sistema salva.

---

## 5. Manter Pessoa Física  
**Fluxo principal:**
1. Acessa cadastro de Pessoa Física.  
2. Informa ou edita dados pessoais (nome, CPF, RG, etc.).  
3. Sistema valida CPF, endereço e contatos.  
4. Sistema salva as informações.

---

## 6. Manter Pessoa Jurídica  
**Fluxo principal:**
1. Acessa cadastro de Pessoa Jurídica.  
2. Informa dados da empresa (Razão Social, CNPJ, etc.).  
3. Sistema valida CNPJ, endereço e contatos.  
4. Sistema salva.

---

## 7. Manter Endereço e Contatos  
**Fluxo principal:**
1. Usuário informa endereço e contatos.  
2. Sistema valida formato (CEP, telefone, e-mail).  
3. Sistema salva os dados.

---

## 8. Anexar / Validar Documentos  
**Fluxo principal:**
1. Usuário anexa documentos.  
2. Sistema verifica formato e integridade.  
3. Sistema armazena os documentos.

---

## 9. Validar CPF  
**Fluxo de validação:**

1. Sistema recebe CPF  
2. Sistema valida dígitos verificadores  
3. Sistema retorna se é válido ou inválido

4. <img width="1303" height="738" alt="casodeuso" src="https://github.com/user-attachments/assets/67cab361-5f3f-4a5a-b0a9-c85b28e06d7c" />


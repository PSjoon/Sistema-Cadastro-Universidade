<img width="1303" height="738" alt="casodeuso" src="https://github.com/user-attachments/assets/67cab361-5f3f-4a5a-b0a9-c85b28e06d7c" />

Este documento reúne os casos de uso modelados na primeira etapa do Projeto Integrador.

---

## 1. Autenticar-se
**Ator:** Usuário  
**Fluxo principal:**  
1. Usuário informa login e senha.  
2. Sistema valida credenciais.  
3. Sistema concede acesso.  

**Fluxo alternativo:**  
- Credenciais inválidas → Exibe mensagem de erro.

---

## 2. Manter Alunos
**Atores:** Administrador, Secretaria Acadêmica  
**Extende:** Manter Pessoa Física  
**Inclui:** Validar CPF, Manter Endereço e Contatos, Anexar Documentos  

**Fluxo principal:**  
1. Usuário seleciona "Manter Alunos".  
2. Sistema solicita dados pessoais e acadêmicos.  
3. Usuário informa/edita dados.  
4. Sistema valida informações.  
5. Sistema salva.  

---

## 3. Manter Professores
**Atores:** Administrador, RH  
**Extende:** Manter Pessoa Física  
**Inclui:** Validar CPF, Endereço, Contatos, Documentos  

**Fluxo:**  
1. Usuário seleciona "Manter Professores".  
2. Sistema solicita dados pessoais e de formação.  
3. Sistema valida informações.  
4. Sistema salva.  

---

## 4. Manter Fornecedores
**Ator:** Setor de Compras  
**Extende:** Manter Pessoa Jurídica  
**Inclui:** Validar CNPJ, Endereço, Contatos, Documentos  

**Fluxo:**  
1. Usuário seleciona "Manter Fornecedores".  
2. Sistema solicita dados da empresa.  
3. Sistema valida.  
4. Sistema salva.  

---

## 5. Manter Pessoa Física
**Fluxo:**  
1. Usuário informa/edita dados pessoais (nome, CPF, RG).  
2. Sistema valida CPF.  
3. Sistema valida endereço e contatos.  
4. Sistema salva.  

---

## 6. Manter Pessoa Jurídica
**Fluxo:**  
1. Usuário informa dados da empresa (Razão Social, CNPJ).  
2. Sistema valida CNPJ.  
3. Sistema valida endereço e contatos.  
4. Sistema salva.  

---

## 7. Manter Endereço e Contatos
**Fluxo:**  
1. Usuário informa endereço e meios de contato.  
2. Sistema valida formato.  
3. Sistema salva.  

---

## 8. Anexar/Validar Documentos
**Fluxo:**  
1. Usuário anexa documentos.  
2. Sistema valida tipo e integridade.  
3. Sistema salva.  

---

## 9. Validar CPF
**Fluxo:**  
1. Sistema recebe CPF.  
2. Valida dígitos verificadores.  
3. Retorna resultado.  

---

## 10. Validar CNPJ
**Fluxo:**  
1. Sistema recebe CNPJ.  
2. Valida dígitos verificadores.  
3. Retorna resultado.  

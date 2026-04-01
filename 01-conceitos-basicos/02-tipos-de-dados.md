# Tipos de Dados

## O que são Tipos de Dados

Os **tipos de dados** definem qual tipo de valor pode ser armazenado em um campo de uma tabela.

Eles ajudam a manter a organização e evitam erros no banco de dados.

Por exemplo, um campo de idade deve armazenar números, e não textos.

---

## Principais Tipos de Dados

### Texto (STRING)

Utilizado para armazenar textos.

Exemplos:
- nomes
- emails
- endereços

Exemplo:
"Felipe", "Brasil", "email@email.com"

---

### Número (INTEGER / FLOAT)

Utilizado para armazenar valores numéricos.

- **INTEGER** → números inteiros  
- **FLOAT** → números com casas decimais  

Exemplos:
- 10
- 25
- 9.5

---

### Data (DATE)

Utilizado para armazenar datas.

Exemplos:
- 2026-01-01
- 2025-12-25

---

### Booleano (BOOLEAN)

Representa valores lógicos:

- verdadeiro (true)
- falso (false)

Exemplo:
- usuário ativo ou inativo

---

## Por que Tipos de Dados são importantes

Os tipos de dados são importantes porque:

- evitam dados inválidos
- melhoram a organização
- facilitam consultas
- ajudam na performance do banco

---

## Exemplo prático

Uma tabela de usuários poderia ter:

- nome → texto
- idade → número
- data_nascimento → data
- ativo → booleano

Cada campo possui um tipo específico para garantir consistência.
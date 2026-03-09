# Relatório de Bugs

## Bug 01 – Cadastro permite campo vazio.

**Severidade:** Média

**Prioridade:** Média

### Descrição

O sistema permite cadastrar um curso com um dos campos vazios, gerando inconsistência nas informações exibidas.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Deixar o campo Nome vazio.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem mesmo com o nome do curso em branco.

### Resultado esperado

O sistema deveria exibir um aviso para preencher o campo em branco.

### Evidência

https://drive.google.com/file/d/1ctlkDukJL9yVXhyZjFyg8y8JjvntLquv/view?usp=sharing

---

## Bug 02 – Cadastro permite descrição vazia.

**Severidade:** Média

**Prioridade:** Média

### Descrição

O sistema permite cadastrar um curso com um dos campos vazios, gerando inconsistência nas informações exibidas.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Deixar o campo Descrição vazio.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem mesmo com a descrição do curso em branco.

### Resultado esperado

O sistema deveria exibir um aviso para preencher o campo em branco.

### Evidência

https://drive.google.com/file/d/1AUKB9rlfxoUrnNa9nY78JuAkV69agjjR/view?usp=sharing

---

## Bug 03 – Cadastro permite data final menor que data inicial.

**Severidade:** Média

**Prioridade:** Média

### Descrição

O sistema permite cadastrar um curso onde a data de fim é anterior à data de início, gerando inconsistência nas informações exibidas.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Preencher os campos do formulário
3. Informar uma data de início maior que a data de fim
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem mesmo com as datas inconsistentes.

### Resultado esperado

O sistema deveria validar as datas e impedir o cadastro caso a data de fim seja menor que a data de início.

### Evidência

https://drive.google.com/file/d/13M388TETLQyEF62Hx6WLbyHxRA3krCeE/view?usp=sharing

---

## Bug 04 – Cadastro com número de vagas negativo.

**Severidade:** Média

**Prioridade:** Média

### Descrição

O sistema permite cadastrar um curso com número de vagas negativo, gerando inconsistência nas informações exibidas.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Inserir um número negativo no campo Vagas.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem mesmo com o número de vagas negativo.

### Resultado esperado

O sistema deveria exibir um aviso para inserir um número maior que 0.

### Evidência

https://drive.google.com/file/d/1szWSeZ9c7It7e_GuQNgS4jUXWMM1cASW/view?usp=sharing

---

## Bug 05 – Cadastro com texto muito grande.

**Severidade:** Média

**Prioridade:** Média

### Descrição

O sistema permite cadastrar um curso com mais de 255 caracteres no campo descrição.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Inserir um texto com mais de 255 caracteres no campo Descrição.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem o curso com caracteres excedentes.

### Resultado esperado

O sistema deveria exibir um aviso de limite de caracteres.

### Evidência

https://drive.google.com/file/d/1jNrvzwpzOSpUNsqnQvPOIMuN0I_YDppz/view?usp=sharing

---

## Bug 06 – Remover curso da lista.

**Severidade:** Alta

**Prioridade:** Alta

### Descrição

Após clicar no botão Excluir Curso, o curso excluído ainda continua na página.

### Passos para reproduzir

1. Acessar a página de listagem de cursos
2. Clicar no botão **Excluir Curso**.
3. Conferir se o curso foi excluído corretamente.

### Resultado atual

O sistema mostra uma mensagem de curso excluído com sucesso, porém o curso ainda continua na lista.

### Resultado esperado

O sistema deveria exibir a mensagem de sucesso e o curso sumir da página.

### Evidência

https://drive.google.com/file/d/1Ae4uHHI3N0CYFfqZNLhUmE4YUDreCq1G/view?usp=sharing

---

## Bug 07 – Remover curso da lista após atualização da página.

**Severidade:** Alta

**Prioridade:** Alta

### Descrição

Após clicar no botão Excluir Curso e atualizar a página, o curso excluído ainda continua na página.

### Passos para reproduzir

1. Acessar a página de listagem de cursos
2. Clicar no botão **Excluir Curso**.
3. Atualizar a página.
4. Conferir se o curso foi excluído corretamente.

### Resultado atual

O sistema mostra uma mensagem de curso excluído com sucesso, porém o curso ainda continua na lista.

### Resultado esperado

O sistema deveria exibir a mensagem de sucesso e o curso sumir da página.

### Evidência

https://drive.google.com/file/d/1ErSnUo_5-l5xh1kfDmI5DAHtzcYrgJkl/view?usp=sharing

---

## Bug 08 – Cadastro com caracteres especiais.

**Severidade:** Baixa

**Prioridade:** Baixa

### Descrição

O sistema permite cadastrar um curso com caracteres especiais no campo Nome do Curso.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Inserir um texto com caracteres especiais no campo Nome do Curso.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem o curso com caracteres especiais.

### Resultado esperado

O sistema deveria exibir um aviso que o texto não permite caracteres especiais.

### Evidência

https://drive.google.com/file/d/1cVPy4f8oNcGBvXtYcc2OxM9oFRO2_DUA/view?usp=sharing

---

## Bug 09 – Cadastro sem selecionar tipo de curso.

**Severidade:** Baixa

**Prioridade:** Baixa

### Descrição

O sistema permite cadastrar um curso sem o usuário selecionar o tipo de curso.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Deixar o campo Tipo de Curso em branco.
3. Preencher todos os outros campos corretamente.
4. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem o curso sem o Tipo de Curso especificado.

### Resultado esperado

O sistema deveria exibir um aviso que o usuário deve selecionar um Tipo de Curso.

### Evidência

https://drive.google.com/file/d/1TPPsc6n2vOHjCcFzzIJ3C371LYx0i8OK/view?usp=sharing

---

## Bug 10 – Cadastro com campos vazios.

**Severidade:** Alta

**Prioridade:** Alta

### Descrição

O sistema permite cadastrar um curso com todos os campos do fomulário em branco.

### Passos para reproduzir

1. Acessar a página de cadastro de cursos
2. Deixar todos os campos em branco.
3. Clicar em **Cadastrar curso**

### Resultado atual

O sistema cadastra o curso normalmente e exibe na listagem o curso com todos os campos vazios.

### Resultado esperado

O sistema deveria exibir um aviso que o usuário deve preencher os campos obrigatórios.

### Evidência

https://drive.google.com/file/d/1nrkODjMP-KBsnrdz2_01LNxBf_b0uKLP/view?usp=sharing

---

## Bug 11 – Navegação entre páginas.

**Severidade:** Baixa

**Prioridade:** Baixa

### Descrição

A lista de cursos exibe os cursos de forma desalinhada, dificultando a visualização do usuário.

### Passos para reproduzir

1. Acessar a página de listagem de cursos
2. Analisar a consistência visual da página

### Resultado atual

O sistema exibe uma lista dos cards em duas colunas, dificultando a visualização do usuário.

### Resultado esperado

O sistema deveria exibir os cards em mais colunas.

### Evidência

https://drive.google.com/file/d/1vxh4H6_7crobdPT-E2eqM_Qh9tBCcevJ/view?usp=sharing

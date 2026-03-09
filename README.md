# DESAFIO QA - BEEDOO 2026

## 📌 Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e gerenciamento de cursos.
Por meio do sistema, o usuário pode cadastrar cursos informando dados como:
- Nome do curso
- Descrição do curso
- Instrutor
- URL da imagem de capa
- Data de início
- Data de fim
- Número de vagas
- Tipo de curso

Após o cadastro, os cursos são exibidos em uma listagem onde o usuário pode visualizar as informações principais do curso e também realizar a exclusão do mesmo.

---

## 🔄 Principais fluxos da aplicação

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

1. Cadastro de curso
2. Listagem de cursos cadastrados
3. Exclusão de cursos

Fluxo principal esperado do usuário:

Cadastrar curso → visualizar curso na lista → excluir o curso (quando necessário)

---

## ⚠️ Pontos críticos para teste

Durante a análise foram identificados alguns pontos críticos que devem ser priorizados nos testes:

- Validação de campos obrigatórios no cadastro de cursos
- Validação das datas de início e fim do curso
- Validação do número de vagas
- Comportamento da aplicação ao cadastrar cursos com dados inválidos
- Atualização correta da lista após o cadastro de cursos
- Exclusão correta de cursos cadastrados
- Persistência dos dados após atualização da página

---

## 🧪 Estratégia de testes

A estratégia de testes utilizada foi baseada em testes exploratórios e testes funcionais manuais.
Foram criados cenários de teste que cobrem:

- Fluxo principal da aplicação
- Cenários negativos
- Validações de campos
- Comportamentos inesperados do sistema

Os cenários e casos de teste foram escritos utilizando a sintaxe Gherkin.

---

## 📊 Cenários e casos de teste

Os cenários e casos de teste foram documentados em uma planilha do Google Sheets.
Link da planilha:

https://docs.google.com/spreadsheets/d/1AkzXpThStHpybgHUe4TCwQzFZ1K1ASvMg3oMxHhET7g/edit?usp=sharing

---

## 🧪 Execução dos testes

Os cenários criados foram executados manualmente na aplicação disponibilizada.
Durante a execução foram registrados:

- Resultado obtido
- Status do teste
- Evidências da execução

🗒️ Resumo da execução dos testes:

Cenários criados: 15  
Testes executados: 15  
Testes aprovados: 4  
Testes falhos: 11  
Bugs identificados: 11 

Os resultados dos testes estão registrados na planilha juntamente com o status de execução.

### Ambiente de teste

Navegador: Google Chrome  
Sistema operacional: Windows 10  
Tipo de teste: Testes manuais funcionais e exploratórios

---

## 🐞 Registro de bugs

Os bugs encontrados durante a execução dos testes foram documentados no arquivo:

[Relatório de bugs](docs/bugs-report.md)

Cada bug contém:

- Título
- Passos para reproduzir
- Resultado atual
- Resultado esperado
- Severidade ou impacto

---

## 📷 Evidências de testes

As evidências da execução dos testes estão disponíveis no link abaixo:

https://drive.google.com/drive/folders/1-QXBo8ETn2YDqnJBKH06oroomY7f1z7c?usp=sharing

---

## ✅ Conclusão

A execução dos testes permitiu validar os principais fluxos da aplicação e identificar diversos problemas relacionados à validação de dados e consistência das informações cadastradas.

A documentação produzida neste repositório apresenta os cenários de teste, resultados da execução e os defeitos encontrados durante a análise da aplicação.

# Atividade Avaliativa: Fundamentos de Teste de Software

**Curso:** Bacharelado em Sistemas de Informação (8º Período)  
**Disciplina:** Teste de Software  
**Professora:** Dra. Ramayane Bonacin Braga  
**Instituição:** IF Goiano – Campus Ceres  
**Integrantes (Dupla):** 
- [Paulo Martins Alves do Prado]
- [Sara Luiz Farias]

---

## 1. Descrição da Atividade

Este repositório contém a documentação e as evidências da atividade avaliativa prática da disciplina de Teste de Software. A atividade consistiu no planejamento, estruturação, execução manual e reporte de defeitos em uma aplicação web, aplicando os conceitos fundamentais de QA (Quality Assurance), rastreabilidade e técnicas de teste baseadas em risco.

---

## 2. Classificação dos Testes (6 Critérios da Aula)

Conforme abordado em aula, a suíte de testes elaborada para esta atividade foi classificada segundo os 6 critérios de teste de software:

| Critério | Rótulo | Justificativa / Contexto |
| :--- | :--- | :--- |
| **1. Nível** | **Sistema** | O teste atua avaliando a aplicação inteira de ponta a ponta através do navegador web. |
| **2. Objetivo** | **Funcional** | Verifica as regras de negócio e funcionalidades centrais da aplicação (ex.: autenticação, gestão de carrinho e exibição de itens). |
| **3. Visão do Código** | **Caixa-preta** | O testador avalia apenas as entradas e saídas pela interface do usuário, sem visualizar o código-fonte interno. |
| **4. Execução** | **Dinâmico** | O sistema é colocado em funcionamento ativo para realização dos testes. |
| **5. Modo** | **Manual** | Os passos do roteiro são executados e verificados por uma pessoa (testador). |
| **6. Motivo** | **Teste Novo** | Trata-se da primeira execução da suíte de testes recém-elaborada. |

> **Síntese:** Trata-se de um **teste manual, funcional, dinâmico, de caixa-preta, no nível de sistema**.

---

## 3. Conceitos Aplicados e Regra de Ouro

Durante o desenvolvimento da suíte no Qase e a execução na aplicação, foram rigorosamente respeitados os seguintes conceitos fundamentais:

* **Regra de Ouro do Teste:** O *Resultado Esperado* de cada caso de teste foi definido **antes** da execução dos passos, evitando que a observação prévia da tela influenciasse o julgamento do testador.
* **Tipos de Testes Elaborados:**
  * **Teste Positivo:** Validação do comportamento esperado utilizando dados válidos (ex.: Login correto).
  * **Teste Negativo:** Validação do comportamento defensivo do sistema utilizando dados incorretos (ex.: Mensagem de erro ao informar senha inválida).
* **Cadeia de Erro, Defeito e Falha:**
  * **Erro:** Engano cometido pelo desenvolvedor/equipe no código ou especificação.
  * **Defeito (Bug):** A imperfeição presente no sistema resultante do erro.
  * **Falha:** O comportamento incorreto ou inesperado observado na tela durante a execução do teste.

---

## 4. Resumo dos Casos de Teste (Qase)

Foram estruturados 4 casos de teste no gerenciador de testes **Qase**, organizados com base na priorização de risco (Login, Carrinho e Interface/Imagens):

1. **CT-01 (Login Positivo):** Validar acesso ao sistema informando usuário e senha válidos.
2. **CT-02 (Login Negativo):** Validar exibição de mensagem de erro apropriada ao tentar autenticar com senha incorreta.
3. **CT-03 (Funcionalidade de Carrinho):** Validar a adição de um produto ao carrinho e verificar se o valor total reflete o valor do produto selecionado.
4. **CT-04 (Interface & Imagens):** Validar o carregamento correto das imagens dos produtos e suas descrições na vitrine principal.

---

## 5. Rastreabilidade e Registro do Defeito (GitHub Issues)

Para garantir a **rastreabilidade** entre a execução dos testes e a comunicação do problema encontrado:

* **Caso de Teste Relacionado:** CT-04 (ou indicar o CT correspondente)
* **Link para a Issue do Defeito:** `[Insira aqui o Link da Issue criada no repositório]`
* **Resumo do Defeito:** Ao executar o teste de interface, identificou-se que determinadas imagens de produtos não carregavam corretamente ou exibiam dados inconsistentes (descreva brevemente o bug encontrado durante a execução).
* **Evidências:** As capturas de tela demonstrando o resultado esperado e o resultado obtido estão anexadas na própria Issue e disponíveis na pasta `/evidencias` deste repositório.

---

## 6. Estrutura do Repositório

```text
├── README.md               # Documentação principal do repositório com respostas e classificações
├── evidencias/             # Capturas de tela (screenshots) dos testes e dos defeitos encontrados
│   ├── CT-01_execucao.png
│   ├── CT-02_execucao.png
│   ├── CT-03_execucao.png
│   └── CT-04_bug_evidencia.png
└── links.md (opcional)     # Links para o projeto no Qase e relatórios
```

---

## 7. Links Úteis

* **Projeto no Qase:** `[Insira aqui o Link do Projeto no Qase]`

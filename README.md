# 📚 Caderno Temático no NotebookLM: Cidadania Financeira, Renda Fixa e Reserva de Emergência

> Projeto prático desenvolvido para o desafio da **DIO (Digital Innovation One)**, aplicando inteligência artificial para **aprendizagem ativa, curadoria documental e engenharia de prompts** via **Google NotebookLM**.

---

## 🎯 1. Contexto e Objetivos

### Contexto
O planejamento financeiro pessoal depende do domínio de conceitos econômicos fundamentais, do entendimento de risco e liquidez, e do uso correto de ferramentas oficiais de simulação. Este caderno temático foi estruturado no **Google NotebookLM** a partir de portais institucionais e regulatórios brasileiros, garantindo um ambiente de estudo fundamentado (*grounded*), sem alucinações de IA.

### Objetivos de Estudo
- [x] Consolidar os conceitos basilares de Cidadania e Educação Financeira a partir das diretrizes do Banco Central e da CVM.
- [x] Analisar os mecanismos de proteção do investidor (FGC) e os instrumentos básicos de Renda Fixa (Poupança vs. Selic).
- [x] Mapear e integrar simuladores oficiais (Calculadora do Cidadão) para planejamento e cálculo de Reserva de Emergência.
- [x] Desenvolver uma esteira de engenharia de prompts iterativa, registrando ajustes e boas práticas de troubleshooting.

---

## 📑 2. Curadoria de Fontes e Links Oficiais

Foram integrados e referenciados portais institucionais, simuladores e canais educativos:

### Portais Oficiais e Educação Financeira
* **Banco Central do Brasil (BCB):** [Portal de Cidadania Financeira](https://www.bcb.gov.br/cidadaniafinanceira)
* **Programa Aprender Valor (BCB):** [aprendervalor.bcb.gov.br](https://aprendervalor.bcb.gov.br)
* **Redes Oficiais do BCB:** [Linktree Institucional](https://linktr.ee/bancocentraldobrasil)
* **Comissão de Valores Mobiliários (CVM):** [Portal do Investidor](http://www.portaldoinvestidor.gov.br/) | [gov.br/investidor](https://www.gov.br/investidor/)
* **Programa de Educação Financeira (TJSC):** [Portal TJSC](https://www.tjsc.jus.br/web/servidor/programa-educacao-financeira)

### Simuladores e Calculadoras Integradas
* **Calculadora do Cidadão (BCB):** [Acesso à Calculadora](https://www.bcb.gov.br/meubc/calculadoradocidadao)
* **Simulador Poupança vs. Selic:** [CalculaInvest](https://www.calculainvest.com.br/poupanca-vs-selic.html)
* **Simulador de Rendimento:** [Simula Financeiro](https://simulafinanceiro.com.br/)
* **Calculadora de Reserva de Emergência:** [Investidor10](https://investidor10.com.br/calculadoras/reserva-emergencia/)

### Garantia e Apoio
* **Fundo Garantidor de Créditos (FGC):** [Site Oficial](https://www.fgc.org.br)
* **Atendimento Educação Financeira (TJSC):** `educacaofinanceira@tjsc.jus.br`

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

O desenvolvimento das consultas no NotebookLM passou por ciclos de teste e refinamento técnico:

### 🔹 Teste 1: Comparação de Rendimento (Poupança vs. Selic)
* **Prompt Inicial (Ingênuo):**  
  > *"O que rende mais: poupança ou taxa Selic?"*
* **Problema Encontrado (Cicatriz):** A IA gerou uma resposta simplista sem citar a regra de corte da Taxa Selic (meta de 8,5% a.a.) e ignorou a isenção de IR na poupança vs. a tabela regressiva da Selic.
* **Prompt Refinado (Estratégico):**  
  > *"Com base nos materiais de Cidadania Financeira e simuladores de rendimento, compare o rendimento da Caderneta de Poupança com títulos atrelados à Selic. Detalhe a regra de remuneração da poupança quando a Selic está acima e abaixo de 8,5% a.a., o impacto do Imposto de Renda e aponte os links de simulação recomendados."*
* **Resultado:** Resposta analítica fundamentada, citando os critérios exatos do Banco Central e recomendando a Calculadora do Cidadão.

---

### 🔹 Teste 2: Dimensionamento de Reserva de Emergência e Proteção do FGC
* **Prompt Inicial (Ingênuo):**  
  > *"Como calcular a reserva de emergência e onde investir?"*
* **Problema Encontrado (Cicatriz):** O modelo recomendou genéricos "CDBs e fundos", sem delimitar os critérios de liquidez imediata ($D+0$/$D+1$) e sem explicar o limite de garantia do Fundo Garantidor de Crédito.
* **Prompt Refinado (Estratégico):**  
  > *"Atue como educador financeiro com base nas fontes institucionais do BCB, CVM e FGC. Apresente o método para dimensionar a reserva de emergência (critérios de 3 a 6 meses para CLT vs. 6 a 12 meses para autônomos) e explique como o teto de R$ 250 mil do FGC protege esse montante em caso de liquidação bancária."*
* **Resultado:** Síntese detalhada em passos executáveis com referência direta às normas de garantia ordinária do FGC e links das calculadoras.

---

## 📖 4. Miniguia de Estudo Consolidado

### 📊 Síntese dos Fundamentos

1. **Cidadania Financeira e Planejamento:**
   * Gastar menos do que recebe, mapear custos fixos e priorizar a quitação de dívidas de juros caros (cheque especial e rotativo do cartão).
   * Uso da **Calculadora do Cidadão** para simular juros reais compostos e correção monetária.

2. **Reserva de Emergência:**
   * **Objetivo:** Segurança e liquidez, não rentabilidade agressiva.
   * **Dimensionamento:** De 3 a 6 meses do custo de vida básico para trabalhadores com renda estável; de 6 a 12 meses para autônomos ou prestadores de serviço.
   * **Onde Alocar:** Ativos com liquidez diária e baixo risco (Tesouro Selic ou CDBs com 100% do CDI emitidos por instituições cobertas pelo FGC).

3. **Mecanismo de Proteção (FGC):**
   * Cobertura de até **R$ 250.000,00** por CPF e por instituição financeira associada.
   * Teto global de **R$ 1.000.000,00** renovável a cada período de 4 anos.

---

### 📚 Glossário de Termos Essenciais

| Conceito | Definição Baseada nas Fontes |
| :--- | :--- |
| **Taxa Selic** | Taxa básica de juros da economia brasileira, fixada pelo Copom/Banco Central, que influencia o custo do crédito e a rentabilidade da Renda Fixa. |
| **Poupança (Regra Atual)** | Rende 0,5% a.m. + TR se a Selic estiver acima de 8,5% a.a.; ou 70% da Selic + TR se a Selic for igual ou menor que 8,5% a.a. Isenta de IR para pessoa física. |
| **CDB (Certificado de Depósito Bancário)** | Título de dívida privada emitido por bancos para captação de recursos, comumente indexado a percentual do CDI e coberto pelo FGC. |
| **FGC** | Fundo Garantidor de Créditos; mecanismo privado de proteção a correntistas e aplicadores em caso de falência ou liquidação de instituição financeira. |
| **Liquidez Diária ($D+0$ / $D+1$)** | Disponibilidade para resgate do capital aplicado no próprio dia ou no dia útil seguinte à solicitação. |

---

### 🔁 Biblioteca de Prompts Reutilizáveis

Cole estes prompts diretamente no chat do NotebookLM para sessões contínuas de estudo:

#### 1. Simulação Prática de Cenário
```text
Considere uma pessoa com custo de vida mensal de R$ 2.500,00 que deseja formar sua reserva de emergência em 12 meses.
Com base nas regras do Banco Central e nos simuladores indicados nas fontes, trace um cronograma de aportes e indique a melhor alternativa de Renda Fixa conservadora para este caso.

# Engenharia de Requisitos: Levantamento e Especificação

Este material didático, baseado na apresentação da Profa. Dra. Luciene Chagas de Oliveira, aborda os conceitos e processos fundamentais da Engenharia de Requisitos no desenvolvimento de software.

> "Feliz aquele que transfere o que sabe e aprende o que ensina". - Cora Coralina

---

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-Requisitos-0078D4?style=for-the-badge&logo=azuredevops)
![Aula 03](https://img.shields.io/badge/Aula-03-blue?style=for-the-badge)
[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## Menu de Navegação

- [O que são Requisitos de Software?](#o-que-são-requisitos-de-software)
- [Tipos de Requisitos](#tipos-de-requisitos)
- [Engenharia de Requisitos](#engenharia-de-requisitos)
- [A Especificação de Requisitos](#a-especificação-de-requisitos)

---

## O que são Requisitos de Software?

Um requisito é a descrição das funções e das restrições de um sistema. É uma condição que um projeto precisa atender para satisfazer uma necessidade. A correta definição dos requisitos é crucial, pois eles podem "salvar ou enterrar" um projeto.

De acordo com a norma IEEE-90, requisitos são:

1.  Uma capacidade que um usuário necessita para resolver um problema ou atingir um objetivo.
2.  Uma capacidade que um sistema deve possuir para satisfazer um contrato, padrão ou outra especificação formal.
3.  O conjunto de todos os requisitos que formam a base para o desenvolvimento do software.

Em resumo, escrever requisitos é o processo de traduzir os desejos e necessidades do cliente em artefatos concretos que a equipe de desenvolvimento possa utilizar. Esta não é uma tarefa simples, pois envolve lidar com a subjetividade e as incertezas da comunicação humana. Cabe ao engenheiro de software capturar as reais necessidades do cliente e transformá-las em requisitos que o satisfaçam.

<div align="right">[⬆️ Voltar ao topo](#menu-de-navegação)</div>

---

## Tipos de Requisitos

Existem diferentes formas de classificar os requisitos de um sistema.

### Níveis de Abstração

- **Requisitos do Usuário:** Declarações de alto nível, em linguagem natural, sobre as funções que o sistema deve fornecer.
- **Requisitos de Sistema:** Descrições detalhadas das funções e restrições do sistema, servindo como um contrato entre o cliente e o desenvolvedor.

### Categorias Principais

#### 1. Requisitos Funcionais (RF)

Descrevem o que o sistema deve fazer em termos de tarefas ou serviços. Eles especificam como o sistema deve reagir a entradas específicas e se comportar em determinadas situações.

- **Foco:** A funcionalidade do sistema.
- **Importante:** Não devem abordar detalhes de implementação.

#### 2. Requisitos Não Funcionais (RNF)

Referem-se a aspectos de qualidade ou restrições que o sistema deve atender. Eles definem _como_ o sistema deve operar, em vez de _o que_ ele deve fazer.

- **Exemplos:**
  - **Performance:** Alta velocidade de execução.
  - **Disponibilidade:** O sistema deve rodar 24 horas por dia.
  - **Padrões:** Conformidade com padrões específicos.
  - **Restrições de Tempo:** Limites de tempo para operações.

#### 3. Requisitos Inversos (RI)

Descrevem condições que não devem ocorrer ou o que o sistema **NÃO** deve fazer.

- **Exemplos:**
  - `[RI-10]` O sistema não deve ser acessado pela internet.
  - `[RI-25]` O sistema não deve permitir vendas com datas retroativas.

<div align="right">[⬆️ Voltar ao topo](#menu-de-navegação)</div>

---

## Engenharia de Requisitos

A Engenharia de Requisitos é a disciplina que se ocupa de descobrir, analisar, documentar e verificar os requisitos de um sistema. Suas atividades visam garantir que o software desenvolvido atenda aos objetivos de negócio e possua alta qualidade.

### Processo de Engenharia de Requisitos

O processo pode ser dividido nas seguintes atividades principais:

1.  **Estudo de Viabilidade:** Uma análise breve para determinar se o sistema contribui para o negócio, se é tecnicamente implementável dentro das restrições de custo e prazo, e se pode ser integrado a outros sistemas.
2.  **Levantamento (Elicitação) e Análise:** Descobrir, organizar, priorizar e documentar os requisitos em interação com os _stakeholders_ (todos os envolvidos que têm influência sobre o projeto, como usuários e gerentes).
3.  **Especificação:** Documentar os requisitos de forma clara e organizada.
4.  **Validação:** Verificar se os requisitos documentados realmente correspondem ao que os stakeholders desejam.

### Técnicas de Levantamento (Elicitação) de Requisitos

- **Entrevistas:** Conversas com stakeholders para coletar informações. Podem ser **fechadas** (com perguntas pré-definidas) ou **abertas** (sem um roteiro fixo).
- **Questionários:** Úteis quando há muitos usuários em locais diferentes, permitindo coletar dados de um grande grupo de pessoas de forma padronizada.
- **Brainstorming:** Reuniões para gerar e explorar ideias livremente. As ideias são posteriormente analisadas, classificadas e priorizadas pelo grupo.
- **Prototipação:** Criação de modelos ou rascunhos do sistema (sketches, wireframes) para elicitar e validar requisitos de forma visual e interativa, especialmente quando há incertezas.

### Desafios Comuns no Levantamento de Requisitos

- Os clientes nem sempre sabem o que querem.
- Usuários e especialistas podem usar terminologias diferentes, causando falhas de comunicação.
- Requisitos de diferentes usuários podem ser conflitantes.
- O ambiente de negócio pode mudar durante o processo.

<div align="right">[⬆️ Voltar ao topo](#menu-de-navegação)</div>

---

## A Especificação de Requisitos

A Especificação de Requisitos é a documentação formal dos requisitos levantados. O seu formato pode variar, mas o foco deve ser sempre o **cliente**.

**Princípios importantes:**

- **Linguagem:** Deve usar a linguagem de negócio do cliente, não a linguagem técnica de TI.
- **Conteúdo:** Deve dizer **o que** o software deve fazer, sem entrar em detalhes de **como** será implementado. Evite incluir trechos de código.
- **Nível de Detalhe:** Uma especificação excessivamente detalhada pode paralisar o projeto. A documentação não substitui a comunicação contínua entre as partes.

### Estrutura Sugerida (Padrão IEEE)

Uma estrutura comum para o documento de especificação inclui:

- **Introdução:** Objetivo e escopo do projeto.
- **Glossário:** Definição de termos e siglas.
- **Descrição Geral:** Características dos usuários e restrições gerais.
- **Requisitos:** Lista detalhada dos requisitos funcionais, não funcionais e inversos.
- **Índice.**

<div align="center">

[⬅️ Voltar ao README Principal](../../README.md)

</div>

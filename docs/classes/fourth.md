# Engenharia de Software: Metodologias RUP, XP e Scrum

Este material oferece uma visão geral sobre três importantes metodologias de desenvolvimento de software: o Processo Unificado Rational (RUP), a Programação Extrema (XP) e o Scrum, com base na apresentação da Profa. Dra. Luciene Chagas de Oliveira.

> "Feliz aquele que transfere o que sabe e aprende o que ensina". - Cora Coralina

---

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-RUP%2C%20XP%20e%20Scrum-0078D4?style=for-the-badge&logo=azuredevops)
![Aula 04](https://img.shields.io/badge/Aula-04-blue?style=for-the-badge)
[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## 📚 Menu de Navegação

- [RUP (Rational Unified Process)](#1-rup-rational-unified-process)
- [Metodologias Ágeis e eXtreme Programming (XP)](#2-metodologias-ágeis-e-extreme-programming-xp)
- [Scrum](#3-scrum)

---

## 1. RUP (Rational Unified Process)

O RUP, ou Processo Unificado Rational, é um framework para gerar processos de desenvolvimento de software. Ele é composto por um conjunto de atividades bem definidas, com responsáveis, artefatos de entrada e saída, e utiliza a linguagem UML (Unified Modeling Language) para seus diagramas.

### Características Principais

O desenvolvimento de software seguindo o RUP possui três características centrais:

- **Iterativo e incremental**
- **Guiado por casos de uso (use cases)**
- **Baseado na arquitetura do sistema**

### Fases do RUP

O ciclo de vida do RUP é dividido em quatro fases sequenciais, cada uma podendo ser decomposta em iterações. Cada iteração realiza uma sequência de atividades (requisitos, análise, implementação, etc.) e geralmente resulta em uma versão executável do sistema.

1.  **Concepção (Inception):** Foco em definir o escopo do projeto, identificando os principais atores e casos de uso.
2.  **Elaboração (Elaboration):** Análise do sistema, detalhamento dos requisitos e definição da arquitetura de software.
3.  **Construção (Construction):** Desenvolvimento iterativo e incremental do produto de software.
4.  **Transição (Transition):** Atividades relacionadas à entrega e implantação do software para os usuários finais.

### Disciplinas e Papéis

O RUP é organizado em disciplinas (ou fluxos de atividades) que ocorrem ao longo das fases, com intensidades diferentes. As principais disciplinas incluem Modelagem de Negócios, Requisitos, Análise & Design, Implementação, Teste e Implantação.

Diferentes papéis são responsáveis por executar as atividades, como:

- **Analista de Sistema**
- **Arquiteto**
- **Projetista**
- **Programador**
- **Testador de Sistema**

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

---

## 2. Metodologias Ágeis e eXtreme Programming (XP)

As metodologias ágeis surgiram como uma alternativa aos processos mais rígidos e sequenciais. Elas são fundamentadas no **Manifesto Ágil**, assinado em 2001, que valoriza:

- **Indivíduos e interações** mais que processos e ferramentas.
- **Software em funcionamento** mais que documentação abrangente.
- **Colaboração com o cliente** mais que negociação de contratos.
- **Responder a mudanças** mais que seguir um plano.

### O que é eXtreme Programming (XP)?

Desenvolvido por Kent Beck nos anos 90, o XP é uma metodologia ágil projetada para equipes pequenas e médias que trabalham com requisitos vagos e em constante mudança. A codificação é considerada a principal tarefa. A ideia central é levar as boas práticas de desenvolvimento ao "extremo", como testar o tempo todo e integrar o código várias vezes ao dia.

### Valores do XP

- **Comunicação:** A comunicação face a face é valorizada como a forma mais rápida de compartilhar conhecimento.
- **Coragem:** Ter coragem para dizer a verdade, recomeçar quando necessário e inovar.
- **Feedback:** O feedback constante aumenta o aprendizado e a produtividade.
- **Simplicidade:** Fazer sempre "o mais simples que funciona" para gerar mais valor.
- **Respeito:** O respeito mútuo é necessário para que os outros valores funcionem efetivamente.

### Práticas do XP

| Prática                    | Descrição                                                                                                            |
| :------------------------- | :------------------------------------------------------------------------------------------------------------------- |
| **Pair Programming**       | Todo o código de produção é desenvolvido por duas pessoas no mesmo computador.                                       |
| **Continuous Integration** | Módulos são integrados e testados várias vezes ao dia. O código só é aceito se passar em 100% dos testes unitários.  |
| **Refactoring**            | Reconstrução contínua do código para remover redundâncias e eliminar funcionalidades inúteis.                        |
| **Small Releases**         | O software é entregue em pequenas versões para que o cliente obtenha valor o mais rápido possível.                   |
| **On-Site Customer**       | O cliente está sempre disponível para a equipe, em tempo integral, para responder a perguntas e definir prioridades. |
| **40-Hour Week**           | Cada programador trabalha 40 horas por semana para manter a produtividade e a qualidade.                             |
| **Coding Standards**       | Todo o código é desenvolvido seguindo um padrão de codificação comum.                                                |

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

---

## 3. Scrum

Scrum é um framework ágil para gerenciamento de projetos que pode ser aplicado a qualquer tipo de projeto complexo. Sua simplicidade, com poucas regras e artefatos, é uma de suas características centrais. Ele não é um método prescritivo, mas um framework que aplica o senso comum e a inteligência de toda a equipe para lidar com a imprevisibilidade.

### Padrões do Scrum

- **Backlog:** Uma lista de todas as funcionalidades desejadas para o produto. Essa lista é priorizada pelo Product Owner (dono do produto).
- **Sprints:** Unidades de tempo de até 30 dias nas quais um conjunto de tarefas do backlog é desenvolvido. Durante um Sprint, as tarefas selecionadas não podem ser alteradas.
- **Encontros Scrum (Daily Scrum):** Reuniões diárias de no máximo 15 minutos para sincronizar a equipe. Cada membro responde a três perguntas: O que você fez ontem? O que você vai fazer hoje? Quais problemas encontrou?
- **Revisão do Sprint (Sprint Review):** Ao final de cada Sprint, uma reunião informal (demo) é realizada para mostrar as funcionalidades concluídas aos stakeholders.
- **Retrospectiva do Sprint:** Uma reunião para a equipe refletir sobre o que funcionou bem e o que pode ser melhorado no próximo Sprint.

### Papéis no Scrum

O Scrum divide as responsabilidades de gerenciamento em três papéis principais:

1.  **Product Owner (Dono do Produto):** É responsável por representar os interesses de todos os stakeholders, gerenciar o Product Backlog e garantir que a equipe desenvolva as funcionalidades de maior valor para o negócio.
2.  **Scrum Master:** É o responsável pelo sucesso do Scrum. Ele ensina o processo, remove impedimentos e garante que a equipe siga as regras e práticas do Scrum.
3.  **Time (Equipe):** É a equipe de desenvolvimento, responsável por escolher as funcionalidades a serem desenvolvidas em cada Sprint e por entregá-las. A equipe é auto-gerenciável e coletivamente responsável pelo sucesso de cada iteração.

<div align="center">

[⬅️ Voltar ao README Principal](../../README.md)

</div>

# Gerência e Rastreabilidade de Requisitos

Este material didático, baseado na apresentação da _[Profa. Dra. Luciene Chagas de Oliveira](https://www.linkedin.com/in/luciene-chagas-de-oliveira-ph-d-b21b3b31/)_, aborda os processos de gerenciamento de mudanças e a importância da rastreabilidade no ciclo de vida dos requisitos de software.

> "Feliz aquele que transfere o que sabe e aprende o que ensina". - CORA CORALINA

---

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-Ger%C3%AAncia%20e%20Rastreabilidade-0078D4?style=for-the-badge&logo=azuredevops)
![Aula 05](https://img.shields.io/badge/Aula-05-blue?style=for-the-badge)
[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## 📚 Menu de Navegação

- [Engenharia de Requisitos: Uma Visão Geral](#engenharia-de-requisitos-uma-visão-geral)
- [Gerenciamento de Requisitos](#gerenciamento-de-requisitos)
- [Rastreabilidade de Requisitos](#rastreabilidade-de-requisitos)
- [Matriz de Rastreabilidade](#matriz-de-rastreabilidade)
- [Ferramentas para Gerência de Requisitos](#ferramentas-para-gerência-de-requisitos)

---

## Engenharia de Requisitos: Uma Visão Geral

A Engenharia de Requisitos é uma área da Engenharia de Software que se divide em dois grandes processos:

1.  **Desenvolvimento de Requisitos (ou Produção de Requisitos):** Envolve todas as atividades para criar e definir os requisitos.

    - **Levantamento:** Coletar os requisitos do software.
    - **Análise:** Modelar o comportamento desejado.
    - **Documentação:** Registrar o comportamento do sistema proposto.
    - **Validação:** Verificar se a especificação atende às necessidades dos clientes e usuários.

2.  **Gerência de Requisitos:** Lida com o gerenciamento de mudanças, configuração, rastreabilidade e qualidade dos requisitos ao longo do projeto.

---

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

---

## Gerenciamento de Requisitos

O Gerenciamento de Requisitos é o processo de compreender e controlar as mudanças nos requisitos de um sistema. Seu objetivo principal é estabelecer uma visão comum sobre os requisitos entre o cliente e a equipe do projeto.

### A Inevitabilidade das Mudanças

É um fato que os requisitos mudam. As mudanças são inevitáveis e podem ocorrer por diversas razões:

- O usuário muda de ideia sobre uma necessidade.
- O ambiente de negócio ou tecnológico se altera.
- O usuário percebe novas possibilidades para o sistema à medida que ele é desenvolvido.

A complexidade reside no fato de que a mudança em um único requisito pode causar grandes impactos em outros requisitos e em artefatos já desenvolvidos, como o design e o código. Por isso, é fundamental gerenciar as mudanças de forma estruturada.

### Atividades do Gerenciamento de Requisitos

O processo de gerenciamento de requisitos envolve um conjunto de atividades para identificar, controlar e rastrear os requisitos e suas alterações. As principais atividades são:

- **Controle de Versão:** Definir esquemas de identificação e rastrear as versões de requisitos individuais e de todo o conjunto de requisitos.
- **Controle de Mudança:** Analisar o impacto de mudanças propostas, tomar decisões sobre elas, atualizar os requisitos e os planos do projeto.
- **Acompanhamento de Status:** Definir e registrar o status de cada requisito (ex: proposto, aprovado, implementado, cancelado) e acompanhar sua evolução.
- **Rastreabilidade:** Definir e manter os relacionamentos entre os requisitos e entre os requisitos e outros elementos do sistema.

### Processo de Gerenciamento de Mudanças

Um processo formal para gerenciar mudanças é essencial.

1.  **Identificação do Problema:** O processo começa com a identificação de uma necessidade de mudança.
2.  **Análise e Especificação da Mudança:** O problema é analisado e a mudança é especificada formalmente. O uso de templates para registrar solicitações garante consistência.
3.  **Análise de Custo e Impacto:** Avalia-se o custo e o impacto da mudança no projeto.
4.  **Implementação:** Se aprovada, a mudança é implementada.
5.  **Revisão:** Os requisitos e outros artefatos impactados são revisados e atualizados.

---

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

## Rastreabilidade de Requisitos

A rastreabilidade é a chave para um bom gerenciamento de mudanças. Ela é a habilidade de descrever e seguir a vida de um requisito, em ambas as direções, ao longo de todo o ciclo de vida do software.

- **Rastreabilidade para Frente (Forward Traceability):** Permite identificar quais partes do produto (design, código, testes) existem por causa de um requisito específico.
- **Rastreabilidade para Trás (Backward Traceability):** Permite identificar, a partir de uma parte do produto, qual requisito originou sua existência.

### Por que Rastrear?

A rastreabilidade é fundamental para:

- **Auxiliar na Gerência do Projeto:** Acompanhar a evolução e a situação de cada requisito.
- **Auxiliar na Gerência de Mudanças:** Avaliar como a alteração de um requisito impactará outros artefatos do sistema.
- **Garantir a Qualidade:** Assegurar que o projeto final atenda a todas as expectativas e que os casos de teste cubram todos os requisitos.

---

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

## Matriz de Rastreabilidade

A Matriz de Rastreabilidade é uma ferramenta utilizada para documentar e visualizar as dependências. Ela permite relacionar:

- Requisitos com outros requisitos dependentes.
- Requisitos com suas fontes (stakeholders).
- Requisitos com artefatos de projeto, como Casos de Uso, componentes de arquitetura e Casos de Teste.

A matriz geralmente contém um identificador único para cada requisito, seu título, descrição e status (ex: atendido, ativo, cancelado).

---

<div align="right">[⬆️ Voltar ao topo](#📚-menu-de-navegação)</div>

## Ferramentas para Gerência de Requisitos

Existem diversas ferramentas que auxiliam no gerenciamento e na rastreabilidade dos requisitos. Exemplos incluem:

- IBM Rational Requisite Pro
- Borland CaliberRM
- HP Quality Center
- Enterprise Architect (EA)

Essas ferramentas, conhecidas como ferramentas CASE, apoiam a rastreabilidade, que por sua vez, apoia o gerenciamento de mudanças.

<div align="center">

[⬅️ Voltar ao README Principal](../../README.md)

</div>

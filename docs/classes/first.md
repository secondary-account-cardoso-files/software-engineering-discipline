# Engenharia de Software: Visão Geral e Fundamentos

Este material oferece uma introdução aos conceitos fundamentais da Engenharia de Software, com base na apresentação da Profa. Dra. Luciene Chagas de Oliveira.

> "Feliz aquele que transfere o que sabe e aprende o que ensina". - Cora Coralina

---

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-Fundamentos-0078D4?style=for-the-badge&logo=azuredevops)
![Aula 01](https://img.shields.io/badge/Aula-01-blue?style=for-the-badge)

<br />

[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## 📚 Menu de Navegação

- [O que é Software?](#o-que-é-software)
- [O que é Engenharia de Software?](#o-que-é-engenharia-de-software)
- [A Crise do Software](#a-crise-do-software)
- [Tipos de Software](#tipos-de-software)
- [Pilares da Engenharia de Software (4 Ps + 1 F de Jacobson)](#pilares-da-engenharia-de-software-4-ps--1-f-de-jacobson)
- [Mitos do Software](#mitos-do-software)
- [Referências Bibliográficas](#referências-bibliográficas)

---

## O que é Software?

Software é a parte lógica de um computador. De forma mais completa, é um conjunto de programas de computador, juntamente com a documentação e a configuração associadas a eles, que instruem a máquina a realizar as funções desejadas.

**Exemplos de Software:**

- Sistemas Operacionais: Microsoft Windows, Linux
- Aplicações: Microsoft Word, Google Chrome

### Características do Software

- É desenvolvido por meio de engenharia, utilizando linguagens de programação.
- Diferente do hardware, o software não sofre desgaste físico.
- A construção de um software é, em geral, uma solução exclusiva para um problema específico.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## O que é Engenharia de Software?

É a disciplina que abrange todos os aspectos relacionados à produção de software. Ela surgiu da necessidade de organizar o desenvolvimento de sistemas computacionais, que se tornavam cada vez mais flexíveis e complexos. O termo foi consolidado na Conferência de Engenharia de Software da OTAN em 1968.

### Processo de Software

É o conjunto de atividades que resultam em um produto de software. As quatro atividades básicas são:

1.  **Especificação:** Definição das funcionalidades do software.
2.  **Desenvolvimento:** A implementação (codificação) do software.
3.  **Validação:** Garantir que o software atende às necessidades do cliente.
4.  **Evolução:** Realizar manutenções e atualizações para atender a novas demandas.

### Metodologias de Desenvolvimento

Também chamadas de Modelo de Processo de Software, descrevem como o processo funciona e o papel das pessoas envolvidas.

**Exemplos:**

- Cascata (Tradicional)
- Incremental
- Evolutivo
- Prototipação
- Espiral
- RUP (Rational Unified Process)
- Scrum

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## A Crise do Software

Entre as décadas de 1960 e 1980, a indústria enfrentou a "Crise do Software", um período marcado por grandes dificuldades na produção de software, como estouro de orçamentos e cronogramas. Um dos casos mais emblemáticos foi o desenvolvimento do sistema operacional OS/360 da IBM, que envolveu mais de mil programadores.

A partir dessa experiência, Frederick Brooks formulou a **Lei de Brooks**:

> Adicionar programadores a um projeto de software atrasado faz com que ele se atrase ainda mais.

Essa crise evidenciou a importância de uma abordagem de engenharia para o desenvolvimento de software, destacando que erros identificados tardiamente no projeto têm um custo de correção exponencialmente maior.

**Custo Relativo para Corrigir um Erro:**

- **Requisitos:** 1x
- **Projeto:** 3-6x
- **Codificação:** 10x
- **Testes de Unidade:** 15-40x
- **Testes de Sistema:** 30-70x
- **Operação de Campo:** 40-1000x

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## Tipos de Software

Os sistemas podem ser classificados de acordo com sua finalidade e características:

| Tipo de Software               | Descrição                                                                                                                                |
| :----------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------- |
| **Básico**                     | Compiladores, drivers e o próprio sistema operacional. São a base para a execução de outros softwares.                                   |
| **Tempo Real**                 | Monitoram, analisam e controlam eventos do mundo real, como sistemas de automação residencial ou monitoramento de dados.                 |
| **Comercial**                  | Aplicados em empresas para tarefas como controle de estoque, vendas e finanças. Também conhecidos como Sistemas de Informação.           |
| **Científico e de Engenharia** | Utilizados para processamento intenso de números e dados em áreas como pesquisa, simulações e robótica.                                  |
| **Embutido ou Embarcado**      | Presentes em dispositivos como celulares, eletrodomésticos e automóveis, operando com restrições de hardware e energia.                  |
| **Pessoal**                    | Ferramentas de produtividade usadas no dia a dia, como processadores de texto, planilhas e editores de imagem.                           |
| **Jogos**                      | Aplicações de entretenimento, que podem variar de simples a extremamente complexos, exigindo alto desempenho gráfico e de processamento. |
| **Inteligência Artificial**    | Sistemas especialistas e redes neurais capazes de aprendizado, que podem ser independentes ou integrados a outros sistemas.              |

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## Pilares da Engenharia de Software (4 Ps + 1 F de Jacobson)

A Engenharia de Software se apoia em cinco pilares fundamentais:

1.  **Pessoas (People):** Todos os envolvidos no projeto (stakeholders), como arquitetos, desenvolvedores, analistas, gerentes e clientes.
2.  **Projeto (Project):** A estrutura organizacional através da qual o desenvolvimento é gerenciado.
3.  **Produto (Product):** Os artefatos criados durante o ciclo de vida, incluindo código-fonte, executáveis, modelos e documentação.
4.  **Processo (Process):** O conjunto de atividades que transformam os requisitos do usuário no produto final.
5.  **Ferramentas (Tools):** Softwares que auxiliam na automação das atividades do processo, como ferramentas CASE e de gerenciamento de projetos.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## Mitos do Software

Existem diversas crenças equivocadas sobre o desenvolvimento de software que podem levar a problemas.

### Mitos da Gerência

- **Mito:** Ferramentas modernas de software e hardware são suficientes.
  - **Realidade:** O uso eficiente de ferramentas exige conhecimento técnico e processos bem definidos.
- **Mito:** Se estamos atrasados, basta contratar mais programadores.
  - **Realidade:** Adicionar pessoas a um projeto já em andamento gera custos de treinamento e comunicação, podendo atrasá-lo ainda mais (Lei de Brooks).

### Mitos do Programador

- **Mito:** Até o programa estar "rodando", não há como medir sua qualidade.
  - **Realidade:** A qualidade deve ser avaliada em todas as fases, através de revisões e testes unitários, muito antes da codificação final.
- **Mito:** O único produto de um projeto é o conjunto de programas.
  - **Realidade:** A documentação, o manual do usuário e os modelos de projeto são tão importantes quanto o código.

### Mitos do Cliente

- **Mito:** Uma lista de intenções é suficiente para começar a desenvolver.
  - **Realidade:** A especificação de requisitos é a fase mais crítica. Erros nesta etapa têm um custo de correção muito elevado.
- **Mito:** Mudanças são fáceis de fazer porque software é flexível.
  - **Realidade:** O custo e o impacto de uma mudança dependem de quando ela é solicitada. Mudanças tardias podem ser extremamente caras e complexas.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## Referências Bibliográficas

- PRESSMAN, R. S. **Engenharia de Software**. McGraw-Hill, 2016.
- SOMMERVILLE, Ian. **Engenharia de Software**. Addison-Wesley, 2019.

<div align="center">

[⬅️ Voltar ao README Principal](../../README.md)

</div>

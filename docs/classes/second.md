# Engenharia de Software: Metodologias de Desenvolvimento de Software

Este material, baseado na apresentação da Profa. Dra. Luciene Chagas de Oliveira, oferece uma visão sobre as diferentes metodologias e modelos de processo para o desenvolvimento de software.

> "Feliz aquele que transfere o que sabe e aprende o que ensina". - Cora Coralina

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-Metodologias-0078D4?style=for-the-badge&logo=azuredevops)
![Aula 02](https://img.shields.io/badge/Aula-02-blue?style=for-the-badge)

<br />

[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## Menu de Navegação

- [Modelos de Processo de Software](#modelos-de-processo-de-software)
- [1. Modelo em Cascata ou Tradicional](#1-modelo-em-cascata-ou-tradicional)
- [2. Modelo Evolucionário ou Evolutivo](#2-modelo-evolucionário-ou-evolutivo)
- [3. Modelo Incremental](#3-modelo-incremental)
- [4. Modelo Espiral](#4-modelo-espiral)
- [5. Desenvolvimento Formal de Sistemas](#5-desenvolvimento-formal-de-sistemas)
- [6. Desenvolvimento Orientado a Reuso](#6-desenvolvimento-orientado-a-reuso)
- [7. Modelo de Prototipação](#7-modelo-de-prototipação)

---

## Modelos de Processo de Software

Um modelo de processo de software é uma representação abstrata de como o software é desenvolvido. Ele não é uma descrição definitiva, mas uma abstração que ajuda a explicar diferentes abordagens para organizar uma atividade inerentemente caótica.

Alguns dos principais modelos (ou paradigmas) são:

- Modelo em Cascata ou Tradicional
- Modelo Evolucionário ou Evolutivo
- Modelo Incremental
- Modelo Espiral
- Desenvolvimento Formal de Sistemas
- Desenvolvimento Orientado a Reuso
- Modelo de Prototipação

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 1. Modelo em Cascata ou Tradicional

O Modelo em Cascata foi o primeiro modelo de desenvolvimento de software, surgindo em 1970. É o mais antigo e amplamente utilizado. Ele propõe um fluxo sequencial, onde o processo avança constantemente para frente através de fases distintas.

### Fases do Modelo em Cascata

1.  **Análise e Definição de Requisitos:** As funções, restrições e objetivos do sistema são estabelecidos em consulta com os usuários e definidos em detalhe.
2.  **Projeto de Sistemas e Software:** Os requisitos são agrupados em sistemas de hardware e software, identificando as abstrações fundamentais e suas relações.
3.  **Implementação e Testes de Unidade:** O projeto é transformado em um conjunto de programas ou unidades de programa. Cada unidade é testada para verificar se atende à sua especificação.
4.  **Integração e Teste de Sistemas:** As unidades são integradas e testadas como um sistema completo para garantir que os requisitos foram atendidos.
5.  **Operação e Manutenção:** O sistema é instalado e colocado em operação. Esta fase envolve a correção de erros não descobertos anteriormente e a implementação de novos requisitos.

### Vantagens

- Simples de gerenciar devido à divisão clara de fases.
- Impõe disciplina, planejamento e gerenciamento ao processo.
- Garante que os objetivos sejam completamente entendidos antes do início da implementação.

### Desvantagens

- É difícil acomodar mudanças nos requisitos depois que o processo já foi iniciado.
- Projetos reais raramente seguem o fluxo sequencial proposto.
- O cliente precisa esperar até o final do projeto para ter uma versão executável do programa.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 2. Modelo Evolucionário ou Evolutivo

Este modelo se baseia na ideia de desenvolver uma implementação inicial, apresentá-la ao usuário para obter feedback e aprimorá-la através de várias versões. As atividades de especificação, desenvolvimento e validação ocorrem concorrentemente para gerar um retorno rápido.

### Tipos de Desenvolvimento Evolucionário

- **Exploratório:** O objetivo é trabalhar com o cliente para explorar seus requisitos e entregar um sistema final, adicionando novas partes de acordo com o andamento.
- **Protótipos Descartáveis:** O objetivo é compreender os requisitos do cliente para então desenvolver uma especificação completa para o sistema final.

### Vantagens

- A especificação pode ser desenvolvida gradativamente.
- Ideal para sistemas de pequeno porte.

### Desvantagens

- O processo não é visível, pois o desenvolvimento rápido não permite tempo para documentar as versões.
- Os sistemas podem se tornar mal estruturados devido a mudanças constantes que corrompem a arquitetura.
- É difícil para os gerentes medirem o esforço, pois o desenvolvimento não é regular.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 3. Modelo Incremental

O Modelo Incremental combina elementos dos modelos em cascata e evolucionário. O cliente identifica e prioriza as funcionalidades do sistema. O desenvolvimento é dividido em incrementos, com as funções de maior prioridade sendo entregues primeiro. Cada incremento pode ser colocado em produção pelo cliente assim que é entregue.

### Vantagens

- O cliente não precisa esperar a entrega do sistema completo para começar a usá-lo.
- Os primeiros incrementos podem servir como protótipos para refinar os requisitos dos incrementos seguintes.
- Metodologias como Extreme Programming (XP) e RUP utilizam abordagens incrementais.

### Desvantagens

- É difícil mapear os requisitos do cliente em incrementos do tamanho correto.
- Em sistemas complexos, pode ser difícil garantir que as diferentes partes (incrementos) se encaixem corretamente.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 4. Modelo Espiral

Criado em 1988, o Modelo Espiral é representado como uma espiral, onde cada volta representa uma fase do processo de software. É considerado mais realista para o desenvolvimento de sistemas grandes e complexos. Uma de suas principais características é a incorporação explícita da **análise de riscos** em cada fase, como requisitos mal compreendidos ou problemas tecnológicos.

### Vantagens

- É versátil para lidar com as mudanças que são inevitáveis no desenvolvimento de software.
- A análise de riscos permite identificar e resolver problemas de forma proativa. Se os riscos não puderem ser resolvidos, o projeto pode ser finalizado mais cedo.
- As estimativas de cronograma se tornam mais realistas à medida que o trabalho avança, pois problemas importantes são descobertos mais cedo.

### Desvantagem

- Existe o risco de o processo se estender indefinidamente e nunca terminar.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 5. Desenvolvimento Formal de Sistemas

Esta abordagem se baseia na transformação matemática de uma especificação formal em um programa executável.

Diferente do modelo em cascata, o processo de desenvolvimento, implementação e teste é substituído por um processo de transformação formal, onde a especificação é refinada através de uma série de transformações matemáticas até se tornar um programa.

É uma abordagem adequada para sistemas que exigem alta segurança e confiabilidade, mas necessita de perícia especializada e pode não trazer ganhos significativos para a maioria dos outros sistemas.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 6. Desenvolvimento Orientado a Reuso

Este modelo formaliza o reuso de componentes de software para acelerar a produção e a prototipagem. O processo geralmente segue estas etapas:

1.  **Análise de componentes:** Busca por componentes existentes que implementem a especificação de requisitos.
2.  **Modificação dos requisitos:** Adequação dos requisitos aos componentes encontrados.
3.  **Projeto de sistema com reuso:** Desenvolvimento de uma infraestrutura para organizar os componentes.
4.  **Desenvolvimento e integração:** Desenvolvimento dos componentes que faltam e integração de todos para criar o sistema final.

### Vantagens e Desvantagens

- **Vantagens:** Reduz custos e riscos ao diminuir a quantidade de software a ser desenvolvido e acelera a entrega.
- **Desvantagens:** Os requisitos podem ser comprometidos durante a adaptação, e pode-se perder o controle sobre as versões dos componentes reutilizados.

<div align="right">

[⬆️ Voltar ao topo](#menu-de-navegação)

</div>

---

## 7. Modelo de Prototipação

O objetivo deste modelo é usar um protótipo para entender e definir melhor os requisitos do sistema, especialmente quando o cliente não os detalhou inicialmente. O desenvolvedor cria um modelo do software que pode ser avaliado e refinado em um ciclo de:

1.  Obter Requisitos
2.  Elaborar Projeto Rápido
3.  Construir Protótipo
4.  Avaliar Protótipo
5.  Refinamento do Protótipo

### Vantagens e Desvantagens

- **Vantagem:** Facilita a determinação dos requisitos iniciais e ajuda todos os envolvidos a compreenderem melhor o que deve ser construído.
- **Desvantagem:** Existe a tendência de utilizar o protótipo como produto final, o que pode comprometer a qualidade do software.

<div align="center">

[⬅️ Voltar ao README Principal](../../README.md)

</div>

<!--
Este arquivo apresenta uma pesquisa didática e visualmente agradável sobre Metodologias de Engenharia de Software.
Inclui sumário de navegação para o README.md principal e uso criativo de imagens e badges.
-->

# Metodologias de Engenharia de Software

<div align="center">

![Engenharia de Software](https://img.shields.io/badge/Engenharia%20de%20Software-Atividade%2002-0078D4?style=for-the-badge&logo=azuredevops)

![Metodologias](https://img.shields.io/badge/Metodologias-Engenharia%20de%20Software-0078D4?style=for-the-badge&logo=azuredevops)
![Processos](https://img.shields.io/badge/Processos-Modelos%20de%20Desenvolvimento-4B8BBE?style=for-the-badge&logo=github)
![Ágil](https://img.shields.io/badge/%C3%81gil-e%20Tradicional-FFCA28?style=for-the-badge&logo=git)

**Pesquisa sobre Metodologias de Engenharia de Software**

[⬅️ Voltar ao README Principal](../../README.md)

</div>

---

## 📚 Sumário

- [1. Modelo em Cascata (Tradicional)](#1-modelo-em-cascata-tradicional)
- [2. Modelo Evolucionário (Evolutivo)](#2-modelo-evolucionário-evolutivo)
- [3. Modelo Incremental](#3-modelo-incremental)
- [4. Modelo Espiral](#4-modelo-espiral)
- [5. Desenvolvimento Formal de Sistemas](#5-desenvolvimento-formal-de-sistemas)
- [6. Desenvolvimento Orientado a Reuso](#6-desenvolvimento-orientado-a-reuso)
- [7. Modelo de Prototipação](#7-modelo-de-prototipação)
- [8. Extreme Programming (XP)](#8-extreme-programming-xp)
- [9. Scrum](#9-scrum)

---

<!-- Navegação entre sessões -->
<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

## 1. Modelo em Cascata (Tradicional)

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Waterfall_model.svg/600px-Waterfall_model.svg.png" alt="Modelo em Cascata" width="400"/>
</div>

O Modelo em Cascata, surgido em 1970, é o mais antigo e propõe um fluxo sequencial de desenvolvimento. Cada fase só inicia após a conclusão da anterior.

**Fases:**

- **Análise e Definição de Requisitos:** Estabelecimento das funções e objetivos do sistema.
- **Projeto de Sistemas e Software:** Agrupamento dos requisitos e definição da arquitetura.
- **Implementação e Testes de Unidade:** Codificação e testes individuais das unidades.
- **Integração e Teste de Sistemas:** Integração das unidades e testes do sistema completo.
- **Operação e Manutenção:** Instalação, operação e manutenção do sistema.

**Vantagens:**  
✔️ Simples de gerenciar  
✔️ Planejamento disciplinado  
✔️ Objetivos claros antes da implementação

**Desvantagens:**  
❌ Dificuldade para mudanças  
❌ Pouca flexibilidade  
❌ Entrega só ao final do projeto

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 2. Modelo Evolucionário (Evolutivo)

<div align="center">
  <img src="https://img.icons8.com/fluency/480/experimental-iteration-2.png" alt="Modelo Evolutivo" width="120"/>
</div>

Baseia-se em criar uma implementação inicial, obter feedback do usuário e aprimorar o sistema em múltiplas versões.

**Tipos:**

- **Exploratório:** Explora requisitos junto ao cliente, entregando incrementos.
- **Protótipos Descartáveis:** Protótipos para entender requisitos antes da especificação final.

**Vantagens:**  
✔️ Especificação gradual  
✔️ Ideal para sistemas pequenos

**Desvantagens:**  
❌ Pouca documentação  
❌ Arquitetura pode ser comprometida  
❌ Difícil medir esforço

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 3. Modelo Incremental

<div align="center">
  <img src="https://img.icons8.com/color/480/000000/add-row.png" alt="Modelo Incremental" width="120"/>
</div>

Combina elementos do cascata e evolutivo. Funcionalidades são priorizadas e entregues em incrementos.

**Vantagens:**  
✔️ Valor entregue cedo ao cliente  
✔️ Incrementos servem como protótipos  
✔️ Usado em XP e RUP

**Desvantagens:**  
❌ Difícil definir tamanho dos incrementos  
❌ Integração pode ser problemática em sistemas complexos

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 4. Modelo Espiral

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Spiral_model_%28Boehm%2C_1988%29.png" alt="Modelo Espiral" width="350"/>
</div>

Criado por Barry Boehm em 1988, é representado como uma espiral, com análise de riscos em cada ciclo.

**Vantagens:**  
✔️ Lida bem com mudanças  
✔️ Análise de riscos contínua  
✔️ Estimativas mais realistas

**Desvantagem:**  
❌ Risco de nunca terminar se mal gerenciado

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 5. Desenvolvimento Formal de Sistemas

<div align="center">
  <img src="https://img.icons8.com/ios-filled/500/000000/math.png" alt="Formal Methods" width="90"/>
</div>

Baseia-se na transformação matemática da especificação em código executável. Indicado para sistemas críticos (ex: aviação).

**Vantagens:**  
✔️ Alta confiabilidade

**Desvantagens:**  
❌ Custo elevado  
❌ Exige especialistas  
❌ Pouco ganho para sistemas comuns

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 6. Desenvolvimento Orientado a Reuso

<div align="center">
  <img src="https://img.icons8.com/color/480/000000/reuse.png" alt="Reuso de Componentes" width="100"/>
</div>

Foca no reaproveitamento de componentes existentes para acelerar o desenvolvimento.

**Processo:**

- Análise de componentes reutilizáveis
- Ajuste dos requisitos
- Projeto com reuso
- Desenvolvimento e integração

**Vantagens:**  
✔️ Reduz custo e riscos  
✔️ Acelera entrega

**Desvantagens:**  
❌ Requisitos podem ser comprometidos  
❌ Controle de versões é desafiador

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 7. Modelo de Prototipação

<div align="center">
  <img src="https://img.icons8.com/fluency/480/000000/prototype.png" alt="Prototipação" width="100"/>
</div>

Utiliza protótipos para identificar e validar requisitos, útil quando o cliente não tem clareza total do que deseja.

**Ciclo:**

1. Obter Requisitos
2. Projeto Rápido
3. Construção do Protótipo
4. Avaliação
5. Refinamento

**Vantagem:**  
✔️ Facilita entendimento dos requisitos

**Desvantagem:**  
❌ Risco de usar o protótipo como produto final

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 8. Extreme Programming (XP)

<div align="center">
  <img src="https://img.icons8.com/color/480/000000/source-code.png" alt="XP" width="100"/>
</div>

Metodologia ágil criada por Kent Beck para equipes com requisitos mutáveis. Leva boas práticas ao "extremo".

**Valores:**

- Comunicação
- Coragem
- Feedback
- Simplicidade
- Respeito

**Práticas Principais:**

- **Pair Programming:** Código feito em dupla
- **Continuous Integration:** Integração e testes contínuos
- **Test-First Design:** Testes antes do código
- **Refactoring:** Refatoração constante
- **Small Releases:** Entregas pequenas e frequentes
- **On-Site Customer:** Cliente sempre disponível

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

## 9. Scrum

<div align="center">
  <img src="https://img.icons8.com/color/480/000000/scrum.png" alt="Scrum" width="100"/>
</div>

Framework ágil para projetos complexos, baseado em experiência, trabalho em equipe e senso comum.

**Pilares:**

- **Backlog:** Lista priorizada de funcionalidades
- **Sprints:** Ciclos de até 30 dias com entregas fechadas
- **Daily Scrum:** Reuniões diárias rápidas
- **Sprint Review:** Demonstração ao final de cada Sprint

**Papéis:**

- **Product Owner:** Gerencia o backlog e representa os stakeholders
- **Scrum Master:** Garante o processo e remove impedimentos
- **Time:** Equipe auto-gerenciável responsável pelas entregas

<div align="right">[⬆️ Voltar ao topo](#sumário)</div>

---

<div align="center">

> _Nota: Kanban, TDD, Lean e Spotify não foram abordados nos materiais de aula fornecidos._

[⬅️ Voltar ao README Principal](../../README.md)

</div>

# ⚙️ Engenharia de Software - Unitri

**Instituição:** [Unitri](https://unitri.edu.br)  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Disciplina:** Engenharia de Software

Este repositório contém meus estudos, anotações e exercícios realizados durante a disciplina de Engenharia de Software. O objetivo é registrar o progresso ao longo do semestre, facilitando a inclusão de novos conteúdos conforme as aulas avançam.

---

## Sumário

- [Aula 01](#aula-01)
  - [Exercício 1](#exercício-1)
- [Aula 02](#aula-02)
  - [Modelos de Processo de Software](#modelos-de-processo-de-software)
  - [Exercício da Aula 02](#exercício-da-aula-02)
- [Próximas aulas](#próximas-aulas)

---

## Aula 01

### Exercício 1

#### 1. O que é um software?

Software é um conjunto de instruções, dados ou programas utilizados para operar computadores e executar tarefas específicas. Pode ser composto por aplicativos, sistemas operacionais, utilitários, entre outros.

#### 2. O que é a Engenharia de Software?

Engenharia de Software é uma área da computação dedicada à especificação, desenvolvimento, manutenção e gerenciamento de software, utilizando princípios, métodos e boas práticas para garantir qualidade, eficiência e confiabilidade.

#### 3. Vantagens e Desvantagens (importância do Software e da Engenharia de Software)

**Vantagens:**

- Automatização de processos
- Aumento de produtividade
- Redução de erros humanos
- Facilidade de acesso à informação

**Desvantagens:**

- Dependência de tecnologia
- Custos de desenvolvimento e manutenção
- Riscos de falhas e bugs

#### 4. Tipos de Softwares

- Software de Sistema (ex: sistemas operacionais)
- Software Aplicativo (ex: editores de texto, navegadores)
- Software de Programação (ex: compiladores, IDEs)
- Software Embarcado (ex: sistemas em dispositivos eletrônicos)

#### 5. Qual é a importância dos tipos de softwares para a empresa ou pessoa?

Cada tipo de software atende a necessidades específicas, otimizando processos, aumentando a produtividade e facilitando a vida de pessoas e empresas. Por exemplo, softwares de gestão auxiliam empresas no controle de recursos, enquanto aplicativos de comunicação conectam pessoas.

#### 6. Exemplos de código com TypeScript

```typescript
// Exemplo simples de função em TypeScript
function saudacao(nome: string): string {
  return `Olá, ${nome}! Bem-vindo à Engenharia de Software.`;
}

console.log(saudacao("Maria"));
```

#### 7. Evolução dos Softwares

Os softwares evoluíram de programas simples e específicos para sistemas complexos, integrados e distribuídos, acompanhando o avanço do hardware e das necessidades humanas e empresariais.

#### 8. Mitos dos Softwares

- "Software é fácil de mudar a qualquer momento."
- "Adicionar mais pessoas ao projeto acelera a entrega."
- "Software sempre pode ser consertado depois."
- "Engenharia de Software é só programação."

---

## Aula 02

### Modelos de Processo de Software

#### ✅ O que são Modelos de Processo de Software?

Modelos de processo de software são representações abstratas de processos que auxiliam no entendimento, explicação e organização das atividades de desenvolvimento. Cada modelo oferece uma perspectiva diferente, ajudando a dar ordem a um processo que, naturalmente, é caótico.

Esses modelos não são descrições definitivas, mas sim ferramentas úteis para explicar diferentes abordagens no desenvolvimento de software.

#### 📌 Principais Modelos de Processo de Software

##### 1. Modelo em Cascata (Tradicional)

Surgiu em 1970, sendo o modelo mais antigo e amplamente usado.

É sequencial, seguindo fases bem definidas:

- Análise de Requisitos
- Projeto de Sistemas e Software
- Implementação e Testes de Unidade
- Integração e Teste de Sistemas
- Operação e Manutenção

**Vantagens:**

- Simples de gerenciar devido à divisão por fases
- Impõe disciplina, planejamento e gerenciamento

**Desvantagens:**

- Dificuldade em lidar com mudanças após início do projeto
- Projeto só é entregue no final (pouca interação com cliente)
- Pouca flexibilidade

##### 2. Modelo Evolucionário (Evolutivo)

Baseia-se em desenvolver uma implementação inicial, apresentar ao cliente e evoluir através de várias versões.

Executa especificação, desenvolvimento e validação de forma concorrente.

**Tipos:**

- **Exploratório:** foco em trabalhar com o cliente para ajustar requisitos
- **Protótipo descartável:** usado para entender requisitos antes da implementação final

**Vantagens:**

- Especificação pode evoluir gradualmente
- Ideal para sistemas pequenos

**Desvantagens:**

- Pouca documentação
- Requer ferramentas específicas
- Mudanças constantes podem comprometer a estrutura do software

##### 3. Modelo Incremental

Combina ideias do cascata e evolutivo.

Entregas são feitas em incrementos, priorizando funções essenciais.

**Vantagens:**

- Cliente recebe funcionalidades mais cedo
- Incrementos podem servir como protótipos

**Desvantagens:**

- Difícil definir tamanho adequado dos incrementos
- Em sistemas complexos, integração pode ser problemática

##### 4. Modelo Espiral

Criado em 1988, representado como uma espiral.

Foca em análise de riscos e é ideal para sistemas grandes.

Cada volta da espiral representa uma fase do processo.

**Vantagens:**

- Alta capacidade de adaptação a mudanças
- Permite prototipação em vários estágios

**Desvantagem:**

- Processo pode nunca terminar

##### 5. Desenvolvimento Formal de Sistemas

Baseado em transformação matemática formal da especificação em código executável.

Indicado para sistemas que exigem altíssima confiabilidade (ex.: aviação, saúde).

**Desvantagens:**

- Custo elevado
- Exige especialistas

##### 6. Desenvolvimento Orientado a Reuso

Baseado no reaproveitamento de componentes já existentes.

**Vantagens:**

- Reduz custo e tempo de desenvolvimento
- Diminui riscos

**Desvantagens:**

- Requisitos podem precisar ser ajustados
- Controle de versão de componentes pode ser difícil

##### 7. Modelo de Prototipação

Cria protótipos para entender os requisitos do cliente.

Útil quando não há clareza inicial sobre as necessidades.

**Vantagens:**

- Ajuda na definição dos requisitos

**Desvantagens:**

- Risco de transformar protótipo em produto final, comprometendo qualidade

### Exercício da Aula 02

**Atividade:** Pesquisa e apresentação sobre os seguintes temas:

- [ ] Modelo em Cascata ou Tradicional
- [ ] Modelo Evolucionário ou Evolutivo
- [ ] Modelo Incremental
- [ ] Modelo Espiral
- [ ] Desenvolvimento Formal de Sistemas
- [ ] Desenvolvimento Orientado a Reuso
- [ ] Modelo de Prototipação
- [ ] Modelo Extreme Programming (XP)
- [ ] Scrum e Kanban
- [ ] Modelo Test Driven Development (TDD)
- [ ] Modelo Lean

---

## Próximas aulas

- [ ] Aula 03: _(Adicionar tópicos e exercícios aqui)_

---

> _Sinta-se à vontade para expandir cada seção conforme novas aulas e conteúdos forem ministrados._

---

**Contato:**

- Email: [cardosofiles@outlook.com](mailto:cardosofiles@outlook.com)
- LinkedIn: [joaobatista-dev](https://www.linkedin.com/in/joaobatista-dev/)
- GitHub: [Cardosofiles](https://github.com/Cardosofiles)
- Portfólio: [cardosofiles.dev](https://cardosofiles.dev/)

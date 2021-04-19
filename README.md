# Trilha QA

### Sumário
- Lógica de Programação
- Testes de acessibilidade
- Noções SQL
- Git
- Metodologia Ágil
- Testes funcionais
  - [O que é Teste de Software?](https://github.com/bfscamargo/QA_Treinamento#o-que-%C3%A9-teste-de-software)
  - [Objetivo do Teste de Software](https://github.com/bfscamargo/QA_Treinamento#import%C3%A2ncia-dos-testes-de-software)
  - [Importância dos Testes de Software](https://github.com/bfscamargo/QA_Treinamento#import%C3%A2ncia-dos-testes-de-software)
  - [Quais são as causas mais comuns para um bug existir?
](https://github.com/bfscamargo/QA_Treinamento#quais-s%C3%A3o-as-causas-mais-comuns-para-um-bug-existir)
  - [Consequências de um bug](https://github.com/bfscamargo/QA_Treinamento#consequ%C3%AAncias-de-um-bug)
  - [Qual é o papel do QA nessa hora?](https://github.com/bfscamargo/QA_Treinamento#qual-%C3%A9-o-papel-do-qa-nessa-hora)

- Automatização de testes
- Testes de Performance
- Versionamento código
- Projeto Integrador

## QA – Aula1 ☕

### O que é Teste de Software?
Teste de software é um processo dentro de um projeto de desenvolvimento de software.
O objetivo desse processo é encontrar falhas no sistema e garantir maior qualidade na entrega do produto.
**Não existe desenvolvimento sem BUG.**

### Objetivo do Teste de Software:
Garantir que o sistema atenda a todos os requisitos exigidos pelo cliente.
Testar aplicações é uma atividade um pouco mais abrangente do que apenas garantir qualidade.
**Cabe ao QA questionar se o que é pedido é suficiente para o negócio.**

### Importância dos Testes de Software:
Testes são um processo implementado pelas empresas para minimizar os custos financeiros e evitar problemas no sistema que por sua vez possam arranhar a imagem da companhia.
O papel do QA é evitar que problemas cheguem até o usuário final.
Um defeito encontrado na fase de desenvolvimento do sistema, pode ter o custo de correção infinitamente menor se comparada a fase de produção.
**Software de qualidade garante uma evolução contínua.**


### Quais são as causas mais comuns para um bug existir?
- Erro de codificação e ou sintaxe.
- Erro de lógica de programação
- Erro de interface com outros sistemas
- Interpretação o equivocada de uma história de desenvolvimento, que por sua vez quando concluída produz um resultado diferente do planejado e especificado
- Falta de tratamento adequado para erros ou situações adversas no sistema ou na infraestrutura

### Consequências de um bug
- Falhas de segurança
-	Acesso não autorizado a funções do sistema
- Perca de dados importantes para a companhia
- Vazamento de informações estratégias ou sensíveis
- Queda de performance das aplicações (loops infinitos)
- Processamento de informações equivocadas
- Prejuízos financeiras
- Desgaste e queda de credibilidade de um produto/empresa no mercado

### Qual é o papel do QA nessa hora? 
- Envolvimento em todas as fases, desde a definição da tarefa até o seu teste final.
- Escrita do BDD (desenvolvimento orientado por comportamento)
- Reportar os problemas com evidências para o time.
- Defender e disseminar cultura de qualidade para todo o time. 
- Criar automação de testes sempre que for possível.
**A qualidade é responsabilidade de todos e não apenas do QA.**

## Aula2

### Testes Funcionais

Introdução

Tipos de testes

## Testes Funcionais

### Caixa Preta

Também chamado de teste funcional, orientado a dado ou orientado a entrada e saída. A técnica de caixa preta avalia o comportamento externo do componente do software.

### Caixa Branca

Conhecido também como teste estrutural ou orientado à lógica. Essa técnica avalia o comportamento interno do comportamento de software. É trabalhado diretamente sobre o código fonte.

### Smoke Test

Conjunto de testes com o intuito de validar se os pontos mais importantes da aplicação continuam funcionando após as alterações.

### Teste de Performance

## Teste de Estresse

O teste de estresse é destinado a avaliar como o sistema responde em condições anormais. Basicamente, é um teste de carga abrangendo cargas de trabalho extremas, memória insuficiente, hardware e serviços indisponíveis ou recursos compartilhados limitados. Normalmente, esses testes são executados para compreender melhor como e em quais áreas o sistema será dividido, para que os planos de contingência e a manutenção de atualização possam ser planejados com bastante antecedência. A utilização dessa técnica é imprescindível para projetos que desenvolvam sistemas críticos, que necessitem de alta eficiência e disponibilidade. A aplicação dessa técnica é indicada durante a fase de teste de sistema.

## Teste de Carga

O teste de carga é uma técnica usada para avaliar os limites operacionais do software. Geralmente, as medições são tomadas com base na taxa de transferência de dados da carga de trabalho e no tempo de resposta da transação. As variações na carga de trabalho normalmente incluem a emulação das cargas de trabalho médias e máximas que ocorrem dentro de tolerâncias operacionais normais. A aplicação dessa técnica é indicada durante as fases de testes de integração e de sistema.

## Teste de estabilidade

Mede o retorno (tempo) do sistema após teste de carga ou teste de estresse.

Homologação
QA
Produção

hacking by google


## Teste de usabilidade

Garantir que o resultado do teste seja igual para o usuário.

## Teste de regressão

Sempre que uma nova funcionalidade for aplicada, a regressão é executada.

## Teste de segurança

Essa técnica de teste deve validar os requisitos de segurança, visando identificar as vulnerabilidade do sistema. Os objetivos desses testes são: prevenir ataques, detectar vulnerabilidades e preparar medidas de contingência para casos de falhar. A aplicação dessa técnica é indicada durante as fases de testes de integração e de sistema.

## Teste de integração

Tem por objetivo encontrar falhas de integração entre as unidades, e não mais em testar as funcionalidades da mesma. Nesta fase as categorias de testes aplicáveis são: testes de interface, testes de dependências entre os componentes.

## Teste de compatibilidade

O sistema deve se adaptar e funcionar em qualquer dispotivos de tamanho de telas diferentes. 

Exemplo:

- PC
- Smartphone
- TV

## Testes exploratórios

Complementar ao teste planejado, feito de forma intuitiva, simula estresse em unidades ou no sistema como um todo.




<h1>App ContaBank - Finanças Pessoais</h1>

Prompt Final (PRD)

```markdown
# PRD: Aplicativo Conversacional de Organização de Finanças Pessoais

## 1. Visão do produto

Criar um aplicativo de organização financeira pessoal baseado em conversas, permitindo que pessoas iniciantes registrem, acompanhem e compreendam suas finanças de maneira simples, acessível e educativa.

O produto busca substituir formulários extensos e planilhas complexas por uma experiência de conversa natural, complementada por visualizações simples, metas financeiras e recomendações práticas.

A proposta central do produto é:

"Organize sua vida financeira conversando, sem planilhas complicadas."

## 2. Contexto

Muitas pessoas desejam organizar melhor suas finanças, mas encontram dificuldades para manter esse hábito.

Aplicativos financeiros tradicionais geralmente exigem preenchimento manual de formulários, configuração de diversas categorias e conhecimento prévio sobre organização financeira.

A proposta deste aplicativo é permitir que o usuário registre e acompanhe sua vida financeira por meio de uma conversa simples e natural.

Exemplo:

"Gastei R$ 42 no supermercado hoje."

O sistema deverá interpretar essa mensagem, identificar as informações relevantes e transformar o conteúdo em uma transação organizada.

## 3. Problema

Muitas pessoas desistem de controlar seus gastos porque as soluções disponíveis exigem registros manuais repetitivos, conhecimento financeiro prévio ou interação com interfaces complexas.

Como consequência, essas pessoas:

- não sabem para onde o dinheiro está indo;
- têm dificuldade para manter o hábito de registrar gastos;
- registram transações de forma irregular;
- não conseguem transformar dados financeiros em ações práticas;
- sentem insegurança ao definir metas;
- não compreendem facilmente relatórios financeiros;
- abandonam aplicativos ou planilhas depois de pouco tempo.

## 4. Objetivo do produto

Facilitar a organização das finanças pessoais por meio de uma experiência conversacional, educativa e acessível.

O aplicativo deverá ajudar o usuário a:

- registrar receitas e despesas;
- compreender seus padrões de consumo;
- acompanhar seu saldo calculado;
- definir metas financeiras;
- visualizar relatórios simples;
- receber orientações de economia;
- desenvolver o hábito de acompanhar suas finanças.

## 5. Público-alvo

### 5.1 Público principal

Pessoas adultas que estão começando a organizar suas finanças e procuram uma solução simples, guiada e sem necessidade de conhecimentos financeiros avançados.

### 5.2 Características esperadas

O público principal poderá incluir pessoas que:

- não mantêm uma planilha financeira;
- registram gastos de forma irregular ou não registram;
- usam aplicativos de mensagens com frequência;
- preferem explicações simples e diretas;
- desejam economizar;
- querem criar uma reserva financeira;
- possuem dificuldade para compreender relatórios complexos;
- desejam alcançar uma meta específica.

### 5.3 Público fora do escopo inicial

O MVP não será direcionado principalmente para:

- investidores experientes;
- profissionais de contabilidade;
- empresas;
- pessoas jurídicas;
- usuários que precisam de gestão completa de patrimônio;
- usuários que exigem integração bancária automática desde o primeiro uso.

## 6. Proposta de valor

O aplicativo permitirá organizar as finanças por meio de conversas, reduzindo a necessidade de preencher formulários ou manter planilhas.

A principal proposta de valor é:

"Organize sua vida financeira conversando, sem planilhas complicadas."

Diferenciais esperados:

- registro de transações em linguagem natural;
- categorização automática;
- confirmação simples antes de salvar;
- correção rápida de informações;
- acompanhamento visual de receitas, despesas e saldo;
- metas financeiras acessíveis;
- orientações educativas;
- experiência adequada para iniciantes.

## 7. Hipóteses do produto

### 7.1 Hipótese principal

Usuários iniciantes registrarão gastos com mais frequência quando puderem fazer isso por meio de uma conversa simples, em vez de utilizar formulários tradicionais.

### 7.2 Hipóteses secundárias

- A categorização automática reduzirá o esforço percebido pelo usuário.
- A confirmação da transação aumentará a confiança nas informações registradas.
- Resumos curtos ajudarão o usuário a entender seus hábitos financeiros.
- A visualização clara do saldo facilitará a compreensão da situação financeira.
- Metas visíveis aumentarão a motivação para acompanhar as finanças.
- Recomendações contextualizadas serão mais úteis do que dicas financeiras genéricas.
- Uma linguagem educativa e sem julgamentos ajudará na retenção dos usuários.

## 8. Jornada principal do usuário

A jornada principal deverá seguir os seguintes passos:

1. O usuário cria uma conta.
2. O usuário conhece a proposta do aplicativo.
3. O usuário informa seu principal objetivo financeiro.
4. O usuário registra uma receita ou despesa por mensagem.
5. O sistema interpreta o valor, o tipo, a categoria, a data e a descrição.
6. O sistema apresenta as informações interpretadas para conferência.
7. O usuário confirma ou corrige a transação.
8. O sistema salva a transação.
9. O sistema atualiza as receitas, as despesas e o saldo calculado.
10. O usuário visualiza o resumo financeiro.
11. O Agente Financeiro apresenta uma observação ou sugestão relevante.
12. O usuário acompanha a evolução de sua meta financeira.

## 9. Escopo do MVP

### 9.1 Onboarding simplificado

O onboarding deverá:

- explicar o propósito do aplicativo;
- apresentar a experiência de conversa;
- perguntar qual é o principal objetivo do usuário;
- apresentar exemplos de mensagens;
- solicitar apenas os dados essenciais;
- explicar como os dados financeiros serão utilizados;
- oferecer a criação opcional da primeira meta.

Exemplos de objetivos:

- entender meus gastos;
- começar a economizar;
- criar uma reserva;
- reduzir gastos em uma categoria;
- controlar melhor minhas despesas;
- alcançar uma meta específica.

### 9.2 Registro de transações por conversa

O usuário poderá registrar receitas e despesas usando linguagem natural.

Exemplos:

- "Gastei R$ 25 com almoço."
- "Recebi R$ 1.500 de um trabalho."
- "Ontem paguei R$ 90 de internet."
- "Comprei um tênis por R$ 280 em três parcelas."
- "Paguei R$ 60 de combustível no cartão."
- "Recebi meu salário de R$ 3.500."

O sistema deverá identificar, quando possível:

- tipo da transação;
- valor;
- moeda;
- descrição;
- data;
- categoria;
- forma de pagamento, se mencionada;
- quantidade de parcelas, se mencionada;
- observações adicionais.

Quando faltar uma informação essencial, o aplicativo deverá fazer uma pergunta curta e objetiva.

Exemplo:

Usuário:

"Paguei a internet."

Aplicativo:

"Qual foi o valor pago?"

### 9.3 Confirmação e correção

Antes de salvar uma transação interpretada com baixa confiança, o sistema deverá apresentar um resumo para confirmação.

Exemplo:

"Entendi que você gastou R$ 42 hoje na categoria Alimentação. Está correto?"

O usuário poderá:

- confirmar;
- alterar o valor;
- alterar a data;
- mudar a categoria;
- alterar a descrição;
- alterar o tipo da transação;
- cancelar o registro.

A confirmação deverá ser simples e exigir o menor número possível de interações.

### 9.4 Classificação automática

O aplicativo deverá classificar automaticamente as transações.

Categorias iniciais sugeridas:

- alimentação;
- moradia;
- transporte;
- saúde;
- educação;
- lazer;
- compras;
- contas e serviços;
- renda;
- outros.

O usuário poderá corrigir a categoria sugerida.

As correções poderão ser utilizadas para melhorar classificações futuras, desde que isso seja explicado de maneira clara e esteja de acordo com as regras de privacidade do produto.

### 9.5 Histórico de transações

O usuário poderá:

- visualizar os registros mais recentes;
- filtrar por período;
- filtrar por categoria;
- filtrar por tipo de transação;
- pesquisar por descrição;
- editar uma transação;
- excluir uma transação;
- verificar se uma transação está confirmada ou pendente.

Cada item do histórico deverá apresentar:

- descrição;
- valor;
- tipo;
- categoria;
- data;
- status de confirmação.

### 9.6 Metas financeiras

O usuário poderá criar uma meta contendo:

- nome;
- valor desejado;
- valor inicial;
- data-alvo opcional;
- contribuição mensal planejada;
- descrição opcional.

Exemplo:

"Quero guardar R$ 3.000 para uma reserva."

O sistema deverá mostrar:

- valor acumulado;
- valor restante;
- percentual concluído;
- progresso ao longo do tempo;
- prazo, quando informado;
- contribuição planejada.

No MVP, o produto poderá priorizar uma meta principal por usuário.

### 9.7 Resumo financeiro e saldo calculado

A tela principal deverá apresentar uma visão simples da situação financeira do usuário no período selecionado.

O resumo deverá exibir três valores em destaque:

1. Receitas.
2. Despesas.
3. Saldo calculado.

As receitas representam a soma das transações confirmadas classificadas como receita no período selecionado.

As despesas representam a soma das transações confirmadas classificadas como despesa no período selecionado.

O saldo calculado representa a diferença entre as receitas e as despesas consideradas no cálculo.

Fórmula:

Saldo calculado = Total de receitas - Total de despesas

Exemplo:

Receitas: R$ 3.500,00
Despesas: R$ 2.750,00
Saldo calculado: R$ 750,00

#### 9.7.1 Comportamento visual do saldo

A cor do valor do saldo deverá mudar automaticamente de acordo com sua situação.

Regras:

- Verde: saldo maior que zero, indicando saldo positivo.
- Vermelho: saldo menor que zero, indicando saldo negativo.
- Preto ou cor neutra principal do tema: saldo igual a zero.

Exemplos:

- R$ 750,00 em verde.
- -R$ 180,00 em vermelho.
- R$ 0,00 em preto ou cor neutra.

O sinal negativo deverá ser exibido sempre que o saldo estiver abaixo de zero.

#### 9.7.2 Indicadores complementares

A situação do saldo não deverá ser comunicada apenas pela cor.

O sistema também deverá apresentar:

- um texto de apoio;
- um ícone visual;
- contraste adequado entre o texto e o fundo;
- uma descrição acessível para leitores de tela.

Estados sugeridos:

- seta para cima e texto "Saldo positivo";
- seta para baixo e texto "Saldo negativo";
- ícone neutro e texto "Saldo zerado".

Exemplo:

Saldo positivo
R$ 750,00

Essa abordagem permite que usuários com daltonismo ou outras dificuldades visuais não dependam exclusivamente das cores verde e vermelha.

#### 9.7.3 Período de cálculo

O usuário deverá visualizar claramente o período considerado no cálculo.

Opções sugeridas:

- este mês;
- mês anterior;
- últimos 30 dias;
- período personalizado.

Por padrão, o painel deverá mostrar o mês atual.

Ao alterar o período, os valores de receitas, despesas e saldo deverão ser recalculados em conjunto.

Exemplo de rótulo:

"Saldo calculado do mês"

#### 9.7.4 Diferença entre saldo calculado e saldo bancário

No MVP, o valor deverá ser identificado como "Saldo calculado".

O saldo calculado será baseado exclusivamente nas transações registradas e confirmadas pelo usuário no aplicativo.

O valor não deverá ser apresentado como saldo bancário, pois poderá não representar todo o dinheiro disponível nas contas do usuário.

Caso o produto tenha integração bancária no futuro, deverá diferenciar claramente:

- saldo calculado pelo aplicativo;
- saldo informado pela instituição financeira.

#### 9.7.5 Atualização do saldo

O saldo deverá ser recalculado quando o usuário:

- registrar uma receita;
- registrar uma despesa;
- confirmar uma transação;
- editar o valor de uma transação;
- alterar o tipo de uma transação;
- excluir uma transação;
- alterar o período de visualização.

Transações canceladas ou ainda não confirmadas não deverão afetar o saldo.

Caso o aplicativo permita salvar transações pendentes, elas deverão ser exibidas separadamente.

#### 9.7.6 Detalhamento dos valores

Ao selecionar um dos valores, o usuário deverá acessar as transações que formam aquele total.

Comportamentos esperados:

- ao selecionar Receitas, exibir apenas as receitas do período;
- ao selecionar Despesas, exibir apenas as despesas do período;
- ao selecionar Saldo calculado, exibir uma explicação simples do cálculo.

Exemplo:

R$ 3.500,00 em receitas
- R$ 2.750,00 em despesas
= R$ 750,00 de saldo calculado

#### 9.7.7 Estado sem transações

Quando não existirem transações no período, o sistema deverá exibir:

"Você ainda não registrou movimentações neste período."

Também deverá ser apresentado um botão ou atalho:

"Registrar primeira transação"

#### 9.7.8 Estado com transações pendentes

Caso existam transações aguardando confirmação, o sistema deverá exibir:

"Existem transações pendentes. Confirme os registros para atualizar o saldo."

Transações pendentes não deverão ser utilizadas no cálculo até que sejam confirmadas.

#### 9.7.9 Erro no carregamento

Se ocorrer uma falha no carregamento, o sistema não deverá substituir o valor por zero.

O sistema deverá apresentar:

"Não foi possível calcular seu saldo agora. Tente novamente."

Essa regra evita que uma falha técnica seja interpretada como saldo zerado.

### 9.8 Agente Financeiro

O Agente Financeiro deverá gerar orientações simples com base nos dados registrados.

Exemplos:

- "Alimentação foi sua maior categoria de gastos nesta semana."
- "Você já completou 40% da sua meta."
- "Se quiser, posso ajudar a definir um limite mensal para lazer."
- "Seus registros ainda são poucos. Continue adicionando movimentações para receber análises mais úteis."
- "Suas despesas estão maiores que suas receitas neste período."
- "Seu saldo calculado está positivo neste mês."

As recomendações deverão:

- utilizar linguagem educativa;
- evitar julgamentos;
- explicar o motivo da sugestão;
- diferenciar fatos, estimativas e sugestões;
- utilizar apenas os dados disponíveis;
- permitir que o usuário ignore a sugestão;
- evitar recomendações de investimentos no MVP;
- evitar promessas de economia ou retorno financeiro.

### 9.9 Limites do Agente Financeiro

No MVP, o agente poderá:

- ajudar a registrar gastos e receitas;
- explicar categorias;
- apresentar padrões de consumo;
- acompanhar metas definidas pelo usuário;
- oferecer sugestões educativas;
- informar quando uma sugestão estiver baseada em poucos dados;
- pedir confirmação quando houver dúvidas.

No MVP, o agente não deverá:

- recomendar investimentos específicos;
- prometer economia;
- prometer retorno financeiro;
- movimentar dinheiro;
- realizar pagamentos;
- tomar decisões em nome do usuário;
- oferecer aconselhamento financeiro profissional personalizado;
- afirmar que o saldo calculado corresponde ao saldo bancário.

## 10. Principais telas

### 10.1 Tela de boas-vindas

Objetivo:

Apresentar a proposta de valor do aplicativo.

Elementos:

- mensagem principal;
- explicação curta;
- botão "Começar";
- acesso à política de privacidade;
- opção de entrar em uma conta existente.

### 10.2 Tela de onboarding

Objetivo:

Identificar a necessidade inicial do usuário e explicar como o produto funciona.

Elementos:

- seleção de objetivo;
- exemplos de mensagens;
- configuração opcional da primeira meta;
- explicação sobre os dados utilizados;
- opção de avançar ou voltar;
- consentimento para tratamento dos dados necessários.

### 10.3 Tela de conversa

Objetivo:

Centralizar o registro de transações e as orientações financeiras.

Elementos:

- campo de mensagem;
- histórico da conversa;
- respostas do agente;
- cartões de confirmação de transações;
- sugestões rápidas;
- atalhos para registrar receita ou despesa;
- acesso à entrada por voz em uma fase futura.

### 10.4 Tela principal ou resumo

Objetivo:

Apresentar a situação financeira do período de maneira simples, acessível e fácil de compreender.

Elementos:

- seletor de período;
- total de receitas;
- total de despesas;
- saldo calculado;
- indicador de saldo positivo, negativo ou zerado;
- variação de cor do saldo;
- indicador textual e visual do estado do saldo;
- gráfico de despesas por categoria;
- progresso da meta principal;
- observação principal do Agente Financeiro;
- alerta de transações pendentes;
- atalho para registrar uma nova transação;
- acesso ao detalhamento dos valores.

O saldo calculado deverá ter maior destaque visual.

Receitas e despesas deverão aparecer logo abaixo ou ao lado, permitindo que o usuário entenda como o saldo foi formado.

Exemplo de organização:

Resumo do mês

Saldo calculado
Saldo positivo
R$ 750,00

Receitas
R$ 3.500,00

Despesas
R$ 2.750,00

### 10.5 Tela de transações

Objetivo:

Permitir a consulta e a correção dos registros.

Elementos:

- lista de transações;
- busca;
- filtros;
- edição;
- exclusão;
- identificação visual das categorias;
- status de confirmação;
- acesso aos detalhes da transação.

### 10.6 Tela de metas

Objetivo:

Permitir que o usuário acompanhe seus objetivos financeiros.

Elementos:

- meta principal;
- barra de progresso;
- valor acumulado;
- valor restante;
- prazo opcional;
- histórico de contribuições;
- contribuição mensal planejada;
- opção de editar a meta.

### 10.7 Tela de configurações e privacidade

Objetivo:

Dar controle ao usuário sobre sua conta, preferências e dados.

Elementos:

- dados da conta;
- preferências;
- moeda;
- notificações;
- exportação de dados;
- exclusão de dados;
- exclusão da conta;
- política de privacidade;
- informações sobre o uso da inteligência artificial.

## 11. Requisitos necessários

### 11.1 Produto e design

- mapeamento da jornada do usuário;
- protótipo navegável;
- biblioteca visual acessível;
- estados de erro;
- estados de carregamento;
- estados de ausência de dados;
- linguagem clara e consistente;
- experiência de correção rápida;
- contraste adequado;
- interface responsiva;
- comunicação do saldo por cor, texto e ícone.

### 11.2 Front-end

- interface de conversa;
- painel financeiro;
- visualização de receitas;
- visualização de despesas;
- visualização do saldo calculado;
- mudança automática da cor do saldo;
- seletor de período;
- histórico de transações;
- gerenciamento de metas;
- autenticação;
- interface responsiva;
- recursos básicos de acessibilidade.

### 11.3 Back-end

- cadastro e autenticação;
- armazenamento de usuários;
- armazenamento de transações;
- armazenamento de metas;
- serviço de categorização;
- cálculo de receitas;
- cálculo de despesas;
- cálculo do saldo;
- geração de resumos;
- registro de eventos de uso;
- mecanismo de exclusão dos dados;
- controle de transações pendentes;
- filtros por período.

### 11.4 Inteligência artificial

- extração estruturada das informações enviadas nas mensagens;
- classificação das transações;
- identificação de informações ausentes;
- geração de respostas educativas;
- controle de contexto da conversa;
- mecanismo de confiança;
- solicitação de confirmação;
- regras para evitar afirmações financeiras indevidas;
- diferenciação entre fatos, estimativas e sugestões.

### 11.5 Estrutura mínima de uma transação

Exemplo:

{
  "tipo": "despesa",
  "valor": 42.00,
  "moeda": "BRL",
  "descricao": "supermercado",
  "categoria": "alimentacao",
  "data": "data_informada_ou_inferida",
  "forma_pagamento": null,
  "parcelas": null,
  "status_confirmacao": "confirmada"
}

## 12. Regras de negócio do resumo financeiro

### RF-RES-01

O sistema deve calcular o saldo subtraindo as despesas das receitas do período selecionado.

### RF-RES-02

O sistema deve exibir o saldo positivo em verde.

### RF-RES-03

O sistema deve exibir o saldo negativo em vermelho e com sinal negativo.

### RF-RES-04

O sistema deve exibir o saldo zerado em preto ou na cor neutra definida pelo tema.

### RF-RES-05

O sistema deve apresentar um indicador textual, além da cor, informando se o saldo está positivo, negativo ou zerado.

### RF-RES-06

O sistema deve recalcular os valores após a confirmação, edição ou exclusão de uma transação.

### RF-RES-07

Transações canceladas ou não confirmadas não devem compor o saldo calculado.

### RF-RES-08

O sistema deve informar claramente o período considerado no cálculo.

### RF-RES-09

O sistema deve permitir o acesso às transações que compõem as receitas e as despesas.

### RF-RES-10

Uma falha no carregamento não deve ser apresentada como saldo zerado.

### RF-RES-11

Os valores devem utilizar o formato monetário brasileiro.

Exemplo:

R$ 1.250,00

### RF-RES-12

No MVP, o valor deve ser identificado como "Saldo calculado", e não como saldo bancário.

### RF-RES-13

Ao alterar o período, receitas, despesas e saldo devem ser atualizados em conjunto.

### RF-RES-14

O saldo deve considerar somente transações confirmadas pertencentes ao período selecionado.

### RF-RES-15

A situação do saldo deve ser comunicada por cor, texto e ícone.

### RF-RES-16

O usuário deve conseguir acessar uma explicação simples sobre como o saldo foi calculado.

### RF-RES-17

Quando não existirem transações no período, o sistema deve apresentar um estado vazio e um atalho para registrar a primeira transação.

## 13. Critérios de aceite do resumo financeiro

### Cenário 1: saldo positivo

Dado que o usuário possui R$ 2.000,00 em receitas confirmadas
E possui R$ 1.500,00 em despesas confirmadas
Quando acessar a tela principal
Então o saldo calculado deverá ser R$ 500,00
E o valor deverá aparecer em verde
E deverá ser exibido o texto "Saldo positivo"

### Cenário 2: saldo negativo

Dado que o usuário possui R$ 1.000,00 em receitas confirmadas
E possui R$ 1.250,00 em despesas confirmadas
Quando acessar a tela principal
Então o saldo calculado deverá ser -R$ 250,00
E o valor deverá aparecer em vermelho
E deverá ser exibido o texto "Saldo negativo"

### Cenário 3: saldo zerado

Dado que o usuário possui R$ 1.000,00 em receitas confirmadas
E possui R$ 1.000,00 em despesas confirmadas
Quando acessar a tela principal
Então o saldo calculado deverá ser R$ 0,00
E o valor deverá aparecer em preto ou em cor neutra
E deverá ser exibido o texto "Saldo zerado"

### Cenário 4: transação pendente

Dado que o usuário possui uma despesa ainda não confirmada
Quando acessar a tela principal
Então a despesa pendente não deverá afetar o saldo calculado
E o sistema deverá informar que existe uma transação pendente

### Cenário 5: atualização após edição

Dado que o usuário alterou uma despesa confirmada de R$ 100,00 para R$ 80,00
Quando a alteração for salva
Então o total de despesas deverá ser atualizado
E o saldo calculado deverá ser recalculado

### Cenário 6: alteração do período

Dado que o usuário está visualizando o mês atual
Quando selecionar o mês anterior
Então as receitas deverão considerar apenas o mês anterior
E as despesas deverão considerar apenas o mês anterior
E o saldo deverá ser recalculado para o mês anterior

### Cenário 7: falha de carregamento

Dado que ocorreu uma falha ao carregar as transações
Quando o usuário acessar a tela principal
Então o sistema não deverá exibir o saldo como R$ 0,00
E deverá informar que não foi possível calcular o saldo

### Cenário 8: período sem transações

Dado que o usuário não possui transações no período selecionado
Quando acessar a tela principal
Então o sistema deverá apresentar um estado sem movimentações
E deverá apresentar um atalho para registrar a primeira transação

## 14. Fora do escopo do MVP

Para manter o MVP pequeno e testável, os seguintes recursos ficam fora da primeira versão:

- integração com bancos;
- leitura automática de extratos;
- pagamentos pelo aplicativo;
- recomendação de investimentos;
- gestão de carteira de investimentos;
- compartilhamento familiar;
- renegociação de dívidas;
- leitura automática de recibos;
- suporte completo por voz;
- previsões financeiras avançadas;
- gestão financeira empresarial;
- conciliação automática de contas bancárias;
- movimentação de dinheiro.

## 15. Métricas de sucesso

### 15.1 Ativação

- conclusão do onboarding;
- criação da primeira meta;
- registro da primeira transação;
- confirmação correta da primeira transação;
- visualização do primeiro resumo financeiro.

### 15.2 Engajamento

- frequência de registro de transações;
- quantidade de dias ativos;
- retorno após a primeira semana;
- uso do histórico;
- uso do resumo financeiro;
- número de interações com o Agente Financeiro;
- acompanhamento da meta principal.

### 15.3 Qualidade da experiência

- percentual de transações confirmadas sem edição;
- percentual de categorias corrigidas;
- quantidade de mensagens necessárias para registrar uma transação;
- avaliação da utilidade das recomendações;
- taxa de erros de interpretação;
- percentual de usuários que compreendem o saldo calculado;
- percentual de usuários que conseguem localizar as transações de uma categoria.

### 15.4 Valor percebido

Perguntas sugeridas:

- "O aplicativo ajudou você a entender melhor seus gastos?"
- "Foi fácil registrar uma transação?"
- "Você entendeu como o saldo foi calculado?"
- "Foi fácil identificar se o saldo estava positivo, negativo ou zerado?"
- "Você usaria este aplicativo toda semana?"
- "As recomendações pareceram úteis e respeitosas?"
- "Você se sentiu seguro ao registrar suas informações?"

As metas numéricas deverão ser definidas depois de uma rodada inicial de entrevistas ou testes de usabilidade.

## 16. Plano de validação inicial

### 16.1 Etapa 1: entrevistas exploratórias

Conversar com pessoas do público-alvo para entender:

- como controlam seus gastos atualmente;
- por que abandonaram outros métodos;
- quais informações financeiras evitam registrar;
- quais tipos de orientação consideram úteis;
- quais preocupações possuem sobre privacidade;
- se conversariam com um aplicativo sobre dinheiro;
- como interpretam os conceitos de receita, despesa e saldo;
- quais informações esperam encontrar em uma tela principal.

### 16.2 Etapa 2: teste de protótipo

Criar um protótipo navegável contendo:

- onboarding;
- conversa;
- confirmação da transação;
- tela principal;
- receitas;
- despesas;
- saldo calculado;
- meta;
- histórico.

Tarefas sugeridas para o teste:

1. Registrar um gasto ocorrido hoje.
2. Registrar uma receita.
3. Registrar um gasto ocorrido em outra data.
4. Corrigir uma categoria.
5. Criar uma meta.
6. Identificar o saldo do período.
7. Informar se o saldo está positivo, negativo ou zerado.
8. Encontrar a categoria com maior gasto.
9. Consultar as transações que formam o total de despesas.
10. Excluir uma transação.
11. Alterar o período do resumo.

Durante o teste, observar:

- onde o usuário hesita;
- quais termos geram dúvidas;
- se a confirmação é compreendida;
- se o saldo calculado é compreendido;
- se os relatórios são fáceis de interpretar;
- se o uso das cores é compreendido;
- se o texto complementar ajuda na interpretação;
- se o agente transmite confiança sem parecer autoritário.

### 16.3 Etapa 3: MVP assistido

Antes de automatizar completamente a inteligência artificial, parte das respostas poderá ser preparada ou revisada manualmente pela equipe.

Essa abordagem poderá ajudar a validar:

- quais mensagens os usuários realmente enviam;
- quais informações normalmente ficam ausentes;
- quais categorias causam mais confusão;
- quais recomendações são consideradas úteis;
- quais erros comprometem a confiança;
- quais explicações sobre o saldo são mais fáceis de compreender.

### 16.4 Etapa 4: piloto controlado

Disponibilizar o MVP para um grupo pequeno e acompanhar:

- registros concluídos;
- correções feitas;
- retorno ao aplicativo;
- problemas de interpretação;
- dúvidas frequentes;
- percepção de segurança;
- utilidade das recomendações;
- compreensão do saldo calculado;
- utilização dos filtros por período;
- interação com receitas, despesas e saldo.

## 17. Critérios para considerar o MVP validado

O MVP poderá ser considerado promissor quando houver evidência de que:

- os usuários conseguem registrar transações sem treinamento extenso;
- a maioria entende o que foi registrado;
- as correções podem ser feitas facilmente;
- o resumo ajuda na compreensão dos gastos;
- os usuários entendem a diferença entre receitas, despesas e saldo;
- os usuários entendem que o saldo é calculado com base nas transações registradas;
- a variação de cor ajuda na identificação da situação financeira;
- o texto e o ícone permitem compreender o saldo sem depender somente da cor;
- parte relevante dos participantes retorna voluntariamente;
- as recomendações são percebidas como úteis, claras e não julgadoras.

## 18. Privacidade e segurança

Como o produto lidará com informações financeiras pessoais, deverá incluir requisitos mínimos de privacidade e segurança.

O aplicativo deverá oferecer:

- consentimento para armazenamento de dados;
- explicação clara sobre o uso das informações;
- coleta apenas dos dados necessários;
- possibilidade de corrigir registros;
- possibilidade de excluir transações;
- possibilidade de excluir os dados;
- possibilidade de excluir a conta;
- proteção dos dados durante a transmissão;
- proteção dos dados durante o armazenamento;
- prevenção contra exposição de informações sensíveis no chat;
- comunicação clara sobre o uso da inteligência artificial.

O produto deverá evitar solicitar informações bancárias sensíveis que não sejam necessárias para o funcionamento do MVP.

## 19. Riscos principais

### 19.1 Erros de interpretação

Risco:

O sistema poderá registrar valor, data, categoria ou tipo de transação incorretamente.

Mitigação:

- confirmação explícita;
- indicação de baixa confiança;
- edição simples;
- perguntas objetivas;
- possibilidade de cancelar o registro.

### 19.2 Perda de confiança

Risco:

Uma resposta errada poderá fazer o usuário abandonar o aplicativo.

Mitigação:

- linguagem transparente;
- possibilidade de correção;
- histórico acessível;
- ausência de afirmações excessivamente confiantes;
- explicação sobre como os valores foram calculados.

### 19.3 Recomendações inadequadas

Risco:

O agente poderá apresentar sugestões genéricas, invasivas ou incompatíveis com a realidade do usuário.

Mitigação:

- recomendações opcionais;
- explicação do motivo da sugestão;
- uso apenas dos dados disponíveis;
- linguagem educativa;
- ausência de julgamentos;
- possibilidade de ignorar a sugestão.

### 19.4 Privacidade

Risco:

O usuário poderá ter receio de compartilhar informações financeiras.

Mitigação:

- coleta mínima;
- controles de exclusão;
- explicações acessíveis;
- proteção dos dados;
- transparência sobre o uso da inteligência artificial.

### 19.5 Confusão entre saldo calculado e saldo bancário

Risco:

O usuário poderá acreditar que o saldo exibido representa o valor disponível em sua conta bancária.

Mitigação:

- utilizar o nome "Saldo calculado";
- explicar a fórmula;
- informar que o valor depende das transações registradas;
- não utilizar o termo "Saldo bancário" no MVP;
- permitir o acesso ao detalhamento das receitas e despesas.

### 19.6 Dependência exclusiva das cores

Risco:

Alguns usuários poderão não conseguir diferenciar o saldo positivo do negativo apenas pelas cores.

Mitigação:

- utilizar texto;
- utilizar ícones;
- utilizar sinais matemáticos;
- garantir contraste adequado;
- fornecer descrições para leitores de tela.

### 19.7 Escopo excessivo

Risco:

A equipe poderá tentar incluir integração bancária, investimentos e automações antes de validar o uso do chat.

Mitigação:

Concentrar o MVP nos seguintes recursos:

- registro conversacional;
- categorização;
- confirmação;
- histórico;
- receitas;
- despesas;
- saldo calculado;
- resumo;
- metas;
- recomendações educativas.

## 20. Priorização recomendada

### 20.1 Obrigatório no MVP

- onboarding;
- criação e acesso à conta;
- registro de transações por chat;
- interpretação de valor, data, tipo e descrição;
- categorização automática;
- confirmação e edição;
- histórico de transações;
- total de receitas;
- total de despesas;
- saldo calculado;
- mudança de cor do saldo;
- indicador textual da situação do saldo;
- seletor de período;
- detalhamento dos valores;
- resumo financeiro básico;
- uma meta principal;
- Agente Financeiro com orientações básicas;
- privacidade;
- exclusão de dados;
- exclusão da conta.

### 20.2 Importante, mas pode entrar depois

- múltiplas metas;
- notificações inteligentes;
- comparações avançadas;
- personalização detalhada do agente;
- exportação de relatórios;
- categorias personalizadas;
- orçamento mensal por categoria;
- lembretes de contas.

### 20.3 Recursos futuros

- integração bancária;
- entrada por voz;
- leitura de comprovantes;
- importação de extratos;
- planejamento familiar;
- investimentos;
- previsões financeiras;
- alertas preditivos;
- compartilhamento de metas;
- gestão de assinaturas.

## 21. Resumo do MVP

O MVP deverá permitir que o usuário:

1. Crie uma conta.
2. Informe seu objetivo financeiro.
3. Registre receitas e despesas por conversa.
4. Confirme ou corrija os dados interpretados.
5. Consulte o histórico de transações.
6. Visualize receitas, despesas e saldo calculado.
7. Identifique visualmente se o saldo está positivo, negativo ou zerado.
8. Consulte como o saldo foi calculado.
9. Crie e acompanhe uma meta financeira.
10. Receba orientações educativas do Agente Financeiro.
11. Controle seus dados e sua privacidade.

O principal objetivo do MVP será validar se uma experiência conversacional reduz o esforço necessário para registrar transações e ajuda pessoas iniciantes a compreender melhor sua situação financeira.
```
Interações com o Lovable

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirement Document): (PRD).

> Corrigir erro de build (compilação).

> Desenvolva a tela de Conversa.

> Desenvolva a tela de Transações.

> Continue o desenvolvimento da tela de Transações.

> Desenvolva a tela de Metas.

> Mude o nome do app "Conta Clara" para "ContaBank".

> Abra a tela de Metas no preview, crie uma meta e confira a barra de progresso, o quanto falta e o botão "Guardar dinheiro".

> Desenvolva a tela de Configurações.

> Quero que a conversa crie metas indicadas pelo usuário.

> Teste no preview: peça uma meta na conversa e confirme que ela aparece na tela Metas com a barra de progresso e o plano mensal.

> Corrigir erro (tela em branco).

> Na conversa, faça o que vc fez com o cartão de metas. Só mostre que a transação foi concluída, sem os botões "Confirmar" e  "Cancelar".

> Nestes cartões de transações na conversa, coloque o link para a tela Transações, como vc fez no cartão das metas.

Resultado final do site com o Lovable: https://contabankapp.lovable.app

<img width="995" height="513" alt="lovable1" src="https://github.com/user-attachments/assets/5edf28c6-1009-4979-8e64-9663d25da2a1" />
<img width="1001" height="505" alt="lovable2" src="https://github.com/user-attachments/assets/12c23b07-d0fb-4eb7-986a-a520c9442009" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
> É um site que calcula as finanças do usuário de acordo com as suas necessidades. Com o cálculo das Transações (Receitas e Despesas) e cria Metas desejadas pelo cliente. Isso tudo com a ajuda de uma IA assistente que conversa com o usuário de forma simples e em Português.

    
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
  > Praticamente tudo o que eu pedi, e de acordo com o exercício. O interessante é que o Lovable identifica os erros do programa e corrige com a minha autorização.    
  - O que não funcionou como o esperado?
  > Acredito que nada. Ele fez exatamente tudo o que pedi nos prompts. Até fiquei surpreso com a alta tecnologia do Lovable. Fiquei satisfeito!
  - O que aprendeu sobre conversar com IAs?
  > Que posso criar o que quero de forma fácil, numa linguagem mais humana possível e sem usar linguagem de programação. Fiquei satisfeito com o projeto. Superou minhas expectativas.

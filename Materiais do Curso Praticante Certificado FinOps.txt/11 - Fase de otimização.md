# Visão geral da fase de otimização

## Recapitular

Agora que aprendemos como exercitar todos os recursos e compreender nosso uso e gastos na fase Informar, vamos analisar as oportunidades de otimização. Isso pode ser uma otimização do uso, perfil de custo, cobertura, automação ou até mesmo nível de visibilidade.

### Fase de otimização

Na fase Otimizar, direcionamos, definimos e documentamos oportunidades de otimização; tudo isso é uma questão de triagem e priorização.

A fase Otimizar apoia os princípios:

O valor comercial da nuvem impulsiona decisões
Uma equipe centralizada impulsiona FinOps
Aproveite o modelo de custo variável da nuvem

#### Durante a fase de otimização, esperamos ver:

Estamos fazendo o suficiente?

Cada uma dessas capacidades está madura o suficiente?

Estamos progredindo em direção aos nossos objetivos?

Sabemos o suficiente para fazer um bom progresso?


#### A maioria dos recursos que usaremos para realizar a fase Otimizar estão nos domínios:

Todos os domínios e capacidades entrarão em jogo nesta fase

#### A fase Otimizar trata da identificação de oportunidades:

Para fazer FinOps melhor

Para entender melhor o uso

Para melhorar o uso (faça mais onde for valioso, faça menos onde for valioso)

Para melhorar as taxas 

## KPIs e resultados

Para conduzir o resto do trabalho que você fará na fase Otimizar, precisamos saber:

Quais resultados são esperados pelo negócio? 

Quais indicadores-chave de desempenho (KPIs) nossa empresa usará para medir o sucesso?

Sua organização pode já ter definidos KPIs relacionados ao uso da nuvem ou ao uso da TI em geral. Caso contrário, talvez seja necessário dar uma olhada nos resultados que você está tentando alcançar com a nuvem:  

Que comportamento ajudará a alcançar esses resultados?
Como você pode medir ou determinar se está realizando esse trabalho?


#### Definindo Desafios de KPI

Definir bons KPIs para uso da nuvem pode ser desafiador porque o uso da nuvem é novo para muitas equipes e porque há muito para medir e muitos dados para medi-lo. 

#### Exemplos de KPIs

Exemplos de maneiras de medir cada uma das capacidades são encontrados na seção de recursos do mundo real dentro de cada capacidade em finops.org(abre em uma nova aba).
Considere a diferença na taxa de cobertura reservada ao usar custo versus uso

Você quer promover o uso de spot? Ou uso reservado? Ou total?

Os KPIs medem o desempenho da equipe FinOps ou das equipes de desenvolvimento?

Taxa de cobertura de reserva (custo ou uso)

Taxa de utilização de reservas 

Oportunidades de otimização como porcentagem dos gastos

Prioridade pontual/preemptiva/baixa como porcentagem da computação

### Metas e metas incrementais

Ao executar a fase de otimização, faça-o pensando em tomar medidas para melhorar os KPIs ou alcançar os resultados definidos. Lembre-se, você não precisa alcançar os resultados em uma única etapa, pense de forma incremental. Torne suas metas e objetivos de prazo imediato alcançáveis, acionáveis ​​e claros. Revisite essas metas sempre que passar pelo ciclo de vida do FinOps.

O que estávamos tentando alcançar da última vez?

Conseguimos isso fazendo o que fizemos?

Sim. Então mais disso, por favor.

Não. Então, precisamos agir com mais escala? Menos escala? Ação diferente?


### Exemplo

Temos um OKR (Objective and Key Results) de ter um ambiente de nuvem altamente otimizado para todos os sistemas de produção. Estabelecemos um KPI para medir isso: porcentagem de desconto para cargas de trabalho de computação de produção de uso consistente - que gostaríamos de alcançar e manter em 50%.

Isso significa que gostaríamos que nosso desconto médio fosse de 50% para todas as nossas instâncias de computação de produção em execução consistente. Alguns serão cobertos por planos de poupança de três anos, alguns computacionais, alguns EC2, alguns serão cobertos por planos de poupança de um ano e alguns serão pagos sob demanda. Tudo isso proporciona diferentes taxas de economia para vários recursos e, claro, nosso mix de carga de trabalho e demanda total também está mudando/crescendo ao longo do tempo. 


#### Expectativas

Não é razoável esperar que o momento em que estabelecemos este KPI passe para atingi-lo num único ciclo. 

Primeiro, não queremos comprar todas as nossas reservas de uma vez, queremos comprá-las de forma incremental ao longo do tempo

Em segundo lugar, não queremos fazer uma aposta muito grande de uma só vez, queremos observar as tendências ao longo do tempo e tomar pequenas ações incrementais

#### Definição de metas

Como meta durante este ciclo na fase de otimização, podemos querer melhorar este KPI de onde está agora para algo um pouco melhor. Talvez estejamos atualmente em 32%. Para melhorar, temos que considerar várias coisas:

Cubra mais recursos que atualmente estão com 0% de desconto

Recursos de cobertura que atualmente obtêm cobertura de desconto mais baixa com opções de desconto mais altas

Temos a opção de comprar algumas ou todas as nossas compras recomendadas com opções de desconto

O que nós fazemos?

#### Agindo

Assim que tivermos um plano sobre o que gostaríamos de realizar, olhamos para as opções e tentamos não só identificar que passo incremental daremos agora, mas também que efeito esperamos que tenha.

Se dermos esse passo, poderemos, no próximo ciclo do ciclo de vida, observar o impacto que realmente tivemos e determinar se as nossas estimativas estavam corretas. Isso nos dará mais informações sobre como nossas ações impactam nossos KPIs e nos dará uma melhor compreensão do que fazer na próxima vez.

Ao darmos pequenos passos, estamos a deixar passar algumas poupanças potenciais, mas, a longo prazo, a nossa abordagem de melhoria incremental e a confiança criada por esta abordagem renderão dividendos maiores.

#### Monitoramento

Colocaremos nossos objetivos e oportunidades em um sistema de rastreamento.

Para Agile, crie um backlog de itens para resolver

Criar visibilidade sobre como estamos indo, no que estamos trabalhando e como estamos priorizando

#### Resumo

Você pode alcançar um sucesso crescente ao longo do tempo, à medida que refina suas metas e objetivos, tornando-se mais matizado e maduro em suas ações.


#### Definindo Bons Objetivos

O primeiro objetivo de qualquer esforço de otimização deve ser uma boa alocação de custos. Sem uma compreensão completa de todos os custos, a otimização terá um objetivo errado. A redução de custos pode ser uma meta – mas não a única ou a mais importante meta. Certifique-se de expressar a economia de custos de forma que permita flexibilidade (o modelo da nuvem).

Triângulo de Ferro = custo > velocidade > qualidade
Lembre-se do triângulo de ferro. O objetivo é tomar decisões baseadas em valor, sabendo que são necessárias compensações entre custo, velocidade e qualidade.


## Principais formas de otimizar o uso

### Gerenciamento de carga de trabalho

A primeira maneira principal de otimizar o uso é por meio do gerenciamento de carga de trabalho. Isso significa ligar as coisas somente quando você precisar delas. Uma equipe central de FinOps, além de utilizar automação, pode ajudar a tornar isso mais fácil. Observe que isso não é apropriado para todas as cargas de trabalho. 

### Escalabilidade e Elasticidade

Outra forma de otimizar seu uso é introduzindo escalabilidade ou elasticidade. A ideia é usar uma série de recursos menores para realizar uma tarefa ou suportar uma carga de trabalho, de modo que, à medida que as demandas dessa carga de trabalho variem ao longo do tempo, o número de pequenos recursos possa ser ajustado. Escalabilidade e elasticidade são funções da arquitetura dos sistemas executados na nuvem. As equipes de arquitetura, de desenvolvimento e de plataforma devem procurar maneiras de conseguir isso, incorporando opções de arquitetura escalonáveis ​​o mais cedo possível e concluindo a rearquitetura envolvida.

#### Exemplos

.Arquiteturas de microsserviços são aquelas em que o aplicativo ou site do usuário final é composto de muitos serviços menores, cada um dos quais fornece uma parte do que o usuário vê. Como cada uma pode ser dimensionada e desenvolvida separadamente, isso proporciona a capacidade de servir a página da Web, fazendo com que todas as seções gerem seu conteúdo de uma só vez em máquinas separadas.

.Instâncias de computação sem estado. Eles não precisam lidar com uma longa série de transações em uma ordem específica, mas podem funcionar apenas em transações atômicas e podem ser usados ​​em vez de servidores de processo com estado que devem esperar que longas sequências terminem (ou que humanos muito lentos responder) usando técnicas de enfileiramento ou desenvolvendo o que é chamado de arquiteturas fracamente acopladas

.As arquiteturas sem servidor contornam muitos dos desafios de escalabilidade, recorrendo a recursos de computação apenas quando há demanda real e fazendo com que cada indivíduo chame seus próprios recursos para executar

.Os aplicativos baseados em contêiner geralmente são criados para escalar horizontalmente, adicionando capacidade conforme necessário 

.Sites básicos geralmente têm o que é chamado de arquitetura de três camadas, onde os servidores front-end aos quais os usuários se conectam podem ser sem estado e podem ser acessados ​​por meio de um “balanceador de carga”, que permite que vários servidores web front-end trabalhem juntos para lidar com a carga. O número deles pode ser ajustado para a demanda real ou prevista


## Dimensionamento de direitos

O Rightsizing sempre deve ser abordado como um esforço colaborativo. A equipe centralizada de FinOps não pode fazer isso sozinha e precisará: pedir ajuda, conversar, discutir, chegar a um acordo e, em seguida, construir um caso de negócio. A equipe de FinOps deve conversar regularmente sobre oportunidades com outras equipes, não apenas quando há um “problema”. Além disso, a equipe de FinOps precisará colaborar com a equipe de arquitetura para construir relações de trabalho e manter-se informada sobre as mudanças planejadas. 

#### É tão importante confirmar uma boa adequação da carga de trabalho quanto identificar oportunidades de mudança!


#### Começando

Onde começar?

Recursos não anexados e ociosos (encontre e remova recursos subutilizados)

Tipos e classes de armazenamento (dimensionamento de direitos, plano de gerenciamento)

Utilização ultrabaixa (didimensionamento)

Instâncias de geração antiga (modernização)

#### Cadência

Mantenha uma cadência mensal com as equipes de desenvolvimento.

Identifique oportunidades de redimensionamento ao longo do mês

Todos deveriam procurar oportunidades de redimensionamento

Mantenha uma cadência regular com as equipes de arquitetura e plataforma

Mudanças planejadas de arquitetura/mudanças de plataforma

Verifique o uso contínuo de serviços e recursos, esteja atento a ensaios e testes


### Redimensionamento versus descontos baseados em compromisso

A otimização e a compra comprometida são as duas faces da mesma moeda. Queremos criar laços e cheques frouxos, ao mesmo tempo que fazemos as duas coisas.  

Certifique-se de não se comprometer com recursos que você possa dimensionar corretamente
Certifique-se de não redimensionar sem verificar o que você já está comprometido em usar
Realizaremos ambos os conjuntos de atividades em sua própria cadência. Inclua pontos de contato com o outro processo nos principais pontos de decisão e antes da análise detalhada. A equipe FinOps pode fornecer às equipes de desenvolvimento informações oportunas para que elas possam agir, ao mesmo tempo que permite que trabalhem na otimização de seu sprint. 

## Otimizar o uso

### Candidatos para otimização

Na fase Otimizar é onde você identificará oportunidades de otimização. Procure uma mistura de vitórias fáceis e elementos mais difíceis. Será mais difícil à medida que você avança (menos vitórias fáceis, melhor uso da equipe). Você desejará fazer uma combinação de todos os itens listados abaixo à medida que avança em seu trabalho.

### Exemplos

Esta é uma lista potencial de oportunidades de otimização. Eles estão mais ou menos em ordem de dificuldade. Alguns deles são exemplos um pouco mais concretos de oportunidades de otimização que você poderia buscar. 

Desativar/ativar ambientes de desenvolvimento, teste e sandbox

Criar/gerenciar políticas de armazenamento para descontinuar o armazenamento ao longo do tempo para níveis mais baratos

Dimensionar computação, bancos de dados, redes, ambientes 

Mude de recursos licenciados de terceiros para recursos nativos da nuvem

Modernizar recursos

Substituição de serviço (ou substituição de licença)

Amadureça sua abordagem DevOps 

Mover para/expandir o uso de contêineres

Mude para sem servidor

Com base no que você vê na fase de informação, sua equipe de FinOps pode criar uma lista de oportunidades de otimização como um exercício de triagem ou brainstorming. A cada oportunidade faça as seguintes perguntas:


bala
Qual é o valor de cada um deles? 


bala
Qual é o esforço necessário?


bala
O que é razoável considerar para a fase de operação?


bala
Com quem precisaríamos conversar para obter todas essas respostas?

## Otimizar taxas

Otimizar as taxas é tarefa da equipe central (princípio FinOps). Compras com desconto com base em compromissos, como instâncias reservadas, planos de poupança e CUDs são o foco principal aqui.

### Desconto

Embora as especificidades possam variar muito de acordo com o fornecedor e o serviço, os descontos em geral são semelhantes, independentemente do fornecedor ou tipo. O compromisso com o provedor de nuvem – em termos de dinheiro, tempo e detalhes – lhe renderá descontos. Quanto mais específicos, maiores ou mais longos forem os seus compromissos, mais você geralmente poderá economizar.

Os provedores de nuvem oferecem descontos porque desejam previsibilidade (o mesmo que os data centers privados, mas com mais escala). Como você está se comprometendo a pagar, você está, por definição, abrindo mão da flexibilidade que o uso do serviço sob demanda oferece. A outra maneira de pensar sobre isso é que os provedores de nuvem estão comprando sua flexibilidade. Apesar de isso ser assustador, não espere. Trabalhe constantemente para obter descontos. 


#### Antes de se comprometer

Os provedores de nuvem são especialistas em descontos. Portanto, antes de se comprometer, consiga prever sua demanda e entender com quais compromissos você pode conviver.
Você não precisa obter o maior desconto de todos os tempos (Crawl Walk Run também se aplica aqui). Se você só consegue prever um número total de gastos no próximo ano, obtenha um desconto de 15% sobre nada. Se você puder prever que usará uma determinada família de instâncias em uma determinada região por três anos, opte pelo desconto de 74%. Além disso, misture o que você compra e como você negocia.

#### Como otimizar

Quais descontos você compra e como você os compra afetarão as ferramentas que você precisa implementar. Como você otimizaria?

Principalmente através de compras para descontos negociados

Se você tiver acordos empresariais para licenças ou outros contratos, trate dessa forma e gaste uma quantidade adequada de tempo, dada a escala de seus gastos

Você não pode otimizar muito em descontos baseados no tempo ou no uso

É importante saber quais descontos estão acontecendo para que você possa utilizá-los em quaisquer outras modalidades


##### Decisões de desconto

Ao procurar descontos, sejam descontos negociados, escalonados ou baseados em compromissos, você tem várias decisões a tomar. 

Você está disposto a pagar adiantado? Isso não é cada vez mais benéfico, mas ainda proporciona um desconto de 10% se isso funcionar com seu custo interno de capital. Se você pagar adiantado, de onde virá esse dinheiro? Como será recuperado por quem o fornece? 

Como você coletará, reconhecerá e aplicará os descontos quando eles chegarem?


Você mostrará descontos aos seus engenheiros ou outros responsáveis ​​pelos custos da nuvem?

#### Descontos baseados em compromissos

RIs, planos de poupança e descontos por uso contínuo são compromissos de usar um determinado tipo de recurso (talvez em um determinado local ou de um determinado tipo) ou de gastar uma determinada quantia de dinheiro (durante um período de um ou três anos, a cada hora de cada dia). 

.Exemplos

Instâncias Reservadas (RIs)

Descontos por uso contínuo (CUDs)

Reservas de capacidade

Planos de Poupança

.Características

Como cupons, não recursos reais

1 ano ou 3 anos

Descontos de 17-75%

Quanto menos flexíveis forem, maior será o desconto

Pagamentos antecipados ou mensais 

Localização, família de instâncias, tamanho, decisões de locação

#### Compra com desconto

Gerenciar descontos é complexo e há muitas decisões a serem tomadas. Esse é um dos motivos pelos quais recomendamos o gerenciamento centralizado com informações de grupos financeiros (seu custo de dinheiro) e de tecnologia (seu uso futuro) para informar decisões.

Os descontos são complexos para serem calculados corretamente e mantidos bem. Talvez seja melhor ter uma pessoa em sua equipe que conheça todas as opções que você tem, por dentro e por fora. Então, peça a outra pessoa que aprenda com essa pessoa. 

Quando você possui esses descontos, eles serão aplicados aos recursos em execução que sua equipe de engenharia lançar. É por isso que temos que ter certeza de que eles continuarão a usá-los. Não há indicação de que um recurso esteja coberto quando você para de usá-lo (a cobertura será aplicada aleatoriamente em todo o seu conjunto de nuvem). 

### Mercado à Vista

Mercado Spot disponível em todos os três principais CSPs:

Instâncias spot da AWS

O GCP tem VMs preemptivas e spot

VMs de baixa prioridade do Azure, VMs sp

#### BENEFÍCIOS

Fornece capacidade “sobressalente” para venda com grandes descontos

Muitas limitações e restrições de uso

Pode ser retirado a qualquer momento em um prazo muito curto

Geralmente com preços 70-91% mais baixos do que as taxas sob demanda

Não é apropriado para todas as cargas de trabalho

#### LIMITAÇÕES

.s VMs podem ser recuperadas em 30 segundos ou 2 minutos.
.A equipe FinOps não pode implementar isso sozinha
.Desafie equipes e arquitetos a encontrar usos pontuais se você usar AWS. A economia de custos pode mudar o jogo se você conseguir lidar com a volatilidade
.Você pode anexar volumes EBS a instâncias spot e permitir que hibernem ou desativá-los com base em alterações de preço ou preempção
.Muitos mais usos significam que o desconto provavelmente diminuirá porque mais estão em uso “normal”

##### FORMULARIOS

Caixas de desenvolvimento, caixas de teste, testes, trabalhos de ciclo curto, tarefas sem estado
Cada vez mais serviços na AWS estão começando a permitir o uso do Spot (por exemplo, Sagemaker, ECS Fargate, etc.
Os aplicativos podem incluir Jenkins, coisas em lote e até K8s quando gerenciados corretamente

## Casos de negócios

### Nunca traga um caso de negócios para uma discussão.

Casos de negócios

Não gaste muito tempo em um caso de negócios até saber que esse tempo será valioso. A quantidade de dados necessários para construir um caso de negócio em torno de uma oportunidade pode ser enorme. Os casos de negócios devem: 


bala
Seja o mais simples, claro e conciso possível


bala
Tenha algo para todos (negócios, tecnologia, finanças)


bala
Use metas/metas mensuráveis, alcançáveis ​​e acionáveis


bala
Ser acordado antes de elaborar os detalhes

Cadência do Caso de Negócios

1

1
Reúna relatórios – Reúna as informações necessárias para concretizar a oportunidade.

2

2
Analisar  –  Avaliar os dados; veja as opções e diferentes parâmetros. Podem ser coisas como: quais termos usar para uma compra de RI, quais tipos de instância devem ser o foco de uma rodada de redimensionamento ou quais tipos de instâncias antigas são o foco da atualização. Descubra o que você deseja alcançar com a ação.

3

3
Documento –  Anote suas decisões, sua justificativa, seu processo de pensamento, aprovações, etc. e salve-os em um repositório apropriado para sua organização.


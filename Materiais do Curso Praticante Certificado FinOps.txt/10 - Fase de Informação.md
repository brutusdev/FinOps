# Fase de Informação

## Visão geral da fase de informação

## Recapitular

Lembre-se de que você está migrando para a nuvem e enfrentando desafios e oportunidades. Você montou uma equipe de FinOps para implementar os princípios de FinOps exercitando os recursos de FinOps. Você analisou as motivações das equipes da sua empresa e dominou os dados de faturamento na nuvem. Agora exercitaremos todas essas capacidades para compreender nosso uso e gastos na fase Informar.

## Fase de Informação:

Na fase Informar, criamos e usamos tags/rótulos, hierarquia de contas e outras taxonomias para alocar todos os custos e obter uma visão quase em tempo real do nosso uso atual da nuvem.

### A fase Informar apoia os princípios

Todos assumem a responsabilidade pelo uso da nuvem

Os relatórios FinOps devem ser acessíveis e oportunos

### Durante a fase de informação, esperamos ver

O que estamos usando e gastando?

É o que esperávamos?

Que valor ele está criando?

Quem é responsável pela sua utilização eficaz?

### A maioria dos recursos que usaremos para realizar a fase Informar estão nos domínios

Compreendendo o uso e o custo da nuvem

Tomada de decisões em tempo real

Acompanhamento de desempenho e benchmarking

## Comunicando

Trabalhe para estabelecer confiança nos números e reportar consistentemente dados de custos da nuvem em todos os grupos. Avalie os materiais de apresentação para o público, precisão, escopo, etc. Leve a sério todos os tipos de problemas de qualidade de dados.

### Relatórios: a interface do usuário do FinOps

Os relatórios e painéis criados para construir FinOps dentro de sua organização podem ser considerados a interface do usuário (IU) do FinOps. Esses relatórios costumam ser o que sua equipe vê ao interagir com os processos de FinOps. Ao analisar seus relatórios e painéis como sua UI, você pode aplicar décadas de pesquisa em um bom design de UI, aplicar práticas de DevOps para gerenciar seus relatórios e projetá-los levando em consideração a psicologia de como os usuários interagem com eles.

#### Criação de relatórios FinOps de qualidade

Diferencie os relatórios de produção dos recursos de reportagem ad hoc e investigativa - e trate-os como o software de produção que são

Priorize a consistência e a qualidade dos dados acima de tudo. Automatize relatórios importantes para evitar erros humanos e garantir entrega consistente

Faça relatórios específicos para as necessidades e motivação de cada pessoa

Forneça contexto: use KPIs em vez de números brutos

Edite sem piedade, simplifique e veja o que é realmente útil para seus usuários

#### Tipos de métricas de custo

Existem vários tipos de métricas de custo disponíveis para uso em relatórios, painéis e como parte de KPIs. Clique em cada cartão abaixo para virar e ver a definição.

##### Custo sob demanda

os preços de tabela declarados publicamente pelos fornecedores, antes de quaisquer descontos.

#### Tarifa com desconto

a tarifa pública descontada com alguns dos descontos disponíveis (nível gratuito, descontos baseados em compromisso, descontos de tarifas negociadas, descontos por uso prolongado).

#### Custo Amortizado  

O custo amortizado de um recurso leva em conta esse pagamento inicial e o distribui com base no uso, atribuindo o custo rateado para cada hora de faturamento.

#### Custo Totalmente Carregado  

São amortizados, refletem as taxas reais de desconto que uma empresa está pagando pelos recursos da nuvem, levam em consideração os custos compartilhados de forma equitativa e são mapeados de acordo com a estrutura organizacional da empresa. Em essência, eles mostram os custos reais da sua nuvem e o que os impulsiona.

#### Taxa não combinada

alguns recursos são cobrados em taxas decrescentes quanto mais você os usa. Isso significa que serão cobradas taxas diferentes pelos recursos à medida que você usar mais ou por períodos mais longos durante o mês. Ao examinar sua fatura, você pode ver que alguns custos de recursos são maiores que outros, mesmo para o mesmo tipo de recurso ou para um recurso idêntico. Quando as taxas são apresentadas desta forma, são chamadas de não combinadas.

#### Taxa combinada

a AWS fornece informações de taxa combinada em sua fatura, mostrando a taxa efetiva para um grupo de recursos com os mesmos atributos, onde alguns dos recursos recebem um desconto de reservas e outros não. Isto pode ajudar a eliminar os efeitos das reservas aplicadas aleatoriamente a recursos em múltiplas contas vinculadas, fornecendo uma taxa consistente para recursos específicos que seriam elegíveis para serem cobertos pela reserva ou pelo plano de poupança.

## Dados no Caminho do Engenheiro

### O Efeito Prius

Em um carro a gasolina normal, o feedback que você recebe sobre sua quilometragem fica atrasado. Você só consegue quando abastece, se pegar um recibo e fizer algumas contas. No Prius e em outros carros elétricos, o motorista recebe feedback instantâneo sobre quando está usando a energia do motor, usando gasolina ou quando está regenerando/carregando. Não há nenhuma luz no painel que diga “Dirija economicamente!” É apenas a inclinação natural dos condutores tentar permanecer na zona verde. Esse efeito permanecerá com você mesmo quando você dirigir em carros a gasolina logo após entrar no elétrico, mas desaparece lentamente. Isso não quer dizer que você não possa andar hiper rápido e potente em um veículo elétrico. Qualquer pessoa que já dirigiu um Tesla com potência total sabe disso. 

Há feedback contínuo sobre o uso do Prius (motor, gasolina ou recarga/carregamento). Portanto, quando precisar usar toda a potência à sua disposição você pode tomar uma decisão consciente de fazê-lo e o carro irá apoiá-la. Contudo, em circunstâncias normais, o feedback contínuo fornecido sobre a utilização tende a orientar um comportamento responsável. 

É semelhante com a nuvem. As equipes de FinOps devem se esforçar para fornecer feedback contínuo, simples e claro aos usuários da nuvem, para mantê-los operando de maneira econômica. As equipes de engenharia responsáveis ​​pelo uso da nuvem responderão às informações de custos e as usarão como uma métrica de eficiência, que é o que queremos. Nós nos referimos a isso como “Colocar dados no caminho do engenheiro”. Isso não funciona apenas para engenheiros, colocar uma boa UI na frente de qualquer uma de nossas partes interessadas faz uma grande diferença para manter a otimização da nuvem em mente  . É na fase Informar que a equipe de FinOps cria a transparência de dados que a organização precisa para executar com sucesso o ciclo de vida de FinOps.

## Detecção de anomalia

A detecção de anomalias é crucial para qualquer operação em nuvem. Além do monitoramento operacional e de segurança, o monitoramento de custos pode fornecer sinais de alerta precoce cruciais.

Anomalias ocorrerão. Sistemas de segurança, sistemas de desempenho e sistemas de gerenciamento de configuração detectarão anomalias no uso. As equipes de FinOps também devem escolher ferramentas para ajudar a detectar anomalias nos gastos. Vários métodos de alerta funcionam em diferentes cenários: alterações de gastos, alterações de gastos acima dos desvios padrão e verificação de cada categoria de alocação (por exemplo, US$ 500 de gastos extras podem não ser anômalos em uma fatura mensal de US$ 50.000, mas US$ 500 extras em minha fatura mensal de US$ 200 são). A variação percentual também pode ser um tipo de anomalia e, em alguns casos, gastos de qualquer tipo de serviço inesperado podem ser considerados uma anomalia. As definições de anomalias devem ser continuamente revisadas e refinadas para equilibrar alertas válidos e ruídos.

## avaliação comparativa

Na fase Informar, os benchmarks permitem ver o que está sendo usado, quanto custa e comparar com outros. Existem várias maneiras de avaliar:

#### Benchmarking geral de analistas Detalhes

Flexera, McKinsey, Gartner, IDC, etc.
Fornece algumas informações gerais sobre o estado da nuvem, o estado da adoção da nuvem, a migração para a nuvem, etc.

Provedores de nuvem	
Fornece benchmarking para empresas “como você” (às vezes isso não é fornecido)
Fundação FinOps: Estado do FinOps
Fornece benchmarks para algum uso da nuvem ( data.finops.org(abre em uma nova aba))
Grupo FinOps Slack
Fornece caminhos para conhecer outras pessoas e compilar comparações anedóticas com outras empresas dentro ou fora do seu setor
Benchmarking Interno
Fornece insights entre equipes da sua organização com perfis de uso semelhantes ou para KPIs independentes de tamanho
Benchmarking contra si mesmo
Fornece benchmarks úteis e consistentes ao longo do tempo, bem como um meio de comparar diferentes tipos de equipes


Ao fazer benchmark, trabalhe para desenvolver KPIs que façam sentido comparar entre si. É mais provável que você promova KPIs medidos. Os KPIs orientarão as prioridades – às vezes em detrimento de outras coisas que não estão sendo medidas. É importante selecionar KPIs claros e relevantes que promovam os benefícios relacionados. 

Você usará esses KPIs e pontuações na fase de otimização para utilizar tendências e realizar análises de variação. Você também avaliará o desempenho ao longo do tempo, pois isso é tão importante quanto os números. Além disso, certifique-se de salvar e avaliar consistentemente as tendências de comportamento.

Diferentes benchmarks medirão o desempenho de diferentes equipes. Perguntar se a equipe de FinOps está tendo um bom desempenho é uma questão muito diferente de saber se sua equipe de engenharia, arquitetura ou migração está tendo um bom desempenho.


### Exemplos

Tendência de custo/hora de cálculo: mede a equipe em relação a si mesma ao longo do tempo e compara com qualquer equipe

Taxa de cobertura de uso de computação consistente: mede o desempenho da equipe FinOps na compra de descontos baseados em compromisso

Tendência de economia/custo total recomendada para otimização: Poderia medir cada equipe ou a equipe de arquitetura para trazer arquiteturas mais escaláveis ​​ou usar spot

Certifique-se de não exagerar. Você não pode comparar com outras pessoas até entender seu uso e ter uma linguagem comum para se comunicar (FinOps). 

## Alocação de custos

A alocação de custos (ou atribuição de custos) é a coisa mais importante que você fará como alguém envolvido em FinOps. Para que qualquer pessoa na organização cumpra o princípio: “Todos são responsáveis ​​pela sua utilização da nuvem”, deve saber quanto está a gastar. Além disso, para saber que valor obtemos com os gastos, devemos ser capazes de identificar os custos associados à entrega desse valor. Realizamos a alocação de custos para que possamos produzir esses relatórios para os usuários da nuvem. Esse relatório geralmente é de dois tipos: showback ou estorno. 

### egresso

Os relatórios Showback são relatórios que usam mecanismos de alocação de custos para mostrar à equipe o que ela está usando e gastando.

Showback.png
Esses relatórios podem ser feitos em qualquer nível (o que gastamos em computação em todos os aplicativos, o que gastamos em armazenamento dentro deste microsserviço, o que gastamos em rede apenas no Azure, etc.)

Esses relatórios não são mutuamente exclusivos

Eles são projetados para serem informativos e úteis para que os usuários da nuvem entendam o uso e tomem ações para serem responsáveis ​​por sua eficiência e eficácia.

Eles não são inseridos em um sistema de contabilidade ou razão geral. Em vez disso, são informativos e concebidos para promover a transparência e impulsionar o comportamento.

### Estorno

Os relatórios de estorno são fornecidos ao sistema de contabilidade e aplicados a um orçamento oficial que a organização está monitorando.

Esses relatórios são criados para um P&L específico ou proprietário de orçamento
Eles provavelmente são mutuamente exclusivos (somando todos eles você terá todos os seus gastos na nuvem)

Eles são projetados para criar débitos em relação aos orçamentos estabelecidos no sistema contábil

Estorno SM@2x.png
Os relatórios de estorno podem ser exatamente o mesmo relatório de showback, mas são relatórios de orçamento oficial. Você pode ter versões menos maduras e mais maduras de cada um (talvez seus relatórios tenham custos compartilhados, talvez tenham taxas combinadas, talvez tenham alocações indiretas, talvez não). Por serem semelhantes, podem ser produzidos de forma semelhante, mas é provável que você faça showback para mais grupos.

Os relatórios de estorno enfrentarão muito mais escrutínio. Fazer alterações nos encargos do sistema contábil pode ser difícil ou exigir documentação. Particularmente, as cobranças compartilhadas fora do controle do proprietário do P&L enfrentarão mais escrutínio. Algumas organizações exigem testes de conformidade do SOC para relatórios de estorno. Você desejará salvar e preservar seus relatórios de estorno mais do que os relatórios de showback, que podem ter vida mais curta. Isso pode afetar as ferramentas ou o processo que você usa. 

## Por que escolher um modelo

### Comece o orçamento centralmente

As empresas que adotam a nuvem lentamente podem começar a orçamentar a “nuvem” centralmente

É mais fácil

Não se sabe como os custos serão divididos inicialmente

Permite flexibilidade e inovação, especialmente durante a fase de “projeto de feira de ciências”

### Showback/Estorno

Showback/Estorno vem mais tarde com

Mais itens de custo compartilhado e complexidade no ambiente de nuvem

Melhor previsibilidade

Mais escala tornando os custos da nuvem materiais

### Custos de registro de estorno quando...

O estorno registra custos no sistema contábil quando:

É necessário 

Multinacionais com tratamento tributário diferenciado

Multiunidades de negócios que desejam manter unidades muito separadas (por exemplo, altas fusões e aquisições)

Requisitos altamente regulamentados ou governamentais

Tem que levar em conta as alterações após o fato (os dados de faturamento às vezes aparecem tarde)

Isso é mais complexo operacionalmente para equipes financeiras/contábeis

### Historicamente

O estorno normalmente não pode ser feito na TI tradicional do data center. Os custos irrecuperáveis ​​raramente são cobrados ou rastreados para uso eficiente. O dinheiro já estava fora do controle do proprietário do P&L e não mudava mês a mês. Se o estorno estava sendo feito, provavelmente foi feito apenas no sistema de contabilidade e não nos relatórios mostrados para aqueles que realmente trabalham nos aplicativos.

Ao contrário do data center, o custo da nuvem pode mudar e ser rastreado com mais facilidade e deve ser gerenciado diariamente. Idealmente, todos os custos diretos e indiretos deveriam ser alocados ao orçamento do centro de custo para eles.

### Gerenciando Custos Compartilhados

Tente não dividir os custos compartilhados, a menos que seja necessário. Se você tiver que dividir os custos compartilhados, faça-o da maneira mais simples e viável para sua organização.

#### Gerenciando o compartilhamento de custos

##### Orçamento centralizado 

Faça um orçamento centralizado e pague pelos custos compartilhados sem dividir (trapaça aqui, mas esta é a maneira mais fácil)
Fazemos um orçamento para serviços de segurança e conformidade separadamente. Você, como proprietário de P&L, não se preocupe com eles

##### Distribuição fixa ou uniforme

Crie uma tabela rápida de quanto do total cada orçamento vai pagar
O produto SaaS pagará 80% dos custos de segurança e conformidade, e os outros dois grupos de P&L pagarão 10% cada

###### Proporcional

O custo é dividido com base nos gastos de cada orçamento em algum outro item
Dividiremos o custo do suporte empresarial com base no gasto total em suas contas alocadas diretamente naquele mês. Você obterá a proporção que seu gasto total representa

##### Alocação Direta

O custo é alocado com base no rastreamento do uso de alguns outros dados que não são da conta da nuvem
Extrairemos as informações do cluster Kubernetes que podem identificar quais pods estão sendo executados por qual aplicativo e calcularemos o total de recursos alocados por pod, depois o total por aplicativo e, em seguida, calcularemos o custo total do ambiente, alocaremos esse custo para cada aplicativo e alocar custos diretamente ao resultado de cada aplicação. Além disso, teremos que distribuir uma porcentagem do ambiente de contêiner vago/não utilizado e distribuiremos isso proporcionalmente ao uso dos recursos gerais do contêiner.

### Recursos

#### Alocação de custos:

Alocação de Custos é o conjunto de práticas para dividir uma fatura ou fatura consolidada entre os responsáveis ​​pelos seus diversos componentes. No contexto de FinOps, isso normalmente envolve a divisão de faturas consolidadas do provedor de serviços de nuvem entre vários grupos de TI que usam a nuvem dentro da organização.

#### Análise de dados e demonstração

Análise de dados e showback é a capacidade de aproveitar dados, juntamente com metadados sobre recursos de nuvem e hierarquias de recursos, para criar um mecanismo de relatório quase “em tempo real” para as partes interessadas que chama a atenção: custos totais para a entidade comercial desejada, oportunidades para evitar custos e KPIs para saúde financeira (por exemplo, desempenho de compromissos de redução de taxas, medidas de custo unitário para serviços-chave, métricas de eficiência agregadas por “equipe” desejada, unidade organizacional, etc…).

#### Alocação justa de custos em uma plataforma compartilhada

Este artigo fornece uma visão geral da configuração, dos objetivos e da história da alocação justa de custos em uma plataforma compartilhada.

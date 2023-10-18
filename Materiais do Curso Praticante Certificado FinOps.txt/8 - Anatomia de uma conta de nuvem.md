# Anatomia de uma conta de nuvem

Lembre-se de que você está migrando para a nuvem e enfrentando desafios e oportunidades. Sua equipe de FinOps está pronta para executar os recursos que permitirão que você atinja os objetivos dos princípios de FinOps. Um dos maiores desafios que você enfrentará é algo específico da nuvem: a enorme quantidade de informações apresentadas na fatura da nuvem.

## Níveis de uso da nuvem e informações de custo

Parte do motivo pelo qual FinOps pode ser tão desafiador é a quantidade de dados que as equipes de FinOps precisam gerenciar para relatar o uso, encontrar otimizações e agir de acordo com elas em um ciclo rápido. 

### Dados resumidos da fatura

–
Dados resumidos da fatura no nível da conta de gerenciamento, inscrição ou cobrança

Uso resumido para toda a sua organização

Pode ser dividido por nome de serviço

Pode ou não incluir descontos 

Várias páginas cobrindo um valor ilimitado de gastos, entregues uma vez por mês após o fato

### Ferramentas de relatórios de uso e custos

–
Plataforma de relatórios de uso e custos fornecida pelo provedor de nuvem (ou por terceiros ou que você cria)

Uso reportável com mais flexibilidade

Pode ou não incluir taxas específicas, metadados e informações de resumo

Ferramenta do tipo Business Intelligence para criação de relatórios personalizados, disponíveis a qualquer momento

### Dados detalhados de uso e cobrança

–
Dados detalhados de custo e uso por meio de arquivo CUR ou APIs de cobrança

Informações detalhadas de uso com granularidade total

Conjuntos de dados extremamente grandes, até bilhões de linhas de dados por mês, entregues todos os dias

## Nível da fatura

As faturas são para cobrança, não para FinOps. Este é um exemplo de relatório de fatura produzido por um provedor de nuvem. Ele resume centenas de milhares de dólares, agregados por serviço, com poucos detalhes. São poucos dados para gerenciar com eficácia o custo ou o uso. No entanto, arquivos CUR, extratos de cobrança e APIs de cobrança fornecem uma quantidade muitas vezes esmagadora de dados.

É crucial encontrar as ferramentas certas que lhe permitam obter os dados necessários com o nível de detalhe certo para o seu nível de maturidade para tomar as decisões em tempo real que você precisa.

## Plataformas de gerenciamento de custos em nuvem

Os provedores de nuvem oferecem ferramentas para ver mais granularidade. Essas ferramentas geralmente fornecem uma maneira básica de analisar os dados. Essas ferramentas estão sempre avançando e se tornando mais flexíveis e detalhadas.

### AWS

AWS tem o processo de faturamento mais maduro

Mesmo assim, a fatura e o CUR vêm de sistemas diferentes, raramente correspondem 100% ao centavo

Em constante evolução

CUR é o formato de fatura de terceira geração

CUR alimentado por equipes de serviço individuais, também não totalmente consistente internamente

### Azure

Faturas mensais ou trimestrais, dependendo da relação contratual

Os dados de faturamento por meio de APIs de faturamento pré-2020 não incluem custos de lista, amortização de pagamentos antecipados, custos de RI pré-pagos, informações específicas de recursos (conjuntos de escala, por exemplo),  

Dados de utilização disponíveis no Azure Monitor

Ferramentas/plataformas internas avançadas significativas para relatórios

### GPC

Mais resumido dos três, porém menos maduro

As informações no nível do recurso não estão facilmente disponíveis, a exportação de faturamento é resumida no nível do SKU

## Custo e uso detalhados

Há muita linguagem nova introduzida no uso da nuvem e nos dados de faturamento, e precisamos saber como lidar com isso. Os provedores de nuvem geralmente fornecem dados de faturamento todos os dias; é importante entender como está chegando o faturamento e como entender as informações. 

### Os dados brutos da nuvem não são legíveis por humanos. 

As contas da nuvem podem chegar a centenas de milhões ou bilhões de linhas de dados.

A AWS divide seu arquivo CUR mensal em dezenas de arquivos no bucket S3 onde eles são armazenados, de modo que cada arquivo seja menor que o limite máximo de tamanho de arquivo em algumas máquinas. Portanto, o CUR nem pode ser carregado de uma só vez no Excel. É muito grande.

O Azure e o GCP fornecem dados por meio de uma API, que permite mais controle sobre o tamanho do conjunto de dados e como ele é resumido. No entanto, esses serviços também possuem várias APIs.

### Os dados de cobrança contêm os detalhes sobre cada item cobrado.

Os dados de faturamento contêm atributos sobre as cobranças (metadados ou dimensões), como região ou ID da instância ou o tempo de execução, as tags, a descrição, o tamanho, etc. 

As métricas incluem o tempo de execução ou a quantidade de uso e a(s) taxa(s).

Várias taxas podem ser cotadas, taxas combinadas, taxas não combinadas, taxas amortizadas, etc. 

### Uma máquina virtual pode ser cobrada com diversas taxas. 

Parte do tempo de uma máquina virtual pode ser coberta por reservas e parte sob demanda.

Cada combinação de “taxa x uso” ou “taxa x tempo” será uma linha separada.

Alguns serviços também incluem muitos tipos de cobranças/medidores – uso, armazenamento, iops, unidades de leitura/gravação, transferência de dados, etc. 

#### Esses arquivos e APIs são documentados de maneira imperfeita e mudam com frequência.

Eles podem entrar em muitas equipes que despejam dados na discussão de dados de faturamento, se for útil.

Eles podem abordar a questão de a qualidade dos dados ser um problema a ser gerenciado se você criar suas próprias consultas.

Eles podem fazer melhorias contínuas nesta área por parte de todos os fornecedores.

## Fundamentos de dados de faturamento na nuvem

No nível básico, cada item possui um tempo ou número de uso e uma taxa. Multiplicamos isso para obter o custo. Todo o resto são detalhes (muitos detalhes). Se você quiser alterar o custo por conta própria, existem duas alavancas principais:

Altere quanto você usa (descentralizado)
Alterar a taxa que você paga (centralizada)
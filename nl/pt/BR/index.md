---

 

copyright:

  years: 2015, 2018

lastupdated: "2018-01-19" 

---


{:shortdesc: .shortdesc} 
{:new_window: target="_blank"}

# O que há de novo no {{site.data.keyword.Bluemix_notm}}
{: #whatsnew}

Mantenha-se atualizado com os novos recursos e serviços que estão disponíveis no {{site.data.keyword.Bluemix}}, para que você aproveite ao máximo sua experiência com o {{site.data.keyword.Bluemix_notm}}. As atualizações são organizadas nestas categorias: [Plataforma do {{site.data.keyword.Bluemix_notm}}](index.html#platform_category), [{{site.data.keyword.Bluemix_local_notm}}, {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal), [Cálculo](index.html#compute_category) e [Serviços](index.html#services_category).
{:shortdesc}

## Plataforma {{site.data.keyword.Bluemix_notm}}
{: #platform_category}

### A região Leste dos EUA do {{site.data.keyword.Bluemix_notm}} Foundry Service agora está disponível
Novo a partir de: 15 de dezembro de 2017

Um novo datacenter Leste dos EUA agora está disponível em Washington, DC. Essa nova região pode ser acessada usando o terminal `us-east.bluemix.net`. Para obter detalhes sobre os serviços disponíveis para compra nessa nova região, consulte [Serviços por região](/docs/services/services_region.html#services_region).

### Suporte para recursos na União Europeia
Novo a partir de: 14 de dezembro de 2017

Se seus serviços e data centers estão localizados na Europa, o {{site.data.keyword.Bluemix_notm}} agora oferece recursos adicionais para proteger seus dados na União Europeia. É possível solicitar suporte a ser fornecido pelas equipes de sucesso do cliente que estão localizadas na Europa. Esse suporte está disponível 24 horas por dia, 7 dias por semana. Consulte [Ativando a opção Suportado pela União Europeia](/docs/pricing/eusupported.html#bill_eusupported) e [Solicitando suporte para recursos na União Europeia](/docs/support/index.html#eusupported) para obter mais informações.

### Retirada de suporte para o TLS 1.0 e 1.1
Novo a partir de: 28 de novembro de 2017

Em 1º de março de 2018, o {{site.data.keyword.Bluemix_notm}} irá retirar o suporte para o TLS 1.0 e o TLS 1.1 em muitos dos nossos produtos e serviços de nuvem como parte do nosso compromisso de oferecer uma nuvem que seja segura para o núcleo e em alinhamento com as melhores práticas do segmento de mercado para segurança e privacidade de dados. Para saber mais sobre como essa mudança afeta você e quais ações você pode precisar tomar, consulte [Retirada de suporte para o TLS 1.0 e 1.1](/docs/troubleshoot/appsectls.html).

### Uma nova maneira de organizar recursos em sua conta
Novo a partir de: 16 de novembro de 2017

Os grupos de recursos são uma nova maneira de criar agrupamentos customizáveis de recursos da conta e o acesso ao grupo e aos recursos dentro dele é gerenciado usando o Identity and Access Management (IAM). Todo mundo começa com um grupo de recursos padrão. É possível renomear esse grupo de recursos e incluir novas instâncias de serviço à medida que você as cria do catálogo. 

Para usuários com uma conta pay-as-you-go ou de assinatura, é possível criar grupos de recursos adicionais para tornar o uso do gerenciamento de cotas e da visualização de faturamento para um conjunto de recursos mais fácil. Também é possível agrupar recursos para tornar mais fácil para você designar o acesso de usuários a mais de um serviço por vez. Para saber mais sobre como trabalhar com grupos de recursos para sua conta, consulte [Gerenciando grupos de recursos](/docs/admin/resourcegroups.html#rgs).

### Atualizações para o {{site.data.keyword.Bluemix_notm}} IAM
Novo a partir de: 16 de novembro de 2017

A introdução de [grupos de recursos](/docs/overview/resource-groups.html#whatis) em sua conta do {{site.data.keyword.Bluemix_notm}} abriu uma nova maneira de designar acesso. Usuários e IDs de serviço podem ter acesso designado a todos os serviços em um grupo de recursos permitindo designar rapidamente acesso a mais de um recurso por vez. Também é possível customizar o acesso para cada usuário ou ID de serviço designando o acesso apenas para alguns serviços em um grupo de recursos ou você apenas opta por designar acesso aos recursos individuais até o nível da instância de serviço.
 
Para obter mais informações sobre os recursos que você pode aproveitar usando o IAM, consulte [Quais recursos o IAM fornece?](/docs/iam/index.html#features)

### Customizar sua visualização de painel 
Novo a partir de: 16 de novembro de 2017

É possível visualizar e gerenciar todos os recursos em sua conta em seu painel no console do {{site.data.keyword.Bluemix_notm}}. E agora é possível configurar filtros para customizar sua visualização. Por exemplo, é possível filtrar por grupo de recursos para visualizar os recursos específicos em um grupo de recursos. Também é possível filtrar por região ou espaço do Cloud Foundry. Para obter mais detalhes, consulte [Gerenciando recursos no painel](/docs/overview/ui.html#dashboardview).


### Centro de suporte
Novo a partir de: 2 de novembro de 2017

Agora temos o novo Centro de Suporte, onde é possível procurar por informações, postar perguntas em nossa comunidade do desenvolvedor e gerenciar chamados. Acesse **Suporte > Centro de Suporte** na barra de menus do console do {{site.data.keyword.Bluemix_notm}}. 

### Introdução ao IBM Cloud
Novo a partir de: 31 de outubro de 2017

O Bluemix agora é IBM Cloud. Exceto pelo lançamento de nosso novo nome, nada mudou. Ainda é possível construir e executar facilmente seus aplicativos e serviços, como sempre. Veja o [IBM Cloud Blog](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais detalhes.

### Conta Lite
Novo a partir de: 31 de outubro de 2017

Uma conta Lite é nosso novo tipo conta, que fornece acesso para experimentar serviços grátis selecionados sem restrições de tempo. Essa nova conta também inclui rastreamento de uso e recursos de eficiência para ajudá-lo a gerenciar melhor seus recursos. Para saber mais sobre o que está disponível, consulte [Tipos de conta](/docs/pricing/index.html#liteaccount).

### Recurso de autenticação do aplicativo Identity and Access Management
Novo a partir de: 6 de outubro de 2017

O Identity and Access Management (IAM) agora fornece a capacidade de criar um ID de Serviço, que pode ser considerado uma identidade que pode ser usada para que os aplicativos sejam autenticados com seus serviços do {{site.data.keyword.Bluemix_notm}}. Em vez de usar as credenciais individuais do usuário, um ID de Serviço pode ser criado com uma chave API associada e permissões de acesso na forma de uma política de serviço que é designada ao ID de Serviço para que você controle o nível de acesso para qualquer aplicativo que se autentica com esse ID.

Para obter mais informações sobre os benefícios desse recurso e como começar a usá-lo, consulte [Apresentando IDs de serviço e chaves API do IBM Cloud IAM](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). 

### Catálogo global do {{site.data.keyword.Bluemix_notm}} 
Novo a partir de: 27 de julho de 2017

Expandindo a última atualização do console para gerenciar suas regiões públicas de um único local no console, o {{site.data.keyword.Bluemix_notm}} agora tem um catálogo global que torna o processo de seleção e implementação de itens selecionados no catálogo um processo mais simplificado. Independentemente da região que você selecionou no console, agora é possível ver todos os serviços que estão disponíveis em todas as regiões públicas de seu catálogo. Depois de selecionar um ladrilho do catálogo, é possível ver em quais regiões o serviço está disponível e selecionar onde você deseja implementá-lo.

Para obter mais informações sobre as atualizações mais recentes para o catálogo, consulte [Um catálogo global do {{site.data.keyword.Bluemix_notm}} torna a construção de coisas mais fácil](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Atualizações do console do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 23 de maio de 2017

Agora é possível gerenciar suas regiões públicas de um único local por meio do console atualizado do {{site.data.keyword.Bluemix_notm}}. O seletor de região oferece acesso simplificado aos seus recursos, e outros aprimoramentos incluem maior disponibilidade e desempenho aprimorado.

Para obter mais informações sobre essa atualização, consulte [Nova UI global do Bluemix para maior disponibilidade e mais](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Identidade e gerenciamento de acesso
Novo a partir de: 01 de maio de 2017

Com as atualizações e melhorias mais recentes, proprietários ou administradores de contas do {{site.data.keyword.Bluemix_notm}} agora podem usar uma nova UI de controle de acesso unificado para aproveitar os recursos a seguir:
 * Gerenciar o acesso de baixa granularidade de usuários aos serviços do Kubernetes e a outros serviços à medida que eles adotam os novos recursos de controle de acesso
 * Designar políticas de serviço e funções do Cloud Foundry para os usuários dentro de suas organizações

Além disso, os usuários da plataforma {{site.data.keyword.Bluemix_notm}} podem criar, excluir e listar chaves API associadas aos seus IDs de usuário. E os usuários da plataforma podem usar essas chaves API para se autenticar ao usar as APIs ou CLIs.

Por último, aprimoramos a nossa capacidade de gerenciamento de usuários unificado para assegurar que em uma conta IaaS-PaaS vinculada, os usuários sejam gerenciados de uma maneira unificada, sem precisar incluir usuários separadamente no Portal do cliente SoftLayer ou no console do {{site.data.keyword.Bluemix_notm}}.

Para obter mais informações sobre a atualização recente, verifique a postagem do blog [Introdução ao Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Mudanças de design de navegação para docs do {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 13 de abril de 2017

Com essa atualização de navegação, achamos que você entenderá melhor como o conteúdo é organizado em todos os nossos docs e será capaz de localizar o conteúdo relevante de forma mais eficiente. Com menos camadas aninhadas de conteúdo, você não precisará procurar muito para encontrar a documentação necessária para ser bem-sucedido no {{site.data.keyword.Bluemix_notm}}.


## {{site.data.keyword.Bluemix_local_notm}} e {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### Atualizações de dezembro para o console de administração
{: #decemberadminconsole}
Novo a partir de: 14 de dezembro de 2017

Com as atualizações e melhorias mais recentes de dezembro, é possível usar os novos recursos a seguir:

#### Assinar notificações para o limite de uso médio de CPU

A média de CPU foi incluída como um tipo de limite em assinaturas de notificação. Agora é possível receber notificações quando o uso da CPU (média em todas as Células de DEA e Diego) fica acima ou abaixo de um determinado limite.

#### Controlar o acesso a sistemas em nuvem na União Europeia 

Combinado com o novo recurso na União Europeia para suportar recursos em nuvem (iniciando com Frankfurt), o console de administração agora tem a capacidade de definir políticas que controlam o acesso de funcionários IBM. É possível gerenciar políticas de controle de acesso, visualizar solicitações de acesso, agir sobre as solicitações e controlar o histórico.
  
#### Informações aprimoradas em relatórios de segurança

Os relatórios de segurança agora incluem nomes fáceis e simples, além de IDs exclusivos para usuários e organizações.

### Atualizações de agosto para o console de administração
{: #augustadminconsole}
Novo a partir de: 31 de agosto de 2017

Com as atualizações e melhorias mais recentes de agosto, é possível usar os novos recursos a seguir:

#### Atualizações para métricas de uso de serviço do {{site.data.keyword.cloudant_short_notm}}

  * O cálculo de métricas de uso para o {{site.data.keyword.cloudant_short_notm}} foi atualizado para refletir a quantidade total de GBs usados e disponíveis em todos os nós em um cluster do {{site.data.keyword.cloudant_short_notm}}. Normalmente, um cluster do {{site.data.keyword.cloudant_short_notm}} contém 3 nós e um documento no banco de dados é replicado entre todos os nós no cluster para alta disponibilidade e recuperação de desastre. Com as atualizações de agosto, a métrica de capacidade na discagem do {{site.data.keyword.cloudant_short_notm}} (disponível na visualização _Uso de Recurso > Serviços_) indica o espaço entre todos os nós no cluster. Por exemplo, se um único cluster do {{site.data.keyword.cloudant_short_notm}} contiver 3 nós, cada um com 1000 GB de capacidade, o limite de capacidade será 3000 GB. Se 1500 GBs de capacidade forem usados, a métrica de uso do {{site.data.keyword.cloudant_short_notm}} será 50%.

#### Atualizações no planejamento de atualizações de manutenção
  
  * No {{site.data.keyword.Bluemix_dedicated_notm}}, os clientes podem gerenciar as datas e horas em que seus ambientes dedicados estão disponíveis para implementação de atualizações do sistema. Os clientes podem definir janelas de disponibilidade que representam datas e horas em que as atualizações de manutenção podem e não podem ser implementadas em seu ambiente Dedicado. Na atualização de agosto, _Janelas de atualização disponíveis_ foi renomeado para _Janelas de atualização_ e _Janelas de atualização indisponíveis_ foi renomeado para _Janelas de blecaute_. Além das mudanças de terminologia, os clientes agora têm mais flexibilidade e margem para definir as datas de blecaute (indisponível). Quando solicitadas, as datas de blecaute exigirão aprovação da IBM e o tempo que leva para obter aprovação irá variar. Quando as datas de blecaute solicitadas forem aprovadas, a IBM irá cancelar quaisquer atualizações existentes que estão atualmente planejadas durante a janela indisponível. A IBM também irá criar novos registros para essas atualizações e irá planejá-las fora das datas de blecaute aprovadas.
  
Consulte o [vídeo de demonstração](https://bit.ly/2eCQNvu){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais informações.

### Atualizações de julho para o console de administração
{: #julyadminconsole}
Novo a partir de: 31 de julho de 2017

Com as atualizações e melhorias mais recentes de julho, é possível usar os novos recursos a seguir:

#### Atualizações para recursos de histórico de uso de recurso

  * Na atualização anterior (junho), a visualização Histórico para uso de memória e disco havia apresentado exibição de dados de uso nas últimas 48 horas, 30 dias e 5 meses. Nessa última atualização de julho, a funcionalidade de histórico de uso do recurso foi expandida para permitir a customização da amplitude de tempo para a qual mostrar dados de uso do recurso. Visualizações por hora, diárias e mensais permanecem, mas os usuários agora podem especificar um dia/hora de início e a duração para a qual exibir as métricas de uso de memória e disco (por exemplo, mostrando o uso de memória por 15 dias a partir de 1º de julho de 2017).
  * Um novo comando da CLI foi introduzido para exibir o histórico de métricas de recursos na CLI. Os parâmetros do comando, bem como exemplos de uso podem ser localizados digitando o seguinte: `_cf ba resource-metrics-history -help_`
 
Consulte o [vídeo de demonstração](https://youtu.be/QBij0jB5qAk){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais informações.

### Atualizações de junho para o console de administração
{: #mayadminconsole}
Novo a partir de: 26 de junho de 2017

Com as atualizações e melhorias mais recentes de junho, é possível usar os novos recursos a seguir:

#### Atualizações na página de uso do recurso

  * Recursos do sistema
    * A visualização Histórico para memória e disco foi atualizada para exibir dados de mais de 48 horas, 30 dias e 5 horas
    * Um link Saiba Mais é fornecido, mostrando como a API de métricas do console de administração é usada para gerar as visualizações Histórico 
  * Aplicativos
    * Fornece informações de uso para todos os aplicativos no ambiente
    * Classifique por nome do aplicativo, memória física, memória reservada, disco físico, disco reservado, CPU física ou nome da organização 
    * A procura é fornecida para filtrar resultados pelo nome do aplicativo e nome da organização
    * Um link Saiba Mais é fornecido, mostrando como a API de métricas do console de administração é usada para gerar a visualização Aplicativos
 
Consulte [Uso de recurso](/docs/hybrid/index.html#resourceusage) para obter mais informações.

#### Atualizações de API para métricas

  * Foram incluídas estatísticas de ambiente, fornecendo médias por dia ou mês para consumo de memória e de disco
  
Consulte [API para métricas](/docs/hybrid/index.html#envappmetricsapi) para obter mais informações.


### Atualizações de maio para o console de administração
{: #mayadminconsole}
Novo a partir de: 30 de maio de 2017

Com as atualizações e melhorias mais recentes de maio, é possível usar os novos recursos a seguir:

 * Melhorias na página Status incluindo diagnósticos mais granulares sobre incidentes que afetam a plataforma e os tempos de execução do {{site.data.keyword.Bluemix_notm}}.
 * Melhorias na página Relatórios e logs de segurança:
   * Os relatórios agora são exibidos em um formato de tabela, simplificando a navegação e procura de relatórios, incluindo a capacidade de classificar por categoria do relatório, nome do arquivo ou data de criação. 
   * Filtragem aprimorada, incluindo filtragem simultânea de múltiplas categorias 
   * Modo de tela cheia para exibir o conteúdo de um relatório
   * Capacidade de excluir relatórios para usuários administrativos com a permissão de "gravação de relatório"
   * Exibição mais rápida de listas de relatório, carregando progressivamente on demand por meio de rolagem contínua, resultando em melhor desempenho geral.
 * Os relatórios de segurança podem ser solicitados on demand dentro de um intervalo de tempo que se estende até uma semana e inicia no máximo 3 meses atrás a partir do horário da solicitação. Observe que é necessária uma configuração específica de ambiente antes que essa capacidade esteja disponível para usuários administrativos. Os usuários administrativos precisarão da permissão de "gravação de relatório" para esse recurso.

### Atualizações de abril para o console de administração
{: #apriladminconsole}
Novo a partir de: 2 de maio de 2017

Com as atualizações e melhorias mais recentes de abril, é possível usar os novos recursos a seguir:

 * O status do aplicativo recém projetado para ambientes Dedicado e Local do {{site.data.keyword.Bluemix_notm}}. É possível procurar rapidamente por nome de componente ou data de postagem. Também é possível alternar entre a visualização de posts de status do componente e as notificações específicas para seu ambiente. Consulte a postagem do blog [Nova Página de Status do {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais informações.
 * Dados de uso de serviço para selecionar serviços no ladrilho Uso de Recursos. Consulte [Detalhes de uso do serviço](/docs/hybrid/index.html#servicesresourceusage) para obter mais informações sobre quais serviços são suportados e o que você pode esperar da nova visualização.

## Computação
{: #compute_category}

### Atualizações mais recentes para buildpacks

Visite as páginas a seguir para obter uma lista acumulativa das atualizações mais recentes:

* [Atualizações mais recentes para o buildpack do SDK for Nodejs](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Atualizações mais recentes para o buildpack do Liberty ](/docs/runtimes/liberty/updates.html#latest_updates)
* [Atualizações mais recentes para o buildpack do ASP.NET Core](/docs/runtimes/dotnet/updates.html#latest_updates)
* [Atualizações mais recentes para o buildpack do IBM XPages for {{site.data.keyword.Bluemix_notm}}](/docs/starters/xpages/index.html#updates)

### Atualizações mais recentes do {{site.data.keyword.containerlong_notm}}

O {{site.data.keyword.containerlong_notm}} lançou sua arquitetura do Kubernetes em maio de 2017. A arquitetura anterior para grupos de contêineres únicos e escaláveis agora estará [totalmente descontinuada a partir de 5 de dezembro de 2017](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").  

[Consulte a documentação para obter informações sobre como iniciar a utilização do ambiente nativo do Kubernetes no {{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html). Se você tiver perguntas, será possível postá-las no Slack em https://ibm-container-service.slack.com/.

### Novo buildpack do Liberty for Java v3.11
Novo a partir de: 17 de julho de 2017

O buildpack do Liberty v3.11 fornece uma nova versão de runtime mensal do Liberty e contém outras melhorias. A versão de runtime mensal do Liberty foi atualizada para a liberação [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/). O IBM JDK foi atualizado para as versões 8.0.4.7 e 7.1.4.5. O buildpack também fornece versões atualizadas do utilitário App Management e do agente Auto-scaling. A biblioteca Cloudant padrão é agora a [java-cloudant](https://github.com/cloudant/java-cloudant) padrão, a [biblioteca Ektorp](https://github.com/helun/Ektorp) ainda está disponível como uma opção, para obter detalhes sobre essa mudança, veja a [postagem do blog](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/). A razão de tamanho de heap padrão agora é de 50% quando seu aplicativo tem menos de 512 MB de memória, se ele tiver mais de 512 MB será de 75%. Agora um novo log de tarefa de preparação foi gerado, que permite a depuração mais fácil de erros de preparação. Consulte a documentação [atualizações mais recentes](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html) para obter informações adicionais.

### Novo buildpack do Liberty for Java v3.10
Novo a partir de: 12 de junho de 2017

O buildpack do Liberty v3.10 fornece novas versões de runtime trimestrais e mensais do Liberty e contém outras melhorias. A versão de runtime padrão do Liberty foi atualizada para 17.0.0.2. A versão de runtime mensal do Liberty foi atualizada para a liberação [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). O buildpack também fornece versões atualizadas do utilitário App Management e do Extreme Scale Client. Veja a documentação de [atualizações mais recentes](/docs/runtimes/liberty/updates.html) para obter informações adicionais.

### Novo buildpack do SDK for Node.js v3.12
Novo a partir de: 16 de maio de 2017

O buildpack v3.12 do SDK for Node.js fornece as versões 0.12.17, 0.12.18, 4.8.0, 4.8.2, 6.10.0 e 6.10.2 do IBM SDK for Node.js. O padrão mudou da 4.x mais recente para a 6.x mais recente, portanto, ele atualmente é 6.10.2. Sendo uma mudança de versão principal, isso poderia afetar apps que estão contando com o padrão. Consulte [Suporte de longo prazo da versão do Node.js e o buildpack do SDK for Node.js](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais informações sobre como evitar quaisquer problemas.

Além dos novos tempos de execução, esta liberação contém uma correção de bug do buildpack de um problema com o manipulador do App Management Health Center e o Node.js versões 6.9.5 e 6.10.0.

### Novo buildpack do Liberty for Java v3.9
Novo a partir de: 27 de abril de 2017

O buildpack do Liberty v3.9 fornece uma nova versão de runtime mensal do Liberty e contém outras melhorias. A versão de runtime padrão do Liberty foi atualizada para incluir as iFixes PI77770, PI77605, IFPI77438 e IFPI79275. A versão de runtime mensal do Liberty foi atualizada para a liberação [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). O cálculo de memória foi movido de preparação para o processo de início, permitindo mudanças mais fáceis de memória heap com a reinicialização de um aplicativo. O buildpack também fornece versões atualizadas do agente de serviço Auto-Scaling e do Extreme Scale Client. Veja a documentação de [atualizações mais recentes](/docs/runtimes/liberty/updates.html) para obter informações adicionais.

## Serviços
{: #services_category}

### {{site.data.keyword.containershort_notm}}: suporte ao Kubernetes 1.8.x
Novo a partir de: 19 de janeiro de 2018

Desde novembro de 2017 o {{site.data.keyword.containershort_notm}} tem suportado o Kubernetes `1.8.x`. Estamos orgulhosos de anunciar que a nossa versão padrão do Kubernetes agora é `1.8.6`. No futuro próximo, forneceremos suporte para `1.9.x`.

### Watson Discovery Visual Insights
Novo a partir de: 30 de novembro de 2017

Explore visualmente conexões desenvolvidas com o entendimento do {{site.data.keyword.discoveryshort}} de elementos semânticos detectados no texto, como entidades, relacionamentos, conceitos e mais.

Comece explorando notícias do mundo com a coleção Notícias do {{site.data.keyword.discoveryshort}} pronta para uso. Ou, explore suas próprias coleções de documentos no {{site.data.keyword.discoveryshort}}. Basta efetuar login com suas credenciais do {{site.data.keyword.Bluemix_notm}}. Consulte [Insights visuais experimentais](https://visual-insights.bluemix.net){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") para obter mais informações.

### Novo serviço do IBM Cloud Managed Database Server Beta
Novo a partir de: 30 de novembro de 2017

Com o novo serviço do IBM Cloud Managed Database Server Beta, é possível criar uma instância do Microsoft SQL Server no {{site.data.keyword.Bluemix_notm}}. É possível usar essa instância do SQL Server da mesma forma que usaria qualquer sistema de gerenciamento de banco de dados, mas sem o esforço e a despesa de configuração de hardware e instalação e manutenção de software.

Esse serviço oferece os recursos a seguir:
* Opção do Microsoft SQL Server versões 2012, 2014 e 2016 Enterprise e Standard Editions
* Várias configurações ou tamanhos predefinidos para atender aos requisitos de carga de trabalho de seu aplicativo
* Totalmente gerenciado pela IBM, incluindo monitoramento, correção, backup, relatórios

Para iniciar, consulte [Introdução ao IBM Cloud Managed Database Server](/docs/services/managed-sql-server/getting-started.html).

### O que há de novo no {{site.data.keyword.mobilepushshort}}
Novo a partir de: 26 de outubro de 2017

Fizemos vários aprimoramentos para o serviço do {{site.data.keyword.mobilepushshort}} nos últimos meses. O serviço agora está disponível na região Frankfurt juntamente com Dallas, Londres e Sydney. A seguir estão os detalhes dos aprimoramentos:

#### Monitoramento
Agora é possível controlar o desempenho de notificação push para períodos de tempo específicos, rastrear o número de notificações enviadas e o número total de dispositivos registrados. Também é possível registrar ganchos da web para ser informado de todos os eventos no ciclo de vida de uma notificação. Mais detalhes podem ser localizados nos links de documentação e na postagem do blog a seguir:
* [Notificações do monitor](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Receber alertas em eventos de webhook](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoramento no IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")

#### Notificações da web
Agora suportamos o navegador da web Safari para notificações da web junto com Firefox, Chrome, Chrome App e Extensões. Os SDKs da web e as informações relacionadas podem ser localizados em [SDK da web do IBM Bluemix Push Notifications](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

#### Notificações mais recentes do Android e iOS
Temos suporte de moeda para notificações do iOS 11. Também incorporamos vários novos aprimoramentos relacionados à notificação por meio do iOS10 e Android N.

* iOS10 – Notificações rich media, imagens, botão e mapas em notificações interativas, suporte de sequência localizada
* Android N – Notificações expansíveis, notificações silenciosas e interativas, configurações de luz de LED

Detalhes adicionais podem ser localizados na documentação [Notificações rich media](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications), na documentação [Notificações interativas e silenciosas](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications) e na documentação [Ativando notificações push avançadas](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications).

#### Suporte a HTTP/2 do APNS
A Apple introduziu o suporte para protocolo HTTP para Notificações da Apple. O serviço do {{site.data.keyword.mobilepushshort}} agora suporta protocolo HTTP/2. Com esse suporte, cargas úteis de notificação podem ter 4 KB com maior rendimento e é fornecido recurso de feedback instantâneo. O Suporte para Certificado Universal permite que o aplicativo se conecte a ambos os ambientes de simulação e produção.

#### Novo plano Lite 
O Plano Lite para serviço do {{site.data.keyword.mobilepushshort}} fornece a capacidade de enviar 100 mil notificações grátis para cada mês. Para obter mais informações, consulte a postagem do blog [Plano Lite para Push Notifications Service no Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").



### O que há de novo no Mobile Analytics
Novo a partir de: 26 de outubro de 2017

Fizemos aprimoramentos para o serviço do {{site.data.keyword.mobileanalytics_short}} nos últimos meses. O serviço agora está disponível nas regiões Frankfurt e Sydney juntamente com Dallas e Londres. A seguir estão os detalhes dos aprimoramentos:

#### Suporte do SDK da web
O {{site.data.keyword.mobileanalytics_short}} agora é um serviço omni channel com a adição de suporte para análise do aplicativo da web. Mais detalhes podem ser localizados em [https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

#### Integração com o serviço do {{site.data.keyword.mobilefoundation_short}}
O serviço do {{site.data.keyword.mobilefoundation_short}} agora alavanca o serviço do {{site.data.keyword.mobileanalytics_short}} para análise do aplicativo, usuário e desempenho. Os usuários podem alavancar a opção de exportação para warehouse do DB2 para construir a análise do adaptador e gráficos customizados. É possível localizar detalhes adicionais nas postagens do blog a seguir:

* [Integração do Mobile Foundation Service com o Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")
* [Construindo gráficos customizados usando o serviço do IBM Bluemix Mobile Analytics e o IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")
* [Construindo gráficos para análise do adaptador usando o serviço do IBM Bluemix Mobile Analytics e o IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")

#### O modelo do {{site.data.keyword.mobilefirst_notm}} agora inclui o {{site.data.keyword.mobileanalytics_short}}
O Mobile Services Boilerplate é um modelo que fornece um conjunto de serviços móveis para que os usuários comecem a usar rapidamente. O serviço do {{site.data.keyword.mobileanalytics_short}} agora faz parte do modelo disponível no [catálogo](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").


### Atualizações para o {{site.data.keyword.streaminganalyticsshort}}
Novo a partir de: 20 de outubro de 2017

* IBM Streams Runner for Apache Beam: agora é possível desenvolver aplicativos Beam localmente em seu ambiente de desenvolvimento do Streams e, em seguida, enviar esses aplicativos para o serviço do {{site.data.keyword.streaminganalyticsshort}} no {{site.data.keyword.Bluemix_notm}}. O IBM Streams Runner for Apache Beam executa pipelines do Beam em um ambiente do Streams. Um aplicativo Beam que é ativado com o Streams Runner é convertido em um arquivo Streams Application Bundle (SAB) que é possível, então, implementar no {{site.data.keyword.streaminganalyticsshort}}. Consulte [IBM Streams Runner for Apache Beam no Streaming Analytics](/docs/services/StreamingAnalytics/gs_beamrunner.html) para obter mais detalhes.
* É possível localizar informações de arquivos de log ainda mais rápido. O console foi atualizado para melhorar a exibição de gráficos de aplicativo para topologias Python ou Java. Consulte [Aprimoramentos no console](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### O IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
Novo a partir de: 12 de outubro de 2017

O IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services é uma oferta experimental que permite medir experiências do cliente fornecendo uma plataforma para criar engajamentos direcionados em várias seções cruzadas de seu público. O serviço do App Launch fornece insights sobre preferências do cliente e pontos de impacto como um resultado dos engajamentos e o ajuda a personalizar o aplicativo para melhor experiência de cliente.

Os Proprietários de Aplicativo agora podem acelerar a entrega de inovações para aplicativos móveis, evitando as complexidades do ciclo de liberação. O serviço do App Launch permite que os proprietários de aplicativos ativem recursos para aplicativos móveis com velocidade e meçam o impacto controlando o público-alvo. O proprietário do aplicativo pode trabalhar com o desenvolvedor de aplicativo para definir os principais indicadores de desempenho para os recursos, medir o impacto e tomar decisões de lançamento e recuperação do recurso com base no feedback em tempo real. O serviço também fornece a capacidade de testar diversas variantes de recursos de aplicativos, componentes da interface com o usuário e mensagens e de tomar decisões com base no feedback.

Para obter mais informações, consulte o [Tutorial de introdução](/docs/services/app-launch/index.html#gettingstartedtemplate).

### Atualizações do {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}}
Novo a partir de: 4 de outubro de 2017

Um novo recurso de customização e novos modelos de idioma estão disponíveis para o usuário no {{site.data.keyword.relationshipextractionshort}}. Os novos idiomas são suporte holandês, coreano e chinês simplificado para WKS.

### Atualização de cluster do {{site.data.keyword.containerlong_notm}}
Novo a partir de: 20 de setembro de 2017

Agora é possível atualizar seus clusters para a versão mais recente disponível do Kubernetes no {{site.data.keyword.Bluemix_notm}}. Usando a GUI ou a CLI, atualize seus nós principais e nós do trabalhador do Kubernetes para o Kubernetes 1.7 e aproveite os novos recursos e correções.

Para obter mais informações, consulte [Kubernetes 1.7 disponível no {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Novo serviço experimental IBM Voice Agent with Watson
Novo a partir de: 15 de setembro de 2017

Com o novo serviço experimental {{site.data.keyword.iva_full}}, é possível criar um agente de voz cognitivo desenvolvido com os serviços do Watson para o qual os clientes podem ligar e falar por telefone. Com a inteligência artificial do Watson em seu backbone, seu agente de voz pode se comunicar como em uma conversação, manipulando interações complexas e resolvendo chamadas de clientes dentro do agente de voz.

O {{site.data.keyword.iva_short}} se conecta continuamente e orquestra os serviços do Watson {{site.data.keyword.speechtotextshort}}, do {{site.data.keyword.conversationshort}} e do {{site.data.keyword.texttospeechshort}} para simular uma conversa de língua natural. Cada agente de voz escala automaticamente para manipular várias chamadas ao mesmo tempo. Nessa liberação experimental, é possível customizar seu agente de voz usando os recursos-chave a seguir:

* Importe o diálogo de amostra do {{site.data.keyword.conversationshort}} para começar e, em seguida, crie seu próprio diálogo para ajustar às necessidades de sua empresa.
* Programe o comportamento do agente de voz dentro do serviço do {{site.data.keyword.conversationshort}} usando nossas APIs. É possível controlar tudo de maneira invasiva para desligar a chamada para qualquer nó em seu diálogo.
* Crie e gerencie facilmente múltiplos agentes de voz se você deseja conectar números de telefone diferentes para agentes cognitivos que são especializados em diferentes tópicos.
* Expanda os recursos do serviço conectando um mecanismo de orquestração de serviços (SOE) para que você possa usar as APIs de terceiros. Por exemplo, o SOE pode atender acionadores do serviço do {{site.data.keyword.conversationshort}}, em seguida, usar as APIs fornecidas para consultar informações em sistemas existentes ou fornecer outras análises.

Para iniciar, consulte a documentação [Introdução ao {{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html).


### Atualização de serviço do {{site.data.keyword.streaminganalyticsshort}}: o console inclui novas maneiras de identificar problemas em seus aplicativos
Novo a partir de: 14 de agosto de 2017
 
Para aplicativos Python e Java, o local do arquivo de origem é exibido com base em suas anotações @spl_note. 
 
Para obter detalhes, consulte [Melhorias mais recentes no {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### O IBM Cloud Monitoring agora também está disponível na região do Reino Unido
Novo a partir de: 01 de agosto de 2017

Use o serviço {{site.data.keyword.monitoringlong}} para expandir as suas capacidades de coleta, retenção e análise no {{site.data.keyword.Bluemix_notm}} ao trabalhar com métricas. 

* Alerta em ação! O {{site.data.keyword.monitoringlong}} oferece uma API que pode ser usada para configurar limites de desempenho e para ser notificada quando esses limites são violados. Defina regras de alerta para uma única instância de serviço ou instância de app e regras de alerta que sejam relatados em um conjunto de instâncias. Quando um alerta for acionado, obtenha uma notificação por meio de um e-mail, um evento de PagerDuty, uma notificação de webhook ou qualquer combinação dos três.

* Inclua métricas customizadas. O plano premium do {{site.data.keyword.monitoringlong}} oferece APIs que podem ser usadas para incluir métricas relevantes de aplicativo e de negócios nos dados do Cloud Monitoring. Também é possível usá-las para enviar dados de métrica de fora do {{site.data.keyword.IBM_notm}} Cloud para o serviço {{site.data.keyword.monitoringlong}}.

* Construa painéis reutilizáveis e torne-os interativos. O Grafana hospedado do {{site.data.keyword.monitoringlong}} fornece suporte para construir painéis customizados com uma ampla escolha de opções de visualização.  Faça seus painéis dinâmicos com modelos usando consultas de métrica com variáveis.

* Acesse seu serviço por meio do catálogo do {{site.data.keyword.Bluemix_notm}}. O {{site.data.keyword.monitoringlong}} está disponível como um quadro de serviço na seção DevOps do catálogo do {{site.data.keyword.Bluemix_notm}}.  Para o serviço {{site.data.keyword.containershort}} com contêineres únicos e de grupo, é possível acessar o serviço na UI do {{site.data.keyword.Bluemix_notm}}.

* Escolha o plano de serviço que se ajuste às suas necessidades. É possível escolher o plano de serviços Lite ou o plano de serviços Premium para corresponder às suas necessidades de uso. O plano Lite oferece coleção de métricas de uma vez por minuto, retenção por 15 dias e alerta complementar.  Como alternativa, é possível selecionar o plano Premium para permitir maior consumo, retenção mais longa de métricas e obter acesso às APIs de serviço, por exemplo, para enviar ou recuperar métricas do serviço {{site.data.keyword.monitoringlong}}. O {{site.data.keyword.monitoringlong}} oferece coleção de métricas de uma vez por minuto.  O plano Lite retém as métricas de resolução integral por 15 dias. O plano Premium retém as métricas de resolução integral por 45 dias.

O serviço anterior do {{site.data.keyword.monitoringshort}} coletava métricas em frequências definidas de serviço começando em 30 segundos e resumidas a frequências de 1 hora ao longo do tempo. O {{site.data.keyword.monitoringlong}} agora oferece coleção de resolução integral em 1 minuto.  O plano Lite retém as métricas por 15 dias.  O plano Premium retém as métricas por 45 dias.

Para obter mais informações sobre o serviço do {{site.data.keyword.monitoringlong}}, consulte [a documentação de Introdução ao monitoramento](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) ou [o IBM Cloud Monitoring – Atualização de serviço com Novos recursos![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).


### O IBM Cloud Log Analysis agora está disponível na região Sul dos EUA
Novo a partir de: 31 de julho de 2017

O serviço {{site.data.keyword.loganalysisfull}} fornece serviços de coleção de logs e de procura de log para a plataforma do {{site.data.keyword.Bluemix_notm}}, coletando dados dos aplicativos e dos serviços do {{site.data.keyword.Bluemix_notm}} automaticamente de serviços selecionados do {{site.data.keyword.Bluemix_notm}}. Use o serviço do {{site.data.keyword.loganalysisshort}} para:

* Reter logs enquanto você desejar.  

    Os logs são armazenados no armazenamento do IBM Cloud. Será possível fazer download de logs quando eles forem necessários.
	
* Gerenciar seus logs retidos e enviar dados do log de fora do {{site.data.keyword.IBM_notm}} Cloud usando a nova API.

* Escolha a quantia de logs que pode ser procurada por dia.  

    Estão disponíveis planos diferentes que podem ser usados para procurar até 500 MB, 2 GB, 5 GB e 10 GB de logs por dia.

* Construa painéis reutilizáveis e torne-os interativos. 

    O Kibana hospedado pelo {{site.data.keyword.loganalysisshort}} fornece suporte para construir painéis customizados.

* Acesse seu serviço por meio do catálogo do {{site.data.keyword.Bluemix_notm}}.  

    Para o serviço do {{site.data.keyword.loganalysisshort}} com contêineres únicos e de grupo e os serviços do {{site.data.keyword.IBM_notm}} Cloud Foundry, é possível acessar o serviço na UI do {{site.data.keyword.Bluemix_notm}}.

Para obter mais informações sobre o serviço do {{site.data.keyword.loganalysisshort}}, consulte a [Introdução ao {{site.data.keyword.loganalysisfull}}](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis) e a visão geral do [{{site.data.keyword.loganalysisshort}}](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov).

### O IBM dashDB for Analytics foi renomeado
Novo a partir de: 18 de julho de 2017

A tabela a seguir resume o novo nome:

| Nome anterior               | Novo nome                   | Data de vigência |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 18 de julho de 2017  |
{: caption="Tabela 1. Mudança de nome de serviço" caption-side="top"}
 
Para obter uma lista acumulativa de atualizações para o Db2 Warehouse on Cloud e o Db2 on Cloud, consulte: [O que há de novo no Db2 Warehouse on Cloud e no Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). 

### O IBM Cloud Monitoring agora está disponível na região Sul dos EUA
Novo a partir de: 17 de julho de 2017

Use o serviço {{site.data.keyword.monitoringlong}} para expandir as suas capacidades de coleta, retenção e análise no {{site.data.keyword.Bluemix_notm}} ao trabalhar com métricas. 

* Alerta em ação! O {{site.data.keyword.monitoringlong}} oferece uma API que pode ser usada para configurar limites de desempenho e para ser notificada quando esses limites são violados. Defina regras de alerta para uma única instância de serviço ou instância de app e regras de alerta que sejam relatados em um conjunto de instâncias. Quando um alerta for acionado, obtenha uma notificação por meio de um e-mail, um evento de PagerDuty, uma notificação de webhook ou qualquer combinação dos três.

* Inclua métricas customizadas. O plano premium do {{site.data.keyword.monitoringlong}} oferece APIs que podem ser usadas para incluir métricas relevantes de aplicativo e de negócios nos dados do Cloud Monitoring. Também é possível usá-las para enviar dados de métrica de fora do {{site.data.keyword.IBM_notm}} Cloud para o serviço {{site.data.keyword.monitoringlong}}.

* Construa painéis reutilizáveis e torne-os interativos. O Grafana hospedado do {{site.data.keyword.monitoringlong}} fornece suporte para construir painéis customizados com uma ampla escolha de opções de visualização.  Faça seus painéis dinâmicos com modelos usando consultas de métrica com variáveis.

* Acesse seu serviço por meio do catálogo do {{site.data.keyword.Bluemix_notm}}. O {{site.data.keyword.monitoringlong}} está disponível como um quadro de serviço na seção DevOps do catálogo do {{site.data.keyword.Bluemix_notm}}.  Para o serviço {{site.data.keyword.containershort}} com contêineres únicos e de grupo, é possível acessar o serviço na UI do {{site.data.keyword.Bluemix_notm}}.

* Escolha o plano de serviço que se ajuste às suas necessidades. É possível escolher o plano de serviços Lite ou o plano de serviços Premium para corresponder às suas necessidades de uso. O plano Lite oferece coleção de métricas de uma vez por minuto, retenção por 15 dias e alerta complementar.  Como alternativa, é possível selecionar o plano Premium para permitir maior consumo, retenção mais longa de métricas e obter acesso às APIs de serviço, por exemplo, para enviar ou recuperar métricas do serviço {{site.data.keyword.monitoringlong}}. O {{site.data.keyword.monitoringlong}} oferece coleção de métricas de uma vez por minuto.  O plano Lite retém as métricas de resolução integral por 15 dias. O plano Premium retém as métricas de resolução integral por 45 dias.

O serviço anterior do {{site.data.keyword.monitoringshort}} coletava métricas em frequências definidas de serviço começando em 30 segundos e resumidas a frequências de 1 hora ao longo do tempo. O {{site.data.keyword.monitoringlong}} agora oferece coleção de resolução integral em 1 minuto.  O plano Lite retém as métricas por 15 dias.  O plano Premium retém as métricas por 45 dias.

Para obter mais informações sobre o serviço do {{site.data.keyword.monitoringlong}}, consulte [a documentação de Introdução ao monitoramento](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring) ou [o IBM Cloud Monitoring – Atualização de serviço com Novos recursos![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/).

### Upgrade do {{site.data.keyword.contdelivery_short}}
Novo a partir de: 11 de julho de 2017

Os benefícios do upgrade incluem correções de erro, melhorias de desempenho e refinamentos na experiência do usuário. Os aprimoramentos notáveis, se já não estiverem presentes em seu ambiente, incluem:
<ul>
<li>Correções e melhorias para internacionalização e acessibilidade.</li>
<li>Controle de acesso da cadeia de ferramentas, disponível na guia Gerenciar de uma cadeia de ferramentas.</li>
<li>Novas integrações de ferramenta no catálogo da ferramenta Continuous Delivery.</li>
<li>Agrupamento melhorado de várias áreas de trabalho no Orion Web IDE.</li>
<li>Suporte para múltiplas guias do editor no Orion Web IDE.</li>
<li>Suporte para temas de UI no Orion Web IDE.</li>
</ul>

### {{site.data.keyword.uccr_short}} beta 
Novo a partir de: 23 de junho de 2017

O {{site.data.keyword.uccr_short}} é uma solução de gerenciamento de liberação de escala corporativa que suporta ferramentas de implementação nativas de nuvem e no local.

A versão beta do {{site.data.keyword.uccr_short}} fornece os recursos-chave a seguir:
* Use liberações para gerenciar vários planos de implementação e eventos e colaborar com os esforços de liberação de múltiplas equipes.
* Crie eventos para qualquer atividade relacionada à liberação e gerencie-os com o calendário.
* Importe seus próprios eventos e liberações.
* Customize os eventos de calendário para se ajustarem à sua organização.
* Use e-mail e tarefas do tipo Slack para notificações de liberação.

### O DashDB for Transactions foi renomeado para {{site.data.keyword.DB2_on_Cloud_short}}
Novo a partir de: 14 de junho de 2017

IBM {{site.data.keyword.DB2OnCloud_short}} é o novo nome para dashDB for Transactions. Como parte dessa renomeação, antigo serviço autogerenciado do IBM {{site.data.keyword.DB2OnCloud_short}} também será renomeado para IBM Db2 Hosted. Nesse momento, apenas os nomes de exibição foram atualizados, portanto, quaisquer APIs ou interfaces de linha de comandos permanecem sem mudanças.

### Atualizações do {{site.data.keyword.sparks}}: o conector Stocator-S3 inclui suporte para o serviço IBM Cloud Object Storage Cross Region (Beta)
Novo a partir de: 05 de junho de 2017

Os usuários do {{site.data.keyword.sparks}} agora podem acessar e fazer análise em dados armazenados no serviço IBM Cloud Object Storage Cross Region. Esse recurso é oferecido como um Beta. O IBM Cloud Object Storage oferece armazenamento de alta capacidade com custo reduzido para análise e outras aplicações que é escalável, flexível e simples de usar.

O Apache Spark acessa dados do IBM Cloud Object Storage por meio de um conector de armazenamento baseado na tecnologia Stocator, que foi projetado implicitamente para armazenamento de objeto e, portanto, mais rápido que os conectores de armazenamento de objeto anteriores. Como um usuário, não é necessário mudar ou recompilar o código do Apache Spark.

A postagem do blog [Acessar e analisar dados no IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo") descreve o uso de dados do IBM Cloud Object Storage com o {{site.data.keyword.sparks}} no {{site.data.keyword.Bluemix_notm}} e o IBM Data Science Experience (DSx).

Entre em contato conosco por meio do e-mail [sparksrv@us.ibm.com](sparksrv@us.ibm.com), se você tiver qualquer pergunta ou comentário. Sua entrada é muito apreciada!

### Novo plano escalável disponível para o {{site.data.keyword.dashdbshort_notm}} for Transactions
Novo a partir de: 31 de maio de 2017

Um novo plano está disponível para o {{site.data.keyword.dashdbshort}} for Transactions que pode crescer com as necessidades de seu banco de dados. O novo plano Flex permite iniciar com um sistema pequeno e aumentar a capacidade de energia e de armazenamento desse sistema de maneira fácil e rápida. O {{site.data.keyword.dashdbshort}} for Transactions é 100% compatível com o DB2 e fornece um SLA 99,95% em planos de alta disponibilidade.

### Novas atualizações para o serviço do {{site.data.keyword.mobilepush}} no {{site.data.keyword.Bluemix_notm}}
Novo a partir de: 24 de maio de 2017

A seguir estão as novas atualizações disponíveis para o serviço do {{site.data.keyword.mobilepush}} no {{site.data.keyword.Bluemix_notm}}

**Plano Lite**: nós estamos introduzindo um novo Plano Lite além do Plano Básico existente para o {{site.data.keyword.mobilepush}} Service. De acordo com o novo plano, os usuários podem enviar até cem mil mensagens digitais grátis por mês. Ao fazer upgrade do plano Lite para o plano básico, o usuário será cobrado depois de um milhão de mensagens digitais a partir da contagem na qual o uso do plano Lite foi cortado.

**Monitoramento**: agora é possível obter insights sobre notificações enviadas e dispositivos registrados no {{site.data.keyword.mobilepush}} Service Console. Também é possível usar as APIs de REST para rastreamento no nível da mensagem. Da entrega de mensagens, passando pelo envio de mensagens até o recebimento de mensagens, os detalhes podem ser obtidos pela configuração de webhooks. Consulte [Monitoramento para {{site.data.keyword.mobilepush}}](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications).

**Notificações da web**: agora é possível enviar notificações para navegadores da web Safari.

### Atualizações do Secure Gateway
Novo a partir de: 24 de maio de 2017

A atualização de manutenção mais recente do Secure Gateway inclui correções de erros menores no gerenciador de UI e API, documentação atualizada, e o cliente foi atualizado para a versão 1.7.1. O cliente Secure Gateway agora está disponível no AIX 7.1+ e suporta a conexão de saída por meio de um proxy squid.

### Atualizações de serviço do {{site.data.keyword.streaminganalyticsshort}}: desenvolver aplicativos Streams em seu ambiente de desenvolvimento do Python
Novo a partir de: 13 de abril de 2017

No passado, você tinha que instalar uma versão local do IBM Streams para desenvolver aplicativos Python. Esse não é mais o caso. Agora é possível desenvolver aplicativos com Python em seu ambiente de desenvolvimento favorito ou em um bloco de notas interativo do Jupyter.

É possível usar o contexto do STREAMING_ANALYTICS_SERVICE para enviar um aplicativo Python para o serviço do {{site.data.keyword.streaminganalyticsshort}}. O serviço {{site.data.keyword.streaminganalyticsshort}} requer o Python 3.5.

É possível criar aplicativos Python de amostra usando bloco de notas Jupyter no IBM Data Science Experience (DSX) e enviar esses aplicativos à instância do {{site.data.keyword.streaminganalyticsshort}} diretamente do DSX. Confira os aplicativos Python de processamento de fluxo de amostra nos blocos de notas na [página da comunidade do DSX](https://datascience.ibm.com/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

Para obter mais informações sobre as atualizações de serviço do {{site.data.keyword.streaminganalyticsshort}}, consulte [Atualizações do {{site.data.keyword.streaminganalyticsshort}}: integração do DSX e desenvolvimento mais fácil do Python](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo").

### Atualizações do {{site.data.keyword.sparks}}: o Apache Spark 2.1 agora é suportado
Novo a partir de: 21 de abril de 2017

O {{site.data.keyword.sparkl}} está introduzindo o suporte para o Apache Spark 2.1 para criar algoritmos que aproveitam insights de dados complexos. O Apache Spark 2.1 ajudará significativamente no fluxo estruturado com suporte incluído para marcas d'água do tempo de evento e Kafka 0.10. O Apache Spark 2.1 também focou no aumento da estabilidade e da usabilidade nos módulos Spark SQL, SparkR e MLlib. Para obter mais detalhes sobre o Spark 2.1, consulte [Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html).

Estamos felizes em responder perguntas relacionadas ao {{site.data.keyword.sparkl}} ou à versão mais recente do Apache Spark 2.1, que devem ser enviadas para sparksrv@us.ibm.com. 

### O {{site.data.keyword.macm_short}} está sendo descontinuado
Novo a partir de: 18 de abril de 2017

A partir de 30 de março de 2017, o ladrilho de serviço do {{site.data.keyword.macm_long}} será removido do Catálogo do {{site.data.keyword.Bluemix_notm}} e não será mais possível provisionar novas instâncias do MACM. No entanto, instâncias existentes continuarão sendo suportadas. O Fim da Data de Suporte é 30 de março de 2018. Exclua suas instâncias de serviço do {{site.data.keyword.macm_short}} (MACM) antes do Fim da Data de Suporte. Incentivamos os usuários a migrarem para o IBM Watson Content Hub. O Watson Content Hub está disponível no IBM Marketplace e fornece aos usuários uma avaliação grátis de 30 dias. O IBM Watson Content Hub fornece funcionalidade semelhante ao MACM com novos recursos incluídos, tais como o gerenciamento de ativos, a identificação cognitiva usando serviços do IBM Watson e a rede de entrega de conteúdo (CDN) incluída para assegurar uma experiência ideal para seus clientes. A IBM oferece engajamentos de serviço para migrar o conteúdo do MACM para o Watson Content Hub.

### Atualizações de serviço do {{site.data.keyword.streaminganalyticsshort}}: desenvolver aplicativos Streams em seu ambiente de desenvolvimento do Python
Novo a partir de: 13 de abril de 2017

No passado, você tinha que instalar uma versão local do IBM Streams para desenvolver aplicativos Python. Esse não é mais o caso. Agora é possível desenvolver aplicativos com Python em seu ambiente de desenvolvimento favorito ou em um bloco de notas interativo do Jupyter.

É possível usar o contexto do STREAMING_ANALYTICS_SERVICE para enviar um aplicativo Python para o serviço do {{site.data.keyword.streaminganalyticsshort}}. O serviço {{site.data.keyword.streaminganalyticsshort}} requer o Python 3.5.

Confira os aplicativos Python de processamento de fluxo de amostra nos blocos de notas na [página da comunidade do IBM Data Science Experience](http://datascience.ibm.com){: new_window} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo"). 

### Atualizações do {{site.data.keyword.sparks}}: suporte de bloco de notas agora em Data Science Experience
Novo a partir de: 11 de abril de 2017

A sua nova plataforma para trabalhar com blocos de notas e Spark é o Data Science Experience. Inscreva-se para o [Data Science Experience](http://datascience.ibm.com/) e comece a criar blocos de notas e a compartilhar seus conhecimentos com outros cientistas de dados.

Se você trabalhou com blocos de notas no {{site.data.keyword.sparks}}, poderá migrar seus blocos de notas para o Data Science Experience. Para obter mais informações, consulte [Migrando a documentação de blocos de notas](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx).

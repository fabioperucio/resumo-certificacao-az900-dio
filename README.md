# Anotações Pessoais para a AZ-900


#### Nuvem Privada
* Ambiente 100% on Premisse
* Não divide espaço e recurso com ninguém

#### Nuvem Pública
* Pertencente a serviços de nuvem ou provedor de hosting
* Fornece recursos e serviços a várias organizações e usuários
* Acessada via conexão de rede segura

#### Nuvem Híbrida
* O melhor dos dois mundos
* Compartilham recursos entre si; Ambiente On Premisse e Ambiente Cloud

### Comparação dos modelos de nuvem - Custos

#### Pública
* Nenhuma despesa de capital para escalar verticalmente
* Os aplicativos podem ser provisionados e desprovisionados rapidamente
* As organizações pagam apenas pelo que utilizam

#### Privada
+ As organizações tem controle total sobre os recursos e segurança
+ As organizações são responsáveis pela manutenção e pelas atualizações de hardware
 
#### Híbrida
* As organizações determinam onde executar seus aplicativos
* As organizações controlam a segurança, a conformidade e os requisitos legais
* Fornece maior flexibilidade

### Comparação entre CapEx e OpEx

##### Capex - Despesas de capital
* O gasto inicial do dinheiro em Infraestrutura física
* As despesas do Capex tem um valor que se reduz com o tempo.

###### Opex - Despesas Operacionais
+ Gastar com produtos e serviços conforme necessário, pagamento conforme uso
+ Seja cobrado imediatamente

### Modelo baseado em consumo
Os provedores de serviço em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
+ Melhor previsão de custos
+ São fornecidos preços para recursos e serviços individuais
+ A cobrança é feita com base no seu uso real

  
## Módulo 1 - Conceito de Nuvem

##### Benefícios da Nuvem

1. Alta Disponibilidade
- Garantir a melhor perspectiva ao cliente
- SLA - Service Level Agreement (Acordo de Nível de Serviço) - Disponibilidade de 99%, 99,9%, 99,95% - Se esse SLA não for cumprido, o cliente recebe créditos referente ao período não utilizado.
Quanto mais 9, menort o tempo de indisponibilidade.
A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

2. Escalabilidade e Elasticidade
- A escabilidade refere-se à capacidade de ajustar recursos para atender a mudança
- A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
- O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
- Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
- Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
- Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPU's ou RAM à máquina virtual.

3. Elasticidade (Demanda de Black Friday)
- Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
- Um exemplo disso, você pode adicionar maquinas virtuais ou contêineres por meio da expansão.
- Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

4. Confiabilidade
- Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente
- Com o design descentralizado, a núvem permite que você tenha recursos implantados em várias regiões do mundo.
- Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

5. Previsibilidade
- A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework

6. Segurança
- A nuvem oferece ferramentas sde segurança que atendem às necessidades dos clientes, mas é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
- Se você quiser o contole máximo da segurança, a Infraestrutura como Serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutanção.
- Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de Plataforma como Serviço ou Software como Serviço podem ser as melhores estratégias de nuvem para você.
  
7. Governança
- A auditoria baseada em nuvem ajuda a sinalizqar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. A mitigação é a resolução do problema ou pelo menos amenizar os efeitos negativos dele.
- Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

8. Gerenciabilidade
- Um dos principais benefícios da computação em nuvem são as opçoes de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem.
- O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por Exemplo:
- Escalar automaticamente a implantação de recursos com base na necessidade.
- implantar recursos com base em um modelo pré configurado, removendo a necessidade de configuração manual.
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
- Por meio de um Portal na WEB
- Usando uma interface de linha de comando
- Usando API's
- Usando o PowerShell

### Tipos de Serviço na Nuvem

IaaS - Infraestrutura como serviço. O Serviço de nuvem é mais flexível. Você configura e gerencia o hardware para o seu aplicativo

PaaS - Plataforma como serviço. Focado no desenvolvimento de aplicativos. O gerenciamento de plataforma é realizado pelo provedor de nuvem. App's, BD's.

SaaS - Software como Serviço. Modelo de pagamento conforme o uso. Os usuários pagam pelo software que utilizam em um modelo de assinatura.

Observações a respeito de cada um.

Mais acesso à informação - IaaS  
Personalizar - PaaS  
Apenas Software ou Aplicação - SaaS  



# AWS Certified Solutions Architect - Associate (SSA-C03) exam preparation

## Guia do Exame

O exame valida a capacidade do candidato de projetar soluções com base no AWS Well-Architected Framework.

### Domínio 1: Design de arquiteturas serguras
Declaração de tarefa 1.1: Projetar acesso seguro aos recursos da AWS

Conhecimento sobre : 
  - Controles de acesso e gerenciamento em várias contas.
  - Serviços de identidade e acesso federado da AWS (por exemplo, AWS identity and Access Management [IAM], AWS Identity Center [AWS Single-On]).
  - Infraestrutura global da AWS (por exemplo, Zonas de Disponibilidade, Regiões AWS).
  - Práticas recomendadas de segurança da AWS (por exemplo, o princípio de menor privilégio).
  - O modelo de responsabilidade compartilhada da AWS.

Habilidades em :
  - Aplicar as práticas recomendadas de segurança da AWS a usuários do IAM e usuários-raiz (por exemplo, autenticação com multifator [MFA]).
  - Projetar um modelo de autorização flexível que inclua usuários, grupos, funções e políticas do IAM.
  - Projetar uma estratégia de controle de acesso baseada em função (por exemplo, AWS Security Token Service [AWS STS], mudança de função, acesso entre contas).
  - Projetar uma estratégia de segurança para várias contas da AWS (por exemplo, AWS Control Tower, políticas de controle de serviço [SCPs]).
  - Determinar o uso apropriado de políticas de recursos para os serviços da AWS.
  - Determinar quando federar um serviço de diretório com funções do IAM.

Declaração de tarefa 1.2: Projetar cargas de trabalho e aplicações seguras.

Conhecimento sobre:
  - Configuração de aplicações e segurança de credenciais.
  - Endpoints de serviço da AWS.
  - Controle de portas, protocolos e tráfego de rede na AWS.
  - Acesso seguro a aplicações.
  - Serviços de segurança com casos de uso apropriados (por exemplo, Amazon Congnito, Amazon GuardDuty, Amazon Macie).
  - Vetores de ameaças externos à AWS (por exemplo, DDoS, SQL injection).

Habilidades em:
  - Projetar arquiteturas de VPC com componentes de segurança (por exemplo, security groups, tabelas de rotas, ACLs de rede, gateways NAT).
  - Determinar estratégias de segmentação de rede (por exemplo, usando sub-redes públicas e privadas).
  - Integrar serviços da AWS para proteger aplicações (por exemplo, AWS Shield, AWS WAF, IAM Identity Center, AWS Secrets Manager).
  - Proteger conexões de rede externas de e para a nuvem AWS (por exemplo, VPN, AWS Direct Connect).

Declaração de tarefa 1.3: Determinar os controles de segurança de dados apropriados.

Conhecimento sobre:
  - Acesso e governaça de dados.
  - Recuperação de dados.
  - Classificação e retençao de dados.
  - Criptografia e gerenciamento de chaves apropriado.

Habilidades em:
  - Alinhar as tecnologias da AWS para atender aos requisitos de conformidade.
  - Criptografia de dados em trânsito (por exemplo, AWS Certificate Manager [ACM] usando TLS).
  - Implementar políticas de acesso para chave de criptografia.
  - Implementar backups e replicações de dados.
  - Implementar políticas para acesso, ciclo de vida e proteção de dados.
  - Alternar chaves de criptografia e renovar certificados.

### Domínio 2: Design de arquiteturas resilientes

Declaração de tarefa 2.1: Projetar arquiteturas dimensionáveis e com acomplamento fraco.

Conhecimento sobre:
  - Criação e gerenciamento de APIs (por exemplo, Amazon API Gateway, API REST).
  - AWS Managed services com casos de uso apropriados (por exemplo, AWS Transfer Family, Amazon Simple Queue Service [Amazon SQS], Secrets Manager).
  - Estratégias de armazenamento em cache.
  - Princípios de design para microsserviços (por exemplo, cargas de trabalho stateless em comparação com cargas de trabalho stateful).
  - Arquiteturas orientadas por eventos.
  - Como usar adequadamente os aceleradores de borda (por exemplo, rede de entrega de conteúdo [CDN]).
  - Como migrar aplicações para contêineres.
  - Conceitos de balanceamento de carga (por exemplo, Application Load Balancer).
  - Arquiteturas multicamadas.
  - Conceitos de enfileiramento e sistema de mensagens (por exemplo, publicar/assinar).
  - Tecnologias e padrões ser servidor (por exemplo, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS]).
  - Quando usar réplicas de leitura.
  - Orquestração de fluxo de trabalho (por exemplo, AWS Step Functions).

Habilidade em:
  - Projetar arquiteturas orientadas por eventos, microsserviços e/ou multicamadas com base em requisitos.
  - Determinar estratégias de scaling para componentes usados em um projeto de arquitetura.
  - Determinar os serviços da AWS necessários para obter um acoplamento fraco com base em requisitos.
  - Determinar quando usar tecnologias e padrões sem servidor.
  - Recomendar tecnologias apropriadas de computação, armazenamento, redes e banco de dados com base em requisitos.
  - Usar serviços da AWS com propósitos especifícos para cargas de trabalho.

Declaração de tarefa 2.2: Projetar arquiteturas altamentes disponíveis e/ou tolerantes a falhas.

Conhecimento sobre:
  - Infraestrutura global da AWS (por exemplo, Zonas de Disponibilidade, Regiões AWS, Amazon Route 53).
  - AWS Managed Services com casos de uso apropriados (por exemplo, Amazon Comprehend, Amazon Polly).
  - Conceitos básicos e rede (por exemplo, tabelas de rotas).
  - Estratégias de recuperação de desastres (DR) (por exemplo, backup e restauração, luz piloto, warm standby, failover ativo-ativo, objetivo de ponto de recuperação [RPO], objetivo de tempo de recuperação [RTO]).
  - Padrões de design distribuídos.
  - Estratégias de failover.
  - Infraestrutura imutável.
  - Conceitos de balanceamento de carga (por exemplo, Application Load Balancer).
  - Conceitos de proxy (por exemplo, Proxy do Amazon RDS).
  - Cotas de serviço e limitação de largura de banda (por exemplo, como configurar as cotas de serviços para uma carga de trabalho em um ambiente de standby).
  - Opções e características de armazenamento (por exemplo, durabilidade, replicação).
  - Visibilidade da carga de trabalho (por exemplo, AWS X-Ray).

Habilidades em:
  - Determinar estratégias de automação para garantir a integridade da infraestrutura.
  - Determinar os serviços da AWS necessários para fornecer uma arquitetura altamente disponível e/ou tolerante a falhas nas Zonas de Disponibilidade ou Regiões AWS.
  - Identificar métricas com base nos requisitos empresariais para oferecer uma solução altamente disponível.
  - Implementar designs para mitigar pontos únicos de falha. 
  - Implementar estratégias para garantir a durabilidade e a disponibilidade dos dados (por exemplo, backups).
  - Selecionar uma estratégia de DR apropriada para atender aos requisitos empresariais.
  - Usar serviços da AWS que melhoram a confiabilidade de aplicações legados e aplicações que não foram criadas para a nuvem (por exemplo, quando não é possível fazer alterações nas aplicações).
  - Usar serviços da AWS com propósito específico para cargas de trabalho.

### Domínio 3: Design de arquiteturas de alta performance

Declaração de tarefa 3.1: Determinar soluções de armazenamento dimensionáveis e/ou de alto desempenho.

Conhecimento sobre:
  - Soluções de armazenamento híbrido para atender aos requisitos empresariais.
  - Serviços de armazenamento com casos de uso apropriados (por exemplo, Amazon S3, Amazon Elastic File System [Amazon EFS], Amazon Elastic Block Store [Amazon EBS])
  - Tipos de armazenamento com caractéristicas associadas (por exemplo, objeto, arquivo, bloco).

Habilidade em:
  - Determinar quais serviços e configurações de armazenamento atendem às demandas de desempenho.
  - Determinar quais serviços de armazenamento que podem ser dimensionados para atender às necessidades futuras. 

Declaração de tarefa 3.2: Projetar soluções de computação elásticas e de alto desempenho.

Conhecimento sobre: 
  - Serviços de computação da AWS com casos de uso apropriados (por exemplo, AWS Batch, Amazon EMR, Fargate).
  - Conceitos de computação distribuída com base na infraestrutura global e nos serviços de borda da AWS.
  - Conteitos de enfileiramento e sistema de mensagens (por exemplo, publicar/assinar).
  - Recursos de escalabilidade com casos de uso apropriados (por exemplo, Amazon EC2 Auto Scaling, AWS Auto Scaling).
  - Tecnologias e padrões sem servidor (por exemplo, Lambda, Fargate).
  - A orquestração de contêineres (por exemplo, Amazon ECS, Amazon EKS).

Habilidade em:
  - Desacoplar cargas de trabalho para que os componentes possam ser dimensionados de forma independente.
  - Identificar métricas e condições para realizar ações de scaling;
  - Selecionar as opções e os recursos de computação apropriados (por exemplo, tipos de instâncias do EC2) para atender aos requisitos empresariais.
  - Selecionar o tipo e o tamanho de recursos apropriados (por exemplo, a quantidade de memória do Lambda) para atender aos requisitos empresáriais.

Declaração de tarefa 3.3: Determinar soluções de banco de dados de alto desempenho.

Conhecimento sobre:
  - Infraestrutura global da AWS (por exemplo, Zonas de Disponibilidades, Regiões AWS).
  - Estratégias e serviços de armazenamento em cache (por exemplo, Amazon ElasticCache).
  - Padrões de acesso a dados (por exemplo, leitura intensiva em comparação com gravação intensiva).
  - Planejamento da capacidade de banco de dados (por exemplo, unidades de capacidade, tipos de instâncias, IOPS provisionado).
  - Proxies e conexões de banco de dados.
  - Mecanismos de banco de dados com casos de uso apropriados (por exemplo, migrações homogêneas e heterogêneas).
  - Replicações de banco de dados (por exemplo, réplicas de leitura).
  - Tipos e serviços de banco de dados (por exemplo, sem servidor, relacional em comparação com não relacional, na memória).

Habilidades em:
  - Configurar réplicas de leitura para atender aos requisitos empresariais.
  - Projetar arquiteturas de banco de dados.
  - Determinar um mecanismo de banco de dados apropriado (por exemplo, MySQL em comparação com o PostgreSQL).
  - Determinar um tipo de banco de dados apropriado (por exemplo, Amazon Aurora, Amazon DynamoDB).
  - Integrar o armazenamento em cache para atender aos requisitos empresariais. 

Declaração de tarefa 3.4: Determinar arquiteturas de rede dimensionáveis e/ou de alto desempenho.

Conhecimento sobre:
  - Serviços de rede de borda com casos de uso apropriados (por exemplo, Amazon CloudFront, AWS Global Accelerator).
  - Como projetar arquitetura de rede (por exemplo, camadas de sub-rede, roteamento, endereçamento IP).
  - Conceito de balanceamento de carga (por exemplo, Application Load Balancer).
  - Opções de conexão de rede (por exemplo, AWS VPN, Direct Connect, AWS PrivateLink).
  
Habilidade em:
  - Criar uma topologia de rede para várias arquiteturas (por exemplo, global, híbrida, multicamadas).
  - Determinar quais configurações de rede podem ser dimensionadas para acomodar necessidades futuras.
  - Determinar o posicionamento adequado dos recursos para atender aos requisitos empresariais.
  - Selecionar a estratégia de balanceamento de carga apropriada.

Declaração da tarefa 3.5: Determinar soluções de transformação e ingestão de dados de alto desempenho.

Conhecimento sobre: 
  - Serviços de data analytics e visualização de dados com casos de uso apropriados (por exemplo, Amazon Athena, AWS Lake Formation, Amazon QuickSight).
  - Padrões de ingestão de dados (por exemplo, frequência).
  - Serviços de transferência de dados com casos de uso apropriados (por exemplo, AWS DataSync, AWS Storage Gateway).
  - Serviços de transformação de dados com casos de uso apropriados (por exemplo, AWS Glue).
  - Acesso seguro a pontos de acesso de ingestão.
  - Tamanhos e velocidades necessárias para atender aos requisitos empresariais.
  - Serviços de streaming de dados com casos de uso apropriados (por exemplo, Amazon Kinesis).

Habilidades em:
  - Criar e proteger data lakes.
  - Projetar arquiteturas de streaming de dados.
  - Projetar soluções de transferência de dados.
  - Implementar estratégias de visualização.
  - Selecionar opções de computação apropriadas para processamento de dados (por exemplo, Amazon EMR).
  - Selecionar configurações apropriadas para ingestão.
  - Transformar dados entre formatos (por exemplo, .csv em .parquet).


### Domínio 4: Design de arquiteturas econômicas



### What is AWS ? 
Cloud Computing is the on-demand delivery of IT resources with primarily pay-as-you-go pricing.



## Introduction about exam

<p>The exam AWS Certified Solutions Architect - Associate is intended for people who perform the role of solutions architect.</p>

<p>The exam validates the candidate's ability to complete the following tasks:</p>

 - Design solutions that incorporate services to meet business requirements and future needs.

 - Design secure, resilient, high-performance and cost-effective architectures.

 - Analyze existing solutions and determine how to make improvements.

## IAM & AWS CLI

<img src="./images/iam.jpg" alt="Image IAM">

### What is the IAM? 
<p>IAM (AWS Identity and Access Management), is an internet service that helps you control access to the resources securely.</p> 

<p>Root account created by default, shouldn't be used or shared </p>

<p>Users are people within your organization, and can be grouped</p>

<p>Groups only contain users, not other groups</p>

### IAM: Permissions

 - Users or Groups can be assigned JSON document called policies.

 - These policies define the permissions of the users.

 - In aws you apply the least privilege principle: don't give more permissions than a user needs. 

 - IAM is a global service

### IAM: Polices

Consists of
 - Verion: policy language version, always include "2021-10-17"
 - id: an identifier for the policy (optional)
 - Statement: one or more individual statements (required)
 
Statements consists of
 - Sid: an identifier for the statement (optional)
 - Effect: whether the statement allows or denies access (Allow, Deny)
 - Principal: account/user/role to which this policy applied to
 - Action: list of actions this policy allows or denies
 - Resources: list of resources to which the actions applied to
 - Condition: conditions for when this policy is in effect (optional)

 IAM Policies are JSON documents used to describe permissions within AWS. 

 ### IAM Role
  - IAM Users, applications, and services may assume IAM rules
  - User an IAM policy for permissions

 ### Bringing it all together

 - Step 1: IAM Group
 - Step 2: IAM Policy -> IAM Group
 - Step 3: IAM User -> IAM User

### IAM - Password Policy

 - Strong passwords = higher security for your account
 - In AWS, you can setup a password policy:
  * Set a minimum password lenth
  * Require specific character types:
   - including uppercase letters
   - lowercase letters
   - numbers
   - non-alphanumeric characters

 - Allow all IAM user to change their own passwords
 - Require users to change their password after some time (password expiration)
 - Prevent password re-use

 How can users access AWS ? 

To access AWS, you have three options:
 - AWS Management console (protected by password + MFA)
 - AWS Command line interface (CLI): protected by access keys
 - AWS Software Developer KIt (SDK): for code: protected by access keys

Access keys are generated though the AWS Console
User manager their own access keys
Access Keys are secret, just like a password. Don't share them.
Access key ID ~= Username
Secret Access Key ~= password

What's the AWS SDK? 
 - AWS Software Developement Kit (AWS SDK)
 - Language-specific APIs (set of libraries)
 - Enables you to access and manage AWS services programmatically
 - Embedded within your application
 - Supports
   - SDKs (Javascript, Python, PHP, .NET, Ruby, Java, Go, Node.js, C++)
   - Mobile SDKs (Android, iOS ...)
   - IoT Device SDKs (Embedded C, Arduino ...)

### IAM Roles for services

 - Some AWS service will need to perform actions on your behalf

 - To do so, we will assign permissions to AWS services with IAM Roles

 - Commons roles: 
   - EC2 Instance Roles
   - Lambda Function Roles
   - Roles for CloudFormation

### Security best practices in IAM

 - Require human users to use federation with an identity provider to access AWS using temporary credentials.

 - Require workloads to use temporary credentials with IAM roles to access AWS.

 - Require multi-factor authentication (MFA).

 - Update acces keys when needed for use cases that require long-term credentials.

 - Apply least-privilege permissions.

 - Get started with AWS managed policies and move toward least-privilege permissions.

 - User IAM Access analyzer to generate least-privilege policies based on access activity. 

 - Regular review and remove unused users, roles, permissions, policies, and credentials.

 - Use conditions in IAM policies to further restric access.

 - verify public and cross-account access to resources with IAM access Analyzer.

 - Use IAM Acess Analyzer to validate your IAM policies to ensure secure and functional permissions. 

 - Establish permissions guardrails accrros multiple accounts. 

 - Use permissions boundaries to delegate permissions management within an account.



 ## Fundamentos Técnicos da AWS | AWS Technical Essentials

On-premises e computação em nuvem

Devido ao resultados de operações dispendiosas que impossibilitaram algumas workloads e experimentações e para antender 
a essas necessidades surgiu a computação em nuvem. 

Computação em nuvem é uma entrega sob demanda de recursos de TI pela internet com precificação de pagamento conforme o uso.

### Seis vantagens da computação da nuvem

 - Pagamento conforme o uso: Em vez de investir em datacenters e hardwares antes de saber como você vai usá-los, você paga somente quando usa recursos de computação e apenas pelo quanto você usa. 

 - Beneficiar-se de economia massiva da escala: O uso da computação em nuvem permite obter um custo inferior ao que obtém em seu ambiente local. Considerando que o uso de centenas de milhares de clientes é agregado na nuvem, a AWS consegue obter economias maiores de escala, o que resulta em preços mais baixos com pagamento conforme o uso (pay as-you=go);

 - Parar de adivinhar a capacidade: Elimine as suposições ao determinar suas necessidades de capacidade de infraestrutura. 
 Muitas vezes, ao tomar uma decisão sobre a capacidade antes de implantar uma aplicação, você acaba precisando lidar com recursos e ociosos ou com capacidade limitada. Com a computação em nuvem, esses problemas são resolvidos. Você pode acessar a quantidade de capacidade que quiser e aumentar e reduzir a escala na vertical, conforme a necessidade em apenas alguns minutos. 

 - Aumentar a velocidade e a agilidade: Os recursos de TI estão a apenas um clique de distância, o que significa que você reduz o tempo para disponibilizar recursos para seus desenvolvedores de semanas para minutos. Isso resulta em um aumento drástico na agilidade da organização, pois o custo e o tempo necessário para experimentar e desenvolver são significativamente mais baixos. 

 - Realize economia de custos: As empresas podem se concentrar em projetos que diferenciam seus negócios em vez de manter datacenters. A computação em nuvem permite que você se concentre em seus clientes, ao invés de no trabalho pesado de estruturar, empilhar e manter a estrutura física. Isso, geralmente, é chamado de trabalho pesado indiferenciado.

 - Obtem alcance global em minutos: As aplicações podem ser implantadas em várias regiões ao redor do mundo com alguns cliques. Isso significa que você pode oferecer baixa latência e uma melhor experiência aos seus clientes a um custo mínimo. 

 ### O que são Regioes ?
 As regiões são locais geograficos em todo o mundo em que a AWS hospeda seus datacenters. As regiões da AWS têm o nome do local em que elas residem. Por exemplo, nos Estados unidos, a Região do Norte da virgínia é chamada de Região do Norte da virgínia e a Região no Oregon é chamada de Região do Oregon. A AWS tem regiões na Ásia-Pacífico, Canadá, Europa, Oriente Médio e América do Sul, e continua a expandir para atender às necessidades dos clientes. 

 ### Quando você decidir qual região da AWS hospedar suas aplicações e workloads, considere quatro aspectos principais: 

 - Latência;
 - Preço;
 - Disponibilidade do serviço;
 - Conformidade






 ### AWS Partner: AWS Well-Architected Best Practices

 O que é AWS Well-Architected ? 
  - AWS Well-Architected são as praticas recomendadas pela AWS que ajuda arquitetos de nuvem a construir infraestruturas seguras, resilientes, eficientes, e de alta peformance para aplicações e workoloads. Baseado em seis pilares 
  - Exelência operacional
  - Segurança
  - Confiabilidade
  - eficiência de peformance
  - otimização de custos e sustentabilidade. 

 O que é AWS Well-Architected Framework? 
  - Descreve os principais conceitos, princípios de projeto e praticas recomendadas para projetar e executar workloads na nuvem. Ao responder algumas perguntas fundamentais, você aprende a quanto sua arquitetura se alinha com as práticas recomendadas da nuvem e recebe orientações para fazer melhorias. 


### Praticas recomendadas do IAM


  - Bloquear o usuário raiz da AWS
    O usuário raiz é uma identidade eficiente e abrangente em sua conta da AWS. Se um usuário mal-intencionado ganhasse o controle das credenciais de usuário raiz, ele seria capaz de acessar todos os recursos em sua conta, incluindo informações pessoais e de faturamento. Para bloquear o usuário raiz, você pode fazer o seguinte : 
    Não compartilhar as credenciais associadas ao usuário raiz;
    Considere excluir as chaves de acesso do usuário raiz;
    Habilitar MFA na conta raiz.

### Computação

 - on-primeses
 - cloud


### Amazon EC2

Para criar uma instância do EC2, você deve definir o seguinte: 

 - Especificações de hardware, como CPU, memória, rede e armazenamento
 - Configurações lógicas, como localização de rede, regras de firewall, autenticação e sistema operacional de sua escolha. 
# Breve descrição de cada serviço cobrado na prova AWS Cloud Practitioner

## Sumário

[Analytics](#analytics)

- [Amazon Athena](#amazon-athena)
- [AWS Data Exchange](#aws-data-exchange)
- [Amazon EMR (Elastic MapReduce)](#amazon-emr-elastic-mapreduce)
- [AWS Glue](#aws-glue)
- [Amazon Kinesis](#amazon-kinesis)
- [Amazon MSK (Managed Streaming for Apache Kafka)](#amazon-msk-managed-streaming-for-apache-kafka)
- [Amazon OpenSearch Service](#amazon-opensearch-service)
- [Amazon QuickSight](#amazon-quicksight)
- [Amazon Redshift](#amazon-redshift)

[Integração de Aplicativos](#integração-de-aplicativos)

- [Amazon EventBridge](#amazon-eventbridge)
- [Amazon Simple Notification Service (Amazon SNS)](#amazon-simple-notification-service-amazon-sns)
- [Amazon Simple Queue Service (Amazon SQS)](#amazon-simple-queue-service-amazon-sqs)
- [AWS Step Functions](#aws-step-functions)

[Aplicações Empresariais](#aplicações-empresariais)

- [Amazon Connect](#amazon-connect)
- [Amazon Simple Email Service (Amazon SES)](#amazon-simple-email-service-amazon-ses)

[Gestão financeira na nuvem](#gestão-financeira-na-nuvem)

- [AWS Budgets](#aws-budgets)
- [AWS Relatório de Uso e Custo](#aws-relatório-de-uso-e-custo)
- [AWS Cost Explorer](#aws-cost-explorer)

[Computação](#computação)

- [AWS Batch](#aws-batch)
- [Amazon EC2 (Elastic Compute Cloud)](#amazon-ec2-elastic-compute-cloud)
- [AWS Elastic Beanstalk](#aws-elastic-beanstalk)
- [Amazon Lightsail](#amazon-lightsail)
- [Zonas Locais da AWS](#zonas-locais-da-aws)
- [AWS Outposts](#aws-outposts)
- [AWS Wavelength](#aws-wavelength)

[Contêineres](#contêineres)

- [Amazon Elastic Container Registry (Amazon ECR)](#amazon-elastic-container-registry-amazon-ecr)
- [Amazon Elastic Container Service (Amazon ECS)](#amazon-elastic-container-service-amazon-ecs)
- [Amazon Elastic Kubernetes Service (Amazon EKS)](#amazon-elastic-kubernetes-service-amazon-eks)

[Interação com os Clientes](#interação-com-os-clientes)

- [AWS Activate para Startups](#aws-activate-para-startups)
- [AWS IQ](#aws-iq)
- [AWS Managed Services (AMS)](#aws-managed-services-ams)
- [AWS Support](#aws-support)

[Banco de dados](#banco-de-dados)

- [Amazon Aurora](#amazon-aurora)
- [Amazon DynamoDB](#amazon-dynamodb)
- [Amazon MemoryDB para Redis](#amazon-memorydb-para-redis)
- [Amazon Neptune](#amazon-neptune)
- [Amazon RDS (Relational Database Service)](#amazon-rds-relational-database-service)

[Ferramentas do Desenvolvedor](#ferramentas-do-desenvolvedor)

- [AWS AppConfig](#aws-appconfig)
- [AWS CLI (Command Line Interface)](#aws-cli-command-line-interface)
- [AWS Cloud9](#aws-cloud9)
- [AWS CloudShell](#aws-cloudshell)
- [AWS CodeArtifact](#aws-codeartifact)
- [AWS CodeBuild](#aws-codebuild)
- [AWS CodeCommit](#aws-codecommit)
- [AWS CodeDeploy](#aws-codedeploy)
- [AWS CodePipeline](#aws-codepipeline)
- [AWS CodeStar](#aws-codestar)
- [AWS X-Ray](#aws-x-ray)

[Computação de Usuário Final](#computação-de-usuário-final)

- [Amazon AppStream 2.0](#amazon-appstream-20)
- [Amazon Workspaces](#amazon-workspaces)
- [Amazon WorkSpaces Web](#amazon-workspaces-web)
  
[Web e Dispositivos Móveis de Front-end](#web-e-dispositivos-móveis-de-front-end)

- [AWS Amplify](#aws-amplify)
- [AWS AppSync](#aws-appsync)
- [AWS Device Farm](#aws-device-farm)

[Internet das Coisas (IoT)](#internet-das-coisas-iot)

- [AWS IoT Core](#aws-iot-core)
- [AWS IoT Greengrass](#aws-iot-greengrass)

[Machine Learning](#machine-learning)

- [Amazon Comprehend](#amazon-comprehend)
- [Amazon Kendra](#amazon-kendra)
- [Amazon Lex](#amazon-lex)
- [Amazon Polly](#amazon-polly)
- [Amazon Rekognition](#amazon-rekognition)
- [Amazon SageMaker](#amazon-sagemaker)
- [Amazon Textract](#amazon-textract)
- [Amazon Transcribe](#amazon-transcribe)
- [Amazon Translate](#amazon-translate)

[Gerenciamento e Governança](#gerenciamento-e-governança)

- [AWS Auto Scaling](#aws-auto-scaling)
- [AWS CloudFormation](#aws-cloudformation)
- [AWS CloudTrail](#aws-cloudtrail)
- [Amazon CloudWatch](#amazon-cloudwatch)
- [AWS Compute Optimizer](#aws-compute-optimizer)
- [AWS Config](#aws-config)
- [AWS Control Tower](#aws-control-tower)
- [AWS Health Dashboard](#aws-health-dashboard)
- [AWS Launch Wizard](#aws-launch-wizard)
- [AWS License Manager](#aws-license-manager)

[Console de Gerenciamento da AWS](#console-de-gerenciamento-da-aws)

- [Console de Gerenciamento](#console-de-gerenciamento)

[Gerenciamento de Contas e Recursos](#gerenciamento-de-contas-e-recursos)

- [AWS Organizations](#aws-organizations)
- [AWS Resource Groups e Tag Editor](#aws-resource-groups-e-tag-editor)

[Serviços de Governança e Compliance](#serviços-de-governança-e-compliance)

- [AWS Service Catalog](#aws-service-catalog)
- [AWS Systems Manager](#aws-systems-manager)
- [AWS Trusted Advisor](#aws-trusted-advisor)

[AWS Well-Architected Tool](#aws-well-architected-tool)

- [Ferramenta do AWS Well-Architected](#ferramenta-do-aws-well-architected)

[Migração e Transferência](#migração-e-transferência)

- [AWS Application Discovery Service](#aws-application-discovery-service)
- [AWS Application Migration Service (AWS AMS)](#aws-application-migration-service-aws-ams)
- [AWS Database Migration Service (AWS DMS)](#aws-database-migration-service-aws-dms)
- [AWS Migration Hub](#aws-migration-hub)
- [AWS Schema Conversion Tool (AWS SCT)](#aws-schema-conversion-tool-aws-sct)
- [Família AWS Snow](#família-aws-snow)
- [AWS Transfer Family](#aws-transfer-family)

[Redes e Entrega de Conteúdo](#redes-e-entrega-de-conteúdo)

- [Amazon API Gateway](#amazon-api-gateway)
- [Amazon CloudFront](#amazon-cloudfront)
- [AWS Direct Connect](#aws-direct-connect)
- [AWS Global Accelerator](#aws-global-accelerator)
- [Amazon Route 53](#amazon-route-53)
- [Amazon VPC (Virtual Private Cloud)](#amazon-vpc-virtual-private-cloud)
- [AWS VPN (Virtual Private Network)](#aws-vpn-virtual-private-network)

[Segurança, Identidade e Conformidade](#segurança-identidade-e-conformidade)

- [AWS Artifact](#aws-artifact)
- [AWS Audit Manager](#aws-audit-manager)
- [AWS Certificate Manager (ACM)](#aws-certificate-manager-acm)
- [AWS CloudHSM](#aws-cloudhsm)
- [Amazon Cognito](#amazon-cognito)
- [Amazon Detective](#amazon-detective)
- [AWS Directory Service](#aws-directory-service)
- [AWS Firewall Manager](#aws-firewall-manager)
- [Amazon GuardDuty](#amazon-guardduty)
- [AWS Identity and Access Management (IAM)](#aws-identity-and-access-management-iam)
- [AWS IAM Identity Center (AWS Single Sign-On)](#aws-iam-identity-center-aws-single-sign-on)
- [Amazon Inspector](#amazon-inspector)
- [AWS Key Management Service (AWS KMS)](#aws-key-management-service-aws-kms)
- [Amazon Macie](#amazon-macie)
- [AWS Network Firewall](#aws-network-firewall)
- [AWS Resource Access Manager (AWS RAM)](#aws-resource-access-manager-aws-ram)
- [AWS Secrets Manager](#aws-secrets-manager)
- [AWS Security Hub](#aws-security-hub)
- [AWS Shield](#aws-shield)
- [AWS WAF (Web Application Firewall)](#aws-waf-web-application-firewall)

[Serverless](#serverless)

- [AWS Fargate](#aws-fargate)
- [AWS Lambda](#aws-lambda)

[Armazenamento](#armazenamento)

- [AWS Backup](#aws-backup)
- [Amazon Elastic Block Store (Amazon EBS)](#amazon-elastic-block-store-amazon-ebs)
- [Amazon Elastic File System (Amazon EFS)](#amazon-elastic-file-system-amazon-efs)
- [AWS Elastic Disaster Recovery](#aws-elastic-disaster-recovery)
- [Amazon FSx](#amazon-fsx)
- [Amazon S3 (Simple Storage Service)](#amazon-s3-simple-storage-service)
- [Amazon S3 Glacier](#amazon-s3-glacier)
- [AWS Storage Gateway](#aws-storage-gateway)

## Analytics

### Amazon Athena

**Descrição:** Permite consultar dados armazenados no Amazon S3 usando SQL padrão.

**Como funciona:** O Amazon Athena é um serviço de análise interativo e sem servidor criado em frameworks de código aberto, com suporte a formatos de tabela e arquivo abertos. O Athena fornece uma maneira simplificada e flexível de analisar petabytes de dados onde eles residem. Analise dados ou crie aplicações a partir de um data lake do Amazon Simple Storage Service (S3) e mais de 30 fontes de dados, incluindo fontes de dados on-premises ou outros sistemas em nuvem usando SQL ou Python. O Athena é construído com mecanismos Trino e Presto de código aberto e frameworks Apache Spark, sem necessidade de provisionamento ou configuração.

**Uso típico:** Análise ad-hoc de dados armazenados no Amazon S3. Conheça os conceitos e tipos de buckets, objetos, políticas de controle de acesso e configurações de versão. Evite configurações de acesso públicas não intencionais.

### AWS Data Exchange

**Descrição:** Facilita a troca segura de dados entre organizações.

**Como funciona:** O AWS Data Exchange é o único mercado de dados com mais de 300 provedores que oferece milhares de conjuntos de dados por meio de arquivos, tabelas e APIs, tudo em um só lugar. Como assinante de dados, você pode procurar conjuntos de dados no AWS Marketplace  e encontrar a assinatura certa para o seu negócio. Como provedor de dados, você pode aproveitar as tecnologias mais recentes da AWS para experimentar, criar e fornecer ofertas diferenciadas aos seus clientes.

**Uso típico:** Compartilhamento de conjuntos de dados entre diferentes empresas.

### Amazon EMR (Elastic MapReduce)

**Descrição:** Oferece ambiente de processamento distribuído para processar grandes volumes de dados usando frameworks como Apache Spark e Hadoop.

**Como funciona:** Amazon EMR é a solução de big data em nuvem líder do setor para processamento de dados, análise interativa e machine learning que usa estruturas de código aberto, como Apache Spark, Apache Hive e Presto.

**Uso típico:** Processamento e análise de grandes conjuntos de dados.

### AWS Glue

**Descrição:** Serviço de ETL (Extract, Transform, Load) totalmente gerenciado para preparar e carregar dados para análise.

**Como funciona:** O AWS Glue é um serviço de integração de dados com tecnologia sem servidor que facilita a descoberta, preparação, movimentação e integração de dados de várias fontes para análise, machine learning (ML) e desenvolvimento de aplicações.

**Uso típico:** Limpeza e transformação de dados para análise.

### Amazon Kinesis

**Descrição:** Permite a ingestão e processamento em tempo real de grandes volumes de dados de streaming.

**Como funciona:** O Amazon Kinesis processa e analisa de forma econômica os dados de streaming em qualquer escala como um serviço totalmente gerenciado. Com o Kinesis, você pode consumir dados em tempo real como vídeo, áudio, logs de aplicações, clickstreams de sites e dados de telemetria de IoT para machine learning (ML), análises e outras aplicações.

**Uso típico:** Análise de dados de streaming em tempo real.

### Amazon MSK (Managed Streaming for Apache Kafka)

**Descrição:** Oferece um serviço gerenciado para clusters Apache Kafka, facilitando a construção de aplicativos de streaming.

**Como funciona:** O Amazon MSK facilita a ingestão e o processamento de dados de streaming em tempo real com o Apache Kafka totalmente gerenciado.

**Uso típico:** Processamento de dados em tempo real usando Kafka.

### Amazon OpenSearch Service

**Descrição:** Serviço totalmente gerenciado que facilita a implantação, operação e escala do Elasticsearch.

**Como funciona:** O Amazon OpenSearch Service facilita a execução de análises de log interativas, o monitoramento de aplicações em tempo real, pesquisas de sites e muito mais. O OpenSearch é um conjunto de pesquisa e análise de código aberto distribuído derivado do Elasticsearch. O Amazon OpenSearch Service oferece as versões mais recentes do OpenSearch, suporte para 19 versões do Elasticsearch (versões de 1.5 a 7.10), bem como recursos de visualização fornecidos pelo OpenSearch Dashboards e Kibana (versões de 1.5 a 7.10). O Amazon OpenSearch Service atualmente tem dezenas de milhares de clientes ativos com centenas de milhares de clusters sob gerenciamento processando centenas de trilhões de solicitações por mês.

**Uso típico:** Pesquisa e análise de dados não estruturados.

### Amazon QuickSight

**Descrição:** Serviço de visualização de dados que torna mais fácil criar gráficos, dashboards e relatórios interativos.

**Como funciona:** O Amazon QuickSight permite que todos em sua organização entendam seus dados por meio de perguntas em linguagem natural, do uso de painéis interativos ou procurando automaticamente padrões e discrepâncias com tecnologia de machine learning.

**Uso típico:** Criação de painéis de visualização para análise de dados.

### Amazon Redshift

**Descrição:** Data warehouse totalmente gerenciado, otimizado para análise de grandes conjuntos de dados.

**Como funciona:** O Amazon Redshift usa SQL para analisar dados estruturados e semiestruturados em data warehouses, bancos de dados operacionais e data lakes, usando hardware e machine learning criados pela AWS para oferecer a melhor relação entre preço e performance em qualquer escala.

**Uso típico:** Armazenamento e consulta de dados analíticos.

## Integração de Aplicativos

### Amazon EventBridge

**Descrição:** Serviço de barramento de eventos para ingestão, processamento e entrega de eventos em tempo real.

**Como funciona:** Crie aplicações orientadas por eventos em escala na AWS, sistemas existentes ou aplicações SaaS

**Uso típico:** Integração de diferentes serviços e aplicativos por meio de eventos.

### Amazon Simple Notification Service (Amazon SNS)

**Descrição:** Serviço de mensagens pub/sub (publicar/assinar) que permite a entrega de mensagens para diferentes destinos.

**Como funciona:** O Amazon Simple Notiﬁcation Service (Amazon SNS) envia notificações de duas maneiras: A2A e A2P. A maneira A2A fornece um sistema de mensagens com alto throughput e baseado em push para mensagens entre diversos sistemas distribuídos, microsserviços e aplicações sem servidor orientadas a eventos. Essas aplicações incluem o Amazon Simple Queue Service (SQS), o Amazon Kinesis Data Firehose, o AWS Lambda e outros endpoints HTTPS. A funcionalidade A2P, por sua vez, permite o envio de mensagens para seus clientes utilizando textos SMS, notificações por push e e-mail.

**Uso típico:** Envio de notificações push, e-mails, e mensagens de texto.

### Amazon Simple Queue Service (Amazon SQS)

**Descrição:** Serviço de fila de mensagens que permite a comunicação entre diferentes partes de um aplicativo.

**Como funciona:** O Amazon Simple Queue Service (SQS) permite que você envie, armazene e receba mensagens entre componentes de software em qualquer volume, sem perder mensagens ou precisar que outros serviços estejam disponíveis.

**Uso típico:** Desacoplamento de componentes de aplicativos distribuídos.

### AWS Step Functions

**Descrição:** Serviço que coordena a execução de várias funções como um fluxo de trabalho.

**Como funciona:** O AWS Step Functions é um serviço de fluxo de trabalho visual que ajuda os desenvolvedores a usar os produtos da AWS para desenvolver aplicações distribuídas, automatizar processos, orquestrar microsserviços e criar pipelines de dados e machine learning (ML).

**Uso típico:** Orquestração de tarefas e microserviços em aplicativos.

## Aplicações Empresariais

### Amazon Connect

**Descrição:** Serviço de centro de contato na nuvem para interações com clientes.

**Como funciona:** Com o Amazon Connect, você pode configurar uma central de atendimento em questão de minutos, e ela pode ser dimensionada para oferecer suporte a milhões de clientes.

**Uso típico:** Implementação de soluções de atendimento ao cliente.

### Amazon Simple Email Service (Amazon SES)

**Descrição:** Serviço para envio de e-mails em grande escala de maneira econômica.

**Como funciona:** O Amazon Simple Email Service (Amazon SES) permite que você alcance clientes com confiança sem um servidor de e-mail on-premises do Simple Mail Transfer Protocol (SMTP) usando a API do Amazon SES ou a interface SMTP.

**Uso típico:** Envio de e-mails transacionais e de marketing.

## Gestão financeira na nuvem

### AWS Billing Conductor

**Descrição:** Ferramenta para gerenciar e otimizar os custos da AWS, proporcionando visibilidade e controle financeiro.

**Como funciona:** O AWS Billing Conductor é um serviço de cobrança personalizável que personalizar dados de cobrança para corresponder a uma lógica comercial desejada de reembolsos ou estornos. Para começar, você mapeia suas contas para grupos de cobrança, que são mutuamente exclusivos. Em seguida, pode definir os parâmetros de cobrança para cada grupo, como regras de preços e itens de linha personalizados. Depois que cada grupo de cobrança for definido, você poderá visualizar a saída da sua configuração, por grupo de cobrança, na página Faturas do console de cobrança, além de gerar um Relatório de custo e uso (CUR) para cada grupo de cobrança.

**Uso típico:** Análise e otimização de custos na nuvem.

### AWS Budgets

**Descrição:** Serviço que ajuda a definir metas de custo personalizadas e a receber alertas quando os limites são atingidos.

**Como funciona:** Com o AWS Budgets, defina orçamentos personalizados para rastrear seus custos e o uso e responda rapidamente a alertas recebidos de notificações por email ou SNS se você exceder seu limite.

**Uso típico:** Monitoramento e controle de gastos na AWS.

### AWS Relatório de Uso e Custo

**Descrição:** Fornece relatórios detalhados sobre o uso e os custos dos recursos da AWS.

**Como funciona:** Com o AWS Cost and Usage Reports (CUR), você pode revisar, detalhar e organizar os dados mais abrangentes de custo e uso para sua conta.

**Uso típico:** Análise detalhada do consumo e custos na nuvem.

### AWS Cost Explorer

**Descrição:** Ferramenta de visualização que ajuda a explorar, entender e controlar os custos da AWS.

**Como funciona:** O Explorador de Custos da AWS tem uma interface fácil de usar que permite visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo. Comece a usar rapidamente criando relatórios personalizados que analisam dados de custos e uso. Analise dados de forma resumida (por exemplo, custos e uso totais em todas as contas) ou detalhe os dados de custos e uso para identificar tendências, determinar causadores de custos e detectar anomalias.

**Uso típico:** Análise visual e relatórios sobre os custos na AWS.

## Computação

### AWS Batch

**Descrição:** Serviço para executar trabalhos em lote de maneira eficiente na AWS.

**Como funciona:** O AWS Batch permite que desenvolvedores, cientistas e engenheiros executem com eficiência milhares de tarefas de computação em lote e em ML enquanto otimizam recursos computacionais para que você possa se concentrar na análise de resultados e na solução de problemas.

**Uso típico:** Processamento em lote de grandes volumes de dados.

### Amazon EC2 (Elastic Compute Cloud)

**Descrição:** Oferece capacidade de computação redimensionável na nuvem.

**Como funciona:** O Amazon Elastic Compute Cloud (Amazon EC2) oferece a plataforma de computação mais ampla e aprofundada, com mais de 750 instâncias e opções de processadores, armazenamentos, redes, sistemas operacionais e modelos de compras mais recentes para ajudar você a atender melhor às necessidades da sua workload. Somos o primeiro grande provedor de nuvem a oferecer suporte para processadores Intel, AMD e Arm, a única nuvem com instâncias Mac do EC2 sob demanda e a única nuvem com redes Ethernet de 400 Gbps. Oferecemos a melhor performance de preço para treinamento de machine learning, bem como o menor custo por instâncias de inferência na nuvem. Mais workloads SAP, computação de alta performance (HPC), ML e Windows são executadas na AWS do que qualquer outra nuvem.

**Uso típico:** Hospedagem de aplicativos e máquinas virtuais. Familiarize-se com tipos de instância, grupos de segurança, pares de chaves, volumes de armazenamento e imagens AMI. Mantenha a segurança aplicando atualizações e patches.

### AWS Elastic Beanstalk

**Descrição:** Facilita a implantação e a escalabilidade de aplicativos web.

**Como funciona:** O Elastic Beanstalk é um serviço para implementar e escalar aplicações e serviços da Web. Envie seu código e o Elastic Beanstalk gerencia automaticamente a implantação, desde o provisionamento de capacidade, balanceamento de carga e escalabilidade automática até o monitoramento da integridade de aplicações.

**Uso típico:** Implantação rápida e gerenciamento de aplicativos web. Compreenda as políticas IAM, papéis, usuários e grupos. Implemente o princípio do menor privilégio ao conceder permissões.

### Amazon Lightsail

**Descrição:** Oferece instâncias de máquinas virtuais, bancos de dados e outros recursos para facilitar o início de projetos.

**Como funciona:** Crie um site ou uma aplicação com apenas alguns cliques. Configure automaticamente ambientes de rede, acesso e segurança. Escale facilmente à medida que você cresce ou migre seus recursos para o ecossistema mais amplo da AWS, como o Amazon EC2.

**Uso típico:** Implantação simplificada de aplicativos web.

### Zonas Locais da AWS

**Descrição:** Extensão da infraestrutura da AWS para locais físicos para processamento local.

**Como funciona:** O AWS Local Zones é uma espécie de implantação de infraestrutura posiciona a computação, armazenamento, banco de dados e outros produtos seletos da AWS perto do público em geral e dos centros industriais.

**Uso típico:** Execução de aplicativos em locais específicos.

### AWS Outposts

**Descrição:** Oferece infraestrutura totalmente gerenciada na premiação para estender os serviços da AWS.

**Como funciona:** O AWS Outposts é uma família de soluções totalmente gerenciadas que fornecem infraestrutura e serviços da AWS para praticamente qualquer local da borda ou on-premises para uma experiência híbrida verdadeiramente consistente. As soluções do Outposts permitem que os clientes estendam e executem serviços da AWS nativos on-premises e estão disponíveis em uma variedade de formatos, de servidores Outposts 1U e 2U a racks Outposts 42U e várias implantações de rack.

**Uso típico:** Execução de serviços da AWS localmente.

### AWS Wavelength

**Descrição:** Fornece serviços da AWS em bordas de rede para aplicativos de baixa latência.

**Como funciona:** O AWS Wavelength incorpora serviços de computação e armazenamento da AWS em redes 5G, fornecendo infraestrutura de computação de borda móvel para desenvolvimento, implantação e escalabilidade de aplicações de latência ultrabaixa.

**Uso típico:** Aplicações sensíveis à latência em dispositivos móveis e IoT.

## Contêineres

### Amazon Elastic Container Registry (Amazon ECR)

**Descrição:** Registro totalmente gerenciado para armazenar, gerenciar e implantar imagens de contêiner do Docker.

**Como funciona:** O Amazon Elastic Container Registry (Amazon ECR) é um registro de contêiner totalmente gerenciado que oferece hospedagem de alta performance para que você possa implantar imagens e artefatos de aplicações de forma confiável em qualquer lugar.

**Uso típico:** Armazenamento e distribuição de imagens de contêiner.

### Amazon Elastic Container Service (Amazon ECS)

**Descrição:** Serviço de orquestração de contêineres que facilita a execução de aplicativos em contêineres na AWS.

**Como funciona:** Basta descrever suas aplicação e os recursos necessários, e o Amazon ECS vai executar, monitorar e escalar a aplicação em opções flexíveis de computação com integrações automáticas com outros serviços de suporte da AWS de que sua aplicação precise. Execute operações do sistema, como criar regras personalizadas de escalabilidade e capacidade, além de observar e consultar dados de logs de aplicações e telemetria.

**Uso típico:** Implantação e gerenciamento de contêineres. Compreenda a orquestração de contêineres, clusters, tarefas e serviços. Esteja ciente das opções de implantação e monitoramento.

### Amazon Elastic Kubernetes Service (Amazon EKS)

**Descrição:** Serviço totalmente gerenciado que facilita a execução do Kubernetes na AWS.

**Como funciona:** O Amazon Elastic Kubernetes Service (Amazon EKS) é um serviço gerenciado do Kubernetes para executar o Kubernetes na nuvem da AWS e em datacenters on-premises. Na nuvem, o Amazon EKS gerencia automaticamente a disponibilidade e a escalabilidade dos nós do ambiente de gerenciamento do Kubernetes, que são responsáveis por programar contêineres, gerenciar a disponibilidade das aplicações, armazenar dados de cluster e outras tarefas principais. Com o Amazon EKS, você pode aproveitar toda a performance, escalabilidade, confiabilidade e disponibilidade da infraestrutura da AWS, bem como integrações com serviços de rede e segurança da AWS. On-premises, o EKS fornece uma solução Kubernetes consistente e totalmente compatível com ferramentas integradas e implantação simples em AWS Outposts, máquinas virtuais ou servidores bare metal.

**Uso típico:** Orquestração de contêineres usando o Kubernetes.

## Interação com os Clientes

### AWS Activate para Startups

**Descrição:** Oferece recursos e benefícios para startups em estágio inicial, incluindo créditos e suporte técnico.

**Como funciona:** Por meio do AWS Activate, a AWS disponibilizou bilhões de dólares para possibilitar que as empresas solucionem os problemas mais complexos do mundo e provem o que é possível com o poder da tecnologia em nuvem. Inscreva-se para receber até USD 100 mil em créditos da AWS a fim de garantir os recursos e o capital necessários para começar a preparação para o futuro.

**Uso típico:** Apoio a startups no desenvolvimento e crescimento.

### AWS IQ

**Descrição:** Conecta clientes com especialistas da AWS para receberem assistência técnica, pagando por hora ou por projeto.

**Como funciona:** O AWS IQ permite que os clientes encontrem, colaborem com segurança e paguem especialistas terceirizados certificados pela AWS para trabalhos sob demanda em um projeto. Especialistas em AWS IQ podem ajudar você a iniciar e concluir seus projetos mais rapidamente oferecendo ajuda prática remotamente em vários tipos de projetos, como hospedagem do seu site, migração do seu banco de dados, configuração da sua rede, criação de sua solução de análise ou otimização do seu uso de serviços da AWS.

**Uso típico:** Obtenção de ajuda especializada em projetos específicos.

### AWS Managed Services (AMS)

**Descrição:** Oferece serviços gerenciados para operações diárias de infraestrutura na AWS.

**Como funciona:** O AWS Managed Services (AMS) ajuda você a adotar a AWS em escala e a operar com mais eficiência e segurança. Aproveitamos os serviços padrão da AWS e oferecemos orientação e execução das práticas recomendadas operacionais, com automações, habilidades e experiência especializadas que são contextuais ao seu ambiente e aplicações. O AMS fornece recursos proativos, preventivos e de detecção que elevam o nível operacional e ajudam a reduzir riscos sem restringir a agilidade, permitindo que você se concentre na inovação. A AMS amplia sua equipe com recursos operacionais, incluindo monitoramento, gerenciamento de incidentes, Detecção e Resposta a Incidentes da AWS, segurança, patches, backup e otimização de custos.

**Uso típico:** Terceirização de operações e gerenciamento de infraestrutura.

### AWS Support

**Descrição:** Oferece planos de suporte técnico para ajudar os clientes a aproveitarem ao máximo os serviços da AWS.

**Como funciona:**

- Developer: Recomendado se você estiver experimentando ou testando a AWS
- Business: Nível mínimo recomendado para quem tem workloads de produção na AWS.
- Enterprise On-Ramp: Recomendado para quem tem workloads essenciais à produção ou aos negócios na AWS
- Enterprise: Recomendado para quem tem negócios e/ou workloads essenciais na AWS
  
**Uso típico:** Suporte técnico e consultoria para clientes AWS.

## Banco de Dados

### Amazon Aurora

**Descrição:** Banco de dados relacional compatível com MySQL e PostgreSQL, oferecendo desempenho e escalabilidade aprimorados.

**Como funciona:** O Amazon Aurora oferece segurança integrada, backups contínuos, computação sem servidor, até 15 réplicas de leitura, replicação multirregional automatizada e integrações com outros produtos da AWS.

**Uso típico:** Aplicações que exigem um banco de dados relacional de alto desempenho.

### Amazon DynamoDB

**Descrição:** Banco de dados NoSQL totalmente gerenciado, altamente escalável e de baixa latência.

**Como funciona:** O Amazon DynamoDB é um banco de dados de chave-valor NoSQL, sem servidor e totalmente gerenciado, projetado para executar aplicações de alta performance em qualquer escala. O DynamoDB oferece segurança integrada, backups contínuos, replicação multirregional automatizada, armazenamento em cache na memória e ferramentas de importação e exportação de dados.

**Uso típico:** Aplicações que requerem acesso rápido e escalabilidade horizontal.

### Amazon MemoryDB para Redis

**Descrição:** Banco de dados totalmente gerenciado baseado no Redis, otimizado para casos de uso de cache e armazenamento em memória.

**Como funciona:** O Amazon MemoryDB para Redis é um banco de dados durável com leituras de microssegundos, gravações baixas de menos de dez milissegundos, escalabilidade e segurança corporativa. O MemoryDB oferece disponibilidade de 99,99% e recuperação quase instantânea sem perda de dados.

**Uso típico:** Caching e armazenamento em memória de dados.

### Amazon Neptune

**Descrição:** Banco de dados de grafo totalmente gerenciado que permite criar e consultar grafos.

**Como funciona:** O Amazon Neptune Database é um banco de dados de grafos com tecnologia sem servidor criado para escalabilidade e disponibilidade superiores. O Neptune Database oferece segurança integrada, backups contínuos e integrações com outros produtos da AWS.
O Amazon Neptune Analytics é um mecanismo de banco de dados analítico que permite analisar rapidamente grandes volumes de dados de grafos para gerar insights e encontrar tendências com base em dados armazenados em buckets do Amazon S3 ou em um banco de dados do Neptune. O Neptune Analytics usa algoritmos integrados, pesquisa vetorial e computação na memória para executar em questão de segundos consultas em dados com dezenas de bilhões de relacionamentos.

**Uso típico:** Modelagem e consulta de dados em formato de grafo.

### Amazon RDS (Relational Database Service)

**Descrição:** Oferece serviços gerenciados para bancos de dados relacionais, como MySQL, PostgreSQL, Oracle e SQL Server.

**Como funciona:** O Amazon Relational Database Service (Amazon RDS) é uma coleção de serviços gerenciados que facilita a configuração, a operação e a escalabilidade de bancos de dados na nuvem. Escolha entre oito mecanismos populares: Amazon Aurora PostgreSQL Compatible Edition, Amazon Aurora MySQL Compatible Edition , RDS for PostgreSQL , RDS for MySQL, RDS for MariaDB, RDS for SQL Server, RDS for Oracle e RDS for Db2. Implante localmente com o Amazon RDS no AWS Outposts ou com acesso elevado ao sistema operacional subjacente e ao ambiente de banco de dados usando o Amazon RDS Custom.

**Uso típico:** Implantação e gerenciamento simplificado de bancos de dados relacionais. Conheça os tipos de banco de dados suportados, opções de backup, configurações de segurança e escalabilidade.

## Ferramentas do Desenvolvedor

### AWS AppConfig

**Descrição:** Gerencia a configuração de aplicativos em tempo real, permitindo ajustes dinâmicos sem precisar redeploy.

**Como funciona:** O AWS AppConfig reduz o tempo de inatividade do aplicativo, permitindo que você crie regras para validar sua configuração. AWS AppConfig simplifica a administração de aplicativos em grande escala ao implantar alterações de configuração a partir de um local central.

**Uso típico:** Configuração dinâmica de aplicativos.

### AWS CLI (Command Line Interface)

**Descrição:** Interface de linha de comando para interagir e gerenciar recursos na AWS.

**Como funciona:** A AWS Command Line Interface (AWS CLI) é uma ferramenta unificada para o gerenciamento de seus produtos da AWS. Com apenas uma ferramenta para baixar e configurar, você poderá controlar vários produtos da AWS pela linha de comando e automatizá-los usando scripts.

A AWS CLI v2 oferece diversos novos recursos incluindo instaladores aprimorados, novas opções de configuração, como AWS IAM Identity Center (sucessor do AWS SSO), e vários recursos interativos.

**Uso típico:** Automação de tarefas e gerenciamento de recursos via linha de comando.

### AWS Cloud9

**Descrição:** Ambiente de desenvolvimento integrado (IDE) baseado na nuvem para escrever, executar e depurar código.

**Como funciona:** O AWS Cloud9 é um Integrated Development Environment (IDE – Ambiente de desenvolvimento integrado) que permite escrever, executar e depurar código usando apenas um navegador. O ambiente inclui um editor de código, um depurador e um terminal. O Cloud9 é fornecido com ferramentas essenciais para linguagens de programação comuns, incluindo JavaScript, Python e PHP, entre outras, para que você não precise instalar arquivos ou configurar a máquina de desenvolvimento para iniciar novos projetos. Como o IDE do Cloud9 é baseado na nuvem, você pode trabalhar nos projetos no escritório, em casa ou em qualquer lugar usando uma máquina conectada à Internet. Além disso, o Cloud9 oferece uma experiência transparente para desenvolvimento de aplicativo sem servidor. Dessa forma, você pode definir recursos, depurar e alternar entre execução local e remota de aplicativos sem servidor com facilidade. Com o Cloud9, você pode compartilhar rapidamente o ambiente de desenvolvimento com sua equipe, o que possibilita a programação em pares e o controle mútuo das entradas em tempo real.

**Uso típico:** Desenvolvimento colaborativo e remoto.

### AWS CloudShell

**Descrição:** Shell baseado na nuvem que fornece uma interface de linha de comando com ambientes pré-configurados.

**Como funciona:** Usando o AWS CloudShell, um shell baseado em navegador, você pode executar scripts rapidamente com a AWS Command Line Interface (CLI), experimentar APIs de serviço usando a AWS CLI e usar outras ferramentas para aumentar sua produtividade. O ícone do CloudShell aparece nas regiões da AWS onde o CloudShell está disponível.

**Uso típico:** Execução de comandos AWS diretamente no navegador.

### AWS CodeArtifact

**Descrição:** Repositório de software gerenciado para armazenar, gerenciar e compartilhar artefatos de software.

**Como funciona:** O CodeArtifact permite armazenar artefatos usando gerenciadores de pacotes populares e criar ferramentas como Maven, Gradle, npm, Yarn, Twine, pip, NuGet e SwiftPM. O CodeArtifact pode buscar automaticamente pacotes de software sob demanda de repositórios de pacotes públicos para que você possa acessar as versões mais recentes das dependências da aplicação.

**Uso típico:** Gerenciamento centralizado de artefatos de software.

### AWS CodeBuild

**Descrição:** Serviço de compilação totalmente gerenciado que compila código fonte, executa testes e produz pacotes de software.

**Como funciona:** O AWS CodeBuild é um serviço de integração contínua totalmente gerenciado que compila código-fonte, executa testes e produz pacotes de software prontos para implantação.

**Uso típico:** Automação do processo de compilação de código.

### AWS CodeCommit

**Descrição:** Serviço de controle de versão totalmente gerenciado que hospeda repositórios Git privados.

**Como funciona:** O AWS CodeCommit é um serviço de controle de código-fonte totalmente gerenciado, seguro e altamente escalável que hospeda repositórios privados do Git.

**Uso típico:** Controle de versão e colaboração em equipe.

### AWS CodeDeploy

**Descrição:** Automatiza a implantação de aplicativos em instâncias EC2, servidores locais e serviços na AWS.

**Como funciona:** O AWS CodeDeploy é um serviço de implantação totalmente gerenciado que automatiza implantações de software em vários serviços de computação, como Amazon Elastic Compute Cloud (EC2), Amazon Elastic Container Service (ECS), AWS Lambda e seus servidores on-premises. Use o CodeDeploy para automatizar implantações de software e eliminar a necessidade de operações manuais propensas a erros.

**Uso típico:** Implantação automatizada e rollback de aplicações.

### AWS CodePipeline

**Descrição:** Serviço de integração contínua e entrega contínua (CI/CD) para automação de pipelines de desenvolvimento.

**Como funciona:** O AWS CodePipeline é um serviço totalmente gerenciado de entrega contínua que ajuda a automatizar pipelines de lançamento para oferecer atualizações rápidas e confiáveis de aplicações e infraestruturas.

**Uso típico:** Automação de fluxos de trabalho de entrega de software.

### AWS CodeStar

**Descrição:** Facilita o desenvolvimento, a implantação e a operação de aplicativos na AWS.

**Como funciona:** O AWS CodeStar permite que você desenvolva, crie e implante rapidamente aplicações na AWS. O AWS CodeStar disponibiliza uma interface de usuário unificada, permitindo que você gerencie facilmente suas atividades de desenvolvimento de software em um só lugar. Com o AWS CodeStar, é possível configurar toda a sua cadeia de ferramentas de entrega contínua em questão de minutos, possibilitando que você comece o lançamento de códigos mais rapidamente. **IMPORTANTE: Em 31 de julho de 2024, a Amazon Web Services (AWS) descontinuará o suporte para criar e visualizar projetos do AWS CodeStar.**

**Uso típico:** Implantação rápida e gerenciamento de aplicativos.

### AWS X-Ray

**Descrição:** Serviço para rastreamento, análise e monitoramento de aplicativos distribuídos.

**Como funciona:** O AWS X-Ray fornece uma visão completa das solicitações à medida que elas percorrem sua aplicação e filtra dados visuais em cargas úteis, funções, rastreamentos, serviços, APIs e muito mais com movimentos sem código e com pouco código.

**Uso típico:** Identificação e resolução de problemas de desempenho em ambientes distribuídos.

## Computação de Usuário Final

### Amazon AppStream 2.0

**Descrição:** Oferece streaming de aplicativos para desktops, permitindo que usuários executem aplicativos remotamente.

**Como funciona:** O AppStream 2.0 corresponde a um serviço do AWS End User Computing (EUC) que pode ser configurado para transmissões de aplicações SaaS ou entrega de áreas de trabalho virtuais com persistência seletiva. Quando o AppStream 2.0 é usado para áreas de trabalho virtuais, os arquivos salvos e as configurações da aplicação persistem entre as sessões do usuário e uma nova área de trabalho virtual é atribuída ao usuário sempre que ele realiza o login.

**Uso típico:** Entrega de aplicativos de forma remota para usuários finais.

### Amazon WorkSpaces

**Descrição:** Fornece desktops virtuais na nuvem, permitindo que usuários acessem recursos de computação de qualquer lugar.

**Como funciona:**

**Uso típico:** Desktops virtuais para colaboração e trabalho remoto.

### Amazon WorkSpaces Web

**Descrição:** Acesso aos desktops virtuais da Amazon WorkSpaces através de um navegador web.

**Como funciona:** O WorkSpaces Web é um serviço baseado em Linux de baixo custo e totalmente gerenciado, projetado para facilitar o acesso seguro ao navegador para sites internos e aplicações de Software-as-a-Service (SaaS – Software como serviço), sem a sobrecarga administrativa de dispositivos, gerenciamento de infraestrutura, software cliente especializado ou conexões de rede privada virtual (VPN).

**Uso típico:** Acesso remoto simplificado a desktops virtuais.

## Web e Dispositivos Móveis de Front-end

### AWS Amplify

**Descrição:** Facilita o desenvolvimento e implantação de aplicativos web e móveis, oferecendo serviços backend gerenciados.

**Como funciona:** Crie e hospede seu front-end, adicione atributos como autenticação e armazenamento, conecte-se a fontes de dados em tempo real, implante e escale para milhões de usuários.

**Uso típico:** Desenvolvimento rápido de aplicativos web e móveis.

### AWS AppSync

**Descrição:** Serviço gerenciado para desenvolver APIs GraphQL que conectam aplicativos web e móveis a fontes de dados na nuvem.

**Como funciona:** O AWS AppSync cria APIs GraphQL e Pub/Sub com tecnologia sem servidor que simplificam o desenvolvimento de aplicações utilizando um único endpoint para consultas, atualizações ou publicações de dados de forma segura.

**Uso típico:** Desenvolvimento de APIs para aplicativos web e móveis.

### AWS Device Farm

**Descrição:** Serviço para teste de aplicativos móveis em vários dispositivos reais e simulados.

**Como funciona:** O AWS Device Farm é um serviço de teste de aplicações que permite melhorar a qualidade de suas aplicações móveis e da Web, testando-os em uma ampla variedade de navegadores de desktop e dispositivos móveis reais; sem precisar provisionar e gerenciar qualquer infraestrutura de teste. O serviço permite que você execute seus testes simultaneamente em vários navegadores de desktop ou dispositivos reais para acelerar a execução do seu conjunto de testes e gera vídeos e logs para ajudá-lo a identificar rapidamente problemas com seu aplicativo.

**Uso típico:** Teste automatizado de aplicativos móveis para garantir a compatibilidade.

## Internet das Coisas (IoT)

### AWS IoT Core

**Descrição:** Oferece recursos para conectar dispositivos IoT à nuvem e interagir com eles.

**Como funciona:** O AWS IoT Core permite conectar bilhões de dispositivos de IoT e rotear trilhões de mensagens para serviços da AWS sem gerenciar a infraestrutura.

**Uso típico:** Gerenciamento e comunicação de dispositivos IoT.

### AWS IoT Greengrass

**Descrição:** Extensão do AWS IoT Core que permite executar serviços locais em dispositivos IoT.

**Como funciona:** O AWS IoT Greengrass é um serviço de nuvem e tempo de execução de borda de código aberto para criar, implantar e gerenciar softwares de dispositivo. O AWS IoT Greengrass provisiona componentes pré-criados para que você possa estender facilmente a funcionalidade do dispositivo de borda sem escrever o código. Os componentes do AWS IoT Greengrass permitem que você adicione recursos e se conecte rapidamente a serviços da AWS ou aplicações de terceiros na borda. Dispositivos IoT podem ter vários tamanhos, de dispositivos pequenos baseados em microcontroladores a grandes dispositivos.

**Uso típico:** Execução de serviços IoT localmente em dispositivos.

## Machine Learning

### Amazon Comprehend

**Descrição:** Serviço de processamento de linguagem natural que identifica insights e sentimentos em texto.

**Como funciona:** O Amazon Comprehend é um serviço de processamento de linguagem natural (NLP) que usa machine learning para descobrir insights e relações nos textos.

**Uso típico:** Análise de sentimento e extração de informações de texto.

### Amazon Kendra

**Descrição:** Oferece pesquisa corporativa poderosa usando aprendizado de máquina.

**Como funciona:** O Amazon Kendra é um serviço de pesquisa empresarial inteligente que ajuda você a pesquisar em diferentes repositórios de conteúdos com conectores integrados.

**Uso típico:** Recuperação de informações em grandes conjuntos de dados.

### Amazon Lex

**Descrição:** Serviço para construir interfaces de conversação em voz e texto.

**Como funciona:** O Amazon Lex é um serviço totalmente gerenciado de inteligência artificial (IA) com modelos avançados de linguagem natural para criar interfaces de conversação em aplicações.

**Uso típico:** Desenvolvimento de chatbots e interfaces de voz.

### Amazon Polly

**Descrição:** Converte texto em fala realista usando tecnologia de síntese de fala.

**Como funciona:** O Amazon Polly usa tecnologias de aprendizado profundo para sintetizar a fala humana com sons naturais, para que você possa converter artigos em fala. Com dezenas de vozes realistas em um amplo conjunto de idiomas, use o Amazon Polly para criar aplicações ativadas por fala.

**Uso típico:** Geração de fala sintética em aplicativos.

### Amazon Rekognition

**Descrição:** Serviço de análise de imagem e vídeo que identifica objetos, pessoas, texto, etc.

**Como funciona:** O Amazon Rekognition é um serviço que facilita a adição de análises visuais avançadas aos aplicativos. O Rekognition para imagem permite criar facilmente aplicativos avançados para pesquisar, verificar e organizar milhões de imagens. O Rekognition Video permite extrair o contexto baseado em movimento de vídeos armazenados ou de streamings ao vivo e ajuda a analisá-los.

**Uso típico:** Reconhecimento e análise de conteúdo visual.

### Amazon SageMaker

**Descrição:** Plataforma de machine learning totalmente gerenciada para treinar, implantar e gerenciar modelos de ML.

**Como funciona:** O SageMaker é um serviço totalmente gerenciado para preparar dados e criar, treinar e implantar modelos de machine learning (ML) para qualquer caso de uso com infraestrutura, ferramentas e fluxos de trabalho totalmente gerenciados.

**Uso típico:** Desenvolvimento e implementação de modelos de machine learning.

### Amazon Textract

**Descrição:** Serviço que extrai texto, formulários e tabelas de documentos.

**Como funciona:** O Amazon Textract corresponde a um serviço de machine learning (ML) que extrai automaticamente textos impressos ou manuscritos, elementos de layout e dados de documentos digitalizados. Esse recurso faz mais do que o simples reconhecimento óptico de caracteres (OCR): ele identifica, entende e extrai dados específicos de documentos. Hoje, muitas empresas extraem dados de documentos digitalizados (como PDFs, imagens, tabelas e formulários) manualmente ou por meio de softwares básicos de OCR que requerem configuração manual e atualizações frequentes para acompanhar mudanças nos formulários.

**Uso típico:** Extração automatizada de informações de documentos.

### Amazon Transcribe

**Descrição:** Converte áudio em texto usando tecnologia de reconhecimento de fala.

**Como funciona:** O Amazon Transcribe é um serviço de inteligência artificial (IA) da AWS que permite converter facilmente discurso em texto. Usando a tecnologia Automatic Speech Recognition (ASR – Reconhecimento automático de fala), você pode usar o Amazon Transcribe em uma variedade de aplicações de negócios, incluindo a transcrição de chamadas de voz do atendimento ao cliente, a geração de legendas em conteúdo de áudio/vídeo e a realização de análise de conteúdo (baseada em texto) de áudio/vídeo.

**Uso típico:** Transcrição automática de áudio.

### Amazon Translate

**Descrição:** Serviço de tradução automática de texto.

**Como funciona:** O Amazon Translate é um serviço de tradução automática neural que fornece traduções de idiomas com rapidez, alta qualidade, acessíveis e personalizáveis.

**Uso típico:** Tradução automática de conteúdo.

## Gerenciamento e Governança

### AWS Auto Scaling

**Descrição:** Dimensiona automaticamente os recursos da AWS para atender às demandas variáveis de carga de trabalho.

**Como funciona:** O AWS Auto Scaling monitora os aplicativos e ajusta automaticamente a capacidade para manter um desempenho constante e previsível pelo menor custo possível. Com o AWS Auto Scaling, é fácil configurar a escalabilidade de aplicativos para vários recursos em diversos serviços em questão de minutos. O serviço oferece uma interface de usuário simples e eficiente que permite criar planos de escalabilidade para recursos, como instâncias e frotas spot do Amazon EC2, tarefas do Amazon ECS, tabelas e índices do Amazon DynamoDB e réplicas do Amazon Aurora. O AWS Auto Scaling ajuda a simplificar a escalabilidade por meio de recomendações que permitem que você otimize o desempenho, os custos ou o equilíbrio entre eles.

**Uso típico:** Garantia de escalabilidade automática para aplicações.

### AWS CloudFormation

**Descrição:** Serviço para provisionamento e gerenciamento de recursos da AWS usando modelos declarativos.

**Como funciona:** O AWS CloudFormation permite modelar, provisionar e gerenciar recursos da AWS e de terceiros ao tratar a infraestrutura como código. O AWS CloudFormation é um serviço que fornece aos desenvolvedores e empresas uma forma fácil de criar um conjunto de recursos relacionados da AWS e de terceiros para provisioná-los e gerenciá-los de forma organizada e previsível.

**Uso típico:** Automação e orquestração de infraestrutura como código.

### AWS CloudTrail

**Descrição:** Serviço que registra todas as chamadas de API feitas em uma conta AWS para auditoria e conformidade.

**Como funciona:** O CloudTrail permite fazer auditoria, monitoramento de segurança e solucionar problemas operacionais rastreando a atividade do usuário e o uso da API. O CloudTrail registra, monitora continuamente e retém a atividade da conta relacionada às ações em sua infraestrutura AWS, dando a você controle sobre armazenamento, análise e ações de correção.

**Uso típico:** Auditoria e rastreamento de atividades na AWS.

### Amazon CloudWatch

**Descrição:** Serviço de monitoramento e observabilidade para recursos da AWS, coletando e visualizando dados.

**Como funciona:** O Amazon CloudWatch é um serviço de monitoramento da AWS para os recursos da nuvem e as aplicações que você executa na AWS. Você pode usar o Amazon CloudWatch para coletar e rastrear métricas, coletar e monitorar arquivos de log e definir alarmes. O Amazon CloudWatch pode monitorar recursos da AWS, como instâncias do Amazon EC2, tabelas do Amazon DynamoDB e instâncias do Amazon RDS DB, além de métricas personalizadas geradas pelas suas aplicações e serviços e quaisquer arquivos de log gerados pelas suas aplicações, hospedados on-premises, híbridos, ou em outras nuvens.

**Uso típico:** Monitoramento em tempo real e geração de logs. Entenda como criar e analisar métricas, definir alarmes, configurar registros e criar dashboards.

### AWS Compute Optimizer

**Descrição:** Analisa recursos da AWS e recomenda mudanças para melhorar o desempenho e reduzir custos.

**Como funciona:** O AWS Compute Optimizer ajuda a evitar o provisionamento excessivo e o subprovisionamento de quatro tipos de recursos da AWS — tipos de instância do Amazon Elastic Compute Cloud (EC2), volumes do Amazon Elastic Block Store (EBS), serviços do Amazon Elastic Container Service (ECS) no AWS Fargate e funções do AWS Lambda — com base em seus dados de utilização.

**Uso típico:** Otimização contínua de recursos computacionais.

### AWS Config

**Descrição:** Fornece um inventário detalhado dos recursos da AWS, além de rastrear alterações e conformidade.

**Como funciona:** O AWS Config é um serviço totalmente gerenciado que oferece inventário de recursos, histórico de configuração e notificações de alteração de configuração para usar a segurança e governança. O AWS Config permite descobrir recursos da AWS atuais, registrar configurações para recursos de terceiros, exportar um inventário completo dos seus recursos com todos os detalhes de configuração e saber como um recurso foi configurado em determinado momento.

**Uso típico:** Gerenciamento de configurações e conformidade.

### AWS Control Tower

**Descrição:** Facilita a configuração e governança segura de várias contas da AWS.

**Como funciona:** O AWS Control Tower oferece a maneira mais fácil de configurar e controlar um ambiente AWS seguro e com várias contas. Ele estabelece uma zona de aterrissagem baseada em modelos de práticas recomendadas e permite a governança usando controles que você pode escolher em uma lista predefinida. A zona de destino é uma linha de base bem arquitetada e com várias contas que segue as práticas recomendadas da AWS. Os controles implementam regras de governança para segurança, conformidade e operações.

**Uso típico:** Governança centralizada de várias contas na AWS.

### AWS Health Dashboard

**Descrição:** Oferece informações sobre o status operacional dos serviços da AWS.

**Como funciona:** O AWS Personal Health Dashboard fornece alertas e orientação para eventos da AWS que podem afetar seu ambiente. Embora o Service Health Dashboard mostre o status geral dos produtos da AWS, o Personal Health Dashboard fornece notificações proativas e transparentes sobre seu ambiente específico na AWS.

**Uso típico:** Monitoramento do status dos serviços da AWS.

### AWS Launch Wizard

**Descrição:** Auxilia no dimensionamento e implantação de aplicativos na AWS.

**Como funciona:** O AWS Launch Wizard oferece uma maneira guiada de dimensionar, configurar e implantar recursos da AWS para aplicações de terceiros, como Microsoft SQL Server Always On e sistemas SAP baseados em HANA, sem a necessidade de identificar e provisionar manualmente recursos individuais da AWS. Para começar, você informa no console de serviço os requisitos de sua aplicação, incluindo performance, número de nós e conectividade. Em seguida, o Launch Wizard identifica os recursos adequados da AWS (como instâncias do EC2 e volumes do EBC) para implantar e executar sua aplicação. O Launch Wizard apresenta uma estimativa de custo da implantação e permite que você modifique seus recursos a fim de visualizar instantaneamente uma avaliação atualizada dos custos.

**Uso típico:** Implementação otimizada de aplicativos.

### AWS License Manager

**Descrição:** Rastreia e gerencia licenças de software na AWS para garantir conformidade.

**Como funciona:** O License Manager oferece flexibilidade e controle para gerenciar o uso de licenças de acordo com sua estrutura e processos organizacionais. O License Manager pode ser definido em diferentes configurações para atender às necessidades específicas do negócio. O License Manager facilita o gerenciamento de suas licenças de software de fornecedores como Microsoft, SAP, Oracle e IBM em ambientes AWS e on-premises.

**Uso típico:** Gerenciamento eficiente de licenças de software.

## Console de Gerenciamento da AWS

### Console de Gerenciamento

**Descrição:** Interface baseada na web para acessar e gerenciar serviços e recursos da AWS.

**Como funciona:** O Console de Gerenciamento da AWS fornece uma interface da web simples para a Amazon Web Services. Faça login usando seu nome da conta e senha da AWS. Se você estiver habilitado para usar a AWS Multi-Factor Authentication, será solicitado o código de autenticação do seu dispositivo.

**Uso típico:** Administração e configuração de recursos na AWS.

## Gerenciamento de Contas e Recursos

### AWS Organizations

**Descrição:** Serviço que permite consolidar várias contas da AWS em uma organização para facilitar a administração.

**Como funciona:** O AWS Organizations ajuda a administrar seu ambiente de maneira centralizada conforme você amplia suas cargas de trabalho na AWS. Quer você seja uma startup em crescimento ou uma grande corporação, o Organizations ajuda a criar programaticamente novas contas e alocar recursos, simplificar o faturamento com a configuração de um único método de pagamento para todas as suas contas, criar grupos de contas para organizar seus fluxos de trabalho e aplicar políticas a esses grupos para governança.

**Uso típico:** Gerenciamento centralizado de contas AWS.

### AWS Resource Groups e Tag Editor

**Descrição:** Permite organizar recursos da AWS com base em tags, facilitando a aplicação de políticas e a visualização.

**Como funciona:**

- Grupos de Recursos: Um Grupo de Recursos é uma coleção de recursos que compartilha uma ou mais tags. Ele pode abranger regiões e serviços e pode ser usado para criar o que é, na verdade, um console personalizado que organiza e consolida as informações necessárias por projeto.

- Editor de tags: Até hoje, quando você decidiu começar a usar tags, você se deparou com a tarefa de percorrer seus recursos da AWS serviço por serviço, região por região e aplicar tags conforme necessário. O novo Tag Editor centraliza e agiliza esse processo

**Uso típico:** Organização e aplicação de políticas com base em tags.

## Serviços de Governança e Compliance

### AWS Service Catalog

**Descrição:** Permite às organizações criar e gerenciar catálogos de serviços aprovados para uso interno.

**Como funciona:** O AWS Service Catalog permite que você gerencie centralmente seus recursos de nuvem para obter governança em escala de seus modelos de infraestrutura como código (IaC), escritos nas configurações do CloudFormation ou do Terraform. Com o AWS Service Catalog, você pode atender aos seus requisitos de conformidade e garantir que seus clientes possam implantar rapidamente os serviços de TI aprovados de que precisam.

**Uso típico:** Padronização e controle de serviços utilizados.

### AWS Systems Manager

**Descrição:** Facilita a automação de tarefas operacionais em ambientes da AWS.

**Como funciona:** O AWS Systems Manager permite centralizar dados operacionais de vários serviços da AWS e automatizar tarefas em todos os seus recursos na AWS e em ambientes de várias nuvens e híbridos. Você pode criar grupos lógicos de recursos como aplicações, diferentes camadas de uma pilha de aplicações ou ambientes de produção em comparação com ambientes de desenvolvimento. Com o Systems Manager, você pode selecionar um grupo de recursos e visualizar suas atividades recentes de API, alterações na configuração dos recursos, notificação associadas, alertas operacionais, inventário de software e o status de conformidade de patches. Você também pode trabalhar em cada grupo de recursos dependendo do que necessitar operacionalmente.

**Uso típico:** Automação e gerenciamento de configurações.

### AWS Trusted Advisor

**Descrição:** Oferece recomendações em tempo real para otimizar recursos, melhorar a segurança e economizar dinheiro.

**Como funciona:** O AWS Trusted Advisor ajuda você a otimizar custos, aumentar o desempenho, melhorar a segurança e a resiliência e operar em grande escala na nuvem. O Trusted Advisor avalia continuamente seu ambiente da AWS usando verificações de práticas recomendadas entre as categorias de otimização de custos, performance, resiliência, segurança, excelência operacional e limites de serviço, e recomenda ações para remediar todos os desvios em relação às práticas recomendadas. O Trusted Advisor Priority ajuda os clientes do Enterprise Support a se concentrarem nas recomendações mais importantes, fornecendo recomendações orientadas pelo contexto e priorizadas de sua equipe de contas da AWS.  

**Uso típico:** Otimização contínua e implementação de boas práticas.

## AWS Well-Architected Tool

### Ferramenta do AWS Well-Architected

**Descrição:** Fornece uma abordagem consistente para avaliar arquiteturas de aplicativos na AWS em relação às melhores práticas.

**Como funciona:** A Ferramenta AWS Well-Architected foi projetada para ajudar você a analisar o estado de suas aplicações e workloads em relação às práticas recomendadas de arquitetura, identificar oportunidades de melhoria e acompanhar o progresso ao longo do tempo.

**Uso típico:** Avaliação e melhoria contínua da arquitetura de aplicativos.

## Migração e Transferência

### AWS Application Discovery Service

**Descrição:** Ajuda na coleta de dados sobre ambientes locais para planejamento de migração para a AWS.

**Como funciona:** O AWS Application Discovery Service coleta e apresenta dados para permitir que clientes empresariais entendam a configuração, o uso e o comportamento dos servidores em seus ambientes de TI. Os dados do servidor são mantidos no Application Discovery Service, onde podem ser marcados com uma tag e agrupados em aplicativos para ajudar a organizar o planejamento da migração para a AWS. Os dados coletados podem ser exportados para análise no Excel ou em outras ferramentas de análise de migração para a nuvem.

**Uso típico:** Descoberta de aplicativos e dependências para migração.

### AWS Application Migration Service (AWS AMS)

**Descrição:** Facilita a migração de aplicativos existentes para a AWS.

**Como funciona:** O AWS Application Migration Service minimiza processos manuais demorados e propensos a erros, automatizando a conversão de servidores para execução nativa na AWS Ele também simplifica a modernização de aplicações com opções de otimização integradas e personalizadas.

**Uso típico:** Migração simplificada de aplicativos.

### AWS Database Migration Service (AWS DMS)

**Descrição:** Migração de bancos de dados para a AWS de forma fácil e segura.

**Como funciona:** O AWS Database Migration Service (AWS DMS) é um serviço de replicação e migração gerenciado que ajuda a mover workloads analíticos e bancos de dados para a AWS rapidamente, de forma segura e com o mínimo possível de inatividade e zero perda de dados. O AWS DMS oferece suporte à migração entre mais de 20 mecanismos de banco de dados e análises, como do Oracle para o Amazon Aurora compatível com MySQL, do MySQL para o Amazon Relational Database (RDS) para MySQL, do Microsoft SQL Server para o Amazon Aurora compatível com PostgreSQL, do MongoDB para o Amazon DocumentDB (compatível com MongoDB), do Oracle para o Amazon Redshift e Amazon Simple Storage Service (S3).

**Uso típico:** Migração de dados entre diferentes tipos de bancos de dados.

### AWS Migration Hub

**Descrição:** Permite rastrear e gerenciar migrações de aplicativos para a AWS.

**Como funciona:** O AWS Migration Hub fornece um local central para coletar dados de inventário de servidores e aplicações para avaliação, planejamento e rastreamento de migrações para a AWS. O Migration Hub também pode ajudar a acelerar a modernização de aplicações após a migração.

**Uso típico:** Acompanhamento e gestão centralizada de migrações.

### AWS Schema Conversion Tool (AWS SCT)

**Descrição:** Converte esquemas de bancos de dados para torná-los compatíveis com a AWS.

**Como funciona:** Você pode usar a AWS Schema Conversion Tool (AWS SCT) para converter o esquema de banco de dados existente de um mecanismo de banco de dados para outro. Você pode converter o esquema OLTP relacional ou o esquema de data warehouse. Seu esquema convertido é adequado para um Amazon Relational Database Service (Amazon RDS) MySQL, MariaDB, Oracle, SQL Server, banco de dados PostgreSQL, um cluster de banco de dados Amazon Aurora ou um cluster Amazon Redshift. O esquema convertido também pode ser usado com um banco de dados em uma instância do Amazon EC2 ou armazenado como dados em um bucket do Amazon S3.

**Uso típico:** Conversão de esquemas de bancos de dados para a nuvem.

### Família AWS Snow

**Descrição:** Oferece dispositivos físicos para transferência de dados em grandes volumes para a AWS.

**Como funciona:** A família AWS Snow faz parte do continuum de serviços de nuvem híbrida da AWS que estendem a infraestrutura e os serviços da AWS até a borda, ajudando os clientes a executar aplicações de baixa latência perto de onde os dados se originam, são processados, acionados, além de atender aos requisitos de residência dos dados.

- AWS Snowcone: O AWS Snowcone é um dispositivo portátil, robusto e seguro que oferece computação de borda, armazenamento de dados e transferência em trânsito em um ambiente austero com pouca ou nenhuma conectividade.
- AWS Snowball: Migre dados na escala de petabytes para a AWS com o Snowball. Para trabalhos que exigem vários dispositivos, monitore o estágio do dispositivo com o Large Data Migration Manager do Snow.
- Snowmobile: O AWS Snowmobile move quantidades extremamente grandes de dados para a AWS. Transfira até 100 PB por Snowmobile, um contêiner de transporte reforçado com 45 pés de comprimento puxado por um caminhão semirreboque.

**Uso típico:** Transferência segura de grandes conjuntos de dados.

### AWS Transfer Family

**Descrição:** Fornece serviços gerenciados para transferência de arquivos para e da AWS.

**Como funciona:** A AWS Transfer Family escala com segurança as transferências de arquivos business-to-business recorrentes para os serviços de armazenamento da AWS usando os protocolos SFTP, FTPS, FTP e AS2.

**Uso típico:** Transferência segura de arquivos para a nuvem.

## Redes e Entrega de Conteúdo

### Amazon API Gateway

**Descrição:** Serviço para criar, publicar, manter, monitorar e proteger APIs.

**Como funciona:** O Amazon API Gateway é um serviço gerenciado que permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. APIs agem como a “porta de entrada” para aplicativos acessarem dados, lógica de negócios ou funcionalidade de seus serviços de back-end. Usando o API Gateway, você pode criar APIs do RESTful e APIs do WebSocket que habilitam aplicativos de comunicação bidirecionais em tempo real. O API Gateway dá suporte a cargas de trabalho conteinerizadas e sem servidor, além de aplicativos da web.

**Uso típico:** Exposição e gerenciamento de APIs na AWS.

### Amazon CloudFront

**Descrição:** Serviço de CDN (Content Delivery Network) para entrega rápida e segura de conteúdo.

**Como funciona:** O Amazon CloudFront é uma rede de entrega de conteúdo (CDN) que acelera a entrega de conteúdo estático e dinâmico da Web para usuários finais. O CloudFront distribui o conteúdo por meio de uma rede global de datacenters denominados locais da borda. Quando um usuário final solicita um conteúdo que você está fornecendo com o CloudFront, a solicitação é roteada ao local da borda mais próximo ao usuário final com a menor latência.

**Uso típico:** Distribuição de conteúdo estático e dinâmico globalmente.

### AWS Direct Connect

**Descrição:** Estabelece conexões de rede dedicadas entre data centers locais e a infraestrutura da AWS.

**Como funciona:** O serviço de nuvem AWS Direct Connect é o caminho mais curto para seus recursos na AWS. Seu tráfego de rede permanece todo o tempo na rede global da AWS e nunca entra na Internet pública. Isso reduz as probabilidades de gargalos ou aumentos inesperados de latência. Ao criar uma nova conexão, você pode escolher uma conexão hospedada fornecida por um parceiro de entrega do AWS Direct Connect ou uma conexão dedicada da AWS e implantá-la em mais de 100 locais do AWS Direct Connect ao redor do mundo. Com o AWS Direct Connect SiteLink, você pode enviar dados entre locais do AWS Direct Connect para criar conexões privadas de rede entre os escritórios e datacenters na sua rede global.

**Uso típico:** Conectividade de rede dedicada para ambientes híbridos.

### AWS Global Accelerator

**Descrição:** Roteamento de tráfego globalmente para otimizar a disponibilidade e o desempenho.

**Como funciona:** O AWS Global Accelerator é um serviço de rede que ajuda você a melhorar a disponibilidade, a performance e a segurança de aplicações públicas. O Global Accelerator fornece dois IPs públicos estáticos globais que atuam como um ponto de entrada fixo para seus endpoints de aplicações, como Application Load Balancers, Network Load Balancers, instâncias do Amazon Elastic Compute Cloud (EC2) e IPs elásticos.

**Uso típico:** Aceleração e roteamento de tráfego para aplicativos globais.

### Amazon Route 53

**Descrição:** Serviço de DNS (Domain Name System) para registro e gerenciamento de domínios.

**Como funciona:** O Amazon Route 53 é um serviço da Web de Sistema de Nomes de Domínio (DNS) altamente disponível e escalável. O Route 53 conecta as requisições do usuário a aplicações da Internet executadas na AWS ou on-premises.

**Uso típico:** Gerenciamento de domínios e resolução de DNS.

### Amazon VPC (Virtual Private Cloud)

**Descrição:** Fornece uma rede virtual isolada na AWS, onde você pode lançar recursos.

**Como funciona:** O Amazon Virtual Private Cloud (Amazon VPC) oferece controle total sobre seu ambiente de redes virtual, incluindo posicionamento de recursos, conectividade e segurança. Comece a usar configurando sua VPC no console de serviço AWS. Em seguida, adicione recursos a ela, como instâncias do Amazon Elastic Compute Cloud (EC2) e Amazon Relational Database Service (RDS). Por fim, defina como suas VPCs se comunicam entre si, entre contas, zonas de disponibilidade (AZs) ou Regiões da AWS. No exemplo abaixo, o tráfego de rede está sendo compartilhado entre duas VPCs em cada região.

**Uso típico:** Criação de redes privadas e isoladas na nuvem. Entenda bem os conceitos de subnets, rotas, grupos de segurança e peering de VPC

### AWS VPN (Virtual Private Network)

**Descrição:** Estabelece conexões seguras entre a infraestrutura local e a VPC da AWS.

**Como funciona:** As soluções do AWS Virtual Private Network estabelecem conexões seguras entre redes locais, escritórios remotos, dispositivos de clientes e a rede global da AWS. O AWS VPN é composto por dois serviços: AWS Site-to-Site VPN e AWS Client VPN. Juntos, eles entregam uma solução de VPN na nuvem gerenciada, altamente disponível e elástica para proteger o tráfego da sua rede.

**Uso típico:** Conectividade segura entre ambientes locais e na nuvem.

## Segurança, Identidade e Conformidade

### AWS Artifact

**Descrição:** Fornece acesso a relatórios de conformidade e segurança.

**Como funciona:** O AWS Artifact é sua primeira opção de recurso para informações relacionadas à conformidade que importam para você. Ele fornece acesso sob demanda a relatórios de segurança e conformidade da AWS e ISVs que vendem seus produtos no AWS Marketplace.

**Uso típico:** Acesso a documentos e relatórios de conformidade.

### AWS Audit Manager

**Descrição:** Ajuda na simplificação do processo de auditoria de conformidade.

**Como funciona:** Use o AWS Audit Manager para mapear seus requisitos de conformidade para dados de uso da AWS com estruturas pré-criadas e personalizadas e coleta automatizada de evidências.

**Uso típico:** Gerenciamento e automação de auditorias de conformidade.

### AWS Certificate Manager (ACM)

**Descrição:** Gerencia certificados SSL/TLS para aplicativos implantados na AWS.

**Como funciona:** Use o AWS Certificate Manager (ACM) para provisionar, gerenciar e implantar certificados SSL/TLS públicos e privados para uso com serviços da AWS e seus recursos internos conectados. O ACM elimina processos manuais demorados, como compra, upload e renovação de certificados SSL/TLS.

**Uso típico:** Provisionamento e gerenciamento de certificados SSL/TLS.

### AWS CloudHSM

**Descrição:** Oferece módulos de segurança de hardware dedicados para armazenar chaves criptográficas.

**Como funciona:** O serviço AWS CloudHSM ajuda a cumprir requisitos de conformidade corporativos, contratuais e normativos para a segurança de dados usando instâncias de Hardware Security Module (HSM – Módulo de segurança de hardware) dedicadas dentro da Nuvem AWS. Os parceiros da AWS e da AWS Marketplace oferecem diversas soluções para a proteção de dados confidenciais dentro da plataforma AWS. Porém, para alguns aplicativos e dados sujeitos a obrigações contratuais ou normativas rigorosas para o gerenciamento de chaves criptográficas, ocasionalmente é necessário oferecer proteção adicional.

**Uso típico:** Proteção de chaves criptográficas sensíveis.

### Amazon Cognito

**Descrição:** Serviço de autenticação que facilita a adição de autenticação e autorização a aplicativos.

**Como funciona:** Com o Amazon Cognito, você pode adicionar recursos de inscrição e login de usuários e controlar o acesso a suas aplicações móveis e da Web. O Amazon Cognito oferece um armazenamento de identidade que pode ser dimensionado para milhões de usuários, oferece suporte à federação de identidades sociais e corporativas e oferece recursos avançados de segurança para proteger seus consumidores e negócios. Construído com padrões de identidade aberta, o Amazon Cognito oferece suporte a vários regulamentos de conformidade e se integra a recursos de desenvolvimento de frontend e backend.

**Uso típico:** Gerenciamento de identidade e autenticação de usuários.

### Amazon Detective

**Descrição:** Oferece análise de dados de log para ajudar na investigação de atividades suspeitas.

**Como funciona:** O Amazon Detective simplifica o processo investigativo e ajuda as equipes de segurança a conduzir investigações mais rápidas e eficazes. Com as agregações de dados, resumos e contexto pré-construídos do Amazon Detective, você pode analisar e determinar rapidamente a natureza e a extensão de possíveis problemas de segurança.

**Uso típico:** Detecção e análise de ameaças.

### AWS Directory Service

**Descrição:** Oferece serviços de diretório para autenticação de usuários.

**Como funciona:** O AWS Directory Service for Microsoft Active Directory, também conhecido como AWS Managed Microsoft AD, ativa suas workloads com reconhecimento de diretório e recursos da AWS para usar o AD gerenciado na AWS.

**Uso típico:** Gerenciamento de diretórios para autenticação.

### AWS Firewall Manager

**Descrição:** Gerencia regras de firewall e políticas de segurança na AWS.

**Como funciona:** O AWS Firewall Manager é um serviço de gerenciamento de segurança que permite configurar e gerenciar regras de firewall de maneira centralizada em todas as contas e aplicações no AWS Organizations. À medida que novos aplicações e recursos são criados, o Firewall Manager facilita a aplicação de conformidade em aplicações e recursos, forçando um conjunto comum de regras de segurança.

**Uso típico:** Controle centralizado de políticas de firewall.

### Amazon GuardDuty

**Descrição:** Serviço de detecção de ameaças que monitora atividades maliciosas na sua conta da AWS.

**Como funciona:** O Amazon GuardDuty é um serviço de detecção de ameaças que monitora continuamente suas contas e workloads da AWS para detectar atividades mal-intencionadas e entrega descobertas de segurança detalhadas, permitindo visibilidade e correção.

**Uso típico:** Detecção de ameaças em tempo real.

### AWS Identity and Access Management (IAM)

**Descrição:** Controle de acesso para recursos da AWS, gerenciando usuários e permissões.

**Como funciona:** Com o AWS Identity and Access Management (IAM), você pode especificar quem ou o que pode acessar serviços e recursos na AWS, gerenciar permissões refinadas de maneira centralizada e analisar o acesso para refinar as permissões na AWS.

**Uso típico:** Controle de acesso e autorizações na AWS.

### AWS IAM Identity Center (AWS Single Sign-On)

**Descrição:** Facilita o gerenciamento de acesso único (SSO) em várias contas e aplicativos.

**Como funciona:** O Centro de Identidade do AWS IAM ajuda você a criar ou conectar com segurança as identidades da sua força de trabalho e gerenciar o acesso dela de maneira centralizada em contas e aplicações da AWS. O Centro de Identidade do IAM é a abordagem recomendada para autenticação e autorização da força de trabalho na AWS para organizações de qualquer tamanho e tipo. Com o Centro de Identidade do IAM, você pode criar e gerenciar identidades de usuário na AWS ou conectar facilmente sua fonte de identidade existente, como o Microsoft Active Directory, o Okta, o Ping Identity, o JumpCloud, o Google Workspace e o Microsoft Entra ID (o antigo Azure AD).

**Uso típico:** Simplificação do acesso único e gerenciamento de identidade.

### Amazon Inspector

**Descrição:** Serviço de avaliação de segurança automatizada para identificar vulnerabilidades.

**Como funciona:** O Amazon Inspector é um serviço automatizado de gerenciamento de vulnerabilidade que verifica continuamente as workloads da AWS em busca de vulnerabilidades de software e exposição não intencional à rede.

**Uso típico:** Avaliação contínua da segurança de recursos.

### AWS Key Management Service (AWS KMS)

**Descrição:** Gerencia chaves de criptografia para proteger dados.

**Como funciona:** O AWS KMS é um serviço gerenciado que ajuda a criar e controlar com mais facilidade as chaves usadas para operações criptográficas. O serviço oferece uma solução de geração, armazenamento, gerenciamento e auditoria de chaves altamente disponível para que você criptografe ou assine digital--mente dados nos suas próprias aplicações ou controle a criptografia de dados nos serviços da AWS.

**Uso típico:** Gerenciamento de chaves criptográficas.

### Amazon Macie

**Descrição:** Oferece descoberta e proteção de dados sensíveis.

**Como funciona:** O Amazon Macie é um serviço de segurança de dados que descobre dados confidenciais por meio de machine learning e correspondência de padrões, proporciona visibilidade dos riscos à segurança dos dados e oferece proteção automatizada contra esses riscos.

**Uso típico:** Identificação e proteção de dados confidenciais.

### AWS Network Firewall

**Descrição:** Oferece firewall gerenciado para proteção de tráfego de rede.

**Como funciona:** Com o AWS Network Firewall, você pode definir regras de firewall que proporcionam controle refinado sobre o tráfego de rede. O Network Firewall trabalha com o AWS Firewall Manager para que você crie políticas com base em regras do Network Firewall e aplique essas políticas em suas nuvens privadas virtuais (VPCs) e contas de forma centralizada.

**Uso típico:** Controle e monitoramento do tráfego de rede.

### AWS Resource Access Manager (AWS RAM)

**Descrição:** Compartilha recursos entre contas na AWS.

**Como funciona:** O AWS RAM ajuda você a compartilhar seus recursos com segurança entre contas da AWS, dentro de sua organização ou unidades organizacionais (UOs) e com perfis e usuários do IAM para tipos de recursos compatíveis.

**Uso típico:** Compartilhamento controlado de recursos entre contas.

### AWS Secrets Manager

**Descrição:** Gerenciamento de segredos, como senhas e chaves de API.

**Como funciona:** O AWS Secrets Manager é um serviço de gerenciamento de segredos que ajuda a proteger o acesso a aplicativos, serviços e recursos de TI. O serviço permite alternar, gerenciar e recuperar facilmente credenciais de banco de dados, chaves de API e outros segredos durante seu ciclo de vida. Usando o Secrets Manager, você pode proteger e gerenciar segredos usados para acessar recursos na Nuvem AWS, em serviços de terceiros e no local.

**Uso típico:** Armazenamento seguro e recuperação de segredos.

### AWS Security Hub

**Descrição:** Oferece um painel centralizado para gerenciamento de segurança.

**Como funciona:** O AWS Security Hub é um serviço de gerenciamento do procedimento de segurança na nuvem (CSPM) que executa verificações de práticas recomendadas de segurança, agrega alertas e possibilita a correção automatizada.

**Uso típico:** Agregação e monitoramento de alertas de segurança.

### AWS Shield

**Descrição:** Serviço de proteção contra ataques DDoS (Distributed Denial of Service).

**Como funciona:** O AWS Shield é um serviço gerenciado que fornece proteção contra ataques distribuídos de negação de serviço (DDoS) para os aplicativos executados na AWS. O AWS Shield Standard é habilitado automaticamente a todos os clientes da AWS sem custo adicional. O AWS Shield Advanced é um serviço pago opcional. O AWS Shield Advanced oferece proteções adicionais contra ataques maiores e mais sofisticados para aplicações executadas no Amazon Elastic Compute Cloud (Amazon EC2), Elastic Load Balancing (ELB), Amazon CloudFront, AWS Global Accelerator e Route 53.

**Uso típico:** Proteção contra ataques distribuídos.

### AWS WAF (Web Application Firewall)

**Descrição:** Firewall de aplicativos web para proteger contra ataques comuns.

**Como funciona:** O AWS WAF é um firewall de aplicações Web que ajuda a proteger aplicações Web de ataques por meio da configuração de regras que permitem, bloqueiam ou monitoram (contagem) solicitações da Web de acordo com condições que você mesmo define. Essas condições incluem endereços IP, cabeçalhos e corpo HTTP, strings de URI, injeção de SQL e cross-site scripting.

**Uso típico:** Proteção contra ameaças web.

## Serverless

### AWS Fargate

**Descrição:** Oferece execução de contêineres sem a necessidade de gerenciar a infraestrutura subjacente.

**Como funciona:** O AWS Fargate é um mecanismo de computação com tecnologia sem servidor e pagamento conforme o uso que permite que você se concentre no desenvolvimento de aplicações sem a necessidade de gerenciar servidores. Mover tarefas como gerenciamento de servidores, alocação de recursos e escalabilidade para a AWS não só melhora sua postura operacional, mas também acelera o processo de passar da ideia à produção na nuvem e reduz o custo total de propriedade.

**Uso típico:** Implantação e execução de contêineres sem provisionamento de servidores.

### AWS Lambda

**Descrição:** Serviço de computação serverless que executa código em resposta a eventos.

**Como funciona:** O AWS Lambda é um serviço de computação sem servidor e orientado a eventos que permite executar código para praticamente qualquer tipo de aplicação ou serviço de backend sem provisionar ou gerenciar servidores. Você pode acionar o Lambda a partir de mais de 200 serviços da AWS e aplicações de software como serviço (SaaS) e pagar apenas pelo que usar.

**Uso típico:** Execução de código sem a necessidade de provisionar servidores. Compreenda os gatilhos, tempo limite de execução, variáveis de ambiente e configurações de memória. Planeje bem a separação de funções para manter o código modular.

## Armazenamento

### AWS Backup

**Descrição:** Oferece backup centralizado e recuperação de recursos da AWS.

**Como funciona:**

**Uso típico:** Backup e recuperação de dados e recursos.

### Amazon Elastic Block Store (Amazon EBS)

**Descrição:** Armazenamento de blocos para uso com instâncias EC2.

**Como funciona:** Com o AWS Backup, é possível definir uma política central de proteção de dados (chamada de plano de backup) que funciona nos serviços da AWS para computação, armazenamento e bancos de dados. O plano de backup define parâmetros como frequência e período de retenção de backup. Depois de definir suas políticas de proteção de dados e atribuir recursos da AWS a elas, o AWS Backup automatiza a criação de backups e os armazena em um cofre de backup criptografado designado por você. As políticas centralizadas no AWS Backup também ajudam a definir controles de acesso e automatizar o gerenciamento de acesso ao backup em todas as suas contas dentro do AWS Organizations.

**Uso típico:** Armazenamento persistente para instâncias EC2.

### Amazon Elastic File System (Amazon EFS)

**Descrição:** Oferece armazenamento de arquivos totalmente gerenciado e escalável.

**Como funciona:** O Amazon Elastic File System (EFS) foi projetado para fornecer um armazenamento de arquivos totalmente elástico sem servidor que ajuda a compartilhar dados de arquivos sem provisionar nem gerenciar a capacidade e a performance do armazenamento. Com poucas seleções no Console de Gerenciamento da AWS, você pode criar sistemas de arquivos acessíveis a instâncias do Amazon Elastic Compute Cloud (EC2), serviços de contêiner da Amazon (Amazon Elastic Container Service (ECS), Amazon Elastic Kubernetes Service (EKS) e AWS Fargate) e funções do AWS Lambda por meio de uma interface de sistema de arquivos (usando APIs padrão de E/S de arquivos de sistema operacional). Eles também oferecem suporte à semântica de acesso total ao sistema de arquivos, como forte consistência e bloqueio de arquivos.

**Uso típico:** Armazenamento compartilhado para instâncias EC2.

### AWS Elastic Disaster Recovery

**Descrição:** Solução de recuperação de desastres gerenciada.

**Como funciona:** O AWS Elastic Disaster Recovery (AWS DRS) minimiza o tempo de inatividade e a perda de dados com recuperação rápida e confiável de aplicações on-premises e baseadas na nuvem com armazenamento acessível, computação mínima e recuperação em um ponto anterior no tempo.

**Uso típico:** Planejamento e execução de recuperação de desastres.

### Amazon FSx

**Descrição:** Oferece sistemas de arquivos totalmente gerenciados para Windows e Lustre.

**Como funciona:** Com o Amazon FSx, ficou mais fácil e econômico iniciar, executar e escalar sistemas de arquivos de alto desempenho e repletos de recursos na nuvem. Ele oferece suporte a uma ampla variedade de workloads com sua confiabilidade, segurança, escalabilidade e amplo conjunto de recursos. O Amazon FSx foi desenvolvido com base nas mais recentes tecnologias de computação, rede e disco da AWS para fornecer alto desempenho e menor TCO. E, como um serviço totalmente gerenciado, ele lida com provisionamento, correções e backups de hardware, liberando você para se concentrar em seus aplicativos, seus usuários finais e sua empresa.

- Amazon FSx para NetApp ONTAP: Armazenamento compartilhado totalmente gerenciado baseado no popular sistema de arquivos ONTAP da NetApp.
- Amazon FSx para OpenZFS: Armazenamento compartilhado totalmente gerenciado baseado no popular sistema de arquivos OpenZFS.
- Amazon FSx para Windows File Server: Armazenamento compartilhado totalmente gerenciado criado no Windows Server.
- Amazon FSx para Lustre: Armazenamento compartilhado totalmente gerenciado baseado no sistema de arquivos de alto desempenho mais popular do mundo.

**Uso típico:** Armazenamento de arquivos para cargas de trabalho específicas.

### Amazon S3 (Simple Storage Service)

**Descrição:** Armazenamento de objetos altamente escalável e durável.

**Como funciona:** O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e performance líderes do setor. Clientes de todos os portes e setores podem armazenar e proteger qualquer quantidade de dados de praticamente qualquer caso de uso, como data lakes, aplicações nativas da nuvem e aplicações móveis. Com classes de armazenamento econômicas e recursos de gerenciamento fáceis de usar, você pode otimizar custos, organizar dados e configurar controles de acesso ajustados para atender a requisitos específicos de negócios, organizacionais e de conformidade.

- Amazon S3 Standard: é um serviço de armazenamento de objetos projetado para fornecer alta resiliência, disponibilidade e desempenho a dados acessados frequentemente. Com baixa latência e alto throughput, é adequado para uma variedade de casos de uso, incluindo aplicações na nuvem, sites dinâmicos, distribuição de conteúdo, aplicativos móveis, jogos e análise de big data. Destacam-se seus recursos de armazenamento de uso geral, desempenho com baixa latência e alto throughput, e uma garantia de disponibilidade de 99,99% com um SLA de 99,9%.
- Amazon S3 Intelligent-Tiering: é um serviço de armazenamento em nuvem que otimiza automaticamente os custos, movendo dados entre níveis de acesso com base na frequência de uso. Oferece alta performance para dados frequentemente, pouco frequentemente e raramente acessados. Não há taxas de recuperação e a automação opcional proporciona economias de até 95%. Com disponibilidade de 99,9%, o serviço tem uma pequena taxa mensal de monitoramento, sem sobrecarga operacional, encargos de ciclo de vida ou duração mínima de armazenamento. Objetos menores que 128 KB são cobrados como acesso frequente.
- Amazon S3 Express One Zone é uma classe de armazenamento de alta performance projetada para proporcionar acesso rápido e consistente a dados frequentemente utilizados e aplicações sensíveis à latência. Ele pode melhorar a velocidade de acesso em até 10 vezes e reduzir os custos de solicitação em 50% em comparação com o S3 Standard. Ao escolher uma zona de disponibilidade específica da AWS, você pode otimizar ainda mais a performance, reduzindo os custos computacionais e acelerando workloads. Os dados são armazenados em buckets de diretório, capazes de lidar com centenas de milhares de solicitações por segundo. Compatível com serviços como Amazon SageMaker, Amazon Athena e Amazon EMR, o S3 Express One Zone facilita a aceleração de workloads de análise e machine learning. Escalável e otimizado para grandes conjuntos de dados, é projetado para oferecer alta disponibilidade de 99,95%, com um SLA de 99,9%.
- Amazon S3 Standard-Infrequent Access (S3 Standard-IA): é adequado para dados com acesso menos frequente, mas que exigem rapidez quando acessados. Oferece os benefícios de resiliência, alto throughput e baixa latência do S3 Standard, com taxas reduzidas por GB de armazenamento e recuperação. Essa combinação de baixo custo e alta performance torna-o ideal para armazenamento de longa duração, backups e dados para recuperação de desastres. Pode ser configurado no nível do objeto, permitindo a coexistência com outras classes de armazenamento no mesmo bucket, como S3 Intelligent-Tiering e S3 One Zone-IA. A política de ciclo de vida do S3 facilita a migração automática entre as classes de armazenamento, sem afetar as aplicações. Principais características incluem acesso rápido a dados pouco frequentes, desempenho similar ao S3 Standard e disponibilidade de 99,9%, com um SLA de 99%.
- Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA): é ideal para dados acessados com pouca frequência, mas que exigem rapidez quando acessados. Ao contrário de outras classes S3, armazena dados em uma única Zona de disponibilidade, proporcionando um custo 20% inferior ao S3 Standard-IA. Recomendado para clientes que buscam uma opção econômica para dados pouco frequentes, é adequado para cópias de backup secundárias ou dados replicados entre regiões da AWS. Oferece alto throughput, baixa latência e onze noves de durabilidade, embora possa ser suscetível à perda de dados em casos extremos. A configuração no nível do objeto e a flexibilidade de usar políticas de ciclo de vida facilitam a migração automática entre classes de armazenamento, sem impacto nas aplicações. Destaques incluem acesso rápido a dados pouco frequentes, desempenho comparável ao S3 Standard e disponibilidade de 99,5%, com um SLA de 99%.

**Uso típico:** Armazenamento e recuperação de dados na nuvem.

### Amazon S3 Glacier

**Descrição:** Armazenamento de objetos de longo prazo e baixo custo.

**Como funciona:**

- Amazon S3 Glacier Instant Retrieval: é uma opção de armazenamento de baixo custo para dados de longa duração, acessados raramente e que requerem recuperação rápida em milissegundos. Permite economia de até 68% em comparação com o S3 Standard-Infrequent Access quando os dados são acessados trimestralmente. Oferece acesso rápido, com desempenho equivalente ao S3 Standard, sendo indicado para arquivar dados como imagens médicas ou conteúdo gerado pelo usuário. Pode-se fazer upload direto ou usar políticas do S3 Lifecycle para migrar dados entre classes de armazenamento. Principais características incluem recuperação instantânea, disponibilidade de 99,9%, e tamanho mínimo do objeto de 128 KB.
- Amazon S3 Glacier Flexible Retrieval: oferece armazenamento de baixo custo para dados de arquivo acessados 1 a 2 vezes por ano, com recuperação assíncrona. É até 10% mais econômico que o S3 Glacier Instant Retrieval. Ideal para backup e recuperação de desastres, permite recuperar grandes conjuntos de dados sem custo, com tempos de acesso configuráveis de minutos a horas. Oferece 99,999999999% de durabilidade e 99,99% de disponibilidade, armazenando dados de forma redundante em múltiplas zonas de disponibilidade. Suporta SSL e criptografia de dados, sendo uma solução eficaz para necessidades de armazenamento externo e casos em que a flexibilidade na recuperação é prioritária. Principais recursos incluem baixo custo, tempos de recuperação configuráveis e suporte ao gerenciamento através da API PUT do S3.
- O Amazon S3 Glacier Deep Archive é a opção mais econômica do S3 para arquivamento de dados raramente acessados, ideal para retenção de longo prazo, especialmente em setores regulamentados. Projetado para conjuntos de dados mantidos por 7 a 10 anos, é uma alternativa acessível para conformidade regulatória em setores como serviços financeiros e saúde. Adequado para backup e recuperação de desastres, é uma opção fácil de gerenciar em comparação com fitas magnéticas. Garante alta disponibilidade de 99,99%, com tempo de recuperação de até 12 horas. Todos os objetos são replicados e armazenados em pelo menos três zonas de disponibilidade, proporcionando resiliência de 99,999999999%. Principais recursos incluem custo muito baixo, alternativa às fitas magnéticas, e suporte à API PUT do S3 para uploads diretos e ao gerenciamento de ciclo de vida do S3.
- O Amazon S3 on Outposts oferece armazenamento de objetos para ambientes AWS Outposts locais. Compatível com as APIs S3, facilita o armazenamento, recuperação e proteção de dados on-premises. Oferece uma classe de armazenamento chamada "OUTPOSTS", ideal para workloads locais com requisitos de residência de dados e necessidades de performance. Principais recursos incluem compatibilidade com objetos do S3, criptografia, autenticação via IAM, transferência de dados para regiões AWS e ações de expiração de ciclo de vida do S3.

**Uso típico:** Armazenamento de arquivos arquivados.

### AWS Storage Gateway

**Descrição:** Conecta ambientes locais com o armazenamento em nuvem.

**Como funciona:** O AWS Storage Gateway é um serviço de armazenamento na nuvem híbrida que oferece acesso local a armazenamento na nuvem praticamente ilimitado. O Storage Gateway oferece um conjunto de protocolos padrão, como iSCSI, SMB e NFS, que permite o uso de armazenamento da AWS sem necessidade de alterar aplicativos existentes. O serviço também disponibiliza performance de baixa latência armazenando em cache dados acessados com frequência no local e, ao mesmo tempo, armazenando dados de modo seguro e resiliente nos serviços de armazenamento na nuvem da Amazon. O Storage Gateway otimiza a transferência de dados para a AWS enviando apenas dados alterados e compactando os dados.

**Uso típico:** Integração de armazenamento local com a nuvem.

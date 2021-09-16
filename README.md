# Resumo do curso AWS Cloud Practitioner Essentials (Portuguese) para preparação para certificação

## MÓDULO 1: INTRODUÇÃO À AWS AMAZON WEB SERVICES (AWS)

### Modelos de implantação para computação em nuvem

* Nuvem
* On-Premises
* Híbrida

## MÓDULO 2: COMPUTAÇÃO NA NUVEM

### Tipos de instância do Amazon EC2

* **Uso geral** fornecem um equilíbrio de recursos de computação, memória e rede. Você pode usá-las para uma variedade de cargas de trabalho
* **Otimizadas para computação** são ideais para aplicações vinculadas à computação que se beneficiam de processadores de alta performance
* **Otimizadas de memória** são projetadas para fornecer rápida performance para cargas de trabalho que processam grandes conjuntos de dados na memória
* **Computação acelerada** usam aceleradores de hardware, ou coprocessadores, para executar algumas funções de forma mais eficiente do que é possível no software executado em CPUs
* **Otimizadas para armazenamento** são projetadas para cargas de trabalho que exigem alto acesso sequencial de leitura e gravação a grandes conjuntos de dados no armazenamento local. 

### Definição de preço do Amazon EC2

* **Sob demanda** são ideais para cargas de trabalho irregulares de curto prazo que não podem ser interrompidas. Não se aplicam custos iniciais ou contratos mínimos
* **Savings Plans do Amazon EC2** permitem reduzir os custos de computação comprometendo-se com uma quantidade consistente de uso de computação por um período de um ou três anos. Esse compromisso de prazo resulta em economias de até 72% em relação aos custos sob demanda
* **Reservadas** são um desconto de faturamento aplicado ao uso de instâncias sob demanda em sua conta. Você pode comprar instâncias reservadas padrão e instâncias reservadas conversíveis por um período de um ou três anos, e instâncias reservadas agendadas por um período de um ano
* **Spot** são ideais para cargas de trabalho com horários de início e término flexíveis ou que podem suportar interrupções. As instâncias spot usam a capacidade de computação não utilizada do Amazon EC2 e oferecem economia de custos em até 90% de desconto dos preços sob demanda
* **Hosts dedicados** são servidores físicos com capacidade de instância do Amazon EC2 totalmente dedicada ao uso do cliente

### Escalabilidade do Amazon EC2 (Amazon EC2 Auto Scaling)

O serviço da AWS que fornece essa funcionalidade (escalabilidade) para instâncias do Amazon EC2 é o **Amazon EC2 Auto Scaling**.  

O Amazon EC2 Auto Scaling permite que você adicione ou remova automaticamente instâncias do Amazon EC2 em resposta à alteração da demanda da aplicação.  

No Amazon EC2 Auto Scaling, você pode usar duas abordagens: escalabilidade dinâmica e escalabilidade preditiva.

* Escalabilidade dinâmica responde às alterações na demanda. 
* Escalabilidade preditiva programa automaticamente o número correto de instância do Amazon EC2 com base na demanda prevista.

### Elastic Load Balancing

**Elastic Load Balancing** é o serviço da AWS que distribui automaticamente o tráfego de entrada de aplicações entre vários recursos, como instâncias do Amazon EC2.    

### Amazon Simple Notification Service (Amazon SNS)

**Amazon Simple Notification Service (Amazon SNS)** é um serviço de publicação/assinatura (pub/sub). Usando tópicos do Amazon SNS, um editor publica mensagens para assinantes.  

### Amazon Simple Queue Service (Amazon SQS)

**Amazon Simple Queue Service (Amazon SQS)** é um serviço de enfileiramento de mensagens.   

Use o Amazon SQS para enviar, armazenar e receber mensagens entre componentes de software, sem perder mensagens ou precisar que outros serviços estejam disponíveis. No Amazon SQS, uma aplicação envia mensagens para uma fila. Um usuário ou serviço recupera uma mensagem da fila, a processa e a exclui da fila.

### AWS Lambda

O **AWS Lambda** é um serviço que permite a execução de códigos sem a necessidade de provisionar ou gerenciar servidores.   

Ao usar o AWS Lambda, você paga apenas pelo tempo de computação que consumir. As cobranças se aplicam somente quando seu código está em execução. Você pode executar códigos para praticamente qualquer tipo de aplicação ou serviço de back-end sem necessidade de qualquer administração.  

### Amazon Elastic Container Service (Amazon ECS)

O **Amazon Elastic Container Service (Amazon ECS)** é um sistema de gerenciamento de contêineres altamente escalável e de alta performance que permite executar e escalar aplicações em contêineres na AWS. 

O Amazon ECS oferece suporte a contêineres Docker.  

### Amazon Elastic Kubernetes Service (Amazon EKS)

**Amazon Elastic Kubernetes Service (Amazon EKS)** é um serviço totalmente gerenciado que você pode usar para executar o Kubernetes na AWS.  

Kubernetes é um software de código aberto que permite implantar e gerenciar aplicações em contêineres em grande escala.  

### AWS Fargate

**AWS Fargate** é um mecanismo de computação sem servidor para contêineres. Ele funciona com o Amazon ECS e o Amazon EKS.  

Ao usar o AWS Fargate, você não precisa provisionar ou gerenciar servidores. O AWS Fargate gerencia sua infraestrutura de servidor para você.

Fonte: https://www.aws.training/Details/eLearning?id=62551




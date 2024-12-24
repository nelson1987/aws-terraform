# aws-terraform
Create api gateway with Terraform in AWS using nodejs

# AWS
Dynamodb
Lambda
Step Functions
Amazon S3 -  O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e performance líderes do setor. Clientes de todos os portes e setores podem armazenar e proteger qualquer quantidade de dados de praticamente qualquer caso de uso, como data lakes, aplicações nativas da nuvem e aplicações móveis. Com classes de armazenamento econômicas e recursos de gerenciamento fáceis de usar, você pode otimizar custos, organizar dados e configurar controles de acesso ajustados para atender a requisitos específicos de negócios, organizacionais e de conformidade.

Api Gateway - O Amazon API Gateway é um serviço gerenciado que permite que desenvolvedores criem, publiquem, mantenham, monitorem e protejam APIs em qualquer escala com facilidade. APIs agem como a “porta de entrada” para aplicativos acessarem dados, lógica de negócios ou funcionalidade de seus serviços de back-end. Usando o API Gateway, você pode criar APIs do RESTful e APIs do WebSocket que habilitam aplicativos de comunicação bidirecionais em tempo real. O API Gateway dá suporte a cargas de trabalho conteinerizadas e sem servidor, além de aplicativos da web.

Cognito - Ferramenta utilizada para autenticação e gerenciamento de contas
SRP - Secure Remote Password Protocol

IAM - Identiy And Acess Management
Cloudwatch
Kinesis
Simple Notification Service
Simple Queue Service
Amazon MQ
Amazon EventBridge
Elasticache


Criar Função Lamdba com Dynamo
Crie a tabela no Dynamodb - Rides
Selecione uma política para o perfil do IAM da função - AWSLambdaBasicExecutionRole 
Crie o perfil - WildRydesLambda
Seleciona as ações da permissão - [PutItem]
Crie a política para a ARN da tabela criada anteriormente - DynamoDBWriteAccess 
Crie a função - RequestUnicorn
Utilizando o perfil criado anteriormente - WildRydesLambda
Teste utilizando a área de testes
Verificar logs no CloudWatch
Vá em Logs -> Grupo de Logs
busque por a/awas/lambda/RequestUnicorn
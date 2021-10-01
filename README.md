# dio-aws-kinesis-analytics
Explorando o Amazon Kinesis Data Analytics e analisando dados em tempo real - streaming de dados

### Serviços AWS utilizados
 - Kinesis Data Streams
 - Kinesis Data Analytics

### Configurações

#### Criando uma aplicação com o Kinesis Data Analytics (utilizando Demo Data Stream)
 - Kinesis Data Analytics Console -> Create application -> Application name [kinesis_damo_analytics] -> Runtime [Legacy SQL] - Create Application
 - Source stream -> Configure - Source [Use demo stream]
 - Discover schema -> Save changes
 - Connect streaming data -> Create a demo stream -> Record pre-processing [Disabled]
 - Discovery schema -> Save and continue
 
#### Executando a aplicação e pesquisando dados (utilizando templates)
 - Run
 - Real-time analytics -> Configure - Add SQL from templates -> Save and run application

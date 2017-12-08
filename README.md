# Projeto

## Objetivos 

* Revisar os conceitos do paradigma orientado a objetos na linguagem de programação Java implementando pequenos desafios 
* Utilizar testes unitários com JUnit 4
* Aplicar a prática de revisão de código através de inspeção de código fonte implementado
* Aplicar a integração contínua através do uso das ferramentas git, maven, sonarqube e jenkins
* Utilizar as expressões lambda (*lambda expressions*) e referências a método (*method references*), facilidades relacionadas ao paradigma funcional introduzidas na versão 8 do java 
* Utilizar a nova biblioteca de classes para datas e horários introduzida na versão 8 do java
* Utilizar pelo menos 1 padrão de projeto da categoria de criação  do catálogo GoF(*creational*)
* Utilizar pelo menos 1 padrão de projeto da categoria estrutural do catálogo GoF (*structural*)
* Utilizar pelo menos 2 padrões de projeto da categoria comportamental do catálogo GoF (*behavioral*)

## Tarefas

* Criar projeto git com nome `unidavi-webdev-poo-project` na conta do aluno no github 
* Criar um commit com o resultado da `Entrega 1 do projeto final` publicado no classroom em novembro
* Criar um commit com orientações no arquivo README.md de como executar a entrega 1 do projeto
* Criar um commit com a estrutura de pastas do projeto reorganizada para atender o padrão usado pelo Maven (src/main/java, src/test/java)
* Criar um commit com arquivo pom.xml configurado para compilar o código fonte, executar os testes automatizados e gerar o arquivo jar
* Criar um commit com orientações atualizadas no arquivo README.md de como executar a entrega 1 do projeto
* Criar um commit com propriedade configurada para encoding UTF8 em código fonte e relatórios (`build.sourceEncoding`, `report.outputEncoding)
* Criar um commit com todas as dependências utilizadas configuradas (junit, driver jdbc)
* Criar um commit com código fonte e javadoc configurados como relatório no site do projeto
* Criar um commit com configuração para empacotar código fonte e javadoc como jar
* Criar um commit com sonar configurado para identificar cobertura de código do projeto
* Criar um commit com resolução de todas as issues de severidade blocker, critical e major resolvidas no sonarqube
* Criar um commit com resolução de todas as issues relatadas pelo sonarqube
* Criar um commit com cobertura de código superior a 80%
* Criar um job jenkins chamado `PROJECT-DEV-BUILD` que compila o código fonte, executa os testes automatizados e empacota o jar
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-build`
* Criar um job jenkins chamado `PROJECT-DEV-SITE` que gera o site do projeto
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-site`
* Criar um job jenkins chamado `PROJECT-DEV-DEPLOY` que versiona o projeto e publica em repositório local
* Criar um commit com uma cópia do arquivo do job jenkins, `config.xml`, armazenada em `src/jenkins/jobs/project-dev-deploy`
* Criar um commit com novo código ou código refatorado para utilização dos métodos forEach e removeIf da Collections API
* Criar um commit com novo código ou código refatorado para utilização da Streams API
* Criar um commit com novo código ou código refatorado para utilização da nova biblioteca de classes para datas e horários (`java.time`)
* Criar um commit com novo código ou código refatorado para codificação e utilização de um (1) padrão de projeto da categoria de criação
* Criar um commit com novo código ou código refatorado para codificação e utilização de um (1) padrão de projeto da categoria estrutural
* Criar um commit com novo código ou código refatorado para codificação e utilização de dois (2) padrão de projeto da categoria comportamental
* Criar um commit com resolução de todas as issues relatadas pelo sonarqube
* Criar um commit com revisão de código de cada classe conforme ferramenta de inspeção criada na semana 1

## Entrega
> Importante: cada aluno deve fazer a entrega em sua própria conta 

* Comunicar a conclusão da atividade `Entrega 2 do projeto final` da ferramenta classroom indicando o endereço do repositório git

## Avaliação
* A nota do projeto final é a média aritmética da nota das 2 entregas
* A nota de cada entrega corresponde a percentual das itens entregues conforme solicitado. 

### Exemplos
* 3 itens entregues completos de 5 solicitados corresponde a nota 6 
* 3 itens entregues incompletos de 5 solicitados corresponde a nota 3 


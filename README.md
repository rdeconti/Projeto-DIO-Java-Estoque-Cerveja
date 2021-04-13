:spiral_calendar: Atualizado em 10 de abril de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One Java

# Desenvolvimento de testes unitários para validar uma API REST de gerenciamento estoques de cerveja

- Este projeto foi proposto pela Digital Innovation One - Link do código original: https://github.com/rpeleias/beer_api_digital_innovation_one
- Professor: Rodrigo Peleias 
- Aulas: https://web.digitalinnovation.one/lab/desenvolvimento-de-testes-unitarios-para-validar-uma-api-rest-de-gerenciamento-estoques-de-cerveja/learning/d00f891f-65bb-4149-85f0-57d771116214

# Descrição

Nesta live coding, vamos aprender a testar, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. Vamos desenvolver testes unitários para validar o nosso sistema de gerenciamento de estoques de cerveja, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito. Além disso, vamos também mostrar como desenvolver funcionalidades da nossa API através da prática do TDD. Durante a sessão, serão abordados os seguintes tópicos:

- Baixar um projeto através do Git para desenolver nossos testes unitários
- Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
- Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
- Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest
- Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
- TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

# Detalhes obtidos nas aulas

- Projeto criado com Spring Boot
- Tem arquivo porn.xml que tem todas as dependências do projeto
- Utiliza Swager para documentar a API
- Utiliza Lombok
- Entity: Beer com classe e atributos, anotações do Lombok gerando automaticamente os gets and sets
- Enums: Tem os tipos de cerveja possíveis
- Repository: Tem o DAO - trabalha com BD e tem interface que procura cervejas por nome

# Para executar o projeto

- Para executar o projeto no terminal, digite o seguinte comando:

        ```shell script
        mvn spring-boot:run 
        ```

        Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

        ```shell script
        mvn clean test
        ```

        Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

        ```
        http://localhost:8080/api/v1/beers
        ```

# Requisitos para execução do projeto

- São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

    -- Java 14 ou versões superiores
    -- Maven 3.6.3 ou versões superiores
    -- Intellj IDEA Community Edition ou sua IDE favorita
    -- Controle de versão GIT instalado na sua máquina
    -- Muita vontade de aprender e compartilhar conhecimento

# Links de referência

    -- [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
    -- [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
    -- [Palheta de at----hos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_Refe--enceCard.pdf)
    -- [Site oficial --o--Spring](https://spring.io/)
    -- [Site oficial --Un--t 5](https://junit.org/junit5/docs/current/user-guide/)
    -- [Site oficial --ock--to](https://site.mockito.org/)
    -- [Site oficial --amcr--st](http://hamcrest.org/JavaHamcrest/)
    -- [Referências - teste-- em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
    -- [Referência para o pa--rão arquitetural REST](https://restfulapi.net/)
    -- [Referência pirâmide d-- testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

# Apresentação da aula

[Neste link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), seguem os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto da nossa sessão.

# Melhorias implementadas

- xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

# Detalhes da aula

- xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

# Exemplos de telas

## Tela inicial

<img src="https://github.com/rdeconti/Projeto-DIO-Java-Gerenciador-De-Pessoas
/blob/main/Test-screens/Tela%20inicial.jpg" />

## Tela de acerto

<img src="https://github.com/rdeconti/Projeto-DIO-Java-Gerenciador-De-Pessoas
/blob/main/Test-screens/Tela%20acertou.jpg" />

## Tela de erro

<img src="https://github.com/rdeconti/Projeto-DIO-Java-Gerenciador-De-Pessoas
/blob/main/Test-screens/Tela%20errou.jpg" />

## Projeto Final Bootcamp Santander 2023 Angular + Java
Último projeto do Bootcamp Santander 2023 - Publicação de uma API RESTful na Nuvem utilizando Spring Boot 3 e Railway

# Diagrama de Classes

```mermaid
classDiagram
    class Client {
        -String name
        -Account account
        -Feature[] features
        -Card card
        -News[] news
    }
    class Account {
        -String number
        -String agency
        -Number balance
        -Number limit
    }
    class Feature {
        -String icon
        -String description
    }
    class Card {
        -String number
        -Number limit
    }
    class News {
        -String icon
        -String description
    }

    Client --> Account
    Client --> Feature
    Client --> Card
    Client --> News
```

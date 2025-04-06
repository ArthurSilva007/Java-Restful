# Santander Dev-Week
Java RestFul API criada para o Santander Dev Week.

## Diagrama de Classes

'''Mermaid


classDiagram
    class User {
        +String name
        +Account account
        +Feature features
        +Card cards
        +News news
    }

    class Account {
        +String number
        +String agency
        +float balance
        +float limit
    }

    class Feature {
        +String icon
        +String description
    }

    class Card {
        +String number
        +float limit
    }

    class News {
        +String icon
        +String description
    }

    User --> Account
    User --> Feature
    User --> Card
    User --> News
'''

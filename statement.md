# Bienvenue

Bonjour à tous. Ce playground va servir à présenter et expliquer deux nouveaux design pattern,à savoir le design pattern Factory ainsi que le design pattern Abstract Factory.

# Design Pattern

Les design patterns, ou "patron de conception", sont des méthodes utilisées en développement logiciel. Ils permettent d'optimiser, de clarifier du code informatique et de le rendre plus robuste, en répondant principalement à une problématique posée par les choix de conceptions.

De cette manière, les design patterns remplissent souvent plusieurs conditions qui respectent les principes SOLID.

**Qu'est-ce que les principes SOLID ?**

Les principes SOLID sont des principes permettant de répondre aux critères permettant de dire d'une conception que cette dernière répond aux attentes de l'évolutivité du code. Il existe 5 principes SOLID qui sont les suivants :

1. SRP (Single Responsability Principle)
2. OCP (Open-Close Principle)
3. LSP (Liskov Substitution Principle)
4. ISP (Interface Segregation Principle)
5. DIP (Dependency Inversion Principle)

**Mais d'où viennent les design patterns ?**

Les design patterns proviennent à l'origine de l'architecte Christoper Alexander, qui rédigea un livre nommé **A Pattern Language**, définissant un ensemble de patrons d'architecture. Plus tard, les design patterns sont formalisés dans le livre **Design Patterns - Elements of Reusable Object-Oriented Software** du **Gang Of Four** composé de **Erich Gamma, Richard Helm, Ralph Johnson** et **John Vlissides**.

Chaque design pattern doit répondre à un problème pouvant se manifester lors de la réalisation d'objets en programmation, et ce de telle sorte à ce que le design pattern puisse être utilisé plusieurs fois dans diverses situations.

Il existe différents types de design patterns, que nous pouvons regrouper sous 3 familles :
1. Les patterns de création
2. Les patterns de structuration
3. Les patterns comportementaux.

Aujourd'hui, les deux designs pattern que nous allons aborder font parti de la famille des **patterns de création** et répondent à la problématique suivante : **Comment peut-on créer des objets sans pour autant savoir quelle classe sera utilisé ?**


# Pourquoi la famille des patterns de création ?

Nos deux design patterns sont considérés en tant que pattern de création parce qu'ils permettent **d'instancier**, de **créer** des objets dérivant d'un autre objet. Plus simplement, c'est une autre façon d'utiliser le polymorphisme sans pour autant y faire appel.

De cette façon, nos design patterns respectent souvent les principes OCP et LSP de l'ensemble SOLID.

Nous allons à présent vous expliquer les principes des deux design patterns.

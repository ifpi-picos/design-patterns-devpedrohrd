Padrão Factory Method
O padrão Factory Method é um padrão de projeto de software que define uma interface para a criação de objetos, mas deixa as subclasses decidirem qual classe de objeto instanciar.

Objetivo

O objetivo do padrão Factory Method é encapsular a criação de objetos, deixando as subclasses responsáveis por criar os objetos reais. Isso torna o código mais flexível e reutilizável.

Participantes

O padrão Factory Method possui os seguintes participantes:

Cliente: Representa o usuário do sistema. O cliente solicita a criação de um objeto a uma fábrica.
Fábrica: Representa uma classe abstrata que define a interface para a criação de objetos. A fábrica fornece um método abstrato que as subclasses devem implementar para criar objetos.
Subclasse: Representa uma classe concreta que implementa a interface Fábrica. A subclasse define como os objetos devem ser criados.

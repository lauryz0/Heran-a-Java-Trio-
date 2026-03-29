# Herança-Java
 🚗 Sistema de gestão de frota

Este projeto foi desenvolvido como parte de um desafio prático de Programação Orientada a Objetos (POO). O objetivo é demonstrar a aplicação de conceitos fundamentais como herança, polimorfismo e encapsulamento em Java.

Integrantes
-Laura Fagundes Freitas RA=42413265
-
-

## 🛠️ Tecnologias Utilizadas
* **Java 21** (JDK 21)
* **Git & GitHub** (GitHub Flow)
* **Paradigma:** Orientação a Objetos

- Projeto -
O sistema simula uma hierarquia de veículos sob o pacote `br.edu.frota`.

### Hierarquia de Classes:
* **Veiculo (Superclasse):** Classe abstrata que contém os atributos base (`marca`, `modelo`) e o método comum `emitirSom()`.
* **Carro (Subclasse):** Especialização com atributo próprio `quantidadePortas` e sobrescrita (@Override) do método de som.
* **Moto (Subclasse):** Especialização com atributo próprio `temCarenagem` e sobrescrita (@Override) do método de som.

### Polimorfismo em Ação:
No método `Main`, utilizamos uma `List<Veiculo>` para gerenciar diferentes tipos de objetos (Carros e Motos) de forma genérica, demonstrando como a superclasse pode referenciar subclasses dinamicamente.


 

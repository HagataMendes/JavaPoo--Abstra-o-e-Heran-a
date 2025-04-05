# Java: Aula 6 SENAI SUZANO

# Formação Java Oracle 

## 🔨 Objetivos do projeto

Abstração & Herança
## 4. Herança
Permite que uma classe herde atributos e métodos de outra.
No código, Cliente e Instrutor herdam de Pessoa.

```java
class Animal {
    void fazerSom() {
        System.out.println("Som de animal");
    }
}

class Cachorro extends Animal {
    @Override
    void fazerSom() {
        System.out.println("Latido");
    }
}





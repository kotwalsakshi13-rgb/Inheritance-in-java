# Inheritance Example in Java

This project demonstrates a simple example of **single inheritance** in Java.  
A child class (`Dog`) inherits methods from a parent class (`Animal`).

---

## 📂 Project Structure
- **Animal.java** – Parent class  
- **Dog.java** – Child class  
- **InheritanceExample.java** – Main class to run the program  

---

## 📘 Code

```java
class Animal {
    void eat() {
        System.out.println("Animal is eating");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Dog is barking");
    }
}

public class InheritanceExample {
    public static void main(String[] args) {
        Dog d = new Dog();
        d.eat();
        d.bark();
    }
}

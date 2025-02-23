{lang=en}
### Interface

Multiple meanings, depending on context:

  1. Boundary across which two building blocks interact or communicate with each other.
  2. Design construct that provides an abstraction of the behavior of concrete components, declares possible interactions with these components and constraints for these interactions.

An example for the second meaning is the programming language construct interface from the object-oriented language Java(tm):

```java
/* File name : Animal.java */
interface Animal {
   public void eat();
   public void move();
}

/* File name : Horse.java */
public class Horse implements Animal {

   public void eat() {
      System.out.println("Horse eats");
   }

   public void move() {
      System.out.println("Horse moves");
   }
```

{lang=de}
### Schnittstelle

Mehrere Bedeutungen, je nach Kontext:

  1. Grenze, über die zwei Bausteine ​​hinweg interagieren oder miteinander kommunizieren.
  2. Entwurfskonstrukt, welches eine Abstraktion des Verhaltens konkreter Komponenten bereitstellt und mögliche Interaktionen sowie Einschränkungen für die Interaktionen mit diesen Komponenten  deklariert.

Ein Beispiel für die zweite Bedeutung ist das Programmiersprachenkonstrukt Interface aus der objektorientierten Sprache Java(tm):

```java
/* File name : Animal.java */
interface Animal {
   public void eat();
   public void move();
}

/* File name : Horse.java */
public class Horse implements Animal {

   public void eat() {
      System.out.println("Horse eats");
   }

   public void move() {
      System.out.println("Horse moves");
   }
```

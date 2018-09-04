# 100 Days Of Code - Log 1

## Day 1: August 30, 2018
### Language: Java

**Today's Progress:**
* Worked and Practiced Java Design Patterns - Adapter and Facade

**Thoughts:** 
* Adapter helps to not modify existing code but rather create a new one. Facade helps to simplify the complex subsystems.

## Day 2: September 04, 2018
### Language: Java

**Today's Progress:**
* Practiced with Java 8 Lambdas

**Thoughts:** 
* Lambdas has Function Descriptor which is the signature of abstract method
* Lambdas can be used on Functional Interface, and the Functional Interface contains only one `abstract` method, it can contain multiple `default` methods as long as it only has one `abstract` method.
* Lambdas example:
  ```java
  () -> {}
  ( List<String> list ) -> list.isEmpty()
  ( Dog dog ) -> System.out.println( dog.getName() );
  ```
* Lambda expressions can be assigned to a variable and to a method expecting a Functional Interface as the argument
* `@FunctionalInterface` annotation is used to indicate that the interface is intended to be a Functional Interface, but it isn't mandatory.



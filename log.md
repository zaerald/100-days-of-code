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

## Day 3: September 05, 2018
### Language: Java

**Today's Progress:**
* Practiced with Java 8 Lambdas

**Thoughts:**
* I am now starting to grasp the topic more
* Behavior parameterization can now be easily achieved with Lambdas

## Day 4: Septembeer 06, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java 8 Lambdas

**Thoughts:**
* I'm having a hard time figuring out how to properly make method references.
* *target typing* makes the lambda expression can be associated with different functional interface
* Type Inference sometimes make the code readable 
  * e.g.
    * No type inference: `(String s) -> s.length()`
    * With type inference: `s -> s.length()`
* *free variables* are variables that aren't the parameters of lambda and defined in an outer scope
* Local variables can be used inside the lambda but they have to be explcitly declared `final` or effectively `final`. Lambda expressions can capture local variables that are assigned to them only once
* *method references* refer the method as name rather than by a description of how to call it
* Target reference is placed before `::` and the name after it.
* method references can be thinked as a syntactic sugar for lambdas

## Day 5: Septembeer 07, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java 8 Lambdas

**Thoughts:**
* I'm starting to grasp method references properly

## Day 6: September 09, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java 8 Lambdas

**Thoughts:**
* I thought I already grasp the method references, yet I still struggle with it, It feels like I know the topic yet it feels like there's still something missing.
* Chaning `Comparator`, composing `Predicate`, `Function` is a good example of using interface `default` methods.


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

## Day 7: September 10, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java 8 Streams

**Thoughts:**
* Streams make it easier to manipulate collections like querying a database.

## Day 8: September 11, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java 8 Streams and Generics

**Thoughts:**
* There are times where I got confused with Generics, because when using Streams and Lambdas you'll have to extensively use Generics which means that I still doesn't fully understand Generics especially when there's a wildcards.
* Streams can be traversed only once
* There are two types of operations on Streams: *intermediate operations* and *terminal operations*
* I'm amazed on how the streams have *loop fusion* which makes the *intermediate operations* merged into the same pass.
* *loop fusion* is applied when there is a *short-circuiting* on the operation
* I practiced working on Generics again to refresh my knowledge on it.
* I realized that there are really much need to learn on Generics.

## Day 9: September 12, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java Generics

**Thoughts:**
* I'm starting to grasp why I can get on `List<? extends Animal>` and can't add. I can add on `List<? super Animal>` and can't get.

## Day 10: September 13, 2018
### Language: Java
**Today's Progress:**
* Practiced with Java Generics

**Thoughts:**
* I can't focus properly because I got sick, so I just scanned it and tried working on few concepts.

## Day 11: September 17, 2018
### Language: Java
**Today's Progress:**
* Eclipse RCP JFace Data Binding

**Thoughts:**
* I still haven't grasped it fully, and got stuck on some part and concepts.

## Day 12: September 18, 2018
### Language: Java
**Today's Progress:**
* Eclipse RCP JFace Data Binding

**Thoughts:**
* I'm still having a hard time working with Java Generics because I can't solve the `...unchecked conversion...` without using unknown type `<?>` to parameterize it properly.
* It's a bit tedious to bind the UI and Models on Java.

## Day 13: September 19, 2018
### Language: Java
**Today's Progress:**
* Eclipse RCP JFace Data Binding

**Thoughts:**
* I still didn't solve the Generics warning 😭
* Added new knowledge on JFace binding

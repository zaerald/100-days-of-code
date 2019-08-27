# 100 Days Of Code - Log 2

## Day 1: July 25, 2019
### Tech Stack: React

**Today's Progress:**
* Setup local environment for React
* Understood some of the main concepts

**Thoughts:** 
Today I started working on the [React Docs Tutorial][react-docs-tutorial], I mostly worked on the `React.createElement` which is found at [ReactElement.js][react-element-source] as it was firstly introduced when the React transforms the JSX at build time, I tried to understand it's implementation. The React element has the properties of `type`, `key`, `ref`, `props` and the `owner` which is the responsible for creating the element itself. I also found out that the `Reaact.Element` is a description of a `React.Component`, the `React.Component` consists of `props`, `context`, `refs` and an `updater`. 

Based on [React Components, Elements, and Instances][react-components-elements-instances]:
> An *element* is a plain object describing what you want to appear on the screen in terms of the DOM nodes or other components.

> A *component* ... takes `props` as an input, and returns an `element` tree as the output.

> Function components don't have instance at all. Class components, have instances.

[react-docs-tutorial]: https://reactjs.org/tutorial/tutorial.html
[react-element-source]: https://github.com/facebook/react/blob/121bfb03bccf3bdb4c5d1ba7cc53b573edb74434/packages/react/src/ReactElement.js#L300-L386
[react-components-elements-instances]: https://reactjs.org/blog/2015/12/18/react-components-elements-and-instances.html


## Day 2: July 26, 2019
### Tech Stack: Common JS, React

**Today's Progress:**
* Studied the main similarities and differences of JavaScript and Java.
* Finished the React Tutorial from their [docs][react-docs-tutorial].

**Thoughts:**
By looking up the main similarities and differences of JavaScript and Java helped me to understand and unlearn some of the things I needed to learn JavaScript. I also got a good grasped in understanding how React works and ways on how I can implement it properly.

[react-docs-tutorial]: https://reactjs.org/tutorial/tutorial.html


## Day 3: July 27, 2019
### Tech Stack: CommonJS, React, VueJS

**Today's Progress:**
* [React JS Crash Course][react-js-crash-course]
* [Vue JS Crash Course][vue-js-crash-course]
* Reviewed `this` and `prototype` keywords in JavaScript

**Thoughts:**
Learning 2 different ways on creating front-end applications with interleaving, I'm still confused if the `prototype` is the same with Java `static` keyword as the `prototype` could exists in all of the instances of the object.

[react-js-crash-course]: https://www.youtube.com/watch?v=sBws8MSXN7A
[vue-js-crash-course]: https://www.youtube.com/watch?v=Wy9q22isx3U


## Day 4: July 28, 2019
### Tech Stack: Common JS, VueJS, ReactJS

**Today's Progress:**
* Reviewed created projects
* Studied and reviewed some of the topics from ES6

**Thoughts:**
Today I just reviewed some of the projects I created from the tutorials and also added some enhancements from the tutorial to deepen my understanding.


## Day 5: July 29, 2019
### Tech Stack: VueJS

**Today's Progress:**
* [Learn Vue.js - Full Course for Beginners][learn-vuejs-full-course-for-beginners] by Gwendolyn Faraday

**Thoughts:**
Today I learned more about the VueJS framework with the Vuex and Vue-Router.

[learn-vuejs-full-course-for-beginners]: https://www.youtube.com/watch?v=4deVCNJq3qc


## Day 6: July 30, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Started a new course for React which covers more topics and concepts that also includes Redux.

**Thoughts:**
I managed to review the ES6 portion of that course and the operator '`...`' turns out has 2 behaviors based on the context that is a rest and spread operator, the rest just simply a varargs in Java 😁. Got a good grasp on the modularity of the JavaScript with the import and export.


## Day 7: July 31, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Worked on stateful and stateless components
* 2 way binding of data

**Thoughts:**
As working with React I'm a bit comfortable with it and learned most of its basic features and behaviors also noting that when passing a function through props, there's a very small performance hit when using `() => this.someFunction()` compared to using `this.someFunction.bind(this)`, I'll try to look up more about why the latter is more performant.


## Day 8: August 01, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Dynamically style React components
* Added some small features on top of the existing projects

**Thoughts:**
At first, styling with it feels awkward as you're just really creating an object representation of the styles when setting it up on the JSX file, another thing that I think that it may cause issues when you're importing the css file to the component it is added to the `header` section of the HTML which would affect all of the components currently rendered to the DOM, I'll lookup to find a way to limit the scope or just adding a class to the component container which would be referred to as when selecting the parts of the component.


## Day 9: August 02, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Worked with lists and conditionals
* Styling React Components & Elements

**Thoughts:**
Learned more about the difference between `Array.prototype.slice` and `Array.prototype.splice` as the `slice` doesn't affect the original array but the `splice` does. The technique wherein mutating arrays in React, it is better to go for the immutability which results to creating a copy of an array then mutating it. Another key aspect I learned is that when assigning a `key` props to a component as the React creates a virtual and re-renders the list of components it differentiates it to the current DOM and compares the keys and conditionally checks if it can avoid re-rendering the component.


## Day 10: August 03, 2019
### Tech Stack: VueJS

**Today's Progress:** 
* Learned about the routers using Vue Routers
* Basics of Vuex

**Thoughts:**
By having Vuex, it is now much easier to work with the data as you're only working with a single source of truth.

## Day 11: August 04, 2019
### Tech Stack: CommonJS, Java

**Today's Progress:** 
* Worked on Callbacks, Promises, Async/Await and Event Loops of JavaScript.
* Reviewed Java Streams and the `Collectors` class.

**Thoughts:**
Learned that `async` is just a syntactic sugar for `promise`. Writing it is just a bit weird as if you're writing a synchronous function but behaves as an asynchronous function.


## Day 12: August 05, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Practiced dynamically styling components & elements
* Learned different ways to debug React applications
* Diving Deeper into Components & React Internals

**Thoughts:**
Learned it is hard to have a scoped styling for the component when you're setting up a pseudo selectors, you need to have another dependency to somehting like `Radium`. There's a thing that bothers me about the Error Boundary concept which is a component that wraps another component and thinking if it is a better use case than to just catch the errors instead of wrapping them. Learned some of file structure conventions to organize the source files and improve the modularization of the components.


## Day 13: August 06, 2019
### Tech Stack: CommonJS, ReactJS, Java

**Today's Progress:** 
* CommonJS: Prototypal inheritance
* ReactJS: Worked more on dynamic styling of components
* Java: Reviewed generics subtyping and wildcards

**Thoughts:**
Learned that the `class` in JS are just a syntactic sugar and not a the `class` like Java, the `class` in JS is a prototypal object that is created like a `Function` object and contains the `prototype` which points to the parent. In React I'm still finding a way to style the components like `Vue` with a `scoped` one but found out that we needed a 3rd party library to work on it which is `Radium` as unlike the `Vue`, the template, css, and JS are separated, but with React it is just only a JS that transpiles the jsx syntax into `React.createElement()`.


## Day 14: August 08, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Modular CSS
* Component lifecycle
* Converting stateless to stateful components

**Thoughts:**
Finally found the way how to properly scope styling of the components, also learned the lifecycle of each component.


## Day 15: August 09, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* Component updating lifecycle hooks
* Higher Order Components 

**Thoughts:**
Still don't know when to use each lifecycle hooks but fortunately got aware on these hooks.


## Day 16: August 10, 2019
### Tech Stack: CommonJS, Java

**Today's Progress:** 
* CommonJS: Currying, Composing and Functional purity
* Java: Future and CompletableFuture

**Thoughts:**
With currying, composing and functional purity concepts, I only grasped them a little, so I'll go back to these topics in the near future.


## Day 17: August 11, 2019
### Tech Stack: Redux, VueJS

**Today's Progress:** 
* Redux Basics
* VueJS: Unit Testing

**Thoughts:**
I got a hard time learning unit testing on Vue front-end, I do not know what to test or what part of it to test.


## Day 18: August 12, 2019
### Tech Stack: VueJS

**Today's Progress:** 
* VueJS: Unit Testing

**Thoughts:**
Found myself looking for different resources as I'm having a hard time working on the unit tests for front end side.


## Day 19: August 13, 2019
### Tech Stack: CommonJS, ReactJS, Java

**Today's Progress:** 
* CommonJS: Promises, Async/Await and Currying
* ReactJS: Using references
* Java: Stream Map Collection

**Thoughts:**
Currying helps especially to reduce the number of arguments passed to a function, especially whenever you invoke the function multiple times with the same argument value, this will help like a function generator that holds the passed value that can be used in another function invocation. Working with React, there's so many new terminology and buzz words I encounter like HOCs, functional purity, Pure components and there's too much to handle, so I am planning to work on it bit by bit but on the other hand, I think I grasped the basics of React, I'll just need to practice more of it. With Java's stream collection, I mostly used the `toList()` and there's so much more when using the `Collectors` class, I managed to work on the `Collectors#toMap` to collect the stream.


## Day 20: August 14, 2019
### Tech Stack: ReactJS, Java

**Today's Progress:** 
* ReactJS: Using `ref` and validating `props` types.
* Java: Reviewed and practiced `Collectors#groupingBy`, `Collectors#partitioningBy`, and `Collectors#summarizing(Int|Long|Double)`

**Thoughts:**
I was surprised that React uses a 3rd party library to just check on the property types passed to them, unlike Vue which you can state what are the types that are passed to the child. In Java I'm still having troubles with `groupingBy` especially when passing it with a downstream of `Collectors#mapping` and `Collectors#reducing`.


## Day 21: August 16, 2019
### Tech Stack: CommonJS, ReactJS, Java

**Today's Progress:** 
* CommonJS: Reviewed Promises and Async/Await.
* ReactJS: Learned how to create layout components and the layout container.
* Java: Reviewed `Collectors` API and especiallly the downstreams of `groupingBy`.

**Thoughts:**


## Day 22: August 17, 2019
### Tech Stack: ReactJS, VueJS, Python

**Today's Progress:** 
* ReactJS: Worked on burger builder
* VueJS: Unit Testing
* Python: CLI for XML Parsing

**Thoughts:**
For Unit testing in Vue there's a part that I think I get it, but it feels like I still don't get it.


## Day 23: August 18, 2019
### Tech Stack: VueJS

**Today's Progress:** 
* Unit Testing

**Thoughts:**
I tried to tackle it again, and managed to create a unit tests but not too advanced.

## Day 24: August 19, 2019
### Tech Stack: ReactJS, CommonJS

**Today's Progress:** 
* ReactJS: Just fiddling and try to break some things and see how other things work

**Thoughts:**
By doing this, I managed to recall the topics I've gone through and hoping this would strengthen my recall for the topics and concepts of React.


## Day 25: August 20, 2019
### Tech Stack: React JS

**Today's Progress:** 
* Progress on the course

**Thoughts:**
Mostly followed the tutorial and just try to play with it.


## Day 26: August 21, 2019
### Tech Stack: Java, ReactJS

**Today's Progress:** 
* Worked on the overview of the Java 11 features
* ReactJS Course

**Thoughts:**
Found out that there are many new cool features of Java 11.


## Day 27: August 22, 2019
### Tech Stack: ReactJS

**Today's Progress:** 
* ReactJS Course

**Thoughts:**
Getting the hang of it on React.


## Day 28: August 23, 2019
### Tech Stack: Java

**Today's Progress:** 
* Worked on `Collectors` API and mostly on `groupingBy` collector. 

**Thoughts:**
Still a bit hard to grasp the topics about the `groupingBy` collector and the downstream.


*3 day span as I'm out of town and having no physical access to computer*

## Day 29: August 27, 2019
### Tech Stack: Java

**Today's Progress:** 
* Worked on `Collectors` and reviewed it.

**Thoughts:**
Now having a good grasp on the usage of the `Collectors` API as I'm mostly using `Collectors#toList`.
I have tackled
  * `toList()` - commonly used and familiar with it already
  * `toSet()` - not hard to grasp as it is mostly similar with `toList()`
  * `toCollection()` - this one is different as you're telling which implementation to be used
  * `toMap()` - this needs two parameters, the keyMapper and valueMapper to create the mapping, and another parameter to resolve the duplicates of the values.
  * `collectingAndThen()` - this helps chaining the collection
  * `joining()` - only used in `Stream<String>` to join them, we could add delimters and also having post and pre delimeters.
  * `counting()` - this just basically counts the number of Stream elements
  * `summarizingDouble/Long/Int()` - creates a statistics of the given value
  * `averagingDouble/Long/Int()` - generates the avarage of the given value based on the Stream elements
  * `summingDouble/Long/Int()` - this is the same as `averagingDouble/Long/Int()` but just getting the total value
  * `maxBy()` and `minBy()` - returns the max or min value based on the `Comparator` and also wrapped with `Optional`
  * `groupingBy()` - this could also be another topic but also reviewed it, just also groups the values and creates a Map instance
  * `partitioningBy()` - specialized `groupingBy()` that generates the type of `Map<Boolean, SomeTypeHere>` based on the predicate.
I found out that I still do not fully grasp or not having practiced the `Comparator` interface used for sorting and was also used in `maxBy()` and `minBy()` so I'll tackle it for tomorrow.


## Day 30: 
### Tech Stack: 

**Today's Progress:** 
* 

**Thoughts:**
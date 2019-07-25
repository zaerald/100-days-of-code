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

## Day 2: 
### Tech Stack:

**Today's Progress:**


**Thoughts:**


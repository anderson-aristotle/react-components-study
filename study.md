# React Components Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. _Please do not respond with direct quotes from source
material._ Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- [Components and Props](https://reactjs.org/docs/components-and-props.html)
- [React Components](https://reactjs.org/docs/react-component.html)
- [State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

## Define Components

In your own words, define what a React component is. How can they make our
development process easier?

```md
<!-- your answer here -->
```

## React Building Blocks

Fill in the `<blank>`s:

```md
React considers everything to be a <blank>.
Components are like Javascript <blank> that take <blank> and return <blank>.
```

## Pure Components

Explain what the following means in your own words:
"All React components must act like pure functions with respect to their props."

```md
<!-- your answer here -->
```

## Component Life Cycle

There are a handful of methods designated for handling component life cycle.
Put the following in order of when they are called and define what they do:

Mounting:

```md
componentDidMount()
constructor()
render()
```

Updating:

```md
componentDidUpdate()
render()
setState()
```

## State

We can use the `setState()` method to update our components, but it's easy to
use it incorrectly. Refactor the following *bad* code to use `setState()`
properly.

```js
// Wrong
this.setState({
  counter: this.state.counter + this.props.increment,
});
```

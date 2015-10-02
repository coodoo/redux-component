## Quick Start

React stateful component creator using redux.

### Inspiration

* [react-redux][react-redux]
* [cycle-react](https://github.com/pH200/cycle-react)
* [ducks-modular-redux][ducks-modular-redux]

### Use Cases

#### Stateful component with local state

Sometimes, you don't want every state in your application to go into global redux store. They could be just local state existing in the component with `setState` calls. `redux-component` provides you a clean and testable interface to write such stateful component.

#### Migration to redux

You have a existing flux architecture in the application, but you would like to migrate to `redux`. `redux-component` helps you do that with progressive steps.

#### Start local and push to global when necessary

Build statefull components with `redux-component` and apply `ducks-modular-redux` approach in it. When a global state is needed, simply extract out `actionCreators` and `reducers` into global redux architecture, then `connect` it with the component and you're done.

### Yeah so how do I get started?

Checkout [ducks-modular-redux][ducks-modular-redux]. You've used `connect` from [react-redux][react-redux] already, right? Awesome. You've already learned `redux-component`. Here's the **only** one concept you need to check out [API](https://github.com/tomchentw/redux-component/blob/master/docs/api.md) in the docs and you're cool now.

[react-redux]: https://github.com/rackt/react-redux/
[ducks-modular-redux]: https://github.com/erikras/ducks-modular-redux

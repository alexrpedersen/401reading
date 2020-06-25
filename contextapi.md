# ContextAPI

### Context
- A mean of passing state down the component tree through a Provider/Consumer relationship
- At the high level, a Provider can make its state available, along with means of altering it (methods)
- At the lower level, any component can opt-in and become a Consumer and receive this.state from context

### ways to get context
- wrapper and use a get function to pull in context
- declare the connection directly and access this of the provider
- function components can access via useContext()

## Examples
- https://reactjs.org/docs/context.html
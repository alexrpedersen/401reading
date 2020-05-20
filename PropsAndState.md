# Props and State 

## Props 

#### Components accept arbitrary inputs called props. In JSX, props are passed into a component with a syntax that looks like HTML attributes. These are the equivalent of function params. 
#### props is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on props.
#### After props is passed into the constructors super function, they are available on the context by using this.props.
#### This allows us to pass functions like variables even though we have been doing it with callbacks with jquery. This allows us to get really awesome with it.

## One Data Flow

#### State can only be passed from parent component to a child component through the use of props. This enforces the idea of one way data flow. One way data flow is a way of describing that state can only be passed down the component tree (not up). If a child wants to pass some data to a parent, the parent can pass a function to the child through props and the child may invoke that function and pass it data for the parent to manage.

## Making a functioning clock

### https://reactjs.org/docs/state-and-lifecycle.html


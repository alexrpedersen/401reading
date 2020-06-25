# Application State with Redux
- Requires the combination of 3 distinct aspects into a “Store”
- All components can have access to the "store"

## State
- Reducers - (strategies to alter state)
- Actions (methods that get “dispatched” or “run”, which trigger associated reducers)

## Redux Store
- Where your application state is stored.
- It's job is to identify the various reducers.
- Middleware used globally.
- React uses “reducers” to hold and manage state.
- Reducers manage just one part of the larger application state.
- It creates an initial “empty” state
- Then identifies what todo when called.
- Reducers hear the "dispatch", and “payload”

## React with redux
#### React applications with Redux dispatch “actions” (like an event) with “payload” (data). An action creator function as shown below always returns an action object with the action type to perform and the data to perform it with. When your component wants to modify state, it “Dispatches” (calls) an action and sends whatever payload (data) it needs to, to the reducer.

## https://redux.js.org/
## https://egghead.io/courses/getting-started-with-redux
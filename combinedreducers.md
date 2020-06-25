# Combined Reducers
- Nothing more than pulling in more than one reducers from source and creating a keyed object from them
- Any component can reach into the store and use state

## What's the point of combined reducers?
- Obey the single responsibility principle (single source of truth)
- Each reducer really should have only 1 part of state to manage
- Is this more work/boilerplate? Yes
- Does it allow you decouple logic? Yes

## What about the actions?
- Each reducer technically has its own actions and creators
- However, they can cross over and both be dispatched
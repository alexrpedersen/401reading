# Custom Hooks

## Custom Hooks

#### What are custom hooks?
- Extract duplicated logic from components
- Share common functionality
- But not state…
- Take advantage of useEffect lifecycle
  
### Common use cases – make things DRY!
- Handle forms easily
- Pre-fetch API data
- Connect to services (like socket.io, Q, etc)

### Proper Wiring

- Hooks are exported as a function, named as useXXX()
- Hooks return data or behaviors (functions) that are required to reuse their internal functionality
- Hooks are imported into components
- Components can re-use the hook functionality or data/state as needed
- Hooks do not render
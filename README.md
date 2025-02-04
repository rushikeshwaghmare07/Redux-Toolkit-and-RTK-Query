# Redux-Toolkit-and-RTK-Query 

## Redux -
Redux is an open-source JavaScript library for managing the state of an application in a predictable way. It is commonly used with libraries like React for building user interfaces but can be used with any JavaScript framework or library.

## Toolkit -
The official opinionated, batteries-included tool set for efficient Redux development

## Store -
A store is a central place where the state of our application is stored and it can be created using the configureStore function, and it holds the entire state tree of our application.

**Note -** A store is not a "class". It’s just an object with a few methods on it. To create it, pass your root reducing function to createStore.

## Store Methods

- getState()

- dispatch(action)

- subscribe(listener)

- replaceReducer(nextReducer)

## What is Slice ?
A slice is a **piece of store state** and the corresponding reducer logic to update that state. Slice are a way to organize our Redux store by breaking it down into smaller, more manageable parts.

**Slice Analogy -** Imagine you have a big cake, and you want ot cut it into smaller, more manageable pieces. Each smaller piece is like a "slice" of the cake. In the context redux toolkit a "slice" is like a smaller part of your application's overall state and the instructions on how to change or update that specific part.

## Reducers ?
- Reducers are like the instructions on what to do with slice of the cake.

- They define how the information in a particular slice can be changed or updated.

## useSelector() Hook ?
- useSelector hook allows us to read data form the redux store.

## useDispatch() Hook ?
- The dispatch function is used to send actions to the store, triggering updates to the application state.

- In simpler terms, it lets you change the state in your Redux store form within your React components.

## Redux Toolkit Query
- Redux Toolkit Query (RTK) is specifically designed to simplify data fetching, caching and state management for API calls in a React and Redux application.
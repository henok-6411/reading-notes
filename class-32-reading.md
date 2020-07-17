[homePage](https://henok-6411.github.io/reading-notes)

# Redux - Asynchronous Actions

- Action - When you call an asynchronous API, there are two crucial moments in time: the moment you start the call, and the moment when you receive an answer (or a timeout).

- Redux Thunk - is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the body of the function once the asynchronous operations have completed.
we have to install inorder to use Thunc ``` npm install redux-thunk ``` . Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.



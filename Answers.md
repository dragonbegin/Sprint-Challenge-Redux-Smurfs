1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object? 

-filter -map -spread -reduce

2.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

-actions: the trigger to call a reducer. 
-reducers: a function that never create a side effect.
-store: everything that changes in the application, single javaScript Object holding the state for the application.

3.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

-Application state: global state that can be access from anywhere by connect
-Component state: state component pass down as props.

4.  What is middleware?

-middleware: tool used in programming to intercept data flow and data functionality.

5.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

-redux-thunk: is a node package use to make API calls from data. the action is call inside the action-creator, this allow for direct server data request.

6.  Which `react-redux` method links up our `components` with our `redux store`?

-connect 

# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    It's much easier to to do prop drilling and it's less complex than redux.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    actions is a place to store all the action constants and functions that returns an action object to the reducer, reducer is use to initialize the state with a structure that can't be change and the property inside the state can be change through the switch case. store is use to store the reducer and used as an attribute of the provider.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    redux-thunk allow us to do asyn action, it changes our action-creator to be able to create actions that can contain other actions inside action function.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    I would say redux, it's complicate at first but everything makes sense and I think it's really useful to manipulate the states since you don't have to worry about any side effect.
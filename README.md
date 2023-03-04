# Quiz-5

1. What is a "side effect" in React? What are some examples?

Side effect in React is any function or something that does something in other component. Like fetch data from an api and show this data in the window.

2. What is NOT a "side effect" in React? Examples?

Is not a side effect any function or something that dosent do something in other component. Like a simple component function or

3. When does React run your useEffect function? When does it NOT run

We need to use "useEffect" when we need to run a function or something after the page runs and run it again when the depencies have changed. It cant run when the dependecies of the page dont have changed.

4. How would you explain what the "dependecies array" is?

The dependencies array is an array that contains the values that the useEffect hook depends on. When any of the values in the dependencies array change, the effect function will be called again.

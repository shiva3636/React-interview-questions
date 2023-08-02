# React-interview-questions
This React interview question and answer in brief.
# What is useEffect hook in react js?
UseEffect hook is a function that is provided by react itself. It is used to perform side effects inside the function base components.
It is similar to the lifecycle methods like- **componetDidMount()**, **componentWillMount()**, and **componentWillUnmount()** in class base components.
### It is called just after the render phase is completed and the component is added to the DOM.
The effect is executed asynchronously, so it won't block the rendering of the component.

## Syntex - 
                         `import React, { useEffect } from 'react';

                          const MyComponent = () => {
                           // Effect function
                           useEffect(() => {
                          // Side effects and cleanup code here
                          // This code will run after the component is rendered
                         // It may run again on re-renders depending on dependencies
                         // (or on unmount if you return a cleanup function)
                          }, [/* dependencies */]);

                        // JSX for the component
                         return (
                           // JSX code here
                          );
                        };`

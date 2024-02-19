## React Component Return

Any component can only return a single top level JSX

    WHY?

    - Makes it easy to do reconcilliation. {the process of figuring out what DOM updates needs to happen as rerencer occurs}.

Lets understand it by doing a bit of code.

    Create a React app that has :
        
        - Header component that takes a title as a prop renders it inside a Div.
        - The top level app component renders two headers.
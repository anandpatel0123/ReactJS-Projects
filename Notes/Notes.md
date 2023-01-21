
#### Day-1
```markdown
Steps to create the react component in 5 steps
1. Import the React and ReactDOM libararies
`import React from 'react'`
`import ReactDOM from 'react-dom/cleint'`
2. Get a refference to the div with ID root
`const el = document.getElementByID('root')`
4. Tell react to take control of that element
`const root = ReactDOM.createRoot(el)`
6. Create a component
`function App(){
	return <h1>Hi, there!</h1>
}`
8. Show the component on the screen
`root.render(<App />)`
```

` Note: React cannot render JavaScript objects{}, null, undefined


##### Props (Properties)
`Props can refer to any variable`
<pre>
we can provide an object to a <b>Prop</b>
</pre>

<pre>
function App() {
    const message = "Enter age";
    return (
        <input
            type="number"
            min={5}
            max={10}
            list={[1, 2, 3]}
            style={{ color: "red" }}
            alt={message}
        />
    );
}
</pre>

#### Converting HTML to JSX

```markdown
1. All prop names follow camelCase
2. Number attributes use curly braces 
`<textarea autoFocus={true} />`
`<textarea autoFocus />;`
3. Boolean 'ture' can be written with just the property name. 'False' should be written with curly braces
4. The 'class' arrtibute is written as 'className'
5. In-line styles are provided as Objects
```


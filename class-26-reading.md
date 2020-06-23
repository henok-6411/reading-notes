[homePage](https://henok-6411.github.io/reading-notes)

# Class 26 — Hooks API 

- What does a component’s lifecycle refer to?

    it refers the cycle from creation to unmount from the DOM.This cycle have four major steps initialization,mounting,updating and unmounting.
    
- Why are functional components preferred over class components?

    It's less complicated and shorter to write. 
    
- What is wrong with the following code?
 ``` import React, {useState, useEffect} from 'react'; 
   
function MyComponent(props) {
  const [count, setCount] = useState(0); 
     
  function changeCount(e) {
    setCount(e.target.value); 
  }
     
  let renderedItems = []
     
  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update'); 
    }, [count]); 
       
    renderedItems.push(<div key={i}>Item</div>); 
  }
     
  return (<div>
    	<input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```


# React

### Brief History :

* 2011 - Created by Facebook
* 2012 - Used on Instagram
* 2013 - Open Sourced
* 2015 - Reactive native released
* 2016 - React 15 was released
* Present - 50K+ components at Facebook, Full staff, Used by many

### Why should you choose React:

### Flexibility: 
* React is a library, not a framework. More flexible than frameworks like Angular and Ember. Used for creating components for web apps, can generate static sites using some tools,
* Using React Native, we can create truly native mobile apps. With tools like Electron, we can build desktop apps. Server rendering using NEXT.js, React VR for virtual reality. 
* React renderers: render is separate from React, react-dom, react-native, react vr and many are the renderers respectively.
* Server side rendering: NEXT.js, Gatsby, Phenomic
* Can be used in existing apps to replace some components with react gradually.. 

### Developer Experience:

* React API is very small and straight forward, very few concepts to master

```

import React from 'react';

function HelloWorld( props ){
    return <div> Hello {props.name} </div>
}

```
```
import React from 'react';

class Helloworld extends React.Component {
  render() {
     return <div> Hello {props.name} </div>
  }
}
```

JSX compiles to JS

```
<h1 color="red"> Heading here</h1>

React.createElement("h1", {color:"red"},"Heading here");

```

React handles HTML with Javascript, no need to learn new specific rules/keywords for syntax, looping and conditional.

### Corporate Investment:

* react code-mod automatically updates all components to latest code change. 
* easily resolve breaking changes by running a script.


### Community

* huge active community
* a huge list of components are freely available

### Performance

* smartly updates DOM in a most efficient way

### Testability:

* Tests are automatically configured
* run in memory via node
* reliable and deterministic unit tests
* popular tools are avilable (all js test tools can be used)

## Tradeoffs:

* Framework vs Library (framework has clear advantage)
* Concide vs Explicit
* Template centric vs JS centric
* Separate template vs single file for component
* Standard vs non standard
* Community vs Corporate backing 



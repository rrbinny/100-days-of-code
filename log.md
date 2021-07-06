# 100 Days Of Code - Log

### Day 1: June 20, 2021

**Today's Progress**:
Today I worked on this TypeScript + React Project Course I was doing by Stephen Grider.
I completed the mini-project which was to encompass everything I was learning about TypeScript to the point within the course. TypeScript syntax, Type annotations, Type inference engine, interfaces, Type Definition Files, TypeScript Design Patterns.
Other than that I worked on coding problems on CodeWars.
**Thoughts:**
I feel that I got a lot of through TypeScript with fair ease. Stephen explains stuff really well so I got a grasp of it pretty easily. Plus I've used Java and the similarities are there.
**Link to work:**
https://github.com/rrbinny/maps

### Day 2: June 21, 2021

**Today's Progress**:
Today I worked on this TypeScript + React Project Course I was doing by Stephen Grider.
I learnt about using React with TypeScript and the big differences with Type Annotations and interfaces to make sure everything conforms.
I started making progress learning about using Redux with TypeScript.
**Thoughts:**
This was quite a lot for me today if I have to be honest. Even though it was explained well, I need to make sure to look over my notes and the projects to make sure I understand everything.
**Link to work:**
https://github.com/rrbinny/rts
https://github.com/rrbinny/reduxts

### Day 3: June 22, 2021

**Today's Progress**:
Today I worked on this TypeScript + React Project Course I was doing by Stephen Grider.
I completed the Redux with TypeScript mini-app.
**Thoughts:**
Redux with TypeScript is a bit weird. I think one of things that confused me especially was using custom Hooks to make sure to set a type on a specific hook to make sure that the state it accesses is the type of object we define in TS in an interface.
**Link to work:**
https://github.com/rrbinny/reduxts

### Day 4: June 23, 2021

**Today's Progress**:
Today I worked on this TypeScript + React Project Course I was doing by Stephen Grider.
I learnt about Webpack bundling and transpiling as well as started the process of introducing ESBuild to the full application.
**Thoughts:**
There was a lot to take in for this, I think I need some time to really read into ESBuild and Webpack and truly understand the concepts
and methods used.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 5: June 24, 2021

**Today's Progress**:
Continued on the Stephen Grider course. Using ESbuild, the application can now transpile and bundle CSS, NPM Modules and JS Code in general. I used caching so that the unpkg(copy of NPM registry) isn't called all the time.
**Thoughts:**
I got a lot done today and I feel I have a deep understanding of ESBuild.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 6: June 27, 2021 (missed two days because I had a lot of stuff going on)

**Today's Progress**:
Continued on the JBook Application. I made some progress handling code execution in the browser.
**Thoughts:**
Working with iFrames to get our code running is a weird rabbit hole but I understand the flow that on how
code will be transpiled and bundle in the browser.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 7: June 28, 2021

**Today's Progress**:
Continued on the JBook Application. I finished handling code execution and created a code editor inside the react app.
**Thoughts:**
I made some great progress today in actually getting the code editor finished with autoformatting and syntax highlighting inside the application.
Can't wait to go further!!
**Link to work:**
https://github.com/rrbinny/jbook

### Day 8: June 29, 2021

**Today's Progress**:
Continued on the JBook Application. Made progress on adding resizable components within the application and refactoring the application.
**Thoughts:**
Using the react-resizable package to do this is a simple to understand but to work in the application it is a bit weird
**Link to work:**
https://github.com/rrbinny/jbook

### Day 9: July 1st, 2021

**Today's Progress**:
Continued on the JBook Application. I completed the resizable components, error handling for async and bundling errors as well as
the markdown editor for the application!
**Thoughts:**
I didn't have too many issues working with the md-editor package. It made things easier, I guess the main focus was
just on styling and making sure it was inline with the colours of the application. Other than that error handling
was fine too in terms of async errors but with code bundling errors I found it weird how I had to move the bundling error
message in front of the preview window.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 10: July 2nd, 2021

**Today's Progress**:
Continued on the JBook Application. I added the redux store, reducers, actions and action creators in relation to a
specific code cell. I started using Immer to make the cell logic inside the cellsReducer much easier to read and not as long-winded.
**Thoughts:**
Using redux with TS was pretty straightforward because I had done the previous redux-ts mini project prior in the course. I was surprised by how Immer simplifies, the updating state process all that code to just update one property in the state just changed to one line!
**Link to work:**
https://github.com/rrbinny/jbook

### Day 11: July 3rd, 2021

**Today's Progress**:
Continued on the JBook Application. Defined the actions for the cellsReducer and started connecting React to Redux (by this I mean creating the actual code cells).
**Thoughts:**
Nothing too much to say honestly, had to fix some issues here there when defining actions in particular with the produce function with immer but it was fine.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 12: July 5th, 2021

**Today's Progress**:
Continued on the JBook Application. Continued on creating the actual code cells, with the action bars to move components, delete them etc.
**Thoughts:**
Nothing too much tbh for this instance.
**Link to work:**
https://github.com/rrbinny/jbook

### Day 13: July 6th, 2021

**Today's Progress**:
Continued on the JBook Application. Completed what I was doing previously in terms of the actual code cells, action bars etc. I connected the bundler to the redux side of the application. THe bundler renders immediately on an initial adding of a code cell and subsequently when the user types codes and doesn't type anything for 1 second.
**Thoughts:**
Trying to get the bundler to work with Redux was not too hard honestly. I just had to transition my thinking of local state for bundling, to using the redux store instead and doing the bundling process through redux.
**Link to work:**
https://github.com/rrbinny/jbook

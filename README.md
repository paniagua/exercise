# Exercise Description

## Part I
Create a hello-world JS application. This application will serve as a foundation for Part II - setting up the tools and environment. The application must fulfill the following requirements:
i
- ES6 support
- At least 3 javascript files, of which 2 are required in one main javascript file(e.g. main.js, can have other name ).
- One of the required javascript file must have a class inside and the class must be used by main javascript file.
- The other required javascript file must manipulate write to the DOM “Hello World” when the page is ready.
- The assets must be transpiled and bundled by a modern bundler, like browserify, webpack, etc.
- All dependencies must come locally, not from CDN.
- DOM must be manipulated only when DOM is loaded. Don't use jQuery!
- The app should be easy to install and open on port 3000. E.g. by running `npm install && npm start`, after open `http://localhost:3000`


## Part II
Using the existing application from Part I add some new functionality.

Using React, create a single player version of a speed-typing game with following functionality.

- There must be multiple random words on the screen for user to type.
- There must be an input where an user can type words.
- There must be an area which shows statistics - Words per minute and accuracy.
- The user input needs to be handled only within the input component. It does NOT need to be propagated to parent. As such, when user types a word, the random words components and statistics components do not need to be affected.

Every component must be in a different file.
All required data, like random words, stats, etc can be mocked/hard-coded.
All props must be validated.
Dont put node_modules dir to solution.
Use camel case code style for everything, except CSS.
Don't use jQuery!

Please add your solution to a public repository (e.g github or bitbucket) and share it with us. 

### Help Materials

https://docs.google.com/presentation/d/1trH4HnyjGWTS-Hl0TbbPkgEf4Cik-hx5AXuvMERftZY/edit?usp=sharing
https://docs.google.com/presentation/d/1SBNY81GXoQGY9AV5zEyPRRGu1s7qoSXP9gnC9F8Q8tM/edit?usp=sharing

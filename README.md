# NBA-Player-Data
## Purpose: 
Visualized individual player’s profile and shot data. Provide customized view by building a shot chart - both hexbin and scatter

This project was bootstrapped with Create React App.
```
npm install -g create-react-app 
```
Use ``` npm start ``` to render UI in browser

#### FrameWorks and Tools:
React, D3, Ant Design, Node.js, NPM, etc.

#### Data Sourced: 
Fetched data from stats.nba.com

#### Tech Stacks:
- React:
  - React is maintained by Facebook, and is a JavaScript library for building user interface. It has been a popular building framework to create interactive UIs since it is component-based.
  (Take a React tutorial on official website: https://reactjs.org/tutorial/tutorial.html)
  - Each component manages their own state, it is very easy for programmers to pass data through your app since the component is written in JavaScript. Components can be reused (even in different projects), and programmers can develop new features in React without rewriting existing codes.<br>
  Define small components -> Build up into large components (composing components)<br>
  Think about using component to split UI into many isolated, independent pieces. 
  
  #### Virtual DOM and Diffing Algorithm
  - DOM (Dcoument Object Model). When a change occurs, a new virtual DOM is created to reflect the new state of the data model.
  - Since a new virtual DOM has been createds, now React has two virtual DOM to runs a diffing algorithm on them. The main concept of diffing algorithm is to get the set of changes between the new one and the old one. 
  - The last step is applying these changes (and ONLY these changes) to real DOM, and render it.
  
  
- Ant Design:<br>
(Official Website: https://ant.design/)
  - Ant Design provides many UI components, reliable libraries, and other open sources for UI design, which can be used directly in your project to improve the efficiency of development. <br>
  In this project, I used components from Ant Design to create the search bar, slider under the chart, ect.<br>


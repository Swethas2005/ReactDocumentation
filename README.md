# React-Documentation

#### 1.What is React?
`React` is an open-source JavaScript library for building *user interfaces or UI components. It was developed and is maintained by` **Facebook.` React is particularly popular for creating **single-page applications* where user interfaces need to be dynamic and responsive.

#### 2.Who made React?
`React` was created by Jordan Walke, a software engineer at Meta, who released an early prototype of React called `"FaxJS"`.
`React` was created and developed by `*Facebook*`.

#### 3.What is Babel?
`Babel` is a JavaScript compiler that converts modern JavaScript code into a version that is compatible with all browsers. 

#### 4.How does Babel convert html code in React into valid code?
`Babel` is a key tool that can translate JSX syntax, which is used to create HTML-like code in React components, into valid JavaScript code that can be executed in preferred browsers. By converting the JSX code into JavaScript functions that return the same HTML-like structures.

#### 5.What is ReactDOM used for? Write an example?
`ReactDOM` is a package in React that provides DOM-specific methods that can be used at the top level of a web app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with an API containing the various methods to manipulate DOM.

>const reactRoot = ReactDOM.createRoot(rootElement)
reactRoot.render(element)


#### 6.What are the packages that you need to import for react to work with?
 For the React to work as intended we need to import certain React package and ` React DOM package`into the script tag,
 
 React Package: https://www.unpkg.com/react@18.2.0/umd/react.development.js
 

 
React DOM Package : https://www.unpkg.com/react-dom@18.2.0/umd/react-dom.development.js
 

 #### 7.How do you add react to a web application?
 In order to add React to your Web application,
 1. Add React and ReactDOM libraries to your webpage using these packages.

 React Package: https://www.unpkg.com/react@18.2.0/umd/react.development.js
 

 
React DOM Package : https://www.unpkg.com/react-dom@18.2.0/umd/react-dom.development.js
 
 2. Define a location in your HTML (like a div with an ID of "root") where your React application will be attached.
  3. *React and React.createElement* : In vanilla JavaScript, you'd interact directly with the DOM elements using the Document API. With React, you don't do that. Instead, you deal with *React elements*. We use createElement method from react to create React elements

  #### 8.What is React.createElement?
 
In React, React.createElement is a function that is used to create React elements.

#### 9.What are the three properties that createElement accept?
The React.createElement function accepts three properties:

1.Type (String or React Component): This is the type of the React element to be created. It can be either a string representing an HTML tag (e.g., 'div', 'span') or a reference to a React component. This is the first argument of the createElement function.

2.Props (Object): An object containing the properties (or "props") you want to pass to the element. These can include attributes such as classname, style, or any custom data that the component might use. This is the second argument of the createElement function.

3.Children (React Elements, Strings, or Arrays): Any additional arguments after the props are considered the children of the element. Children can be other React elements created using createElement, strings, or even arrays of elements. This is the third and subsequent arguments of the createElement function.

#### 10.What is the meaning of render and root?
1. In React, render refers to the process of converting React components into HTML elements and displaying them on the user interface.
2. In the context of React applications, the root usually refers to the root DOM element where the entire React application is mounted.

---


Hello, I'm Sayeed Ahmed, and I'm excited to embark on my journey into React.js. Eager to explore its powerful capabilities for building dynamic and efficient user interfaces.

1. What is React ?
> React is like a toolbox for web developers, It's all about making websites more interactive and dynamic. Imagine building with Lego blocks – React lets you create reusable building blocks for your web pages, making it easier to build and maintain awesome websites

2. Who made React ?
> React was developed by Jordan Walke, a software engineer at Facebook. It was first deployed on Facebook's newsfeed in 2011 and later open-sourced in May 2013. Since then, it has gained widespread adoption in the web development community.

3. What is babel ?
> Think of Babel as a translator for JavaScript. When developers write code using the latest and coolest features (like ES6 or ES7), Babel steps in and transforms that code into a version that older browsers can understand

4. How does Babel convert html code in React into valid code ?
> Think of Babel as a magician for your React code. When you write  fancy HTML-like stuff (called JSX) in your JavaScript, Babel steps in and transforms it into a language everyone's browser can understand.

5. What is ReactDOM used for? Write an example ?
> ReactDOM is like the boss of rendering in React. It takes your fancy React components and puts them into the DOM (Document Object Model), making your web page come to life. Here's a simple example:

*>  const myComponent = () => {
        return <div>Hello, ReactDOM!</div>;
    };

    Now, ReactDOM steps in to render this component into an actual web page. You might do something like this:

*>    ReactDOM.render(<myComponent />, document.getElementById('root'));

In plain English, this says, "Hey ReactDOM, take my cool 'myComponent' and stick it into the HTML element with the ID 'root'." And just like that, your component becomes part of your web page, thanks to ReactDOM's rendering magic.

6. What are the packages that you need to import for react to work with ?
> To make React do its thing, you need a couple of buddies, and they come in the form of packages. Think of them as teammates that help your web development game.

React: import React from 'react';
ReactDOM: import ReactDOM from 'react-dom';
Babel: import '@babel/preset-react';

7. How do you add react to a web application ?
>
 1. Set up NodeJS and npm:
    Ensure that Node.js and npm (Node Package Manager) are installed on your machine
 2. Create a React application:
    open your terminal and run
 ---- npx create-react-app my-react-app ----
 3. Navigate to the project directory ;
 ---- cd my-react-app ----
 4. Start the Development Server;
 ---- npm start ----
 5. Explore the React App:
    Open your code editor and explore the src folder. The main component is usually in src/index.js. Modify this file to make changes to your React app.
    // src/index.js
    import React from 'react';
    import ReactDOM from 'react-dom';
    import App from './App'; // App is your main component

    ReactDOM.render(
    <React.StrictMode>
        <App />
    </React.StrictMode>,
    document.getElementById('root')
    );
 6. Building and Deploying:
 ---- npm run build ----



# Learning React

## Introduction to React
    React is a free and open-source front-end JavaScript library  
    for building user interfaces based on UI components.  
    It is maintained by Meta and a community of individual developers and companies.  

    React is used to build single page applications, these are the applications that  
    reload only once, and changes pages doesn't reload the pages.  

    React Js is based on UI components, entire web application is broken down  
    into multiple web UI components used in React Js, same components can be  
    re-used.

## Installation
    Node js => It's a javascript runtime which helps us to run javascript on our local machine  
    we don't require any browser to javascript if we have Node js installed.  
      
    VS code => Source code editor, used to write and run code quickly.  
      
    npm => Once we install Node js, by default npm is also installed, it helps us to  
    download packages in Node js.   
      
    React Dev Tools => It's a chrome extension, it helps in seeing the react components etc  
    on the browser during run time.  
      
    Thunder Client => Alternative of Postman, it's a VS code extension.  
      
    ES7 React/Redux/GraphQL/React-Native-Snippets => provides shorcuts on many statements, It's a  
    VS code extension.  
      
    Bracket Pair Colorizer => Colorizes the brackets to tell us where they ends, It's VS code extension.  
      
    Auto Rename Tag => It's used to rename the tags once the pairing tag name is changed,  
    It's a VS code extension.  
      
    Live Server => We can visualize a static page by selecting on Go Live, It's a VS code extension.  
      
    Prettier => Code formatter, It's a VS code extension.  
      
## Starting with React 
    create-react-app is a package which gives us the basic folder structure, to build a react app  
    it can be downloaded using the node package manager npm.  
      
    To install the package we use the command  
    npm install create-react-app  [ to do it locally ]  
    npm install -g create-react-app [ to do it globally { which can be used later in other projects }]  
      
    npm VS npx  
      
    If the package in question is to be used only once or twice and not every  
    time the project runs, it is better to use NPX because it would execute  
    the package directly, without installing it. NPM is used to install packages,  
    and we should do this in case of dependencies or packages which  
    are crucial to our project.  
      
    Is react a library of framework ?  
      
    React is technally a javascript library, but it competes directly with Angular and Vue JS frameworks  
    that's why some people also refer react as a framework.  
      
    React follows a component based architecture :  
    We build components in react for the web page and values in those components are sent via props  
    these components can be reused in other projects making the software re-usable.  
      
    NOTE:  
    if we want all the react app folders to be in the pwd:  
    npx install create-react-app .  
    if we want all the react app folders to be in some named folder [ ie: my-app ]:    
    npx install create-react-app my-app  
    NAMING CONVENTION FOR PARENT FOLDER SHOULD BE FOLLOWED  
      
## Folder Structure  
    1] node_modules : This folder contains the modules / packages that are required for our react app,  
    whichever package we install using npm, is installed in this node_modules folder.  
    2] .gitignore : This file contains the folders / files that we don't want to push to github.  
    3] package-lock.json & package.json : These files contains the dependencies or versions of the packages,  
    used in our react app, IF WE WANT TO REBUILD THE NODE MODULES WE ONLY NEED THESE 2 FILES.  
    4] Read.md : Basic react project readme.  
    5] src : Our react app components are placed in src folder, each components will be supplied with props,  
    and they will have their states.  
    Understanding props and state in short:  
    props : If we build a basic form which is unfilled, so props are the fillers in that form, and the form is  
    the component.  
    App.js is a component, and index.js is an entry point,  
    index.js says to render the App component and take the content to  
    the root.  
    state : The current set of props for that form is called state of that form or component, if any of the prop  
    changes in the component / form, then the state of the component / form is said to be changed.  
    6] public : It has the main file for the react app that is the index.html, it contains basic html and files  
    linkages required for the react app, it has a div element with id = root, with the help of javascript this  
    div is populated in the main react app / page, bootstrap linking can be done in this file.  
      
    Note: To build the react app for production, we use the command  
    npm run build  
    gives the optimized version of our web-site.  
      
    Note: In react components can be function based or class based components.  
    Earlier, create-react-app used to use class based components.  
      
    






# ⚡ Universal JS, HMR and SSR ⚡

### Setup
`npm install`

For Development (HMR)

`npm run dev`

For Production (SSR)

`npm run build && npm run prod`


### What is it?

*Universal JS: -*
JavaScript that can run on both the server and client (or any other JS platform for that matter) !

*Hot Module Reloading: -*
Replaces modules that have been changed in real time while preserving the state.

*Server Side Rendering: -*
Renders Pages on the initial for fast page loads and search engine optimization

### Why?

Incredibly Productive

Extremely Flexible

Blazing Fast

... And its just plain cool 😎

### How?

The Basic setup goes like this...

An express server handles requests, renders the webpage and handles all file requests.

Webpack is used to bundle everything up, listen for files changes and hot reload them into the client.

React Router is used match the requested url and is then rendered with the redux store on the server using the `react-dom-stream` `renderToStaticMarkup` method.

We will be using React, Redux and React Router to match url requests, and render the state to html that we can then send back to the client.
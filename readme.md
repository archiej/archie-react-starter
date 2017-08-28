#archie-react-starter

<ol>
    <li><a href="#description">Description</a></li>
    <li><a href="#purpose">Getting Started</a></li>
    <li><a href="#stack">Stack</a></li>
    <li><a href="#additionalinfo">Additional Information</a></li>
</ol>

<h2 id="description">Description</h2>
For when I don't want to use create-react-app, JSBin or the like. This is a simple starter project for quickly getting me up and running to write react code. Nothing fancy, feel free to use.  


<h2 id="gettingstarted">Getting Started</h2>
Here's how you get started:

<h4>Requirements</h4>
Make sure you have node + npm installed. Preferably, use node v8 and above, since that is the version used to write this starter.

<h4>Step 1: Get the Repository</h4>

<code>git clone git@github.com:archiej/archie-react-starter.git</code>



<blockquote>
<h4>For Windows users</h4>

You may also need to install some packages globally:
<code>npm i -g nodemon webpack-dev-server</code>

Change the dev script in package.json to:
<code>nodemon --exec babel-node lib/server.js</code>

Remove pm2 from dependencies in  package.json, and add:
<code>"nodemon":"*"</code>
<hr>
</blockquote>

<h4>Step 2: Install Dependences</h4>
<code>npm i</code>

<h4>Step 3: Start the pm2 server to start the view engine and serve the endpoint</h4>
<code>yarn dev</code>
<h4>Step 4: Start the build and watch for the client-side and start developing</h4>
<code>yarn webpack</code>

Goto to <code>localhost:8080</code> in chrome

<h2 id="stack">Stack</h2>
This starter includes the following (among other smaller dependencies):

<ul>
    <li><strong>React</strong> - Awesome framework for building scalable, fast web apps</li>
    <li><strong>Redux</strong> - Redux is a predictable state container for JavaScript apps</li>
    <li><strong>Webpack</strong> - Module bundler that basically replaces Grunt and Gulp</li>
    <li><strong>pm2</strong> - Advanced, performant, production process manager for Node.js</li>
    <li><strong>Express</strong> - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications</li>
    <li><strong>Yarn</strong> - Yarn caches every package it downloads so it never needs to download it again.</li>
</ul>


<h2 id="additionalinfo">Additional Information</h2>

For better debugging, install Redux DevTools for Chrome here:
https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en

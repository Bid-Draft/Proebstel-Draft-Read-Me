<h1>Proebstel-Draft Application</h1>
<p>Proebstel-Draft is a web application built using Ruby on Rails and React. This README provides instructions on how to set up and run the application.</p>

<h2>Prerequisites</h2>
<p>Before you begin, ensure you have met the following requirements:</p>
<ul>
  <li>You have installed <a href="https://www.ruby-lang.org/en/documentation/installation/">Ruby</a> 3.2.2</li>
  <li>You have installed <a href="https://nodejs.org/en/download/">Node.js</a> 19.x</li>
  <li>You have installed <a href="https://www.npmjs.com/get-npm">npm</a> 9.x</li>
  <li>You have installed <a href="https://www.postgresql.org/download/">PostgreSQL</a></li>
</ul>

<h2>Installation Instructions</h2>

<h3>Node.js & React Setup</h3>
<ol>
  <li>Clone this repository to your local machine.
      Replace "username" with your GitHub username.
      <pre><code>git clone https://github.com/username/bid-draft.git</code></pre>
  </li>
  <li>Navigate into the directory of the cloned repository.
      <pre><code>cd bid-draft</code></pre>
  </li>
  <li>Install the dependencies for the project.
      <pre><code>npm install</code></pre>
  </li>
</ol>

<h3>Ruby on Rails Setup</h3>
<ol>
  <li>Ensure you are in the root directory of the cloned repository.</li>
  <li>Install the Rails gem.
      <pre><code>gem install rails</code></pre>
  </li>
  <li>Install the project's dependencies.
      <pre><code>bundle install</code></pre>
  </li>
</ol>

<h3>Database Setup</h3>
<ol>
  <li>Make sure PostgreSQL is running on your machine.</li>
  <li>Set up the database.
      <pre><code>rake db:create db:migrate</code></pre>
  </li>
</ol>

<h2>Usage</h2>

<h3>Starting the Application</h3>
<ol>
  <li>Start the Node.js/React part of the application.
      <pre><code>npm start</code></pre>
  </li>
  <li>In a new terminal window, start the Rails server.
      <pre><code>rails server</code></pre>
  </li>
</ol>
<p>Open your browser and visit <a href="http://localhost:3000">http://localhost:3000</a>.</p>

<h3>Building the Application</h3>
<p>To create a production-ready build of the application, run the build command. This will create a <code>build</code> directory with the compiled assets.</p>
<pre><code>npm run build</code></pre>

<h3>Using the Application Solo</h3>
<p> If you are someone who is about to hire me the best way to use this web app solo is to go too www.proebsteldraft.com and create a game. This will take you to a lobby, copying the url and pasting it into an incognito window will allow one to see the full functionality.

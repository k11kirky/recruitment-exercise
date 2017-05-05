<h1>Lavanda Recruitment Exercise</h1>
<h3>Welcome!</h3>
  <p>
    ...to Lavanda's Offline Recruitment Exercise. This is meant to be a relaxed and enjoyable exercise that will allow you to show us your skills. We don't expect you to spend hours on this, but you are welcome to take as long as you like. 

<h3>Instructions</h3> 
  <h4>Initial Setup</h4>
  <ol>
  <li>fork this repo</li>
  <li>Install Ionic: <code>$ npm install -g ionic</code>
  <li>Clone your fork locally and <code>$ cd</code> in</li>
  <li><code>$ npm install</code></li>
  <li><code>$ ionic serve</code>
  </ol>
  <p>You should now be up and running with ionic running on localhost:8100 and browser syncing etc running. </p>
  <p>
    While this exercise uses a skeleton Ionic app (Ionic 3 on Angular 4 and Typescript), this is not a test of your Ionic knowledge and you don't need to know anything about Ionic to start working on this project. If you are completely new to Ionic and Typescript you will find the <a href="http://ionicframework.com/docs/v2">Ionic docs</a> provide useful background. 
    </p>
    <h3>The Rules</h3>
    <p>
    The rules are simple: we would like you to build out a simple dashboard page within this app skeleton which consumes data from an API endpoint we provide and renders it using C3 charts. The view should be manipulable by a simple pair of date selectors. That's it! There are two charts to build. 
  </p>
 <img src="https://github.com/lavanda-uk/recruitment-exercise/blob/master/src/assets/dashboard-design.png" />
  <p>
    To help get you started we have created an empty dashboard page and wired up the app so it can be loaded from the menu. 
  </p>
  <p>Please, use https://test-calendar.herokuapp.com/ to fetch calendar data that you can use to populate the dashboard view.</p>
<p>
Example request:</p>
<code>
HTTP GET https://test-calendar.herokuapp.com/?from=2017-08-01&to=2017-08-31
</code>
<p>In the response example, you can find booked and unavailable dates. Booked dates will have source (platform from where the booking came from originally) and gbp_price (indicating the amount that was charged for the stay) fields.</p>
    <p>
    You can readup on C3 charts here: <a href="http://c3js.org/">C3 charts</a>. The C3 dependency is already installed in the project. You may wish to <a href="http://leaveyourcave.com/how-to-integrate-ionic-2-with-c3-js/" target="_blank">read this article</a> to understand how the C3 is set up within Ionic, but we have done all this setup for you already, so as not to waste your time. 
  </p>
  <p>
    While not essential and definitely not the only way to do it, you can feel free to make use of any Ionic components which are all available to you out of the box. The <a href="http://ionicframework.com/docs/v2">Ionic docs</a> will show you the way.
  </p>

  <h3>Submitting Your App</h3>
  <p>When you are happy with your code, please commit the result to your forked github repo and send us the link!</p>

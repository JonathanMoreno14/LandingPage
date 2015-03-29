# LandingPage

Created this Landing Page using Bootstrap. The web page consist of a background image, courtesy of Public Domain Images. The call to action is a transparent panel with a button and email subscription. Fonts, courtesy of Google Fonts. 

## Install

Add this links to your head tag within your html document
```
<link href="css/style.css" rel="stylesheet">
<link href='http://fonts.googleapis.com/css?family=Cabin+Condensed|Pacifico' rel='stylesheet' type='text/css'>
```
Add this code to your body of your html document
```
  <div class="landing-page">
      <div class="container">
        <div class="row">
          <div class=".col-md-6 panel panel-default">
            <h1>Welcome to the Landing page</h1>

            <p>Subscribe to our newsletter and recieve the latest news and updates.</p>

            <p>Find more information on our services and what we can do for you.</p>

            <form action="">
            <div class="input-group input-group-lg">
              <span class="input-group-addon" id="sizing-addon1"><span class="glyphicon glyphicon-envelope" aria-hidden="true"></span></span>
              <input type="text" class="form-control" placeholder="Email" aria-describedby="sizing-addon1">
            </div>

            <p><span class="help-block"><smal>We do not spam. Unsubsribe anytime.</small></span></p>

              <a href="#"><button type="button" class="btn btn-primary btn-lg">Sign Up</button></a>
            </form>
            <p class="lower-p">User License under <a href="license.html" target="_blank">The MIT License (MIT)</a>.</p>
        </div>
      </div> <!-- Row -->
    </div> <!-- Container -->
</div><!-- Landing Page Div -->

```

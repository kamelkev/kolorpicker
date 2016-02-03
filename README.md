Kolorpicker is a simple jQuery based component to display a color picker and palette selector upon selection of an html input text field.

This particular color picker offers a tile based method of selecting colors, which separates it from the many photoshop-style color pickers currently available.
How to Implement

1. Include jquery within your HEAD block
2. Include kolorpicker within your HEAD block
3. Add class "kolorPicker" to your input field 

### Screenshot and Demo ###

![kolorpicker](http://kamelkev.github.io/kolorpicker/images/picker.jpg)

[Demo here](http://kamelkev.github.io/kolorpicker/)

### Full Example ###

    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
      <html>
        <head>
          <title>jQuery kolorPicker </title>
          <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js" type="text/javascript"></script>
          <script src="jquery.kolorpicker.js" type="text/javascript"></script>
          <link rel="stylesheet" href="style/kolorpicker.css" type="text/css" media="screen, tv, projection, print" />
        </head>

        <body>
          <h1>jQuery kolorPicker Demo</h1>
          <p>Just click into the field to start picking a color</p>
          <br />
          <div class="labs-demo clearfix">
            <h3>Demo</h3>
            <form>
              <input type="text" value="#FFFFFF" class="kolorPicker">
            </form>
          </div>
        </body>
      </html>

### Credits ###

- Kevin Kamel
- Chelsea Rio
- Evan Levent 

### Sponsorship ###

This code has been developed under sponsorship of MailerMailer LLC.

### Copyright ###

© 2001–2016 MailerMailer LLC. All Rights Reserved.

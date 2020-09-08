---
permalink: /contact/
title: "Contact Us"
---
<head>
  <meta charset="utf-8">
  <title>forms</title>
  </head>
<body>
  <form class="gform" name="gform" target="hidden_iframe" onsubmit="submitted=true;"
        action="https://docs.google.com/forms/d/e/1FAIpQLSeVfhAKWSZ12j7pDg9sLRwjq5Zrq1s88mR8alNr6Tg4Y_o_gg/formResponse?">
    <label for="entry.2005620554">Name</label><br>
    <input type="text" name="entry.2005620554" id="entry.2005620554"><br>
    <label for="entry.1045781291">Email</label><br>
    <input type="text" name="entry.1045781291" id="entry.1045781291"><br>
    <label for="entry.839337160">Comments</label><br>
    <textarea name="entry.839337160" id="entry.839337160" rows="8"
              cols="50"></textarea><br>
    <input type="submit" name="" value="submit"?
           </form>
          <iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted){}"></iframe>
  <script
  src="http://code.jquery.com/jquery-3.5.1.min.js"
  integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
  crossorigin="anonymous"></script>
    <script type="text/javascript">
      var submitted = false;
    </script>
        <script type="text/javascript">
          $('#gform').on('submit', function(e)){
          $('#gform *').fadeOut(2000);
          $('#gform').prepend('Your Submission has been sent. We will get back to you as soon as possible');
          });
    </script>
    </body>

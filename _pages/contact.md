---
permalink: /contact/
title: "Contact Us"
---
<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSeVfhAKWSZ12j7pDg9sLRwjq5Zrq1s88mR8alNr6Tg4Y_o_gg/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  First name:<br>
  <input type="text" name="entry.2005620554" id="entry.2005620554"><br>
  Email:<br>
  <input type="text" name="entry.1045781291" id="entry.1045781291">
  Comments:<br>
   <input type="text" name="entry.839337160" id="entry.839337160"><br>
   <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>   

---
permalink: /contact/
title: "Contact Us"
---
   <form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/mentoringsuperhighway@gmail.com" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Enter Message Here" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
   
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

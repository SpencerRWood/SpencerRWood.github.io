---
layout: page
title: Contact
permalink: /contact/
---

### Contact me

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
	<input type="hidden" name="_subject" value="Website contact" />
	<br> <br>
    <textarea style="width:300px; height:150px;" name="message" placeholder="Your message"></textarea>
	<input type="text" name="_gotcha" style="display:none" />
	<br>
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'Spencer.R.Wood' + '@' + 'gmail' + '.' + 'com');
</script>


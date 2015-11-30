---
layout: page
title: Contact
permalink: /contact/
---

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
	<input type="hidden" name="_subject" value="Website contact" />
	<br> <br>
    <textarea name="message" placeholder="Your message"></textarea>
	<input type="text" name="_gotcha" style="display:none" />
	<br>
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'Spencer.R.Wood' + '@' + 'gmail' + '.' + 'com');
</script>

Some information about you!

### More Information

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)
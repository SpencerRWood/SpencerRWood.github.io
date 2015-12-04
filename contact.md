---
layout: page
title: Contact me
permalink: /contact/
---


Fill out the text boxes below if you would like to get in touch with me or if you have any questions! I will get back to you as soon as I can! 

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name" style="width:300px;">
	<br> <br>
    <input type="email" name="_replyto" placeholder="Your email" style="width:300px;">
	<input type="hidden" name="_subject" value="Website contact" />
	<br> <br>
    <textarea style="width:300px; height:150px;" name="message" placeholder="Your message"></textarea>
	<input type="text" name="_gotcha" style="display:none" />
	<br>
    <input type="submit" value="Send">
	<input type="hidden" name="_next" value="//www.spence.io/thanks" />
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'Spencer.R.Wood' + '@' + 'gmail' + '.' + 'com');
</script>


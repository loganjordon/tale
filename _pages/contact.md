---
layout: post
title: "Contact"
permalink: /contact
---

<form action="https://getsimpleform.com/messages?form_api_token=e7e8d755eef01729692b3f4035b20e0e" method="post">
	<input type='hidden' name='redirect_to' value="https://www.loganjordon.com/success" />
	<!-- <input type='hidden' name='redirect_to' value="http://localhost:4000/success" /> -->
	
From:
	<input class="email" type='email' name='email' autocomplete="off" placeholder="Email" required/>
	<br>
	<br>
Message:
	<textarea name="message" placeholder="Comment, concern, prayer request..." required></textarea>
	<br>
	Do you want me to reply back to you?
	<input type="radio" id="reply_back_yes" name="reply_back" value="yes">
	<label for="reply_back_yes">Yes</label>
	<input type="radio" id="reply_back_no" name="reply_back" value="no" checked>
	<label for="reply_back_no">No</label>
	<br><br>
	<input type='submit' value='Submit' />
</form>
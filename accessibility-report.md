<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contact Me</title>
</head>

<body>

<h1>Contact Me</h1>

<form>

<fieldset>
<legend>Personal Information</legend>

<label for="name">Full Name</label>
<input type="text" id="name" placeholder="Enter your full name" required>

<br><br>

<label for="email">Email</label>
<input type="email" id="email" placeholder="Enter your email" required>

<br><br>

<label for="phone">Phone</label>
<input type="tel" id="phone" placeholder="Enter phone number">

</fieldset>

<br>

<fieldset>
<legend>Message Details</legend>

<label for="subject">Subject</label>
<select id="subject">
<option>General Inquiry</option>
<option>Project Collaboration</option>
<option>Feedback</option>
</select>

<br><br>

<label for="message">Message</label>
<textarea id="message" minlength="50" required placeholder="Write your message"></textarea>

<br><br>

<label>
<input type="checkbox">
Subscribe to newsletter
</label>

</fieldset>

<br>

<button type="submit">Submit</button>

</form>

</body>
</html>

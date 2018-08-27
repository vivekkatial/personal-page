---
title: Contact
description: If you ever want to contact me, feel free to hit me up on any of my handles otherwise feel free to fill out the form below.
type: page
featured_image: "/images/space-bg.jpeg"
menu:
  main: {}

---


Social media links are in the header otherwise fill out the form below. I have used netlifys form service to make the form so they will ask you to confirm your email.

<form name="contact" method="POST" netlify>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <div data-netlify-recaptcha></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

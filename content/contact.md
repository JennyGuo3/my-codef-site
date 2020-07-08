---
title: "Contact"
date: 2020-07-08T14:24:47+01:00
menu: "main"
draft: false
weight: 7
---

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
  	  <label>Your Number <input type="Number" name="Number" /></label>
  </p>
  <p>
    <label>Your Role: <select name="Occupation[]" multiple>
      <option value="Full-time student">Full-time student</option>
      <option value="Graduate">Graduate</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

 ![Contact](/Contact.jpg)


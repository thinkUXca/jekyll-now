---
layout: page
title: Contact
permalink: /contact/
---
Want to say hi? Send us an email using the form below, and we'll get back to you as soon as possible!

<div class="container">
  <form action="https://formspree.io/info@thinkux.ca" method="POST">
    <div class="form-group row">
      <label for="name">Name</label>
      <input type="text" class="form-control" name="name" required>
    </div>
    <div class="form-group row">
      <label for="_replyto">Email</label>
      <input type="email" class="form-control" name="_replyto" required>
    </div>
    <div class="form-group row">
      <label for="_subject" class="col-sm-2 col-form-label col-form-label-lg">Subject</label>
      <div class="col-sm-10">
        <input type="text" class="form-control" name="_subject" required>
      </div>
    </div>
    <div class="form-group">
      <label for="_message">Message</label>
      <textarea name="_message" class="form-control"></textarea>
     </div>
    <div class="form-group">
      <input type="submit" class="btn btn-lg" value="Send">
    </div>
  </form>
</div>

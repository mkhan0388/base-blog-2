---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

<form>
  <div class="row">
  <div class="col">
    <input class="form-control" type="text" placeholder="First Name" id="first" required>
    <label for="first">First Name</label>
    <input class="form-control" type="text" placeholder="Last Name" id="last" required>
    <label for="last">Last Name</label></div>
    <div class="col">
    <input class="form-control" type="email" placeholder="email" id="email" required>
    <label for="email">Email</label>
    <input class="form-control" type="number" placeholder="age" id="age">
    <label for="age">Age</label></div>
    <div class="col">
    <input class="form-control" type="text" placeholder="Message" id="message" required>
    <label for="message">Message</label></div>
    </div>
    <button>Submit</button>
    </form>

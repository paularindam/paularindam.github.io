---
layout: default
title: Arindam Paul
---

<div id="contact">

  <h1 class="pageTitle">Contact Me</h1>
<p class="intro">To get in touch with me, please fill out the form or drop by my office or follow me on social media by clicking the icons below</p>
  <div class="contactContent">

    <p> <font color="purple"><b>
    Department of EECS<br>
      Northwestern University<br>
      LG65 <br>
    2145 Sheridan Road<br>
    Evanston, Illinois 60208</b>
  </font></p>
    <img src="{{ '/assets/img/contact.jpg' | prepend: site.baseurl }}" alt="" height="280" weight ="280">
  </div>
  <form action="http://formspree.io/your@mail.com" method="POST">


    <label for="name">Name</label>    
    <input type="text" id="name" name="name" class="full-width"><br>
    <label for="email">Email Address</label>
    <input type="email" id="email" name="_replyto" class="full-width"><br>
    <label for="message">Message</label>
    <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Send" class="button">
  </form>
</div>

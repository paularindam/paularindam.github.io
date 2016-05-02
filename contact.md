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
      <a href="http://www.mccormick.northwestern.edu/contact/tech-room-finder-map.php?id=LG65&room-floor=0&room-id=854&room-ingress="><font color="purple">LG65</font></a> <br>
    <a href ="https://maps.northwestern.edu/facility/132"><font color="purple">2145 Sheridan Road</font></a><br>
    Evanston, Illinois 60208</b>
  </font></p>
    <img src="{{ '/assets/img/contact.jpg' | prepend: site.baseurl }}" alt="" height="280" weight ="280">
  </div>
  <form action="MAILTO:arindam.paul@eecs.northwestern.edu" method="POST" enctype="text/plain">


    <label for="name">Name</label>    
    <input type="text" id="name" name="Name of the Sender" class="full-width"><br>
    <label for="email">Email Address</label>
    <input type="email" id="email" name="replyto" class="full-width"><br>
    <label for="message">Message</label>
    <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Send" class="button">
  </form>
</div>

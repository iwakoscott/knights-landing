---
title: Contact Us
date: 2018-02-08 11:26:00 -08:00
position: 6
addToNavBar: true
layout: simple
---

<form action="https://formspree.io/{{site.email}}" method="POST">
  <input type="hidden" name="_format" value="plain" />
  <input class="form-control mb-1 mt-1" type="text" name="name" placeholder="name" required="true"/>
  <input class="form-control mb-1 mt-1" type="email" name="_replyto" placeholder="email"  required="true"/>
  <textarea class="form-control mb-1 mt-1" name="message" rows="7" placeholder="your message" required="true"></textarea>
  <input type="text" name="_gotcha" style="display: none;" />
  <input type="hidden" name="_next" value="{{page.url}}" />
  <button class="btn btn-success btn-lg mt-3 send-button float-right" type="submit"><i class="fa fa-chevron-circle-right fa-lg m-1"></i> Send</button>
</form>

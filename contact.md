---
layout: default
title: 联系我们
---

<div id="contact">
  <h1 class="pageTitle">联系我们</h1>
  <div class="contactContent">
    <!-- <p class="intro">This is an example Contact page. If you want to make changes then do so in the <code>contact.html</code> file.</p>
    <p>The form is provided by <a href="http://formspree.io/">Formspree.</a> Follow the directions on their site to set up the form for use.</p>
    <p>If you have questions about the theme feel free to <a href="mailto:wolfwifee@gmail.com">email me</a> or create an issue on <a href="https://github.com/brianmaierjr/long-haul">GitHub</a>. Enjoy!</p> -->
    <form target="_blank" action="{{ site.social.email | prepend:"https://formspree.io/" }}" method="POST" class="contact">
      <label for="name">您的名字</label>    
      <input type="text" id="name" name="name" class="full-width"><br>
      <label for="email">您的邮箱</label>
      <input type="email" id="email" name="_replyto" class="full-width"><br>
      <label for="message">告诉我们</label>
      <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
      <input type="submit" value="发送" class="button">
    </form>
  </div>

</div>

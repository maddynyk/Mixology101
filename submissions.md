---
layout: default
title: Submissions
permalink: /submissions/
---
  
  <div class="container_contact">
  <h3 class="form_title"> Send us your submissions!</h3>

  <form action="https://formspree.io/{{site.email}}" method="post" class="form">
    <div class="message js-form-message"></div>
    <div class="form_group">
        <textarea name="text" placeholder="Drink name" cols="25" rows="6" class="form-textarea" required></textarea>
    </div>
     <div class="form_group">
        <textarea name="Ingredients" placeholder="Ingredients" cols="25" rows="6" class="form-textarea" required></textarea>
    </div>
    <div class="form_group">
        <textarea name="Recipe" placeholder="Recipe" cols="25" rows="6" class="form-textarea" required></textarea>
    </div>
    <div class="form_group">
        <input type="submit" class="form_btn" value="Send">
    </div>
  </form>
  </div>
</section>

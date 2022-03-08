---
title: tEdör aka Krisztián Hofstädter
layout: default
---

Hello! I am a creative technologist working as a researcher, lecturer, freelancer and artist also known as tEdör. I am a Hungarian, living in England. This website can inform you about my work.

<br>

<div class="tab">
Organise projects 
  
  <button class="tablinks" onclick="openCity(event, 'categories')">thematically</button>
  or 
  <button class="tablinks" onclick="openCity(event, 'time')" id="defaultOpen" >chronologically</button> 
  :
  
  <!--
  or 
  <button class="tablinks" onclick="openCity(event, 'tags')">by tags</button>
  -->
  
</div>

<div id="time" class="tabcontent">
  <h3>ongoing</h3>
  {% include index-cron-ongoing.html %}
  <h3>past</h3>
  {% include index-cron.html %}
</div>

<div id="categories" class="tabcontent">
  {% include index-cat.html %}
</div>
<br>
My cv is [here](https://khofstadter.com/assets/doc/KHofstader-CV.pdf).
<br><br>
You can contact me on kris[at]khofstadter[dot]com
<br><br>
![Krisztián drinking tea](assets/img/khofstadter_by_balazs_kiss.jpg)<br> _photo by Balázs Kiss_

<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>

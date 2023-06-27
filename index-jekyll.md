---
title: tEdör aka Krisztián Hofstädter
layout: default
---

Hey there! I’m tEdör, a Hungarian interdisciplinary researcher living in England. This website shares my progress in learning science to produce art.

While my main focus is on using sound to induce and maintain altered states of consciousness (ASC), I am also interested in developing my personal knowledge management skills with the Zettlekasten method and keeping my family healthy with exercise and food.

Subscribe to my mailing list below to hear more about my progress.

<br> 

## Now
- Developing each chapter of my [PhD thesis](https://www.researchgate.net/publication/368365376_Developing_Brain-Computer_Music_Interfaces_for_Meditation) into research papers for relevant journals as an independent researcher.
- Working on Prof Mariana López's [Enhancing Audio Description II](https://enhancingaudiodescription.com/) project as a postdoc at the University of York.
- Preparing a new syllabus for the [Navigating the Digital World](https://github.com/khofstadter/CS220AU) module as part-time lecturer at the University of Essex and running audio recording and editing workshops. 
- Developing a personalized zettlekasten method in Visual Studio Code using [Foam](https://foambubble.github.io/foam/) while considering the analogue method of Niklas Luhman (and Scott Scheper). 
- Redesigning this website so that it can not only archive my past work but also serve as a vehicle for disseminating new ideas.


<br> 

## Some Past Works
- Music on [Bandcamp](https://tedor.bandcamp.com/)
- Videos on [YouTube](https://www.youtube.com/@krishofstadter/)
- CV in [this PDF](assets/doc/Hofstadter-cv-2023.pdf)

<br> 

## Subscribe
<!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup">
    <form action="https://khofstadter.us8.list-manage.com/subscribe/post?u=29dd7973145c920986a862a12&amp;id=ff84fd9c1a&amp;v_id=3371&amp;f_id=003078e0f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_self">
        <div id="mc_embed_signup_scroll">
        <p>All fields required.</p>
<div class="mc-field-group">
	<label for="mce-FNAME">First Name</label>
	<input type="text" value="" name="FNAME" class="required" id="mce-FNAME" required>
	<span id="mce-FNAME-HELPERTEXT" class="helper_text"></span>
</div>
<div class="mc-field-group">
	<label for="mce-LNAME">Last Name</label>
	<input type="text" value="" name="LNAME" class="required" id="mce-LNAME" required>
	<span id="mce-LNAME-HELPERTEXT" class="helper_text"></span>
</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" required>
	<span id="mce-EMAIL-HELPERTEXT" class="helper_text"></span>
</div>
<br>
<div id="mergeRow-gdpr" class="mergeRow gdpr-mergeRow content__gdprBlock mc-field-group">
		<label class="checkbox subfield" for="gdpr_42739"><input type="checkbox" id="gdpr_42739" name="gdpr[42739]" value="Y" class="av-checkbox gdpr"><span> Your data is <a href="https://mailchimp.com/legal/terms" target="_blank">safe</a> and you can unsubscribe at any time. I will send one succinct email per week. No more. To subcribe, tick the box and press the button below.</span></label>
</div>
	<div id="mce-responses" class="clear foot">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_29dd7973145c920986a862a12_ff84fd9c1a" tabindex="-1" value=""></div>
        <div class="optionalParent">
            <div class="clear foot">
                <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
            </div>
        </div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->

<br>

<div id="quote"></div>


<script>
  const quotes = {{ site.data.quotes | jsonify }};
  const quote = quotes[Math.floor(Math.random() * quotes.length)];
  document.getElementById("quote").innerHTML =
    `<blockquote><p>${quote.quote}  ~${quote.author} (${quote.year})</blockquote>`;
</script>

<script>
        function contrast() {
            var element = document.body;
            element.classList.toggle("light-mode");
        }
    </script>

---
title: tEdör aka Krisztián Hofstädter
layout: default
---

Hi! I'm tEdör, a Hungarian living in England. I'm a researcher, lecturer, freelancer, and artist interested in interdisciplinary work.

I am remaking the old website, the main things are listed below: 

## now
- contextualizing [PhD thesis](https://www.researchgate.net/publication/368365376_Developing_Brain-Computer_Music_Interfaces_for_Meditation) for research papers 
- [Enhancing Audio Description II](https://enhancingaudiodescription.com/) (postdoc @ University of York)
- preparing a new syllabus for the [Navigating the Digital World](https://github.com/khofstadter/CS220AU) module (part-time lecturing @ University of Essex)
- developing a personalised Zettlekasten method in Visual Studio Code using [Foam](https://foambubble.github.io/foam/)


## past
- music on [Bandcamp](https://tedor.bandcamp.com/)
- videos on [YouTube](https://www.youtube.com/@krishofstadter/videos)
- CV [here](assets/doc/Hofstadter-cv-2023.pdf)

You can contact me on kris[at]khofstadter[dot]com

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
            element.classList.toggle("dark-mode");
        }
    </script>



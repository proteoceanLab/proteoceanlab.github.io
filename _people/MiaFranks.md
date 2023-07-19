---
name: Mia Franks
category: people
position: "PhD Student, Ocean Sciences"
about: "likes cooking, naps, spending time with friends"
twitter: 
linkedin: 'www.linkedin.com/in/mia-franks-5abb48276'
github:
email: 'mgfranks@usc.edu'
stackedoverflow: 
image: 'people/MiaFranks.png'
genericimage: 'people/genericperson.png'
link: 'people/MiaFranks.html'
layout: menu-page
---
<!-- No need to change anything here -->
{% capture post_url %}{{ relativebase }}{{ page.url }}{% endcapture %}
{% assign post_url = post_url | replace: "//", "/" %}

<div class="small-wrapper">
  <div class="about-container">
    <section class="about-header">
      <div class="author-image-container">
        <a href='{{ post_url}} '><img src='{{ relativebase }}/assets/img/{{ page.image }}'></a>
      </div>


<h3> {{page.name}}</h3>
<h4> {{page.position}} </h4>

<section class="about-body">
          <ul class="contact-list">
          {% if page.twitter %}
            <li class="twitter"><a class="twitter" href="https://twitter.com/{{page.twitter}}" target="_blank"><i class="fa fa-twitter"></i></a></li>
          {% endif %}
          {% if page.linkedin %}
            <li class="linkedin"><a class="linkedin" href="https://in.linkedin.com/in/{{page.linkedin}}" target="_blank"><i class="fa fa-linkedin"></i></a></li>
          {% endif %}
          {% if page.github %}
            <li class="github"><a class="github" href="https://github.com/{{page.github}}" target="_blank"><i class="fa fa-github"></i></a></li>
          {% endif %}
          {% if page.email %}
            <li class="email"><a class="email" href="mailto:{{page.email}}"><i class="fa fa-envelope-o"></i></a></li>
          {% endif %}
          {% if page.stackoverflow %}
          <li class="stackoverflow"><a class="stackoverflow" href="https://stackoverflow.com/users/{{page.stackoverflow}}" target="_blank">
            <i class="fa fa-stack-overflow" aria-hidden="true"></i></a></li>
          {% endif %}
          </ul>
          </section>

<!-- Fill in details below, as many paragraphs as you'd like -->
<p>Under Dr. Held, I plan to study nutrient co-limitation. My research prior to joining the lab has spanned paleoclimatolgy, biochemistry, and ocean technology. </p>
<p>I grew up in Tucson, Arizona in the Sonoran Desert, where I nurtured my love for nature. Some of my favorite activities are cooking and eating food (especially Korean food), listening to music, and rowing. </p>

<!-- No need to change anything here -->
</section>
</div>

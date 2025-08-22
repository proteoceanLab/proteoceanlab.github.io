---
name: Anna Warsaw
category: people
position: "PhD Student, Marine & Environmental Biology"
about: "likes taking film photos, going to concerts, and spending time outside"
twitter: 
linkedin: 'www.linkedin.com/in/anna-warsaw-88ba75202/'
github:
email: 'awarsaw@usc.edu'
stackedoverflow: 
image: 'people/AnnaWarsaw.png'
genericimage: 'people/genericperson.png'
link: 'people/AnnaWarsaw.html'
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

<p> I'm a graduate student in the Marine and Environmental Biology program. I'm fascinated by microbes' ability to thrive in dynamic environments and adapt to complex challenges, and I'm interested in studying how microbial interactions enable survival, shape ecosystems, and drive biogeochemical cycling. As an undergrad at the University of Chicago, I completed my thesis investigating diel dynamics and spatial gradients that shape green sulfur bacteria blooms. I then worked as a research technician at UC Santa Barbara studying spatial structuring and the biofilm matrix in "pink berry" environmental biofilms. </p>

<p> I grew up in Holland, Michigan, near Lake Michigan, where I spent a lot of time by the water. In my free time, I enjoy taking film photos, making pottery, going to concerts and movies, and searching for sea glass at the beach. </p>

<!-- No need to change anything here -->
</section>
</div>

create [AnnaWarsaw]

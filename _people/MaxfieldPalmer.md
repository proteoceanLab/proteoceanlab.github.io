---
name: Maxfield Palmer
category: people
position: "PhD Student, Marine & Environmental Biology"
about: "loves the outdoors, cooking large meals for friends, and finding new songs to sing in the car"
twitter: 
linkedin: 'https://www.linkedin.com/in/maxfield-palmer-1603561a8/'
github:
email: 'maxapalm@usc.edu'
stackedoverflow: 
image: 'people/MaxfieldPalmer.png'
genericimage: 'people/genericperson.png'
link: ''
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
<p> In Dr. Held's lab, my goal is to help determine if there is a phenotype to colimitation and which mechanisms are shared across organisms when they are colimitted. I have a background in biological oceanography, microbiology, and biogeochemistry.</p>
<p> I grew up on the Oregon coast, so loving everything related to the ocean comes naturally. Outside of science, I love to spend all the time I can outdoors and can whip up a <strong>MEAN</strong> dinner at a moments notice (I <strong>LOVE</strong> to cook). </p>

<!-- No need to change anything here -->
</section>
</div>

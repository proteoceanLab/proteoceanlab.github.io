---
name: Rachael Peng
category: people
position: "PhD Student, Marine & Environmental Biology"
about: "likes playing the piano, taking walks, and all things Zelda.  "
twitter: 
linkedin: 'https://www.linkedin.com/in/rachael-lin-peng/'
github: 
email: 'rlpeng@usc.edu'
stackedoverflow: 
image: 'people/RachaelPeng.png'
genericimage: 'people/genericperson.png'
link: 'people/RachaelPeng.html'
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
<p>I am a graduate student under in the Marine and Environmental Biology program. I am fascinated by the intricate interplay between microbes and their surrounding environment— how they are affected by ever-changing geochemical fluxes and through their metabolism, inadvertently drive the elemental cycles of our world. </p>
<p>I graduated from UC Berkeley and worked under Dr. John D. Coates (UC Berkeley, Department of Plant and Microbial Biology) studying microbial iodine respiration and its relevant biochemistry. In my free time, I like to spend time lazing around my house, surveying different grocery stores, and more recently, playing Zelda: Tears of the Kingdom on Nintendo Switch.  </p>

<!-- No need to change anything here -->
</section>
</div>

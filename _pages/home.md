---
layout: homelay
excerpt: "Senses in Motion: Sensory Processing in Freely Moving Animals."
sitemap: false
permalink: /
---
<div class="col-sm-12 text-light d-none d-lg-block">
<div class="bg-image"
  style="
    background-image: url('{{ site.url }}{{ site.baseurl }}/images/jumping_mouse.jpg');
    background-size: 100%;
    background-repeat: no-repeat;
    height: 320px
  ">
<div class="titlebox">
<div class="bigtitle">
Senses in Motion: Sensory Processing in <br/>
Freely Moving Animals
</div>
OCTOBER 17 2022, SAINSBURY WELLCOME CENTRE, LONDON, UK
</div>
</div>
</div>

<div class="col-sm-12 d-lg-none">
<div class="titlebox">
<div class="bigtitle">
Senses in Motion: Sensory Processing in Freely Moving Animals
</div>
OCTOBER 17 2022, SAINSBURY WELLCOME CENTRE, LONDON, UK
</div>
<img src="{{ site.url }}{{ site.baseurl }}/images/jumping_mouse.jpg">
</div>

<div class="col-sm-9">
<br/>
<h2>Symposium themes and objectives</h2>
  <p>
Experiments in sensory physiology have traditionally relied on recordings in restrained animals to allow precise control over stimulus parameters and animal behaviour. However, in the real world, sensory perception involves continuous interaction between movements of the observer and sensory inputs. As animals move, sensory feedback resulting from their movements both presents a challenge of distinguishing between external and self-generated stimuli and provides a rich source of information about the content of the environment. Understanding how the brain processes these signals to give rise to perception and guide behaviour poses unique experimental and computational challenges. The symposium will cover experimental, theoretical, and technical work across animal species and sensory systems to address the following broad questions:
  </p>
<ul>
<li>How do sensory signals, self-motion and spatial orientation interact to enable perception and behaviour?</li>
<li>How do animals adjust their movements to optimise sensation?</li>
<li>How do sensory representations in freely moving animals relate to those recorded under head restrained and / or passive conditions?</li>
<li>How can new technologies enable neural recordings, behavioural quantification, and control over sensory stimulation in freely moving animals?</li>
</ul>

</div>

<div class="col-sm-3">
<br/>
<h2>Speakers</h2>
{% for speaker in site.data.speakers %}
{% unless speaker.break %}
<a href="{{ site.url }}{{ site.baseurl }}/speakers#{{ speaker.name }}">{{ speaker.name }}</a><br/>
{% endunless %}
{% endfor %}

<br/>
<h2>Organisers</h2>
<a href="https://www.sainsburywellcome.org/web/people/sepiedeh-keshavarzi">Sepiedeh Keshavarzi</a> and <a href="https://znamlab.org">Petr Znamenskiy</a>.
<p></p>
</div>

<div class="col-sm-12">
<h2>Registration</h2>
The symposium will take place in the auditorium at the Sainsbury Wellcome Centre. Please register as the auditorium has a capacity limit.
<p></p>
<div class="text-center">
<a class="btn btn-primary btn-lg" href="https://www.eventbrite.co.uk/e/391517879517" role="button">Click here to register</a>
</div>
<p></p>
</div>

<div class="col-sm-12">
<h2>Funding</h2>
<p>
The symposium has been made possible by generous support of
<a href="http://www.sainsburywellcome.org">the Sainsbury Wellcome Centre</a> and sponsorship from <a href="https://www.cambridgeneurotech.com/">Cambridge NeuroTech</a> and <a href="https://www.datajoint.com/">DataJoint</a>.
</p>
</div>

<div class="row justify-content-around">
  <div class="col-sm-12 text-center">
    <a href="https://www.sainsburywellcome.org/">
    <img src="{{ site.url }}{{ site.baseurl }}/images/swc_logo.svg" class="img-fluid" alt="SWC logo" width="200 px"></a>
  </div>
  <div class="col-sm-12 text-center">
    <a href="https://www.cambridgeneurotech.com/"> 
    <img src="{{ site.url }}{{ site.baseurl }}/images/CamNeuroTech-Logo.png" class="img-fluid" alt="CamNeuroTech logo" width="200 px"></a>
  </div>
</div>

<div class="col-sm-12">
<p></p>
</div>

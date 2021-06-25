---
title: Michael Breakspear
auto-header: none
icon: fa-anchor
order: 2
---
<head>
<style>
img.portrait {
  border-radius: 50%;
  width: 300px;
  border: 1px solid #ddd;
  padding: 5px;
}
.row {
  display: flex;
  justify-content: center;
}
</style>
</head>

<section>
  <div class="row">
  {% for person in site.team.people %}
	{% if person.initials == "MB" %}
	  <div class="col">
		<img class="portrait" src="{{ person.image }}" alt="">
	  </div> 
	  <div class="col">
	      <h2> {{person.name}} </h2>
              <h3> {{ person.role }} </h3>
		 {{ person.research_interest | markdownify }}
		 <ul class="icons">
		{% for network in person.social %}
		  <li><a href="{{- network.url -}}" class="{{ network.icon }} fa-2x"></a></li>
		{% endfor %}
		</ul>
	  </div> 
	{% endif %}
  {% endfor %}
  </div>
</section>

I am the group leader of the Systems Neuroscience Group with interests in computational neuroscience and translational neuroimaging. My contributions to the former focus on dynamic models of large-scale brain activity, toolbox development and the detection of nonlinear dynamics in empirical data. My work in translational imaging encompasses healthy ageing, dementia, bipolar disorder and schizophrenia, with a focus on connectomics and risk prediction.

I grew up in Sydney and studied medicine, philosophy and mathematics. I undertook early career research training in the School of Physics at the University of Sydney before moving to the School of Psychiatry at UNSW as a mid-career researcher.

I formed the Systems Neuroscience Group at UNSW in Sydney in 2004, then moved to QIMR Berghofer Medical Research Institute from 2009. I relocated to Newcastle in 2019 and established the Systems Neuroscience Group, Newcastle (SNG-Newy) with aspirations to integrate basic methods, bioinformatics and clinical translation with a unique regional Australian character. Our imaging centre is in a beautiful bushland setting on Awabakal country.

In addition to basic research training, I also completed training in psychiatry and nowadays combine my research career with clinical sessions in adult psychiatry. I have an interest in recovery-focussed treatment of mood disorders, psychosis, and addiction. In the past I have worked in Prison Mental Health and Inner City community psychiatry.

I have a passion for climate science, being rather social, and surfing.


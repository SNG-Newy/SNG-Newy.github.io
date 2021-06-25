---
title: Bryan Paton
auto-header: none
icon: fa-magic
order: 8
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
	{% if person.initials == "BP" %}
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

## Research Interests
I have a diverse background in computer engineering, philosophy and cognitive neuroscience. I am a nerd at heart and having this broad experience lets me combine all of my interests.

## Consciousness & Attention
 I am deeply interested in the brain and how perceptual experiences transition from non-conscious to conscious and what are the factors, cognitive, behavioural and neurophysiological involved. I have some experience with binocular rivalry, continuous flash suppression and related paradigms.

## Learning under conditions of uncertainty or volatility
I am also interested in learning, in general, especially models of the process where there are sources of noise and/or uncertainty and when these themselves change over time e.g. volatility. I have also been trying to develop novel paradigms to study these processes in a dyadic, social setting.

## Computational models
Finally I have in interest in how the brain works, and the methods used to study it, having a long background in EEG, MRI and many other related technologies. By combining these methods of data collection and using computational models of the behavioural and neurophysiological mechanisms involved I hope to gain more insight in these phenomena in both the healthy brain and its pathophysiology including Schizophrenia, Autism Spectrum Disorder and Dementia.

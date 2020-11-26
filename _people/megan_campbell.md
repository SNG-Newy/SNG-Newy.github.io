---
title: Megan E. J. Campbell
auto-header: none
icon: fa-pizza-slice
order: 5
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
	{% if person.initials == "MC" %}
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
My previous work focused on the overlapping sensorimotor processes underlying interpersonal interactions, within healthy adult cohorts. By using Bayesian models to explain behavioural and neural datasets I described mechanisms for the context-dependent modulation of automatic imitation responses, a feature of how humans prepare responses during interactions with others. Now my focus has shifted to applying this experience in functional neuroimaging, behavioural paradigms and computational approaches to social-emotional cognition and extending this to clinical populations. In particular, I aim to model dynamic brain networks involved in emotion in order to understand, differentiate and improve diagnosis of mood disorders. [ORCID](https://orcid.org/0000-0003-4051-1529)

## Biography
I recently took up my first postdoctoral position here in the Systems Neuroscience Group, Newcastle. This is a continuation of my slow migration south, having grown up in Far North Queensland where I completed a BPsychHons at JCU Cairns, before moving to Brisbane. There I enrolled in a Masters of Neuroscience at the Queensland Brain Institute fell head-over-heals for the field of cognitive neuroscience, and continued on to obtain my PhD in 2019 at UQ. 




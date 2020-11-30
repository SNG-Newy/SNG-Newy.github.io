---
title: Nikitas Koussis
auto-header: none
icon: fa-chess-knight
order: 6
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
	{% if person.initials == "NK" %}
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
I am very interested in the cognitive symptoms of psychosis
and more generally in the functioning and structure of the 
human brain in pathology and mental illness. 
My work focuses on approaching cognitive dysfunction in psychosis using a Bayesian approach. I hope to describe mechanisms of gain and attention within an interference framework. I utilise functional, diffusion and structural neuroimaging, as well as behavioural and cognitive paradigms, and computational approaches to cognition.

## Biography
Upon completing a Bachelor of Science at Queensland University of Technology in 2017, I worked at QIMR Berghofer Medical Research Institute as assistant to PI on the Prospective Imaging Study of Ageing; an AQIP grant and several other projects. I am currently completing a PhD at University of Newcastle under Michael Breakspear. In my spare time I write fantasy books and seem to be perpetually fixing up my house.

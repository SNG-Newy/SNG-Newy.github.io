---
title: Renate Thienel
auto-header: none
icon: fa-sun
order: 4
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
	{% if person.initials == "RT" %}
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


## Biosketch
I am a Mid-Career Researcher with a passion for improving health outcomes; I hold a PhD (Science), Postgraduate Diploma in Psychology, BSc (Hons); 
\
My research activities span across clinical, cognitive and neuroscientific aspects of health and mental health;
\
My research focuses on work with clinical and non-clinical participants and spans across methodologies such as self-report surveys, clinical and cognitive assessments, magnetic resonance imaging, pharmacological agents, transcranial direct current stimulation, electroencephalography etc.;
\
I have published 56 HERDC research publications including 29 (C1) journal articles, 5 book chapters (1 B1), 1 review (D1) and 25 conference papers, 1 white paper and several governmental reports reflecting her academic efforts and contributions, with a h-index of 17, and 156 citations* ;
\
I have over 10 years of experience working as a mentor and supervisor for domestic and international students including HDR students;
\
My career grant income is $520,853 (excluding $1,500,000 from AI positions) across category 1, category 3 and internal grants including a prestigious 4 year UoN post-doctoral fellowship;
\
Since 2019 I am the Research Manager of Michael Breakspear's Systems Neuroscience Group at HMRI's Imaging Centre where I am coordinating and am involved in the groups various research studies which includes the Newcastle site for the Australian Dementia Network (ADNeT)

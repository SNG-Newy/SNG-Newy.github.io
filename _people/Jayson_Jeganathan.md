---
title: Jayson Jeganathan
auto-header: none
icon: fa-lemon
order: 7
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
	{% if person.initials == "JJ" %}
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

## Biography
I completed his undergraduate studies and MBBS (Hons Class I) at the University of Sydney. Since 2018, he has been an RANZCP accredited psychiatry trainee. Concurrently, his research interests have included network analysis and neuroimaging in bipolar disorder. Currently, I am a PhD student in the lab, investigating emotional inference in psychosis.

## Decoding the brain basis of emotion
Is emotion really as simple as smiling when you’re happy, and frowning when you’re angry? I am investigating how the mind combines multimodal information, including seeing, hearing and feeling the outside world, the inner sensation of organs such as the heart and gut, and our previous experiences, to construct the moment-to-moment emotions that we feel. I am using state-of-the-art brain imaging, emotional analysis, and physiological measurements of our inner organs, to uncover the brain basis of emotion.

## Affective symptoms of early psychosis
In psychosis, impairments in motivation, enjoyment, and emotional facial expressiveness are the most debilitating symptoms for patients, yet we have no effective treatments for them. I aim to integrate recent advances in neuroimaging and machine learning to find out how the brain basis of emotion goes awry in early psychosis



---
title: Léonie Borne
auto-header: none
icon: fa-tree
order: 3
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
	{% if person.initials == "LB" %}
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

Having always been passionate about artificial intelligence and medical imaging, my research work has naturally focused on the development of "intelligent" tools for the study of an "intelligent" organ: the brain.

## Deep learning for the study of cortical folds
After a master's degree in artificial intelligence, I did my PhD with Prof. Jean-François Mangin at Neurospin in France.
My PhD work focused on the development of several **structural MRI analysis** pipelines for the study of cortical folds using **machine learning** algorithms, including **deep learning**. 
The tools I developed are now available in the BrainVISA toolbox ([www.brainvisa.info](www.brainvisa.info)). 

## Brain-behaviour association in dementia
Following my PhD, I started a postdoc in 2020 with Prof. Michael Breakspear in Australia, where I applied my skills to address the challenges of dementia. 
Using **advanced statistical analysis**, I have notably identified a robust association between brain atrophy and cognitive decline during the **preclinical stage of Alzheimer's disease**. 
My work is based on the databases [ADNI](http://adni.loni.usc.edu/), [AIBL](https://aibl.csiro.au/) and [PISA](https://www.qimrberghofer.edu.au/pisa/).


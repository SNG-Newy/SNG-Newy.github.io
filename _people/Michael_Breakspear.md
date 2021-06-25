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

## Public Research Articles Selection

#[Schultze-Kraft, Matthias, et al. "Exploiting the potential of three dimensional spatial wavelet analysis to explore nesting of temporal oscillations and spatial variance in simultaneous EEG-fMRI data." Progress in biophysics and molecular biology 105.1-2 (2011): 67-79.](../assets/articles/Schultze_11_threedwavelets.pdf)

#[Alghowinem, Sharifa, et al. "Multimodal depression detection: fusion analysis of paralinguistic, head pose and eye gaze behaviors." IEEE Transactions on Affective Computing 9.4 (2016): 478-490.](../assets/articles/Alghowinem_16_Multimodal.pdf)

#[Frankland, Andrew, et al. "Comparing the phenomenology of depressive episodes in bipolar I and II disorder and major depressive disorder within bipolar disorder pedigrees." The Journal of clinical psychiatry 76.1 (2015): 32-39.](../assets/articles/Frankland_15_Phenomenology.pdf)

#[Frankland, Andrew, et al. "Clinical predictors of conversion to bipolar disorder in a prospective longitudinal familial high-risk sample: focus on depressive features." Psychological medicine 48.10 (2018): 1713-1721.](../assets/articles/Frankland_15_Predictors.pdf)

#[Gollo, Leonardo L., et al. "Fragility and volatility of structural hubs in the human connectome." Nature neuroscience 21.8 (2018): 1107-1116.](../assets/articles/Gollo_18_Fragility.pdf)

#[Guo, C. C., et al. "Distinct neurobiological signatures of brain connectivity in depression subtypes during natural viewing of emotionally salient films." Psychological medicine 46.7 (2016): 1535.](../assets/articles/Guo_15_PsychMed.pdf)

#[Iyer, Kartik K., et al. "Early detection of preterm intraventricular hemorrhage from clinical electroencephalography." Critical care medicine 43.10 (2015): 2219-2227.](../assets/articles/Iyer_15_CCMed.pdf)

#[Valenzuela, Michael J., et al. "Posterior compensatory network in cognitively intact elders with hippocampal atrophy." Hippocampus 25.5 (2015): 581-593.](../assets/articles/Valenzuela_15_Hippocampus.pdf)

#[Zalesky, Andrew, et al. "Connectome sensitivity or specificity: which is more important?." Neuroimage 142 (2016): 407-420.](../assets/articles/Zalesky_16_sensitivity.pdf)


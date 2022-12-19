---
layout: about
title: About
permalink: /
subtitle: <a href="https://www.di.ens.fr/willow/">Inria, Ecole Normale Supérieure, Paris, France </a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>Inria Paris</p>
    <p>2 rue Simone IFF</p>
    <p>Paris, France</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

# Biography
I'm a researcher at the interface of Robotics, Perception, Learning and Control inside the [Willow research group](https://www.di.ens.fr/willow/). My research is devoted to the embedding of Optimal Control theory inside the formalism of Machine Learning, with dexterous manipulation and agile locomotion as the main target applications. 

In September 2018, I joined the [Willow research group](https://www.di.ens.fr/willow/) as a postdoctoral fellow.
Before that, I was a postdoctoral researcher inside the [Gepetto research group](http://projects.laas.fr/gepetto/index.php) at LAAS-CNRS in Toulouse, France.
From 2014 to 2017, I was a PhD candidate in the same [Gepetto research group](http://projects.laas.fr/gepetto/index.php). 
My research was at this time devoted to the understanding of the computational fundations of anthropomorphic locomotion. On one side, I highligthed some mechanismes underlying bipedalism among human beings. On the other side, I developed new mathematical formulations for the locomotion of humanoid robots.

I received my degree in Computer Science and Applied Mathematics with highest honor from [Ecole Normale Supérieure de Cachan](http://www.ens-cachan.fr/version-anglaise/) in 2013. In 2014, I was a visiting student inside the [Optimization in Robotics and Biomechanics](http://orb.iwr.uni-heidelberg.de) group with Katja Mombaur at the University of Heidelberg, Germany. 

## Main collaborators

My reseach is done in collaboration with:
[Francis Bach](https://www.di.ens.fr/~fbach/), [Jean Ponce](https://www.di.ens.fr/~ponce/), [Cordelia Schmid](https://thoth.inrialpes.fr/~schmid/), [Josef Sivic](https://www.di.ens.fr/~josef/) and [Ivan Laptev](https://www.di.ens.fr/~laptev/) for the Machine Learning and Vision aspects.
In the past, I used to collaborate with [Jean-Paul Laumond](http://homepages.laas.fr/jpl), [Nicolas Mansard](http://projects.laas.fr/gepetto/index.php/Members/NicolasMansard), [Olivier Stasse](https://homepages.laas.fr/ostasse/drupal/node/11), [Mehdi Bennalegue](http://mehdi.benallegue.com), [Andrea Del Prete](http://projects.laas.fr/gepetto/index.php/Members/>  \AndreaDelPrete) and [Steve Tonneau](http://www.stevetonneau.fr) for the Robotics perspectives.

## Software

I'm also the main developper of many Robotics software, among them:

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
